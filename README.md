# Google Invisible reCAPTCHA Integration with EJS and Nodemon

This repository demonstrates the integration of Google Invisible reCAPTCHA into an HTML form using EJS for templating and Nodemon for development. Google Invisible reCAPTCHA is a free service that helps protect your website from spam and abuse without user interaction. This sample application showcases a simple and effective way to implement Invisible reCAPTCHA in your contact forms.

## Features

- **Invisible reCAPTCHA**: Seamlessly integrated without disrupting the user experience.
- **EJS Templating**: Dynamic rendering of HTML content using EJS.
- **Nodemon**: Automatically restarts the server during development upon detecting changes.
- **Asynchronous Loading**: The reCAPTCHA script loads asynchronously for better performance.
- **Form Validation**: Ensures the form is only submitted if the reCAPTCHA verification is successful.
- **Easy Setup**: Step-by-step instructions to register and integrate reCAPTCHA on your website.

## Getting Started

To get started, follow the instructions in the [README](README.md) file to register your site with Google reCAPTCHA, integrate the reCAPTCHA API into your HTML form using EJS, and test the implementation locally with Nodemon.

## Technologies Used

- Node.js
- Express
- EJS
- Nodemon
- Google reCAPTCHA API

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/google-invisible-recaptcha-ejs.git
    cd google-invisible-recaptcha-ejs
    ```
2. Install the dependencies:
    ```sh
    npm install
    ```
3. Start the server with Nodemon:
    ```sh
    npm run dev
    ```
4. Open your browser and navigate to `http://localhost:3000` to test the form submission with Invisible reCAPTCHA enabled.
