Soul Code Calculator (SCLC)
Soul Code Calculator is a web-based numerology application designed to calculate "Soul Code" and "Life Code" based on an individual's date of birth and birth time. It visualizes the data through matrices and prediction triangles, and calculates a specific "Lucky Number" using a unique algorithm.


Features
=============
Dual Calendar Calculation: Calculates data based on both Solar (Soul Code) and Lunar (Life Code) calendars.

Numerology Charts:

Matrix (Bingo Line): Visual representation of number frequencies and connections.

Triangle Prediction: 9-year cycle prediction based on the current year.

IQ & Relations: Interpretations for relationship types (Parent, Teacher, Friend, Partner, Guru, Self).

Lucky Number System:

Uses complex calculation logic (Variables A-J) to determine a 4-digit lucky number.

Validation System: Automatically checks if the calculated Lucky Number aligns with the Soul/Life Code base number to ensure accuracy.

PDF Export: Built-in "Save PDF / Print" feature formatted perfectly for A4 paper.

Responsive Design: Works seamlessly on Desktop, Tablets, and Mobile devices.

Input Flexibility: Robust date parsing supports YYYY-MM-DD and DD/MM/YYYY formats.

Tech Stack
Core: HTML5, JavaScript (ES6+)

Styling: Tailwind CSS (via CDN)

Libraries:

lunar-javascript: For Solar to Lunar date conversion.

toastify-js: For alert notifications.


How to Run
=============
Since this is a static Single Page Application (SPA), no backend server installation is required.

Clone or Download the repository.

Ensure you have an active internet connection (required to load Tailwind CSS and libraries via CDN).

Open index.html (or your filename) directly in any modern web browser (Chrome, Edge, Safari, Firefox).

Tip: For the best experience during development, use the "Live Server" extension in VS Code.

Usage Guide
=============
Enter Details:

Name: Enter the client's name.

Date of Birth: Select from the calendar or type manually.

Time: Enter birth time (default is 00:00).

Predict Year: Enter the year you want to forecast (default is current year).

Calculate: Click the "SCLC Code" button.

View Results: Scroll down to see the Soul/Life tables, Matrices, Triangles, and Lucky Numbers.

Export: Click "Save PDF / Print" to save the analysis as a PDF file or print it on A4 paper.

Algorithm Overview
=============
Basic Calculation (Recursive Sum)
Numbers are summed recursively until they become a single digit (except for specific intermediate steps in the chart).

Example: 1985 -> 1+9+8+5 = 23 -> 2+3 = 5.

Lucky Number Logic
The application uses a specific step-by-step logic (A to J) to generate a 4-digit code:

Left Side: Sum of Day + Month.

Right Side: Sum of Year digits.

Combination: Cross-summation between left and right results to generate variables C, D, E, F, G, H, I, J.

Result: The final code is derived from G I F J.

Validation: The system sums the result of the Lucky Number and compares it against the Start Number (Soul/Life Code base) to verify accuracy.


License
=============
This project is for educational and personal use.


Note for Developers
If you encounter CORS issues or libraries not loading, please check your internet connection as the project relies on jsDelivr and CDNjs.

Created by SoulCodeJourney Team
