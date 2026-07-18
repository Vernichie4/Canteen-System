PROJECT TITLE:
MoMuMaNay: Simple Online Canteen Ordering and Receipt System

SECTION:
CSIT371L

GROUP NUMBER:
BSIT3A_GROUP03_CANTEEN_SYSTEM

GROUP MEMBERS:
1. Malfroy Dash Alfonso
2. John Aster Dublin
3. Chaps Marquez
4. Jpeniel Tolentino
5. Aleli Vernice Vitug

SYSTEM REQUIREMENTS:
- XAMPP (Apache + MySQL)
- PHP 8.x
- MySQL / phpMyAdmin
- Composer (for TCPDF)
- Web browser (Chrome/Edge/Firefox)

DATABASE NAME:
canteen_db

ADMIN ACCOUNT:
Email: admin@gmail.com  
Password: admin123  

USER ACCOUNT:
Email: aleli@gmail.com  
Password: 22233  

PROJECT URL AFTER SETUP:
http://localhost/BSIT3A_GROUP03_CANTEEN_SYSTEM/SOURCE_CODE/canteen_system/login.php

STEPS TO RUN THE SYSTEM:
1. Extract the ZIP file.  
2. Copy the `BSIT3A_GROUP03_CANTEEN_SYSTEM` folder to `D:\xampp\htdocs\`.  
3. Open XAMPP Control Panel.  
4. Start Apache and MySQL.  
5. Open phpMyAdmin (http://localhost/phpmyadmin).  
6. Create a database named `canteen_db`.  
7. Import the SQL file located at:  
   `D:\xampp\htdocs\BSIT3A_GROUP03_CANTEEN_SYSTEM\DATABASE\canteen_db.sql`  
8. Open browser and go to:  
   `http://localhost/BSIT3A_GROUP03_CANTEEN_SYSTEM/SOURCE_CODE/canteen_system/login.php`  
9. Login using the admin or user account written above.  

FEATURES COMPLETED:
[✓] Registration
[✓] Login and Session
[✓] Admin Food CRUD
[✓] Search Food
[✓] User Ordering
[✓] Auto Computation
[✓] Upload Proof of Payment
[✓] Payment Simulation
[✓] Email/SMS Simulation
[✓] Import CSV/Excel
[✓] Export CSV/Excel
[✓] PDF Receipt
[✓] Socket Demo
[✓] Basic OOP
[✓] Documentation
[✓] Screenshots

KNOWN ERRORS OR LIMITATIONS:
- UI/UX design is basic and may look rusty.  
- Real email/SMS notifications are not implemented; only simulated.  
- Reference numbers cannot be automatically confirmed; must be checked manually by admin.  
- Some greeting messages are missing on certain pages.  
- Despite these limitations, all main functions work as intended.  

SPECIAL NOTES FOR THE TEACHER:
- Please refer to the included screenshots in the documentation for visual confirmation of each feature.  
- The socket demo requires running `server.php` and `client.php` from the `socket_demo` folder in separate terminals.  
- PDF receipts require Composer and TCPDF installed (`composer install` in project root).  
