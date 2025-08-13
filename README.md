# Ex01 Portfolio
## Date:

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
```
HTML

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Site</title>
     <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet" 
    integrity="sha384-LN+7fdVzj6u52u30Kp6M/trliBMCMKTyK833zpbD+pXdCLuTusPj697FH4R/5mcr" crossorigin="anonymous">  
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <header>
        <div class="containe">
        <div class="sub-container">
            <div class="firstchild">
                <h1 class="name">Selvaganesh </h1><p class="pro">/ WEB DEVELOPER</p>
            </div>
            <ul>
                <a href=""><li><li>ABOUT ME</li></li></a>
                <a href=""><li><li>RESUME</li></li></a>
                <a href=""><li>PROJECT</li></a>
                <a href=""><li><li>CONTACT ME</li></li></a>
            </ul>
        </div>
    </div>
    </header>
    <div class="box1">
        <div class="box2">
            <div class="box3">
                <div class="personal">
                    <img src="./My_Ph.jpg" alt="person-photo" height="200px" width="200px" class="selva">
                    <h2 class="h2">Selvaganesh B</h2>
                    <div class="line">
                        <hr >
                    </div>
                    <div class="web">
                        <p>Web Developer</p>
                    </div>
                    <div class="icons">
                        <a href="https://www.instagram.com/_.kishore.__7?igsh=MW16ZmQ3bXEzN3lieA=="><img src="./instagram.png" alt="instagram" height="30px" width="30px" class="ph 1"></a>
                        <img src="./linkedin.png" alt="linkedin" height="30px" width="30px" class="ph 2">
                        <img src="./twitter.png" alt="twitter" height="30px" width="30px" class="ph 3">
                        <img src="./facebook.png" alt="facebook" height="30px" width="30px" class="ph 4">
                    </div>
                </div>
            </div> 
        </div>
        <div class="mainbox">
            <div class="mainbox2">
                <div class="head">
                    <h1 class="h1">Hello</h1>
                </div>
                <div class="intro">
                    <h2>I am Selvaganesh</h2>
                </div>
                <div class="btn btn-outline-primary">
                   RESUME
                </div>
                <div class="btn btn-primary">
                   PROJECT
                </div>
                <div class="para">
                    <p>
                        I am passionate about coding and problem-solving.<br>
                        My skills include Python, HTML, CSS, and JavaScript.<br>
                        I enjoy creating applications that are both functional and user-friendly.<br><br>
                        My career goal is to become a Full-Stack Developer.<br>
                        I constantly explore new tools and technologies to enhance my expertise.<br>
                        I aim to combine front-end creativity with back-end efficiency.<br>
                        Building innovative, AI-driven solutions excites me the most.<br>
                    </p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <div class="footers">
            <div class="maindown1">
                <p>@ Selvaganesh<br>Full Stack Developer</p>
            </div>
            <div class="maindown2">
                <div class="down one">
                    <p>CONTACT<br>7558104544</p>
                </div>
                <div class="down one">
                    <p>WRITE<br>selvaganeshbaskar4@gmail.com</p>
                </div>
                <div class="down three">
                    <p>FOLLOW<br>
                    <img src="./instagram.png" alt="" height="25px" width="25px">
                    <img src="./facebook.png" alt="" height="25px" width="25px">
                    <img src="./linkedin.png" alt="" height="25px" width="25px">
                    <img src="./twitter.png" alt="" height="25px" width="25px">
                    </p>
                </div>
            </div>
        </div>
    </footer>
</body>
</html>

CSS

.sub-container{
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
            margin-left: 20px;
            padding-top: 15px;        }
li{
            list-style: none;
            display: inline-block;
            margin-left: 20px;
            color: #000;
        }
.name{
            font-size: 1.5rem;
        }
li:hover{
            color: blue;
        }
.pro,.name{
            display: inline-block;
        }
.box2{
            margin: 0;
            margin-top: 150px;
            width: 600px;
            height: 900px;
            background-color: #F3E2D4;
            display: inline-block;
        }
.containe{
    position: fixed;
    top: 0;
    z-index: 2;
    height: 150px;
    width: 100%;
    background-color: white;
   ;
}
ul{
    margin-left: 700px;
}

.photo{
    height: 450px;
    width: 200px;
    background-color: red;
    display: inline-block;
    left: 100px;
}


.box1{
            width: 100%;
            height: 900px;
            margin-top: px;
            position: relative;
            z-index: 1;
        }
        .box2{
            height: 800px;
            width: 600px;
            background-color: #F3E2D4;
            position: relative;
        }
        .box3{
            height: 530px;
            width: 350px;
            position: absolute;
            background-color: white;
            top:150px;
            left: 400;
            box-shadow: 5px 5px 30px black;
        }
        .personal{
            height: 470px;
            width: 350px;
            background-color: #EEEEEE;
            position: absolute;
        }
        .selva{
            border-radius: 100%;
            position: absolute;
            top: 40px;
            left: 80px;
        }
        .h2{
            position: absolute;
            top: 270px;
            left: 80px;
        }
        .line{
            position: relative;
            top: 320px;
            width: 50px;
            left: 150;
            color: blue;
        }
        .web{
            position: absolute;
            top: 360px;
            left: 130px;
        }
        .icons{
            position: absolute;
            top: 485px;
            left: 25%;
        }
        .ph{
            margin-left: 10px;
        }
        
        .mainbox{
            position: absolute;
            display: inline-block;
            top: 350px;
            left: 830px;
        }
        .head{
            margin-bottom: 25px;
        }
        .intro{
            margin-bottom: 25px;
        }
        .btn{
            margin-bottom: 25px;
        }
        button{
            margin-left: 20px;
            border-radius: 50px;
        }
        footer{
            position: relative;
            top: 90px;
            bottom: 30px;
        }
        .footers{
            padding: 20px;
        }
        .down,.maindown2,.maindown1{
            display: inline-block;
        }
        .maindown2{
            position: absolute;
            left: 700px;
        }
        .down{
            margin-left: 100px;
        }
        .maindown1{
            position: absolute;
            left: 100px;
        }

```
## OUTPUT
![alt text](image.png)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
