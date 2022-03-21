<h1>This is an HTML project called FizzBuzz</h1>
<p><i>Please note, if you the code below looks incomplete, view the raw files in order to see the full code</i></p>
<blockquote>
<pre>
<code>
&lt!DOCTYPE html&gt
&lthtml&gt
&lthead&gt
&ltmeta charset="UTF-8"&gt
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 0; i < 100; i++) {
		displayHTML += "&ltp&gt" + i + "&lt/p&gt";
	}
	display.innerHTML = displayHTML;
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
</code>
</pre>
<p><a href="https://github.com/hannahboba/hannahsproject/blob/main/README.md">Home</a><br></p>
