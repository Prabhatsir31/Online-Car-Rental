# Online Car Rental

A web-based application for renting cars online. This project enables users to browse, book, and manage car rentals, while providing admins with tools to manage vehicles, bookings, and users.

---

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Database Setup](#database-setup)
- [Default Credentials](#default-credentials)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## Demo

_Add screenshots or a link to a demo if available._

---

## Features

- **User Registration and Login**  
  Secure authentication for users and admins.

- **Car Browsing**  
  Search and filter available cars by brand, price, and more.

- **Booking System**  
  Users can book and manage their car rentals online.

- **Admin Dashboard**  
  Manage vehicles, bookings, users, and view analytics.

- **Responsive Design**  
  Mobile-friendly and accessible user interface.

- **Email Notifications**  
  Automated emails for booking confirmations and status updates.

---

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Bootstrap, Less
- **Backend:** PHP
- **Database:** MySQL
- **Other:** jQuery, AJAX

---

## Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/Prabhatsir31/Online-Car-Rental.git
    cd Online-Car-Rental
    ```

2. **Install Dependencies**  
   Ensure you have PHP, MySQL, and a web server (e.g., XAMPP/LAMP/WAMP) installed.

3. **Database Setup**  
   - Create a database named `carrental`.
   - Import the provided SQL file (`carrental.sql`) into your MySQL server.

4. **Configure Database Connection**  
   Update your database credentials in the configuration file (likely `includes/config.php`).

5. **Run the Application**  
   - Place the project folder in your web server’s root directory.
   - Start your web server and navigate to `http://localhost/Online-Car-Rental` in your browser.

---

## Usage

### Default Credentials

#### User
- **Username:** test@gmail.com
- **Password:** Test@12345

#### Admin
- **Username:** admin
- **Password:** Test@12345

---

## Database Setup

- Database Name: `carrental`
- Import the included SQL file before running the project.
- Without the database, the project will not function.

---

## Folder Structure

```
Online-Car-Rental/
  ├─ admin/                  # Admin dashboard files
  ├─ assets/                 # Static assets (CSS, JS, images)
  ├─ includes/               # Configuration and helper scripts
  ├─ pages/                  # User-facing pages
  ├─ vendor/                 # Third-party libraries (if any)
  ├─ carrental.sql           # Database schema
  ├─ index.php               # Entry point
  └─ README.md
```


---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to your branch (`git push origin feature/your-feature`)
5. Open a pull request

---

## License

_This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information._

---

## Contact

If you find any errors or have questions, feel free to contact us.

- [Your Name/Team]
- [Your Email]
- [GitHub Issues](https://github.com/Prabhatsir31/Online-Car-Rental/issues)

---

## Acknowledgments

- Thanks to everyone who has contributed or provided feedback.
- Leave a comment or star the repo if you enjoy the project!

---

Thank you for downloading and using Online Car Rental!
