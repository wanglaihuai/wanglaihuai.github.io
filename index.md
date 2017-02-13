<html>
<head >
<meta charset="UTF-8">
<title>
老司机解析
</title>
</head>
<body bgcolor="#2292DD">
<center>
<br/>
<br/>
<br/>
<input id="txt" style='font-size:30px'>
<br/>
<br/>
<select style='font-size:30px' id="slc">

<option value="http://www.wmxz.wang/B/index.php?url=">接口1</option>
<option value="https://api.47ks.com/webcloud/?url=">接口2</option>
<option value="http://000o.cc/jx/ty.php?url=">接口3</option>
<option value="http://www.yydy8.com/common/?url=">接口4</option>
<option value="http://jx.71ki.com/index.php?url=">接口5</option>
<option value="http://47.89.49.245/video.php?url=">接口6</option> 
<option value="http://player.gakui.top/?url=">接口7</option> 
<option value="http://www.97zxkan.com/jiexi/97zxkanapi.php?url=">接口8</option> 
<option value="http://www.wmxz.wang/video.php?url=">芒果专用接口（超清）</option>
</select>
<br/>
<br/>
<input type="button"  style='font-size:30px'  value="解 析" onclick="sub()" style="width:100;height:40;">

</center>
</body>
<script>      
function sub(){
var content = document.getElementById("txt").value;
var ads=document.getElementById("slc").value;  
window.open(ads+content);
}
</script>

</html>
