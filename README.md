<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" type="text/css" href="myStyles.css">
  <script>
    function makeLines(times, text){
      var result = "";
      for (var i=0; i<times;i++){
        result += text+"<br/>";
      }
      return result;
    }
  </script>
</head>

<body>
<a href="index.html">Back</a>
<h1>why did the chicken cross the road?</h1>
<h2>Nobody knows!!!</h2>
<p1>That was stupid.</p1>
<script>

  document.write(makeLines(100, "LOL"));
</script>
</body>

</html>
