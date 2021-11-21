<html>
  <head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js" type="text/javascript"></script>
    <link rel="stylesheet" type="text/css" href="style.css">
     <script>
    $(document).ready(function(){
       $("#img1").hide();
      $("#btn1").click(function(){
        $("#img1").toggle(1000);
       });
    
    });
  </script>
  </head>
 
  <body>
    <h2 class="animated bounce">超級注意</h2>
    <div class="btn btn-block btn-primary"><button id="btn1">好</button></div>
    <div id = "img1">
    <img style= "display: none" src="https://stickershop.line-scdn.net/stickershop/v1/sticker/33607109/android/sticker.png">
    </div>
    
    <h3>個人連結</h3>
     <div class = "text-danger">
       <a herf = "https://www.instagram.com/rectangle1227/">Instagram</a>
    </div>
  </body>
</html>
