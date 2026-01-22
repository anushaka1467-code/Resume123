# Resume123
<!DOCTYPE html>
<html>
<head>
<title>Anusha K A Resume</title>
<style>
body {
    font-family: Arial;
    background: #0f172a;
    color: white;
    padding: 20px;
}

/* Folder Button Style */
.folder {
    background: #2563eb;
    padding: 12px;
    width: 220px;
    margin: 8px 0;
    border-radius: 8px;
    cursor: pointer;
    font-weight: bold;
    text-align: center;
}

.folder:hover {
    background: #1d4ed8;
}

/* Hidden Content */
.content {
    display: none;
    background: #111827;
    padding: 10px;
    border-radius: 8px;
    margin-bottom: 10px;
}

/* Profile Image */
img {
    width: 150px;
    border-radius: 50%;
    border: 3px solid white;
}
</style>
</head>

<body>

<h1>📁 Anusha K A Resume Folder</h1>

<!-- Profile Image -->
<img src="Anusha.jpg" alt="Anusha Photo">

<!-- Folder Sections -->
<div class="folder" onclick="toggle('personal')">📂 Personal Details</div>
<div id="personal" class="content">
<p><b>Name:</b> Anusha K A</p>
<p><b>Email:</b> anushaka1467@gmail.com</p>
<p><b>Phone:</b> 7899442587</p>
<p><b>Address:</b> Sonnehalli, Shiradi Sai Layout, Bangalore</p>
</div>

<div class="folder" onclick="toggle('education')">📂 Education</div>
<div id="education" class="content">
<p><b>BCA:</b> Indus Valley College, Bangalore (2023–2025)</p>
<p><b>PU Commerce:</b> Govt PU College Garthikere – 82%</p>
<p><b>CGPA:</b> 9.2</p>
</div>

<div class="folder" onclick="toggle('skills')">📂 Skills</div>
<div id="skills" class="content">
<ul>
<li>Java, Python, C++, JavaScript</li>
<li>SQL</li>
<li>Fast Learner</li>
<li>Interested in Data Science</li>
</ul>
</div>

<div class="folder" onclick="toggle('internship')">📂 Internship</div>
<div id="internship" class="content">
<p>Intern at IMTDA INFO TECH</p>
</div>

<div class="folder" onclick="toggle('languages')">📂 Languages</div>
<div id="languages" class="content">
<ul>
<li>Kannada</li>
<li>English</li>
<li>Hindi (Moderate)</li>
</ul>
</div>

<!-- JavaScript -->
<script>
function toggle(id) {
    let box = document.getElementById(id);
    if (box.style.display === "block") {
        box.style.display = "none";
    } else {
        box.style.display = "block";
    }
}
</script>

</body>
</html>
