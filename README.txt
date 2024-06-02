# Portfolio Website

Welcome to my personal portfolio website. This project showcases my skills, experiences, and projects. You can visit the live site at [https://roaring-selkie-56771b.netlify.app/](https://roaring-selkie-56771b.netlify.app/).

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)
- [License](#license)

## Overview
This portfolio website is designed to provide an online presence and showcase my work as a developer. It includes sections such as About Me, Resume, Projects, and Contact.

## Features
- **Responsive Design**: The site is fully responsive and works on all devices.
- **Interactive Elements**: Includes interactive elements like buttons, forms, and animations.
- **Downloadable CV**: Provides an option to download my CV.
- **Contact Form**: Visitors can send me messages through a contact form.

## Technologies Used
- **Frontend**:
  - HTML5
  - CSS3
  - JavaScript
  - [Font Awesome](https://fontawesome.com/) for icons

- **Backend**:
  - Node.js
  - Express.js
  - Nodemailer for handling email submissions

- **Hosting**:
  - Netlify

## Installation
To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/harithebeast/portfolio.git
    cd portfolio
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Run the application**:
    ```bash
    node app.js
    ```

## Usage
Visit [https://roaring-selkie-56771b.netlify.app/](https://roaring-selkie-56771b.netlify.app/) to view the live website.

### Contact Form
The contact form allows users to send me messages directly to my email. Ensure that you configure your email and password in the `app.js` file for Nodemailer:

```javascript
const transporter = nodemailer.createTransport({
    service: 'gmail',
    auth: {
        user: 'your-email@gmail.com',
        pass: 'your-email-password'
    }
});
