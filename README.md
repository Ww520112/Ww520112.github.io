<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script type="text/javascript" src="http://ajax.microsoft.com/ajax/jquery/jquery-1.4.min.js"></script>    
    <title>Document</title>

    <script type="text/javascript">
    $(Document).ready(function(){
        alert("你好，JQuery！");
        var myBtn=document.getElementById("MyBtn");
        var $btnJQ=$(myBtn);
        alert($btnJQ.val());
    })
     </script>

     <style type="text/css">
    div{
        background: red;
        width: 300px;
        height: 200px;
        
    }
    </style>

</head>
<body>
    <div></div>

</body>
</html>
