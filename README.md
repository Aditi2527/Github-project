<html>
<head>
    <title>
        calculator
    </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Online Calculator</h1>
<form name="form1" class="calci" action="index.html" method="post">
<input type="text" name="answer" id="display">
<br></br>
<input type="button" class="btndesing" value="c" onclick="form1.answer.value=''">
<input type="button" class="btndesing" value="<" onclick="form1.answer.value=form1.answer.value.substring(0,form1.answer.value.length*1-1)">
<input type="button" class="btndesing" value="0.0" onclick="form1.answer.value+='.00'">
<input type="button" class="opratordesing" value="/" onclick="form1.answer.value+='/'">
<br></br>
<input type="button" class="btndesing" value="7" onclick="form1.answer.value+='7'">
<input type="button" class="btndesing" value="8" onclick="form1.answer.value+='8'">
<input type="button" class="btndesing" value="9" onclick="form1.answer.value+='9'">
<input type="button" class="opratordesing" value="*" onclick="form1.answer.value+='*'">
<br></br>
<input type="button" class="btndesing" value="4" onclick="form1.answer.value+='4'">
<input type="button" class="btndesing" value="5" onclick="form1.answer.value+='5'">
<input type="button" class="btndesing" value="6" onclick="form1.answer.value+='6'">
<input type="button" class="opratordesing" value="-" onclick="form1.answer.value+='-'">
<br></br>
<input type="button" class="btndesing" value="1" onclick="form1.answer.value+='1'">
<input type="button" class="btndesing" value="2" onclick="form1.answer.value+='2'">
<input type="button" class="btndesing" value="3" onclick="form1.answer.value+='3'">
<input type="button" class="opratordesing" value="+" onclick="form1.answer.value+='+'">
<br></br>
<input type="button" class="opratordesing" id="zero"  value="0" onclick="form1.answer.value+='0'">
<input type="button" class="btndesing" value="." onclick="form1.answer.value+='.'">
<input type="button" class="opratordesing" value="=" onclick="form1.answer.value=eval(form1.answer.value)">


</form>
</body>
</html>


