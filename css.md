body												
{
	background-color: #191d21;             
	font-family: 'League Gothic', sans-serif;
	font-size: 30px;
	margin: 0;
}

.nav
{
	width: 80%;
	margin: 0 auto;
}

header
{
	background: #55D6AA;
}

header::after
{
	content: '';
	display: table;
	clear: both;
}

.logo
{
	float: left;
	padding: 10px 0;
}

nav
{
	float: right;
}

nav ul
{
	margin: 0;
	padding: 0;
	list-style: none;
}

nav li
{
	display: inline-block;
	margin-left: 70px;
	padding-top: 23px;
	
	position: relative;
}

nav a
{
	color: #444;
	text-decoration: none;
	display: block;
	text-transform: uppercase;
	font-size: 17px;
}

nav a:hover
{
	color: #444;
}

nav a::before
{
	content: '';
	display: block;
	height: 5px;
	background-color: #444;
	
	position: absolute;
	top: 0;
	width: 0%;
	
	transition: all ease-in-out 150ms;
}

nav a:hover::before
{
	width: 100%;
}

.container
{
	margin-left: auto;
	margin-right: auto;
	padding-top: 40px;
	width: 1100px;
	text-align: justify;
}

.postcard1
{
	width: 450px;
	text-align: center;
	padding: 5px;
	margin-right: 100px;
	float: left;
}

.postcard1 p
{
	padding: 5px;
	margin-top: 10px;
	color: #ffffff;	
}

.postcardmulti1
{
	width: 450px;
	padding: 5px;
	float: left;
}

#multi1
{
	float: left;
	width: 112px;
	height: 50px;
}

#multi2
{
	float: left;
	width: 112px;
	height: 50px;
}

#multi3
{
	float: right;
	width: 112px;
	height: 50px;
}

#multi4
{
	float: right;
	width: 112px;
	height: 50px;
}

#multi5
{
	float: right;
	width: 440px;
	height: 200px;
	padding: 20px;
}
