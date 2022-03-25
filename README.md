# Assessment-1-Chapter-1

[HTML]

<!DOCTYPE html>

<html>
<head>
    <meta charset="utf-8"/>
    <title>Intro to CSS</title>
    <link rel="stylesheet" href="p1.css"/>
</head>
<body>
    <h1 id="id1">The heading have a id and font-size of 50</h1>
    <h2 class="class1">The heading have a font style of unset</h2>
    <div>
        <p>
            This paragraph is in div section and will have a text color of white
        </p>
    </div>
</body>
</html>

[StyleSheet]

body
*{
    text-align:center;
}
body{
    background-color:black;
}
h1{
    text-align:center;
    font-size: 50px;
    color:lightpink;
}
#id1{
    font-style:italic;
    color:aquamarine;
}
.class1{
    font-size:unset;
    color:cyan;
}
div, p {
    color: white;
}
