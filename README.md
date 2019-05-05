# mrflu58.github.io


HTMl Code : 
<!DOCTYPE html>
<html>
<head>
	<title>Ryan Fluharty's Website</title>
</head>

<body>
	<a href="#About Me">About Me</a>
	<a href="#Resume">Resume</a>
	<div id="About Me">
		<h1>About Me</h1>
		<h3>This webpage is designed to be a testing ground for my web design skills</h1>
	</div>
		<p>I currently only know how to use HTML but I am taking lessons on CSS and eventually will add javascript to my knowledge as well. My goal is for one day this webpage to be a solid addition to my resume and add to my job qualifications.</p>
	<div id="Resume">
	<h1>Resume</h1>
	<p>Click <a href="resume.com"><strong>here</strong></a> to view my resume!</p>
	</div>





</body>
</html>

CSS Code :
body {
    margin: 60px auto;
    width: 70%;
}
nav ul, footer ul {
    font-family:'Helvetica', 'Arial', 'Sans-Serif';
    padding: 0px;
    list-style: none;
    font-weight: bold;
}
nav ul li, footer ul li {
    display: inline;
    margin-right: 20px;
}
a {
    text-decoration: none;
    color: #999;
}
a:hover {
    text-decoration: underline;
}
h1 {
    font-size: 3em;
    font-family:'Helvetica', 'Arial', 'Sans-Serif';
}
p {
    font-size: 1.5em;
    line-height: 1.4em;
    color: #333;
}
footer {
    border-top: 1px solid #d5d5d5;
    font-size: .8em;
}

ul.posts { 
    margin: 20px auto 40px; 
    font-size: 1.5em;
}

ul.posts li {
    list-style: none;
}
