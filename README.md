# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### Screenshot

![](./images/image-qr-code.png)

### Links

- Solution URL: [Netlify](https://adorable-panda-bbe4d5.netlify.app/)
- Live Site URL: [Netlify](https://adorable-panda-bbe4d5.netlify.app/)



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### my-process

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- CSS stylesheet -->
    <link rel="stylesheet" href="./styles.css">

    <!-- Icon -->
    <link rel="icon" href="./images/favicon-32x32.png">

    <!-- Fonts-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">

    <title>QR code component</title>
</head>

<body>
    <section>
        <div class="qr-container">
            <img src="./images/image-qr-code.png" alt="QR Code">
        </div>

        <div class="text">
            <h1>
                Improve your front-end skills by building projects
            </h1>

            <p>
                Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
            </p>
        </div>
    </section>
</body>

</html>
```
```css
/* Global Styles */
* {
    font-family: "Outfit", sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body Styles */
body {
    background-color: lightgray;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    padding: 20px;
    width: 100%;
}

/* Section Styles */
section {
    background-color: white;
    border-radius: 20px;
    padding: 20px;
    text-align: center;
    max-width: 320px;
    max-height: 497px;
}

/* QR Code Container Styles */
.qr-container {
    margin-bottom: 20px;
}

.qr-container img {
    border-radius: 10px;
    width: 100%;
    height: auto;
}

.text {
    width: 288px;
    height: 129px;
    gap: 16px;
}

/* Heading Styles */
h1 {
    font-size: 1.5rem;
    color: hsl(218, 44%, 22%);
    margin-bottom: 15px;
    font-weight: 700;
}

/* Paragraph Styles */
p {
    font-size: 15px;
    color: hsl(220, 15%, 55%);
    line-height: 1.5;
    font-weight: 400;
}

/* Image Styles */
img {
    width: 288px;
    height: 288px;
    border-radius: 10px;
}

```

## Author

- Frontend Mentor - [@arnoldagaba](https://www.frontendmentor.io/profile/arnoldagaba)
- Twitter - [@yourusername](https://www.twitter.com/agabaarnie)

