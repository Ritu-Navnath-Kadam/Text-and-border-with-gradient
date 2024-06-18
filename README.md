# Text-and-border-with-gradient
<!DOCTYPE html>

<html>
<head>
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
  <title>Hello, World!</title>
  <link rel="stylesheet" href="LG.css">
</head>
<body>
  <h1>Low aim is crime</h1>
  <div class="box with-conic-gradient">
  Border with conic gradient
</div>
</body>
</html>

body
{
  align-items:center;
  justify-content:center;
  
}

h1
{
  font-size:80px;
  font-family:times new roman;
  font-weight:bold;
  text-align:center;
  background:linear-gradient(to right,lightblue,cyan,blue,navy,black);
  color: transparent;
  background-clip:text;
  display:flex;
  
}
.with-conic-gradient {
  border-style: solid;
  border-width: 10px;
  border-image: conic-gradient(red, yellow, lime, aqua, blue, magenta, red) 1;
}
.box {
  width: 300px;
  height: 200px;
  max-width: 100%;
  margin: 1rem auto;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2rem;
}
