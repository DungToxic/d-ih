@@ -47,4 +47,36 @@ header h2 {
header h4 {
  font-family: 'Pacifico';
  text-align: center;
}

@media only screen and (max-width: 500px) {
  header h2 {
    font-family: 'Pacifico';
    font-size: 45px;
    text-align: center;
    margin-bottom: 30px;
  }
  header h4 {
    font-family: 'Pacifico';
    text-align: center;
    padding: 15px;
  }
  #no{
    position: absolute;
    display: inline-block;
    left: 7%; 
    top: 40vh;
    font-size: 14px;
    padding: 3px;
    -webkit-transition: all 0.1s ease-out;
  }
  #yes{
    position: absolute;
    display: inline-block;
    left: 58%; 
    top: 40vh;
    font-size: 14px;
    padding: 3px;
    -webkit-transition: all 0.3s ease-out;
  }
