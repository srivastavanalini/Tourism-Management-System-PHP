# Tourism Management System (TMS)

[![PHP Version](https://img.shields.io/badge/PHP-7.4%2B-blue.svg)](https://www.php.net/)
[![MySQL Version](https://img.shields.io/badge/MySQL-8.0%2B-orange.svg)](https://www.mysql.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()

A comprehensive web-based platform designed to streamline tourism operations, allowing users to browse and book tour packages while providing administrators with robust management tools.

---

## ![Features](https://img.shields.io/badge/Main-Features-blue?style=for-the-badge)

### ![User Panel](https://img.shields.io/badge/For-Users-lightgrey?style=flat-square)
- **User Authentication**: Secure sign-up and sign-in functionality.
- **Package Browsing**: Explore a wide range of tour packages with detailed information and pricing.
- **Online Booking**: Seamless booking process for selected tour packages.
- **Tour History**: Track and manage personal booking history.
- **Issue Ticketing**: Raise and monitor support tickets for tour-related problems.
- **Account Management**: Update profile details and manage security settings.

### ![Admin Panel](https://img.shields.io/badge/For-Admins-lightgrey?style=flat-square)
- **Centralized Dashboard**: Overview of system statistics including bookings, users, and enquiries.
- **Package Management**: Create, update, and manage tour package details and images.
- **Booking Oversight**: Monitor, approve, or cancel user bookings efficiently.
- **User Administration**: Manage system users and their active statuses.
- **Issue Resolution**: View and respond to user-reported tickets.
- **Enquiry Management**: Handle incoming queries from potential customers.
- **Content Management (CMS)**: Manage static pages like Contact Us, About Us, and Privacy Policy.

---

## ![Tech Stack](https://img.shields.io/badge/Technology-Stack-blue?style=for-the-badge)

- **Frontend**: ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
- **Backend**: ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
- **Database**: ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
- **Server**: ![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=flat-square&logo=xampp&logoColor=white) / ![WAMP](https://img.shields.io/badge/WAMP-3F51B5?style=flat-square) / ![LAMP](https://img.shields.io/badge/LAMP-000000?style=flat-square)

---

## ![Installation](https://img.shields.io/badge/Installation-Guide-blue?style=for-the-badge)

1. **Clone or Download**: Download the repository to your local machine.
2. **Move Folder**: Copy the `tms` folder to your server's root directory (e.g., `xampp/htdocs`, `wamp/www`, or `/var/www/html`).
3. **Database Setup**:
   - Open **PHPMyAdmin**.
   - Create a new database named `tms`.
   - Import the `tms.sql` file (found in the `SQl FIle` folder).
4. **Configuration**:
   - Ensure your database connection settings in `tms/includes/config.php` match your local environment.
5. **Launch**:
   - Access the User Portal: `http://localhost/tms`
   - Access the Admin Portal: `http://localhost/tms/admin`

---

## ![Credentials](https://img.shields.io/badge/Access-Credentials-blue?style=for-the-badge)

### ![Admin Portal](https://img.shields.io/badge/Admin-Access-red?style=flat-square)
- **Username**: `admin`
- **Password**: `Test@123`

### ![User Portal](https://img.shields.io/badge/User-Access-green?style=flat-square)
- **Username**: `test@gmail.com`
- **Password**: `Test@123`

---

## ![Structure](https://img.shields.io/badge/Project-Structure-blue?style=for-the-badge)

```text
├── SQl FIle/           # Contains database export (tms.sql)
└── tms/                # Main Application Folder
    ├── admin/          # Administrator Dashboard and Management
    ├── css/            # Stylesheets
    ├── fonts/          # Custom Web Fonts
    ├── images/         # Static Media Assets
    ├── includes/       # Reusable components (Header, Footer, Config)
    ├── js/             # Client-side scripts
    └── ...             # Core PHP Pages (index.php, profile.php, etc.)
```

---

## ![Security](https://img.shields.io/badge/Security-Notice-blue?style=for-the-badge)
- SQL Injection protection via prepared statements (recommended for production).
- Password management features.
- Session-based authentication for both User and Admin panels.

---

## ![License](https://img.shields.io/badge/License-Information-blue?style=for-the-badge)
This project is open-source and available under the ![MIT License](https://img.shields.io/badge/License-MIT-green?style=flat-square).
