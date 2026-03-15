# protfilo
This Protfilo Describes About ME

<!DOCTYPE html>
<html>
<head>
	<style>
	body{
    background-color:#f5f7fa; 
    margin:20px;
    font-family: Arial, sans-serif;
}

nav{
    margin-bottom:20px;
}
nav a{
    text-decoration:none;
    margin:10px;
    color:black;
    font-weight:bold;
}

nav a:hover{
    color:#2ecc71;
}
div{
    width:250px;
    float:right;
    margin-left:20px;
}
img{
    width:100%;
    border-radius:10px;
}
p{
    line-height:1.6;
}
form{
    margin-top:20px;
}
.submit{
    background-color:#2ecc71;
    color:white;
    border:none;
    padding:8px 15px;
    cursor:pointer;
}

.submit:hover{
    background-color:#27ae60;
}
@media screen and (max-width:768px){
    
    div{
        float:none;
        margin:auto;
        display:block;
    }
    nav{
        text-align:center;
    }

    body{
        margin:10px;
    }
}
form{
    width:300px;         
    margin:40px auto;    
    padding:20px;
    border:2px solid #ccc; 
    border-radius:10px;
    background-color:white;
    text-align:center;
}
    <title>Vinay Badanala - Portfolio</title>
    <meta charset="UTF-8">
    <meta name="author" content="Badanala Vinay">
    <meta name="description" content="This website represents personal website of Vinay Badanala">
    <meta name="keywords" content="vinay, badanala, personal website">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
	<main>
	<nav>
		<a href="#HOME">HOME</a> |
		<a href="#about">About Me</a> |
		<a href="#edu">Educational Details</a> |
		<a href="#Skills">Skills</a> |
		<a href="#project">Projects</a> |
		<a href="#Certifications">Certifications</a> |
		<a href="#Contact">Contact Us</a>
	</nav>
		<div style="width:250px">

			<img src="./pass.png" alt="Vinay Badanala Profile Photo" width="100%">
	
		</div>
		<h1 id="HOME">Hello, I'm Vinay Badanala</h1>
		<p>
			I am a passionate Java Full Stack Developer with hands-on experience 
			in building web applications using modern technologies.
		</p>
	</main>
<!-- About section -->
<h1 id="about">About Me</h1>
<p>
Hello, I’m Vinay Naga Sai Ram Badanala, a recent graduate from PSCMR College, Vijayawada. 
I am passionate about building efficient and user-friendly software solutions and 
continuously improving my technical skills as a software developer.
</p>
<!-- Education section -->
<h1 id="edu">Educational Details</h1>
<p>
I hold a Bachelor's degree from PSCMR College of Engineering and Technology, Vijayawada. 
In addition to my formal education, I specialized in Java Full Stack Development, acquiring 
knowledge of both front-end and back-end technologies including Java, HTML, CSS, and modern 
web development practices.
</p>
<!-- Skills section -->
<h1 id="Skills">Skills</h1>
<ul style="list-style-type:square">
<li><strong>Programming Languages:</strong> Java, JavaScript</li>

<li><strong>Frontend Technologies:</strong> HTML5, CSS3, React.js, Bootstrap</li>

<li><strong>Backend Technologies:</strong> Core Java, JDBC, Servlets, JSP</li>

<li><strong>Frameworks:</strong> Spring, Spring Boot</li>

<li><strong>Database:</strong> MySQL</li>

<li><strong>Version Control:</strong> Git, GitHub</li>

<li><strong>Tools & IDEs:</strong> Eclipse, VS Code</li>

<li><strong>Web Technologies:</strong> REST APIs</li>

<li><strong>Design Skills:</strong> UI/UX Design, Responsive Web Design</li>

</ul>

<!-- Projects section -->
<h1 id="project">Projects</h1>

<h2>Telegram Bot (Automation Project)</h2>

<p>
Created a Telegram Bot using Telegram Bot API and Python to automate user responses 
and handle commands.

<a href="https://www.linkedin.com/posts/vinay-naga-sai-ram-badanala-a865422b4_telegrambot-python-automation-activity-7341492211168989184-76oP" target = "_">
Check Project
</a>
</p>

<h2>Game Review (Front-End Page)</h2>

<p>
Developed a responsive Game Review Web Page using HTML5, CSS3, and JavaScript to 
showcase game ratings and reviews.

<a href="https://www.linkedin.com/posts/vinay-naga-sai-ram-badanala-a865422b4_google-drive-sign-in-activity-7338824277158215680-eIRc" target = "_">
Check Project
</a>
</p>

<!-- Certifications section -->
<h1 id="Certifications">Certifications</h1>

<ul>

<li>Hackerrank (2024) – Python Basic Certification</li>

<li>Swecha AP (2024) – Internship on Interactive Web Application with DevOps</li>

<li>CodeTantra (2024) – Python Programming Certification</li>

<li>Supraja Technologies (2024) – Cyber Security: Web Application Vulnerability Assessment & Penetration Testing</li>

<li>NPTEL (2025) – Introduction to Industry 4.0 and Industrial Internet of Things</li>

<li>AIMERS (2025) – Generative Artificial Intelligence</li>

<li>Adobe (2025) – Generative AI Content Creation</li>

<li>ALLPro Trainings (2025) – Java Master Class Completion Certificate</li>

<li>Scaler Masterclass (2026) - React Master Class Completion Certificate</li>

</ul>

<!-- Contact section -->
<h1 id="Contact">Contact</h1>

<form name="Contact" method="post">

<label>Name:</label><input type="text" name="name" placeholder="Enter Your Name" required><br><br>

<label>Suggestions:</label><textarea class = "textarea" id ="textarea" ></textarea><br><br>

<input type="submit"  class ="submit" id = "submit" value="Submit">

</form>

<!-- Footer -->
<footer>

<p>@2026 - Badanala Vinay</p>

</footer>

</body>
</html>

