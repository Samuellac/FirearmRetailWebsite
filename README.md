# Firearm Retail Website

This is my web development project for **FIT1050 - Web Fundamentals** at **Monash University**.

## 📄 Overview

The website is a mock e-commerce platform called **Clover Firearms**, showcasing firearm products, deals, and an enquiry form. It is a static site built using HTML, CSS, and JavaScript.

## 🎨 Template

I used the existing **ZeroFour** HTML5 template from [html5up.net/zerofour](https://html5up.net/zerofour) as the base layout. I modified:

- The content and text throughout the site
- All image assets (e.g. homepage banners, product visuals)
- The site color scheme and font styles

## ✨ Features Added

- **EmailJS Integration**: I implemented an additional JavaScript feature using [EmailJS](https://www.emailjs.com/) that allows users to send enquiry form responses directly to an email address.
  - The form is located on the homepage under the "Enquiries" section.
  - Submissions trigger `emailjs.sendForm(...)` on form submission.
