Responsive Webpage Project
This project is a simple webpage featuring a fixed navbar, collapsible left menu, main content area, and right-side panel. Additionally, the webpage adjusts its scaling based on the screen size to provide a better user experience across different devices.

Features
Fixed Navbar: A navbar that stays at the top and does not move when scrolling.
Three Sections:
Left Menu: A collapsible menu on the left side of the screen.
Main Content: The main content area where information or other elements will be displayed.
Right Panel: A side panel on the right for additional information or widgets.
Footer: A footer that stays at the bottom of the page.
Responsive Design: The page dynamically shrinks based on the width of the screen using JavaScript:
If the screen width is between 992px and 1600px, shrink the page by 90%.
If the screen width is between 700px and 767px, shrink the page by 80%.
If the screen width is between 600px and 700px, shrink the page by 75%.
If the screen width is less than or equal to 600px, shrink the page by 50%.
Prerequisites
Text Editor: Visual Studio Code.
Web Browser: Google Chrome, Mozilla Firefox, or any modern browser to view and test the webpage.

Setup
Clone the Repository: Clone the repository or download the project files to your local machine.

Open in Text Editor: Open the index.html, styles.css, and script.js files in your preferred text editor.

Open in Web Browser: After opening the files, open index.html in your browser to view the webpage.

File Breakdown
1. index.html
This is the main HTML structure of the webpage. It contains the fixed navbar, three sections (left menu, main content area, and right panel), and footer. The left menu is collapsible, and the JavaScript function will manage the page's scaling based on screen width.

2. styles.css
This file contains the CSS for styling the webpage. It includes styles for the fixed navbar, collapsible menu, main content, and right panel. It also ensures the page is responsive, with media queries to handle different screen sizes.

3. script.js
This JavaScript file handles the scaling functionality. It checks the width of the screen and applies the appropriate scaling based on the width ranges mentioned in the requirements.
