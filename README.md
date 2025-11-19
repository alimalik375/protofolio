# protofolio
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>CourseHub – Learn Anything</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <nav>
    <h2 class="logo">CourseHub</h2>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="courses.html">Courses</a></li>
    </ul>
  </nav>
</header>

<section class="hero">
  <div>
    <h1>Learn New Skills Anytime</h1>
    <p>Online courses for students, developers, and professionals.</p>
    <a class="btn" href="courses.html">Browse Courses</a>
  </div>
</section>

<footer>
  <p>© 2025 CourseHub – All Rights Reserved</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Courses – CourseHub</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <nav>
    <h2 class="logo">CourseHub</h2>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="courses.html">Courses</a></li>
    </ul>
  </nav>
</header>

<section class="content">
  <h1>Available Courses</h1>

  <div class="card-container">

    <div class="card">
      <h3>HTML & CSS Basics</h3>
      <p>Learn the foundations of web development.</p>
      <a href="course-details.html">View Course</a>
    </div>

    <div class="card">
      <h3>JavaScript Essentials</h3>
      <p>Master the most popular programming language.</p>
      <a href="course-details.html">View Course</a>
    </div>

    <div class="card">
      <h3>Math for Beginners</h3>
      <p>Build strong fundamentals in mathematics.</p>
      <a href="course-details.html">View Course</a>
    </div>

  </div>
</section>

<footer>
  <p>© 2025 CourseHub</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Course Details – CourseHub</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <nav>
    <h2 class="logo">CourseHub</h2>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="courses.html">Courses</a></li>
    </ul>
  </nav>
</header>

<section class="content">
  <h1>HTML & CSS Basics</h1>
  <p>This course teaches the basics of building websites.</p>

  <h2>Lessons</h2>

  <ul class="lesson-list">
    <li><a href="lesson.html">Lesson 1 – Introduction</a></li>
    <li><a href="lesson.html">Lesson 2 – HTML Structure</a></li>
    <li><a href="lesson.html">Lesson 3 – CSS Styling</a></li>
    <li><a href="lesson.html">Lesson 4 – Layout & Flexbox</a></li>
  </ul>
</section>

<footer>
  <p>© 2025 CourseHub</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Lesson – CourseHub</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <nav>
    <h2 class="logo">CourseHub</h2>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="courses.html">Courses</a></li>
    </ul>
  </nav>
</header>

<section class="content">
  <h1>Lesson 1 – Introduction to HTML</h1>

  <div class="video-box">
    <iframe width="100%" height="400" src="https://www.youtube.com/embed/dD2EISBDjWM" allowfullscreen></iframe>
  </div>

  <h2>Notes</h2>
  <p>HTML (HyperText Markup Language) is the structure of all websites.</p>

  <h2>Downloads</h2>
  <a class="btn" href="sample.pdf" download>Download PDF Notes</a>
</section>

<footer>
  <p>© 2025 CourseHub</p>
</footer>

</body>
</html>
<style>* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

/* NAV */
header {
    background: #222;
    padding: 15px;
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 10;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    color: white;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.hero {
    height: 90vh;
    background: linear-gradient(to right, #0066ff, #00aaff);
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 70px;
    text-align: center;
}

.btn {
    background: #0066ff;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 6px;
}

.content {
    padding: 100px 20px 50px;
}

.card-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.card {
    width: 280px;
    margin: 10px;
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px #ccc;
    text-align: center;
}

.lesson-list li {
    list-style: none;
    padding: 10px;
}

.lesson-list li a {
    color: #0066ff;
    text-decoration: none;
}

.video-box {
    margin: 20px 0;
}

footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
}
</style>
