Prerequisites
Before you begin, ensure you have the following requirements:

Basic or Intermediate knowledge of HTML, CSS, and JavaScript.

This website is developed using Bootstrap 5 and requires the following setup.

Setup Instructions
1. Clone the Repository
To run the project locally, you need to clone the repository. Open your terminal or command prompt and run one of the following commands based on your operating system:

For Linux/macOS:

bash
Copy
sudo git clone https://github.com/osemaoje/osemaoje_portfolio.git
For Windows:

bash
Copy
git clone https://github.com/osemaoje/osemaoje_portfolio.git
This will create a local copy of the project on your machine.

2. Include Necessary Dependencies
The project relies on several external libraries for its functionality and styling:

Bootstrap 5: Provides the grid system, layout utilities, and pre-built components.

jQuery: Required for specific Bootstrap components.

Bootstrap Icons: Used for icons across the site.

AOS (Animate On Scroll): For scroll-triggered animations.

3. AOS Animation Library Setup
To use the AOS animation library, follow these steps:

a) Include the AOS Stylesheet
Add the following link to the <head> section of your HTML file:

html
Copy
<link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
b) Include the AOS Script
Add this script just before the closing </body> tag:

html
Copy
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
</script>
This will initialize the AOS library for animations when elements scroll into view.

4. Google Fonts: Josefin Sans
To maintain a consistent font style across the site, the Josefin Sans font is used. Add the following code to the <head> section of your HTML:

html
Copy
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet"/>
5. Run the Project Locally
After cloning the repository, navigate to the project folder:

bash
Copy
cd osemaoje_portfolio
Open the index.html file in your browser to view the website locally.

Project Features
The portfolio website includes the following sections:

Sticky, Responsive Navigation Bar: The navigation bar remains fixed at the top of the screen as you scroll.

Hero Section: A large introductory area, typically featuring a background image or video.

Expertise Section: Showcase your areas of expertise.

Skill Section with Progress Animation: Display your skills with animated progress bars.

Portfolio Section: Highlight your projects or work samples.

Testimonial Section: Include feedback or testimonials from clients.

Blog Section: A section for blog posts, updates, or news (if applicable).

Contact Section: A form or details for visitors to contact you.

Footer Section: Includes copyright information and links to social media.

Fully Responsive: The website is designed to adapt to different screen sizes, ensuring it looks great on mobile, tablet, and desktop devices.

How to Use AOS Animations
To apply AOS animations to an element, simply add the data-aos attribute to the element in your HTML.

Example:

html
Copy
<div data-aos="fade-in">
  <!-- Your content goes here -->
</div>
You can replace "fade-in" with various animation effects such as:

fade-in

zoom-in

slide-up

flip-left

Refer to the AOS documentation for a full list of available animations and options.

License
This project is free to use and does not include any specific license. Feel free to modify and adapt it to your needs.
