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

/* Style for body - applying color and font */
body {
    font-family: 'Arial', sans-serif; /* Setting the font family */
    background-color: #f4f4f9; /* Light background color */
    color: #333; /* Dark text color */
    margin: 0;
    padding: 0;
}

/* Style for header (h1) with specific color and padding */
h1 {
    color: #2c3e50; /* Dark blue color */
    text-align: center;
    padding: 20px;
    margin-top: 50px;
}

/* Class selector for image styling */
.img-style {
    border: 5px solid #2980b9; /* Blue border around the image */
    padding: 10px;
    margin: 20px auto; /* Centering the image */
    display: block; /* Make the image a block element */
    max-width: 100%; /* Ensure the image is responsive */
}

/* ID selector for the container of content */
#content-container {
    width: 80%;
    margin: 0 auto; /* Centering the content */
    padding: 30px;
    background-color: #ffffff; /* White background for the content area */
    border-radius: 10px; /* Rounded corners */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Light shadow for a subtle effect */
}

/* Styling for a button with padding, border, and color */
button {
    padding: 10px 20px;
    background-color: #27ae60; /* Green button */
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #2ecc71; /* Lighter green when hovered */
}






<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1>Welcome to My Styled Page</h1>
    
    <div id="content-container">
        <p>This is a sample paragraph in a styled container. Here, we have used padding, margin, and other CSS properties to style elements.</p>
        
        <img src="https://via.placeholder.com/300" alt="Sample Image" class="img-style">
        
        <button>Click Me</button>
    </div>

</body>
</html>

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
