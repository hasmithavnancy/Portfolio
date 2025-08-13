# Ex01 Portfolio
## Name: Hasmitha V Nancy
## Reg No: 212224040111
## Date:13/8/2025

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
````
html code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header / Hero Section -->
    <header class="hero">
        <div class="container">
            <h1>Hi, I'm <span class="highlight">HASMITHA V NANCY</span></h1>
            <p class="tagline">Web Developer | Designer | Tech Enthusiast</p>
            <a href="#projects" class="btn">View My Work</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>
                I am a B.E (CSE) student passionate about creating interactive, responsive websites
                and learning the latest web technologies. I enjoy solving problems and bringing ideas to life
                through clean code and creative design.
            </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="section bg-light">
        <div class="container">
            <h2>Skills</h2>
            <div class="skills-grid">
                <div class="skill-card">HTML5</div>
                <div class="skill-card">CSS</div>
                <div class="skill-card">C</div>
                <div class="skill-card">Python</div>
                <div class="skill-card">Git & GitHub</div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section">
        <div class="container">
            <h2>Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Portfolio Website</h3>
                    <p>A Personal Portfolio To Showcase My Skills and Projects.</p>
                </div>
                <div class="project-card">
                    <h3>AJIO App</h3>
                    <p>An E-Commerce Fashion Store Web App.</p>
                </div>
                <div class="project-card">
                    <h3>Restaurant Website</h3>
                    <p>An Online Food Ordering & Table Booking Platform.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <footer class="footer">
        <p>Contact: <a>hasmithavnancy@gmail.com</a></p>
        <p>&copy; 2025 HASMITHA V NANCY</p>
    </footer>

</body>
</html>

css code
/* General Styles */
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    line-height: 1.6;
    color: #333;
}

/* Container */
.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}

/* Hero Section */
.hero {
    background: linear-gradient(to right, rgb(245, 186, 187), rgb(255, 234, 234));
    color: white;
    text-align: center;
    padding: 5rem 1rem;
}

.hero h1 {
    font-size: 2.5rem;
}

.highlight {
    color: rgb(87, 86, 79);
}

.tagline {
    margin: 1rem 0;
    font-size: 1.2rem;
}

.btn {
    display: inline-block;
    background: white;
    color: rgb(214, 169, 157);
    padding: 0.7rem 1.5rem;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    transition: background 0.3s;
}

.btn:hover {
    background: rgb(255, 245, 242);
    color: black;
}

/* Section */
.section {
    padding: 3rem 0;
}

.bg-light {
    background: #f4f4f4;
}

/* Skills Grid */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 1rem;
    margin-top: 1.5rem;
}

.skill-card {
    background: white;
    padding: 1rem;
    text-align: center;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Projects Grid */
.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
    margin-top: 1.5rem;
}

.project-card {
    background: white;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Footer */
.footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
}

.footer a {
    color:  rgb(214, 169, 157);
    text-decoration: none;
}

````

## OUTPUT
<img width="1917" height="1085" alt="Screenshot 2025-08-13 092947" src="https://github.com/user-attachments/assets/3218c165-b593-4810-850b-e9ae54eff55e" />

<img width="1919" height="1094" alt="Screenshot 2025-08-13 093001" src="https://github.com/user-attachments/assets/9191506e-8f51-454b-a403-12644d847870" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
