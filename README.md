✈️ **Expedia Flight Reservation Platform**

Expedia is a browser-based air-travel reservation management platform crafted to oversee airline processes, airport administration, passenger registries, ticket reservations, and all related components. The system is developed using PHP (with MySQL stored routines), HTML, CSS (Bootstrap), and JavaScript (jQuery).

🚀 Key Capabilities
🌍 Nation Administration

Create, modify, and display nations. Each nation may contain numerous cities and aviation terminals.

🏙️ City Administration

Handle towns linked to specific nations.

🛫 Airport Administration

Oversee airports, including associating them with their respective towns and nations.

🏢 Airline Activities

Administer airlines and their operational duties.

📑 Reservation Handling

Generate and manage flight reservations, seat classes, reservation types, and payment categories.

👥 Passenger Registry

Maintain traveler information, including identification records, gender details, and reservation data.

💱 Currency Handling

Support multiple currencies for fare calculations and billing.

🪪 ID Document Types

Administer identification categories for travelers.

🚻 Gender Options

Manage gender selections for passenger details.

💻 User Interface

Adaptive interface built with Bootstrap and Font Awesome icons.

📁 Project Layout
Country.html
Controllers/
    airlineoperations.php
    airportoperations.php
    bookingclassoperations.php
    bookingoperations.php
    bookingsupplyoperations.php
    bookingtypeoperations.php
    cityoperations.php
    countryoperations.php
    currencyoperations.php
    flightsupplyoperations.php
    genderoperations.php
    identificationoperations.php
    passengermanifestoperations.php
    paymentmethodoperations.php
CSS/
    all.min.css
    bootstrap.min.css
ExpediaDB/
    ExpediaFlightBookingDB.sql
Images/
JS/
    country.js
    ...
Models/
    airport.php
    booking.php
    city.php
    country.php
    currency.php
    db.php
    gender.php
    identification.php
    passengermanifest.php
    ...
webfonts/


Country.html: Primary interface for managing nations.

Controllers/: PHP processors for AJAX actions and core logic.

Models/: PHP objects for database correspondence, each tied to a specific entity.

JS/: JavaScript resources for browser-side interaction (e.g., country.js).

CSS/: Stylesheets (Bootstrap + Font Awesome).

ExpediaDB/: SQL definitions and stored routine scripts.

🗄️ Database Overview

MySQL schema including stored routines for complete CRUD functionality.
Refer to ExpediaDB/ExpediaFlightBookingDB.sql for full structure.

🛠️ Installation Steps

Copy the project into your server directory (e.g., htdocs for XAMPP).

Load the database:

Open phpMyAdmin.

Create a schema titled expediaflightbooking.

Import ExpediaFlightBookingDB.sql.

Configure PHP:

Ensure PHP and MySQL are active (via XAMPP or similar).

Default login details (root, no password) should work.

Launch the system:

In your browser, open:
http://localhost/Xpedia/Country.html

🧰 Tools & Technologies

Server-Side: PHP (OOP), MySQL (stored routines)

Client-Side: HTML, Bootstrap, Font Awesome, jQuery

Communication: AJAX for asynchronous operations

🤝 Contributions

Submissions are appreciated. For major adjustments, kindly create an issue to discuss proposed enhancements.

📄 License

This system is intended strictly for learning and academic demonstration.

✈️ Expedia Flight Reservation System

Effortlessly supervise your airline operations.
