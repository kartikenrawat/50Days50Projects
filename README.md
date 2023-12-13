# 50Days50Projects

Day 1. https://github.com/kartiken/50Days50Projects/tree/main/PasswordGenerator
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    first input: <input type="text" name="text" id="first">
    <br><br>
   second input: <input type="text" name="text" id="second">
   <br><br>
 <button onclick="check()"> Submit</button>
 <br><br>
 <h2 id="result"></h2>

 <script>
    function check(){
        var first_v=document.getElementById=('first').value;
        var second_v=document.getElementById=('second').value;
        var result=document.getElementById=('result');

        if(first_v==second_v){
            document.getElementById("result").innerHTML="correct"
        }
        else{
            document.getElementById("result").innerHTML="incorrect"        }

    }
 </script>
</body>
</html>

if (first_v == second_v) {
                result.innerHTML = "correct";
            } else {
                result.innerHTML = "incorrect";
