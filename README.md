# Term2_DV200_JarrydCarelse_221267
Term 2 readme file with demonstration video
# Term2_DV200_JarrydCarelse_221267
Term 2 Project readMe file with Demo Video
![Alt text](Untitled.png)
<h5 align="center" style="padding:0;margin:0;">Jarryd Carelse</h5>
<h5 align="center" style="padding:0;margin:0;">221267</h5>
<h6 align="center">DV200 2023</h6>
</br>
<p align="center">

  
  
  <h3 align="center">DV200 Term 2</h3>

  <p align="center">
Pearlers is a comprehensive web application meticulously designed to simplify administrative tasks in dental practices. With its user-friendly interface and strategic implementation of cutting-edge technologies, Pearlers ensures efficient management of patient and doctor information, along with seamless appointment scheduling.

 <br>
    
   <br />
   <br />
   <a href="path/to/demonstration/video">View Demo</a>
    ·
    <a href="https://github.com/username/projectname/issues">Report Bug</a>
    ·
    <a href="https://github.com/username/projectname/issues">Request Feature</a>
</p>
<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Project Description](#project-description)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [How to install](#how-to-install)
* [Features and Functionality](#features-and-functionality)
   * [Wireframes](#wireframes)
* [Development Process](#development-process)
   * [Implementation Process](#implementation-process)
        * [Highlights](#highlights)
        * [Challenges](#challenges)
   * [Future Implementation](#peer-reviews)
* [Final Outcome](#final-outcome)
    * [Mockups](#mockups)
    * [Video Demonstration](#video-demonstration)
* [Conclusion](#conclusion)
* [License](#license)
* [Contact](#contact)


<!--PROJECT DESCRIPTION-->

### Project Description

Pealers is a web-based appointment management system specifically designed for dentists. This PHP and MySQL-powered website empowers dental professionals to efficiently schedule, manage, and monitor patient appointments. With a user-friendly interface, it simplifies the administrative tasks associated with patient appointment booking, editing, and viewing.


### Built With

* VS Code
* Php
* Sql
* HTML/CSS
* ZZAMP
* Figma

<!-- GETTING STARTED -->
<!-- Make sure to add appropriate information about what prerequesite technologies the user would need and also the steps to install your project on their own mashines -->
## Getting Started

The following instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### How to install

### Installation
Here are a couple of ways to clone this repo:

Clone the Repository:

bash
Copy code
git clone [YourRepositoryURL]
Install XAMPP:
If you haven't already installed XAMPP, download and install it from the official website.

Database Setup:

Launch XAMPP and start the Apache and MySQL services.
Open phpMyAdmin from the XAMPP Control Panel or by visiting http://localhost/phpmyadmin in your web browser.
Create a new database with the name [YourDatabaseName] (e.g., pealers_db).
Configuration:

In the project folder, find the configuration file (e.g., config.php) and update the database connection settings. Replace [DB_Host], [DB_User], [DB_Password], and [DB_Name] with your XAMPP database configuration:
php
Copy code
$dbHost = '[DB_Host]'; // Typically 'localhost'
$dbUser = '[DB_User]'; // Your MySQL username
$dbPassword = '[DB_Password]'; // Your MySQL password
$dbName = '[DB_Name]'; // Your database name (e.g., 'pealers_db')
Start the Website:

Move the project folder to your XAMPP "htdocs" directory (e.g., C:\xampp\htdocs\ on Windows or /Applications/XAMPP/htdocs/ on macOS).
Open a web browser and visit http://localhost/[YourProjectName] (e.g., http://localhost/pealers) to view and use the Pealers website.
  
<!-- FEATURES AND FUNCTIONALITY-->
![Alt text](compare.jpg
)
### The section where one can select two cars and compare them side by side.


![Alt text](chart.jpg
)
### Using Chart.js you can select a car you would like to view information on and it gives you the information in a form of a line chart.



## Development Process

Technology Stack

Back-end: PHP
Database: MySQL (using XAMPP)
Front-end: HTML, CSS, JavaScript
Development Phases

1. Database Design and Setup
Created a MySQL database using XAMPP to store patient information and appointment records.
Designed the database schema to ensure data integrity and efficient retrieval.

2. User Authentication
Implemented user authentication to ensure secure access for authorized users.
Created user roles (e.g., dentists, administrative staff) with appropriate permissions.

3. Front-end Development
Designed and developed the front-end using HTML, CSS, and JavaScript.
Focused on creating an intuitive and responsive user interface for both desktop and mobile devices.

4. Appointment Scheduling
Developed features for scheduling patient appointments, including date and time selection and service type specification.
Implemented validation to prevent scheduling conflicts.

5. Appointment Editing
Enabled the editing of existing appointments to accommodate rescheduling or changes in patient preferences.
Ensured data consistency and integrity during the editing process.

6. Appointment Viewing
Created a dashboard for dentists to view and manage upcoming appointments.
Displayed patient information and appointment details for efficient patient management.

#### Challenges
##Challenges Faced

*Styling and CSS Integration:

Styling web applications to achieve a polished and user-friendly interface can be challenging. You may have struggled with designing and implementing consistent and visually appealing styles across the entire application. This might include challenges related to layout design, color schemes, responsive design for various screen sizes, and ensuring that your styles work as expected in different web browsers.
Addressing this challenge may involve learning and using CSS best practices, understanding CSS frameworks (such as Bootstrap), and spending time fine-tuning the styling to achieve the desired look and feel for your website. It's common for developers to iterate through multiple design revisions and make adjustments to achieve a visually appealing and user-friendly design.

<!-- MOCKUPS -->
## Final Outcome

### Mockups
![Alt text](home.jpg
)
<br>
![Alt text](compare.jpg
)
<br>
![Alt text](chart.jpg
)

<!-- VIDEO DEMONSTRATION -->
### Video Demonstration

To see a run through of the application, click below:

[View Demonstration](https://drive.google.com/file/d/1NGFQRjZjbKTZfkI7rD953dGHe0_uxuZx/view?usp=sharing 
)

<!-- AUTHORS -->
## Authors

* **Jarryd Carelse** 

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.\

<!-- LICENSE -->
## Contact

* **Jarryd Carelse** - [221267@virtualwindow.co.za](mailto:email@address)
