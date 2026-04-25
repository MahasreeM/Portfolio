# Ex01 Portfolio
## Date: 25-04-2026
## Reg.no: 212224110035
## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
### HOME
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Maha Shree Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Maha Shree M</h1>
        <p>B.E CSE (IoT) Student | Frontend Developer | IoT Enthusiast</p>

        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Me</a>
            <a href="project.html">Projects</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <section class="home">
        <h2>Welcome to My Portfolio</h2>

        <p>
            Hello! I am Maha Shree M, a second-year student studying
            Computer Science and Engineering (Internet of Things)
            at Saveetha Engineering College.
        </p>

        <p>
            I am passionate about learning new technologies,
            improving my technical skills, and building innovative projects.
            I have strong interest in IoT, Frontend Development,
            Cloud Computing, and Machine Learning.
        </p>

        <p>
            This portfolio website contains information about me,
            my skills, projects, achievements, certifications,
            and contact details.
        </p>
    </section>

</body>
</html>
```

### ABOUT ME
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>About Me</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>About Me</h1>

        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Me</a>
            <a href="project.html">Projects</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <section>

        <h2>Career Objective</h2>
        <p>
            I am enthusiastic about advancing in the fields of Frontend Development,
            Cloud Technologies, and Internet of Things.
            I aim to apply my knowledge and skills to create
            meaningful technological solutions and contribute
            to innovative projects.
        </p>

        <h2>Education</h2>
        <p>
            B.E. Computer Science and Engineering - Internet of Things<br>
            Saveetha Engineering College<br>
            2024 - 2028
        </p>

        <h2>Skills</h2>
        <ul>
            <li>Internet of Things (IoT)</li>
            <li>Frontend Development</li>
            <li>Computer Networks</li>
            <li>Python</li>
            <li>C Programming</li>
            <li>Flutter</li>
            <li>DBMS</li>
        </ul>

        <h2>Certificates</h2>
        <ul>
            <li>Rashtrabhasha Praveen (Hindi Proficiency)</li>
            <li>IoT Internship - Approtech R&D Solutions Pvt. Ltd.</li>
            <li>Junior Grade Typewriting (English)</li>
            <li>Automation Developer Associate Training - UI Path</li>
            <li>AWS Educate Machine Learning Foundations</li>
            <li>AWS Educate Cloud Computing</li>
        </ul>

    </section>

</body>
</html>
```

### PROJECT
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Projects</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>My Projects</h1>

        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Me</a>
            <a href="project.html">Projects</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <section>

        <h2>1. IoT-Based Smart Waste Collection and Management System</h2>
        <p>
            Developed a smart waste monitoring system using sensors
            and microcontrollers to collect real-time bin data and
            enable remote monitoring for efficient waste collection.
        </p>

        <h2>2. Weather Forecast Web Application</h2>
        <p>
            Built a weather app using HTML, CSS, and JavaScript.
            Integrated OpenWeatherMap API to fetch real-time weather data
            and display temperature and weather conditions.
        </p>

        <h2>3. Restaurant Menu Mobile App</h2>
        <p>
            Developed a restaurant menu application using Flutter
            to display food items, categories, and prices with
            a user-friendly interface.
        </p>

        <h2>4. To-Do List Mobile Application</h2>
        <p>
            Built a task management app using Flutter and Dart
            with features to add, update, and delete tasks.
        </p>

    </section>

</body>
</html>
```

### CONTACT
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Contact Me</h1>

        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Me</a>
            <a href="project.html">Projects</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <section>
      <center>
        <h2>Get In Touch</h2>

        <p>Email: maha1707shree@gmail.com</p>
        <p>Phone: 9600199207</p>
        <p>Location: Chennai, Tamil Nadu</p>
        <p>LinkedIn: www.linkedin.com/in/mahashree17</p>
        <p>GitHub: github.com/MahasreeM</p>
       </center> 
    </section>

</body>
</html>
```

### STYLE.CSS
```
body {
    margin: 0;
    font-family: Arial;
    background-color: #f4f4f4;
}

header {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 20px;
}

nav {
    margin-top: 15px;
}

nav a {
    text-decoration: none;
    color: white;
    margin: 15px;
    font-weight: bold;
}

section {
    width: 80%;
    margin: auto;
    padding: 30px;
    background: white;
    margin-top: 20px;
    border-radius: 10px;
}

h1, h2 {
    color: #2c3e50;
}

header h1 {
    color: white;
}

ul li {
    margin: 10px 0;
}

.home p {
    font-size: 18px;
    line-height: 1.6;
}
```
## OUTPUT

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/e59a3ebf-2f13-481d-9472-4ddeba1b223f" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/3e6880ae-b041-4646-ab74-2f813a683715" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/d085adc0-42ec-4b29-962e-c870a0f1a22b" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/e78eb517-903b-497c-a944-2bd48a9c11db" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
