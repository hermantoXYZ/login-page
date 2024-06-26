# Login Page Tutorial

This README.md file provides a step-by-step guide on how to create a simple and responsive login page using HTML and CSS. By following this tutorial, you will learn the basic structure and styling needed to build a user-friendly login interface.

## Table of Contents
1. [Project Structure](#project-structure)
2. [HTML Code](#html-code)
3. [CSS Code](#css-code)
4. [Final Result](#final-result)


## Project Structure

Before we start coding, let's set up the project structure:

```
login-page/
├──assets/logo
├── index.html
└── styles.css
```

## HTML Code

Create an `index.html` file and add the following code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="login-container">
        <div class="paypal-logo">
            <img src="D:\REACT NATIVE\AiGeneration\Login_Page\assets\papi.png" alt="PayPal Logo">
        </div>
        <form class="login-form">
            <input type="text" placeholder="Email or mobile number" class="input-field">
            <a href="#" class="forgot-email">Forgot email?</a>
            <button type="button" class="next-button">Next</button>
            <div class="or-separator">or</div>
            <button type="button" class="signup-button">Sign Up</button>
            <div class="language-selector">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Flag_of_Indonesia.svg/2560px-Flag_of_Indonesia.svg.png" alt="Indonesian Flag">
                <select>
                    <option value="id">Bahasa Indonesia</option>
                    <option value="en">English</option>
                </select>
            </div>
        </form>
    </div>
</body>
</html>

```

## CSS Code

Create a `styles.css` file and add the following code to style your login page:

```css
/* General Styles */
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f5f5f5;
    font-family: Arial, sans-serif;
}

.login-container {
    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 40px 30px;
    width: 300px;
    text-align: center;
}

.paypal-logo img {
    width: 40px;
    margin-bottom: 20px;
}

.login-form .input-field {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #cccccc;
    border-radius: 5px;
    box-sizing: border-box;
}

.login-form .forgot-email {
    display: block;
    text-align: right;
    margin-bottom: 20px;
    color: #0070ba;
    text-decoration: none;
    font-size: 12px;
}

.login-form .forgot-email:hover {
    text-decoration: underline;
}

.login-form .next-button, 
.login-form .signup-button {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: none;
    border-radius: 5px;
    color: #ffffff;
    font-size: 16px;
    cursor: pointer;
}

.login-form .next-button {
    background-color: #0070ba;
}

.login-form .signup-button {
    background-color: #cccccc;
    color: #333333;
}

.or-separator {
    margin: 20px 0;
    color: #888888;
    font-size: 14px;
}

.language-selector {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 20px;
}

.language-selector img {
    width: 20px;
    margin-right: 5px;
}

.language-selector select {
    border: none;
    background: none;
    color: #333333;
    font-size: 14px;
    cursor: pointer;
}

```

## Final Result

After adding the HTML and CSS code, your login page should look something like this:

![Login Page Screenshot](https://github.com/hermantoXYZ/login-page/blob/main/screnshoot/Capture.JPG)

When you open the `index.html` file in your browser, you will see a simple, clean, and responsive login page.

## Conclusion

Congratulations! You have successfully created a basic login page using HTML and CSS. This example provides a foundation that you can build upon to add more functionality and styles to your login page, such as form validation, error messages, or integration with a backend server for authentication.

Feel free to customize the design and functionality to fit your project's requirements. Happy coding!