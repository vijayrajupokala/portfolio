# Portfolio ⚡️ 
[![GitHub](https://img.shields.io/github/license/vijayrajupokala/portfolio?color=blue)](https://github.com/vijayrajupokala/portfolio/blob/master/LICENSE.md) 
![GitHub stars](https://img.shields.io/github/stars/vijayrajupokala/portfolio) 
![GitHub forks](https://img.shields.io/github/forks/vijayrajupokala/portfolio)

## A minimal portfolio template for Developers!

<h2 align="center">
  <img src="https://github.com/vijayrajupokala/portfolio/blob/master/examples/example.gif" alt="portfolio" width="600px" />
  <br>
</h2>

## Features

⚡️ Modern UI Design + Reveal Animations  
⚡️ One Page Layout  
⚡️ Styled with Bootstrap v4.3 + Custom SCSS  
⚡️ Fully Responsive  
⚡️ Valid HTML5 & CSS3  
⚡️ Optimized with Parcel  
⚡️ Well organized documentation

To view the demo: **[click here](https://vijaynew-portfolio.netlify.app/)**

---

## Why do you need a portfolio? ☝️

- Professional way to showcase your work  
- Increases your visibility and online presence  
- Shows you’re more than just a resume

## Getting Started 🚀

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites 📋

You'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [NPM](http://npmjs.com)) installed on your computer.

node@v16.4.2 or higher
npm@7.18.1 or higher
git@2.30.1 or higher

less
Copy code

Also, you can use [Yarn](https://yarnpkg.com/) instead of NPM ☝️

yarn@v1.22.10 or higher

yaml
Copy code

---

## How To Use 🔧

From your command line, first clone the repository:

```bash
# Clone the repository
$ git clone https://github.com/vijayrajupokala/portfolio

# Move into the repository
$ cd portfolio

# Remove the current origin repository
$ git remote remove origin
After that, you can install the dependencies either using NPM or Yarn.

Using NPM
bash
Copy code
# Fix dependencies if needed
$ npm audit fix
$ npm i @parcel/transformer-sass

# Install dependencies
$ npm install

# Start the development server
$ npm start
Using Yarn
bash
Copy code
# Delete package-lock.json if it exists
$ rm package-lock.json

# Install dependencies
$ yarn

# Start the development server
$ yarn start
Open your browser at http://localhost:1234/ to view the portfolio locally.

Template Instructions:
1. Hero Section
Edit /src/index.html:

html
Copy code
<h1 class="hero-title load-hidden">
  Hi, my name is <span class="text-color-main">Vijaya Raju Pokala</span>
  <br />
  I'm the Full-stack Developer.
</h1>
2. About Section
Profile image inside /src/assets/

Resume PDF inside /src/assets/

html
Copy code
<img src="PASS PIC.jpg" alt="Profile Image">
<a href="Resume(Vijay).pdf">View Resume</a>
3. Projects Section
Update project titles, descriptions, links, and images inside /src/assets/.

4. Contact Section
Add email, phone, or call-to-action message.

5. Footer Section
Add social media links (Twitter, LinkedIn, GitHub, etc.)

Styles
Change theme colors in /src/sass/abstracts/_variables.scss:

scss
Copy code
$main-color: #02aab0;
$secondary-color: #00cdac;
Deployment 📦
Recommended hosting: Netlify

Ensure index.html is in the root or correct publish folder.

Technologies used 🛠️
Parcel - Bundler

Bootstrap 4 - Frontend library

Sass - CSS extension language

ScrollReveal.js - JS animation library

Tilt.js - Tiny parallax JS library

License 📄
This project is licensed under the MIT License - see LICENSE.md for details.

Acknowledgments 🎁
Created by Vijaya Raju Pokala as a clean, responsive portfolio template for developers.