<!DOCTYPE html>
<html>
<head>
	<title>My Personal Profile</title>
</head>
<body>
	<style>
		table{
	background-color: #d2dde0;
	text-decoration-color: lightblue; 
	padding:0px;
	border:2px solid black; width="100%"
}
img{
	align-content: right;
}
li{
	align-content: center;
	display: inline-block;
	padding:3px;
	margin: 5px 30px;
}
ul{
	background-color: #bba4a4;

}
.table1{
	background-color: grey;
	color: white; 
	width: 100%;
	text-align: center;
	padding: 4px
}
		dir{
			background-color: #d2dde0;
			border-style: solid;
            border-color: black;
		}
	</style>

	<ul>
		<li>
			<a href="#name"><h3>Name</h3></a>
		</li>
		<li>
			<a href="#address"><h3>Address</h3></a>
		</li>
		<li>
			<a href="#about"><h3>About me</h3></a>
		</li>
		<li>
			<a href="#interests"><h3>Interests</h3></a>
		</li>
		<li>
			<a href="#hobbies"><h3>Hobbies</h3></a>
		</li>
	</ul>

	<table border="2" width="100%">
	<colgroup>
			<col>
			<col bgcolor=#aec395>
		</colgroup>

		<tr>
			<td><h1 id="name">UNSHA AFTAB</h1></td>
			<td row span="2"><img src="unsha1.jpg" usemap="#group" width="200" height="200"/>
		<map name="group">
		<area shape="rectangle" coords="0,0,50,200" href="#name">
		<area shape="rectangle" coords="51,0,100,200" href="#address">
		<area shape="rectangle" coords="101,0,150,200" href="#about">
		<area shape="rectangle" coords="150,0,200,200" href="#interests">
		</map>
		</td></tr>
		<tr>
			<td colspan="2"><h2 id="address">Address: CB299,LalaZarr,Wah Cantt</h2></td>
			
		</tr>
		<tr><td colspan="2"><h2 id="about">About me:</h2><p>I am Unsha Aftab currently enrolled in bachelors in Computer Science. <br />I am Student of National University of Science and techology. I m currently studying Web Engineering.</p></td></tr>
		<tr><td colspan="2" align="center"><h2 id="interests">Interests</h2></td>
		</tr>
		<td>Cooking</td>
<td>Baking</td>
		</tr>
		<tr>
			<td colspan="2" align="center"><h2 id="hobbies">Hobbies</h2></td>

		</tr>
		<tr><td>Logo-Designing</td>
			<td>Flyers Designing</td>
	
			</tr>
		<tr>
			<td rowspan="3">Skills</td>

			<td bgcolor="#9e9e9e">Java</td>	
	
		</tr>
		<tr><td bgcolor="#9e9e9e">C and C++</td>
		</tr>
		<tr><td bgcolor="#9e9e9e">HTML</td></tr>
<tr>
			<td rowspan="3">Softwares</td>
			<td bgcolor="#86b9b4">Microsoft edge</td>
		</tr>
		<tr>
			<td bgcolor="#86b9b4">Office</td>
		</tr>
		<tr>
			<td bgcolor="#86b9b4">Adobe</td></tr>
		<tr>
			<td rowspan="3">Contact Me:</td>
			<td bgcolor="#c3b8b8">0317873467</td>
		</tr>
		<tr><td bgcolor="#c3b8b8"><a href="https:www.google.com"> Visit my profile </a></td></tr>
		<tr>
			<td bgcolor="#c3b8b8"><a href="https:www.facebook.com"> About me </a></td>
		</tr>
</table>
<br />
<br />
<table class="table1">
	<tr><td>Degrees</td> </tr>
	<tr>
		<td>
			Matric
		</td>
	</tr>
	<tr>
		<td>
			FSC
		</td>
	</tr>
	<tr>
		<td>
			BACHELERS IN COMPUTER SCIENCE
		</td>
	</tr>
</table>
<dir>
<center >
<h1>Feedback form</h1>
<p>Please Fill out this form to help us improve this website</p>
	


<form>
	<table>
		<tr>
			<td>
				<label>Name </label>
			</td>
			<td>
				<input type="text" name="NAME "  value="" placeholder="Please enter your name">
			</td>
		</tr>
		<tr>
			<td>
				<label>Email </label>
			</td>
			<td>			
				<input type="email" name="Email" placeholder="abc@gmail.com">
			</td>
		</tr>
		<tr>
			<td>
				<label>Comments </label> 
			</td>
			<td>
				<textarea rows = "5" cols = "50" name = "Comments">
            Enter Comments here...
         </textarea>
			</td>
		</tr>
	</table>
	
	<br>
	
	<h4>Things you liked!</h4>
	<label>Set design</label><input type="checkbox" name="Set design">
	<label>Links</label><input type="checkbox" name="Links">
	<label>Easy of use</label><input type="checkbox" name="Easy of use"  checked="">
	<label>Images</label><input type="checkbox" name="Images">
	<label>Source code</label><input type="checkbox" name="Source code">
	<h3>How did you get to our website?</h3>
	<label>Search Engine</label><input type="radio" name="">
	<label>Links from another website</label><input type="radio" name="">
	<label>Deitel from website</label><input type="radio" name="">
	<label>Reference in a book</label><input type="radio" name="">
	<label>Others</label><input type="radio" name="">
	<br>
	<br><label><b>Rate our site(1-10)</b></label>
	<select>
		<option value="10" >1</option>
		<option value="10" >2</option>
		<option value="10" >3</option>
		<option value="10" >4</option>
		<option value="10" >5</option>
		<option value="10" >6</option>
		<option value="10" >7</option>
		<option value="10" selected="8" >8</option>
		<option value="10" >9</option>
		<option value="10" >10</option>
	</select>
	<br />
	<br />
	<input type="Submit" name="" value="Submit your enteries">
	<input type="reset" name="" value="Clear your enteries">
	<br />
	<br />
</form>
</center>
</dir>
<br>
<br>
<br>
<h1>
	Techacker.net
</h1>
<p>
	The blogging website created by my group. I m the graphical designer and i also do content writing.
</p>
<p>Click here to see my website</p>
<a href="www.techacker.net">Click Me</a>
</body>
</html>
