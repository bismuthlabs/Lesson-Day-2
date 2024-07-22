# Homework 1

## Objective
Students will create a webpage using a variety of CSS properties and selectors to style HTML elements, reinforcing their understanding of how CSS is used to enhance web page aesthetics and usability.

Instructions:

# Step 1: Create the HTML Document
- Create a new HTML document with the basic structure:
```
<!DOCTYPE html>
<html>
<head>
    <title>My Styled Webpage</title>
    <link rel="stylesheet" href="homework-styles.css">
</head>
<body>
    <h1 id="main-heading">Welcome to My Styled Webpage</h1>
    <p class="intro">This is an introductory paragraph about my webpage. CSS makes styling easy!</p>
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
    <div class="content">
        <h2>Subheading</h2>
        <p>This is another paragraph inside a div element. It has its own styles.</p>
    </div>
    <img src="your-image-source.jpg" alt="A description of the image">
</body>
</html>
```

# Step 2: Create the External CSS File
- Create a new CSS file called homework-styles.css in the same directory as your HTML file.
In homework-styles.css, add the following CSS rules to style the elements:
``` 
/* Style for the main heading */
#main-heading {
    color: purple;
    text-align: center;
    margin-top: 20px;
}

/* Style for the introductory paragraph */
.intro {
    background-color: lightgrey;
    padding: 10px;
    font-style: italic;
}

/* Style for the list items */
ul li {
    color: red;
    font-weight: bold;
}

/* Style for the content div */
.content {
    border: 2px dashed blue;
    padding: 15px;
    margin-top: 20px;
}

/* Style for the subheading within the content div */
.content h2 {
    color: darkgreen;
    text-decoration: underline;
}

/* Style for the paragraph within the content div */
.content p {
    color: darkblue;
    background-color: lightyellow;
    padding: 10px;
}

/* Style for the image */
img {
    border: 2px solid black;
    display: block;
    margin: 20px auto;
}
```


# Step 3: Link the CSS File
- Ensure your HTML file correctly links to the homework-styles.css file by including the following line within the <head> section of your HTML document: 
``` <link rel="stylesheet" href="homework-styles.css"> ```

# Step 4: Test Your Webpage
- Save your HTML and CSS files.
- Open your HTML file in a web browser to see the styled elements.

Ensure that: 
- the heading is purple and centered 
- The introductory paragraph has a lightgrey background with italic text 
- The list items are red and bold 
- The content div has a dashed blue border 
- The subheading inside the content div is dark green and underlined 
- The paragraph inside the content div has dark blue text on a light yellow background 
- And the image has a solid black border and is centered.


--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------


# Homework 2

## Objective
Students will create a personal portfolio webpage using a variety of CSS properties and selectors to practice their understanding of how CSS enhances web page aesthetics and usability.

Instructions:

# Step 1: Create the HTML Document
- Create a new HTML document with the basic structure:
```
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="portfolio-styles.css">
</head>
<body>
    <header>
        <h1 id="main-heading">John Doe's Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <p class="intro">I am a web developer with a passion for creating interactive and dynamic web applications.</p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>A web-based game that helps people learn math quickly.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>A portfolio website to showcase my work and skills.</p>
        </div>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>You can reach me via email at john.doe@example.com.</p>
    </section>
    <footer>
        <p>&copy; 2024 John Doe. All rights reserved.</p>
    </footer>
</body>
</html>

```

# Step 2: Create the External CSS File
- Create a new CSS file called portfolio-styles.css in the same directory as your HTML file.
In portfolio-styles.css, add the following CSS rules to style the elements:
``` 
/* Style for the main heading */
#main-heading {
    color: navy;
    text-align: center;
    margin-top: 20px;
}

/* Style for the navigation bar */
nav ul {
    display: flex;
    justify-content: center;
    list-style-type: none;
    padding: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: darkblue;
    font-weight: bold;
}

nav ul li a:hover {
    color: lightblue;
}

/* Style for the introductory paragraph */
.intro {
    background-color: lightgrey;
    padding: 15px;
    font-style: italic;
    border-left: 5px solid darkgrey;
    margin: 20px;
}

/* Style for the project sections */
.project {
    border: 2px solid black;
    padding: 15px;
    margin: 20px 0;
    background-color: #f9f9f9;
}

.project h3 {
    color: darkgreen;
    text-decoration: underline;
}

.project p {
    color: darkblue;
}

/* Style for the contact section */
#contact {
    background-color: lightyellow;
    padding: 20px;
    border-top: 2px solid darkgrey;
}

/* Style for the footer */
footer {
    text-align: center;
    padding: 10px;
    background-color: darkblue;
    color: white;
}

```


