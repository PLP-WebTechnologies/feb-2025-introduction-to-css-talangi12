# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

HTML CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Styling Example</title>
    <link rel="stylesheet" href="style.css">  </head>
<body>

    <header id="main-header">
        <h1>My Styled Page</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <div class="container">
        <img src="https://images.pexels.com/photos/20787/pexels-photo.jpg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Example Image">

        <div class="box">
            <h2>Box 1 Title</h2>
            <p>This is the content of Box 1.  Lorem ipsum dolor sit amet, consectetur adipiscing elit.  Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </div>

        <div class="box">
            <h2>Box 2 Title</h2>
            <p>This is the content of Box 2.  Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>

</body>
</html>



CSS CODE
/* CSS Reset (Optional but Recommended) */
/* This helps to normalize styles across browsers */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Element Selector */
body {
    font-family: 'Arial', sans-serif; /* Different font */
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* ID Selector */
#main-header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

/* Class Selector */
.container {
    max-width: 960px;
    margin: auto;
    padding: 1rem;
}


img {
    display: block;
    margin: 1rem auto;
    max-width: 100%;
    height: auto;
    border: 5px solid #555; /* Border */
    border-radius: 8px;
}


.box {
    background-color: #fff;
    margin-bottom: 1rem;
    padding: 1rem; /* Padding */
    border: 1px solid #ccc; /* Border */
}

.box h2 {
    color: #007bff;
    margin-top: 0;
    margin-bottom: 0.5rem;
    border-bottom: 2px solid #eee;
    padding-bottom: 0.5rem;
}

.box p {
    margin-bottom: 0;
}

/* Styling Navigation */
nav ul {
    background-color: #444;
    color: #fff;
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0.5rem 0;
}

nav ul li {
    padding: 0 1rem;
}

nav a {
    color: #fff;
    text-decoration: none;
}

nav a:hover {
    color: #007bff;
}

/* Styling Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 0.5rem;
    margin-top: 2rem;
}

Happy Coding! 💻✨
