# html-city-tourism

1.Creating a html file to display the contents as seen in the following image.

Program:
```
<!DOCTYPE html>
<html>
<head>
<title>My Day</title>
</head>
<body>
<table cellpadding= "10" cellspacing="10" style="border-style: double;">
<tr>
<th colspan="2" class="center" style="border-style: double;"><mark>My Day</mark></th>
</tr>
<tr>
<td style="border-style: double;">
<ol>
<li>wake up early
<ul>
<li style="list-style-type: square; margin-bottom: 20px">5AM</li>
<li>walk</li>
<li>jog</li>
</ul>
</li>
</ol>
</td>
<td rowspan="3" style="border-style: double;">
<table>
<tr>
<th colspan="2" class="center highlight" style="border-style: double;"><mark>Things to watch</mark></th>
</tr>
<tr >
<td style="border-style: double;"><img src="1.png" alt="image 1" width="100" height="100" >
<td style="border-style: double;"><img src="2.png" alt="image 2" width="100" height="100">
</tr>
<tr>
<td style="border-style: double;"><img src="3.png" alt="image 3" width="100" height="100">
<td style="border-style: double;"><img src="4.png" alt="image 4" width="100" height="100">
</td>

</tr>
<tr>
<td></td>
</tr>
</table>
</td>
</tr>
<tr>
<td style="border-style: double;">
<ol start="2">
<li>breakfast
<ul>
<li style="list-style-type: square; margin-bottom: 20px">8AM</li>
<li>eggs</li>
<li>coffee</li>
</ul>
</li>
</ol>
</td>
</tr>
<tr>
<td style="border-style: double;">
<ol start="3">
<li>go to Saveetha
<ul>
<li style="list-style-type: square; margin-bottom: 20px">8AM</li>
<li>attend classes</li>
<li>to be continued</li>
</ul>
</li>
</ol>
</td>
</tr>
</table>
</body>
</html>
```
Output:
![Screenshot 2024-07-15 062715](https://github.com/user-attachments/assets/c510cfaf-286d-4be0-91d4-b3c63e5e835b)

Result:
Thus,Creating a html file to display the content in the above picture was executed successfully.


2.To design a website for a College.

Program:

Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="image.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
    </header>
    <main>
        <h1>Saveetha Engineering College</h1>
        <p>Welcome to our college, where we offer a wide range of academic programs and extracurricular activities.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
Academics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academics - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="image.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses/computer-science.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Academics</h1>
        <p>Explore our academic programs and research opportunities.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
Admission.html
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission - College Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="image.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses/computer-science.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Admission</h1>
        <p>Learn about our admission process, requirements, and deadlines.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
Gallery.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery - College Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="image.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses/computer-science.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Gallery</h1>
        <p>Explore our campus and student life through these photos.</p>
        <img src="clg1.jpeg" alt="Gallery Image 1">
        <img src="clg2.jpeg" alt="Gallery Image 2">
        <img src="clg3.jpeg" alt="Gallery Image 3">
        <img src="clg4.jpeg" alt="Gallery Image 4">
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
Courses.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Courses Offered - College Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="image.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Courses Offered</h1>
        <p>We offer a diverse range of courses across multiple disciplines. Explore our course offerings below:</p>
        <ul>
            <li><a href="computer.html">Computer Science</a></li>
            <li><a href="mathematics.html">Mathematics</a></li>
            <li><a href="english.html">English</a></li>
            <li><a href="social.html">Sociology</a></li>
            <li><a href="economics.html">Economics</a></li>
            <li><a href="mangement.html">Business Management</a></li>
        </ul>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
ComputerScience.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Computer Science - College Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="image.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Computer Science</h1>
        <p>Welcome to the Computer Science department. Here you can find information about our programs, faculty, and research opportunities.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
Mathematics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mathematics - College Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="image.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="../index.html">Home</a></li>
                <li><a href="../academics.html">Academics</a></li>
                <li><a href="../admission.html">Admission</a></li>
                <li><a href="../gallery.html">Gallery</a></li>
                <li><a href="../courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Mathematics</h1>
        <p>The Mathematics program at College Name offers a rigorous education in pure and applied mathematics. Our curriculum includes courses in calculus, linear algebra, differential equations, probability, and more.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Calculus I</li>
            <li>Calculus II</li>
            <li>Linear Algebra</li>
            <li>Differential Equations</li>
            <li>Probability and Statistics</li>
            <li>Abstract Algebra</li>
            <li>Real Analysis</li>
            <li>Numerical Methods</li>
        </ul>
        <h2>Faculty</h2>
        <p>Our faculty are leaders in mathematical research and education, committed to helping students succeed in their studies and careers.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
English.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>English - College Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="image.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>English</h1>
        <p>The English program at College Name covers literature, writing, and critical thinking. Students will explore a wide range of literary works and develop strong analytical and communication skills.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Introduction to Literature</li>
            <li>Creative Writing</li>
            <li>Shakespearean Studies</li>
            <li>American Literature</li>
            <li>Modernist Literature</li>
            <li>Postcolonial Literature</li>
            <li>Literary Theory</li>
            <li>Advanced Composition</li>
        </ul>
        <h2>Faculty</h2>
        <p>Our faculty are accomplished writers and scholars, dedicated to fostering a love of literature and a mastery of writing in their students.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
Social.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sociology - College Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="image.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Sociology</h1>
        <p>The Sociology program at College Name examines the structures of societies, groups, and organizations. Our courses cover topics such as social theory, research methods, and social issues.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Introduction to Sociology</li>
            <li>Social Theory</li>
            <li>Research Methods in Sociology</li>
            <li>Sociology of the Family</li>
            <li>Sociology of Education</li>
            <li>Sociology of Health</li>
            <li>Criminology</li>
            <li>Urban Sociology</li>
        </ul>
        <h2>Faculty</h2>
        <p>Our faculty members are experts in various fields of sociology, dedicated to advancing knowledge and solving social problems through research and teaching.</p>
    </main>
</head>
</html>
```
Economics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Economics - College Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="image.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Economics</h1>
        <p>The Economics program at College Name provides students with a solid foundation in economic theory, quantitative methods, and applied economics. Our curriculum prepares students for careers in business, government, and research.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Microeconomics</li>
            <li>Macroeconomics</li>
            <li>Econometrics</li>
            <li>Public Economics</li>
            <li>International Economics</li>
            <li>Development Economics</li>
            <li>Labor Economics</li>
            <li>Financial Economics</li>
        </ul>
        <h2>Faculty</h2>
        <p>Our faculty members are accomplished economists with expertise in various areas of economic research and policy analysis.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```

Management.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Business Management - College Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="image.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
    </header>
    <main>
        <h1>Business Management</h1>
        <p>The Business Management program at College Name equips students with the knowledge and skills needed to succeed in the business world. Our curriculum covers management principles, organizational behavior, finance, marketing, and more.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Principles of Management</li>
            <li>Organizational Behavior</li>
            <li>Financial Management</li>
            <li>Marketing Management</li>
            <li>Operations Management</li>
            <li>Human Resource Management</li>
            <li>Strategic Management</li>
            <li>Business Ethics</li>
        </ul>
        <h2>Faculty</h2>
        <p>Our faculty members are experienced business professionals and academics, dedicated to providing a comprehensive business education to our students.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```

Styles.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

header img {
    max-height: 50px;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 2rem;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
    position: fixed;
    width: 100%;
    bottom: 0;
}
```
Output:

![Screenshot 2024-07-15 063220](https://github.com/user-attachments/assets/58b800ce-0fa4-4589-866e-1caad4d6aae4)
![Screenshot 2024-07-15 063214](https://github.com/user-attachments/assets/005c23d2-2b6c-46e6-bdbb-785bde9cf743)
![Screenshot 2024-07-15 063304](https://github.com/user-attachments/assets/a492c1c8-5f6b-4b32-a03c-69dd6d0eecbb)
![Screenshot 2024-07-15 063257](https://github.com/user-attachments/assets/31c4903c-39a7-45a9-beac-96200eda69d2)
![Screenshot 2024-07-15 063252](https://github.com/user-attachments/assets/5d24f49b-62df-46c5-b02d-8fa588e27eaa)
![Screenshot 2024-07-15 063245](https://github.com/user-attachments/assets/1a772392-8a5b-4734-9271-f91a6935ca27)
![Screenshot 2024-07-15 063238](https://github.com/user-attachments/assets/2f7eab0b-28ed-4265-883c-f7d9a38e4330)
![Screenshot 2024-07-15 063232](https://github.com/user-attachments/assets/12a85b31-343c-453e-a73a-1ea857d574b9)
![Screenshot 2024-07-15 063226](https://github.com/user-attachments/assets/2d7d6f6a-571a-4706-abe2-48279f4ebd0a)
Result:
Thus,Creating a website for college was executed successfully.
