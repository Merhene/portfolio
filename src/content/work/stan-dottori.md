---
title: Stan Dottori, Tattoo Artist
publishDate: 2020-03-02 00:00:00
img: /assets/stock-1.jpg
img_alt: Iridescent ripples of a bright blue and pink liquid with Stan Dottori's logo
description: |
  PHP, Symfony, MySQL, Doctrine, JavaScript, SCSS, Twig, Composer, Yarn, EasyAdmin, Object-Oriented Programming, Relational database
tags:
  - Full-stack
  - Scrum
  - OOP
---

## Stan Dottori, Tattoo Artist



This project involves the development of a web application for a popular tattoo artist based in Lyon, Stan Dottori. The goal is to provide an online portfolio and booking system, allowing clients to view Stan's work, learn about his style and what tattoos are available to be "inked" (flashes).

<!-- Video temporarily unavailable during deployment optimization -->
<div class="video-placeholder" style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); padding: 60px 20px; text-align: center; border-radius: 8px; color: white; margin: 20px 0;">
  <h3>🎥 Demo Video</h3>
  <p>Watch the Stan Dottori Tattoo Artist website demonstration</p>
  <small>Video will be hosted on external platform for optimal performance</small>
</div>

<h5>Front-end :</h5>
The user interface is build with <b>Twig</b> template, and the animations are entirely built using <b>CSS</b>, inspired by tutorials from Kevin Powell and others. <b>JavaScript</b> is used only for the calendar feature.
<h5>Back-end :</h5>
 The core functionality is powered by <b>PHP</b> with the <b>Symfony</b> framework. Data is managed using <b>Doctrine</b> with <b>MySQL</b> as the database system.
<h5>Development Tools: </h5>
<b>Composer</b> is used for PHP package management, and <b>Yarn</b> is employed for JavaScript dependencies.
<h5>Admin Panel: </h5>
The admin interface is powered by <b>EasyAdmin</b>, which simplifies the management of content for the tattoo artist.
<h5>File Uploads:</h5>
The application uses <b>VichUploader</b> to handle file uploads, making it easy for Stan to upload and manage images in his portfolio.
<p><h5>Database Modeling</h5>
The database structure for this app was designed using the <b>MERISE</b> methodology, ensuring a robust and scalable architecture. The process involved:

<b>MCD (Conceptual Data Model</b>): This step focused on defining the entities, attributes, and relationships required to model the moods and user interactions effectively.
<br><br>
<b>MLD (Logical Data Model): </b>The MCD was then translated into a more structured format, outlining primary keys, foreign keys, and detailed relationships. 
<br><br>
<b>MPD (Physical Data Model): </b>Finally, the MLD was converted into the actual implementation in MySQL, optimizing the tables for performance and reliability.

<h5>Wireframes, Mockups, and Prototypes</h5>
To ensure an intuitive user experience, the interface design went through several stages of development using <b>Figma</b>:

<b>Wireframes: </b>Initial low-fidelity wireframes were created to outline the basic structure and navigation flow of the application.
<br><br>
<b>Mockups: </b>These wireframes were then enhanced with color schemes, typography, and UI elements to create high-fidelity mockups that reflect the final look and feel.
<br><br>
<b>Prototypes: </b>Interactive prototypes were developed to simulate the user journey and test the overall usability before implementation.</p>
<br>

#### Improvements

<h5>Pricing issue : </h5>
If you watched the video, you may notice something's wrong with the pricing ! A correction will be made to ensure accurate pricing displays throughout EasyAdmin.
<br>
<h5> Online booking with payment integration:</h5>
One of the next steps is to implement an online booking system that integrates payment processing. The goal is to allow clients to book appointments, pay directly via the platform, and have the appointments automatically added to the tattoo artist's calendar. This will streamline the booking process and create an automated management system for Stan.
