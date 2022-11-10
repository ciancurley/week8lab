<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Three Pieces of JavaScript</title>
    <script type="text/javascript">



        function action() {
            alert("Thank you for clicking me!")
        }

        document.write("Random Number: " + secAnswer)

        function actNumber(){
            document.getElementById("number").innerHTML="Random Number :" + secAnswer;
        }
    </script>
</head>
<body>
    <input type="button" value="Press me for a surprise" onclick="action();"/>
    <script type="text/javascript">
    var name;
    name= prompt("Enter your first name", "Type here")
    alert("Hello " + name)
    </script>

</body>
</html>
