# Exercise 1

## Objective
Students will create a webpage using a variety of CSS properties and selectors to style HTML elements, reinforcing their understanding of how CSS is used to enhance web page aesthetics and usability.

Instructions:

# Step 1: Create the HTML Document
- Create a new HTML document with the basic structure:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Styled Webpage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1 class="main-title">My Webpage</h1>
        <nav>
            <ul>
                <li><a href="#section1">Section 1</a></li>
                <li><a href="#section2">Section 2</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="section1">
            <h2>Section 1</h2>
            <p class="text">This is the first section.</p>
        </section>
        <section id="section2">
            <h2>Section 2</h2>
            <p class="text">This is the second section.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 My Webpage</p>
    </footer>
</body>
</html>
```

# Step 2: Create the External CSS File
- Create a new CSS file called styles.css in the same directory as your HTML file.
In styles.css, add the following CSS rules to style the elements:
``` 
/* Style for the main heading */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.main-title {
    font-size: 2em;
}

.text {
    color: #333;
    padding: 10px;
    background-color: #e0e0e0;
}

section {
    margin: 20px 0;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

```


# Step 3: Link the CSS File
- Ensure your HTML file correctly links to the homework-styles.css file by including the following line within the <head> section of your HTML document: 
``` <link rel="stylesheet" href="styles.css"> ```

# Step 4: Test Your Webpage
- Save your HTML and CSS files.
- Open your HTML file in a web browser to see the styled elements.

Ensure that: 
- The heading is black and centered 
- The paragraphs has a gray background 
- The footer is black and centered 



--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------