# Project
Project for Pixel Art Marker
<!DOCTYPE html>
<html>
<head>
    <title>Pixel Art Maker!</title>
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Monoton">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="border">
    <h1>Lab: Pixel Art Maker</h1>

    <h2>Choose Grid Size</h2>
    <form id="sizePicker">
        <label>Grid Height:</label>
        <h3>(maximum 50)</h3> 
        <input type="number" id="inputHeight" name="height" min="1" max="50" value="8">
        <label>Grid Width:</label>
        <h3>(maximum 50)</h3>      
        <input type="number" id="inputWeight" name="width" min="1" max="50" value="8">
        <input id="size" type="submit">
    </form>

    <h2>Pick A Color</h2>
    <form action="">
      <input type="color" id="colorPicker">
    </form>
    <table id="colorPalette"></table>
    <h2>Design Canvas</h2>
    <table id="pixelCanvas"></table>
  </div>
  <script src="designs.js"></script>
</body>
</html>