# Step 3: Link the CSS File
- Ensure your HTML file correctly links to the homework-styles.css file by including the following line within the <head> section of your HTML document: 
``` <link rel="stylesheet" href="portfolio-styles.css"> ```

# Step 4: Test Your Webpage
- Save your HTML and CSS files.
- Open your HTML file in a web browser to see the styled elements.

Ensure that: 
- heading is navy and centered
- The navigation bar is centered and links change color on hover 
- The introductory paragraph has a lightgrey background with a darkgrey border
- project sections have a black border and background color of #f9f9f9
- The subheading inside the content div is dark green and underlined 
- The contact section has a lightyellow background
- And the footer is darkblue with white text.


--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------


# Homework 3

## Objective
Students will create a fun personal blog page using a variety of CSS properties and selectors to practice their understanding of CSS. This project will emphasize creativity and personal expression through web design.

Instructions:

# Step 1: Create the HTML Document
- Create a new HTML document with the basic structure:
```
<!DOCTYPE html>
<html>
<head>
    <title>My Fun Blog</title>
    <link rel="stylesheet" href="blog-styles.css">
</head>
<body>
    <header>
        <h1 id="main-heading">Welcome to My Fun Blog!</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#posts">Blog Posts</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <p class="intro">Hey there! I'm a fun-loving web developer who enjoys sharing stories and photos. Welcome to my blog!</p>
    </section>
    <section id="posts">
        <h2>Blog Posts</h2>
        <article class="post">
            <h3>My First Blog Post</h3>
            <p>This is my very first blog post! I'm so excited to start this journey.</p>
        </article>
        <article class="post">
            <h3>Another Day, Another Adventure</h3>
            <p>Today, I went hiking and took some amazing photos!</p>
        </article>
    </section>
    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery-item"><img src="image1.jpg" alt="Hiking trip"></div>
        <div class="gallery-item"><img src="image2.jpg" alt="Sunset view"></div>
        <div class="gallery-item"><img src="image3.jpg" alt="Delicious meal"></div>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Feel free to drop me an email at funblogger@example.com.</p>
    </section>
    <footer>
        <p>&copy; 2024 My Fun Blog. All rights reserved.</p>
    </footer>
</body>
</html>

```

# Step 2: Create the External CSS File
- Create a new CSS file called blog-styles.css in the same directory as your HTML file.
In blog-styles.css, add the following CSS rules to style the elements:
``` 
/* Style for the main heading */
#main-heading {
    color: darkmagenta;
    text-align: center;
    margin-top: 20px;
    font-family: 'Comic Sans MS', cursive, sans-serif;
}

/* Style for the navigation bar */
nav ul {
    display: flex;
    justify-content: center;
    list-style-type: none;
    padding: 0;
    background-color: lightcoral;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

nav ul li a:hover {
    color: yellow;
}

/* Style for the introductory paragraph */
.intro {
    background-color: lightpink;
    padding: 15px;
    font-style: italic;
    border-left: 5px solid deeppink;
    margin: 20px;
}

/* Style for the blog posts */
.post {
    border: 2px solid darkblue;
    padding: 15px;
    margin: 20px 0;
    background-color: #f0f8ff;
}

.post h3 {
    color: mediumvioletred;
    text-decoration: underline;
}

.post p {
    color: darkslateblue;
}

/* Style for the gallery */
.gallery-item {
    display: inline-block;
    margin: 10px;
    border: 2px solid lightblue;
}

.gallery-item img {
    width: 200px;
    height: 150px;
    display: block;
}

/* Style for the contact section */
#contact {
    background-color: lightyellow;
    padding: 20px;
    border-top: 2px solid darkgrey;
}

/* Style for the footer */
footer {
    text-align: center;
    padding: 10px;
    background-color: darkblue;
    color: white;
}

```


# Step 3: Link the CSS File
- Ensure your HTML file correctly links to the blog-styles.css file by including the following line within the <head> section of your HTML document: 
``` <link rel="stylesheet" href="blog-styles.css"> ```

# Step 4: Test Your Webpage
- Save your HTML and CSS files.
- Open your HTML file in a web browser to see the styled elements.

Ensure that: 
- heading is darkmagenta and centered with a fun font
- The navigation bar is styled and changes link colors on hover
- The introductory paragraph has a lightpink background with a deeppink border
- blog posts have a darkblue border with a light background
- The gallery images are bordered and aligned, and the contact section has a lightyellow background.

# Additional Challenge (Optional):
Add a background image to the webpage and use CSS to make it look visually appealing.
Add more blog posts and style them with different colors and fonts.