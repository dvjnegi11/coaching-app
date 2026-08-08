# EDUCORE -- E-Learning Website

EDUCORE is a responsive e-learning website designed to provide students
with access to online courses, study materials, educational resources,
and interactive learning features.

The project presents a clean educational landing page with course
categories, key features, facilities, student testimonials, a
call-to-action section, and footer information.

## 📌 Project Overview

EDUCORE aims to make online education accessible and engaging by
providing a simple interface where students can explore courses and
learning resources.

The website includes:

-   A hero/home section introducing EDUCORE
-   Course categories for Intermediate, Degree, and Post Graduation
-   Key features such as learning for all, skill improvement, and
    interactivity
-   Educational facilities including a digital library, courses, and
    study material
-   Student testimonials
-   A contact/enrollment call-to-action
-   Social media links and footer information
-   Navigation for Home, About, Course, Library, and Profile

## ✨ Features

### 1. Course Section

The course section displays three major education levels:

-   **Intermediate** -- Online video courses and study materials up to
    12th grade
-   **Degree** -- Online courses and study materials for bachelor-level
    programs
-   **Post Graduation** -- Online courses and study materials for
    master-level programs

### 2. Key Features

The website highlights three important learning benefits:

-   **Learning For All**
-   **Improve Your Skills**
-   **Interactive Learning**

### 3. Facilities

EDUCORE provides information about:

-   World Class Library
-   Top Courses
-   Amazing Study Material

### 4. Student Testimonials

The testimonials section displays feedback from students about their
experiences with online learning, along with star ratings.

### 5. Call to Action

A dedicated section encourages users to enroll in online courses from
anywhere in the world and provides a **Contact Us** button.

### 6. Responsive Navigation

The navigation menu includes:

-   Home
-   About
-   Course
-   Library
-   Profile

JavaScript is used to open and close the navigation menu on smaller
screens.

## 🛠️ Technologies Used

-   **HTML5** -- Website structure and content
-   **CSS3** -- Styling, layout, colors, spacing, and responsiveness
-   **JavaScript** -- Navigation menu interactions
-   **Font Awesome** -- Icons and star ratings
-   **Image Assets** -- Educational images and testimonial images

## 📂 Project Structure

``` text
coaching_app/
│
├── index.html
├── style.css
│
├── images/
│   ├── img2.jpeg
│   ├── img3.jpeg
│   ├── library.jpeg
│   ├── courses.jpeg
│   ├── study.jpeg
│   ├── pic1.jpg
│   └── pic2.jpg
│
└── README.md
```

> File names may differ depending on the final project organization.

## 🚀 How to Run the Project

### Method 1 -- Open Directly

1.  Download or clone the project.
2.  Open the project folder.
3.  Locate `index.html`.
4.  Open `index.html` in a web browser.

### Method 2 -- Using VS Code

1.  Open the project folder in **Visual Studio Code**.
2.  Install the **Live Server** extension.
3.  Right-click `index.html`.
4.  Select **Open with Live Server**.
5.  The website will open in your default browser.

## 🎨 Website Sections

The main page is organized into the following sections:

1.  **Home / Hero Section**
2.  **Courses We Offer**
3.  **Keys / Features**
4.  **Our Facilities**
5.  **What Our Students Say**
6.  **Call to Action**
7.  **About Us / Footer**

## 📱 Responsive Design

The website is intended to work across different screen sizes,
including:

-   Desktop computers
-   Laptops
-   Tablets
-   Mobile devices

The navigation menu uses JavaScript functions to show and hide the menu
on smaller screens.

## 🔧 JavaScript Navigation

The project uses the following functions for the mobile navigation menu:

``` javascript
var navLinks = document.getElementById("navLinks");

function showMenu(){
    navLinks.style.right = "0";
}

function hideMenu(){
    navLinks.style.right = "-200px";
}
```

`showMenu()` displays the navigation menu, while `hideMenu()` moves it
out of view.

## 📚 Main Learning Goal

The goal of EDUCORE is to create an accessible online learning
environment where students can:

-   Discover educational courses
-   Improve their skills
-   Access study resources
-   Learn through online content
-   Explore educational facilities
-   Learn flexibly from different locations

## 🔮 Future Improvements

The current project is primarily a front-end website. It can be extended
with:

-   User registration and login
-   Student profiles
-   Course enrollment
-   Course search and filtering
-   Video course playback
-   Online quizzes and assessments
-   Progress tracking
-   Downloadable study materials
-   Teacher/instructor dashboards
-   Database integration
-   Online payments
-   Contact and feedback forms

## 👥 Contributors

**AMIGOS**

This project was created as an educational e-learning website project.

## 📄 License

This project is intended for educational and academic use. If you plan
to publish or distribute it commercially, verify the licenses of all
third-party images, icons, fonts, and other assets used in the project.
