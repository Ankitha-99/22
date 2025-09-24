<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2> replace()</h2>
    <p Id="out"></p>
    <script>
        let text="I love Candies";
        let result=text.replace(/Candies/,"Pastries");
    document.getElementById("out").innerText=result;
    </script>
</body>
</html>
