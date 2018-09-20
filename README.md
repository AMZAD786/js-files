<html lang="en">
<head>
    <title>Jquery Chosen - Select Box with Search Option</title>  
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/chosen/1.5.1/chosen.min.css">
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/chosen/1.5.1/chosen.jquery.min.js"></script>
</head>
<body>

<form method="post" action="#">
<div style="width:520px;margin:0px auto;margin-top:30px;">
  <h2>Select Box with Search Option Jquery</h2>
  <select name="selected" class="chosen" style="width:500px;" >
  <option value="1">PHP</option>
  <option value="2">PHP Array</option>
  <option value="3">PHP Object</option>
  <option value="4">PHP Wiki</option>
  <option value="5">PHP Variable</option>
  <option value="6">Java</option>
  <option value="7">C</option>
  <option value="8">C++</option>
  </select>
  <input type="submit" name="submit">
</div>
</form>

<script type="text/javascript">
      $(".chosen").chosen();
</script>


</body>
</html>
