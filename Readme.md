<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

  <h1>🚗 Car Rental System</h1>
  <p><strong>Car Rental System</strong> is a PHP-based web application that allows users to rent cars and administrators to manage car listings and bookings. It features a user-friendly interface for customers and an admin panel for managing the system.</p>

  <h2>🎯 Features</h2>
  <ul>
    <li>User registration and login</li>
    <li>Browse available cars for rent</li>
    <li>Book cars for specific dates</li>
    <li>Admin panel to manage car listings and bookings</li>
    <li>Responsive design for various devices</li>
  </ul>

  <h2>📁 Project Structure</h2>
  <pre>
Car-Rental/
├── admin/              --> Admin panel files
├── assets/             --> CSS, JavaScript, and image assets
├── includes/           --> PHP include files
├── user/               --> User dashboard and booking files
├── index.php           --> Homepage
├── login.php           --> User login page
├── register.php        --> User registration page
├── contact.php         --> Contact form
├── about.php           --> About page
├── LICENSE             --> License file
  </pre>

  <h2>⚙️ Installation</h2>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/Vexx-bit/Car-Rental.git</code></pre>
    </li>
    <li>Set up a MySQL database and import the provided SQL file:
      <ul>
        <li>Create a new database named <code>carrental</code></li>
        <li>Import the <code>carrental.sql</code> file located in the <code>database/</code> directory</li>
      </ul>
    </li>
    <li>Configure the database connection:
      <ul>
        <li>Open <code>includes/config.php</code></li>
        <li>Update the database credentials accordingly</li>
      </ul>
    </li>
    <li>Run the application:
      <ul>
        <li>Place the project folder in your web server's root directory (e.g., <code>htdocs</code> for XAMPP)</li>
        <li>Start your web server and navigate to <code>http://localhost/Car-Rental/</code></li>
      </ul>
    </li>
  </ol>

  <h2>🔐 Default Login Credentials</h2>
  <h3>User Account</h3>
  <ul>
    <li>Username: <code>test@gmail.com</code></li>
    <li>Password: <code>Test@123</code></li>
  </ul>

  <h3>Admin Account</h3>
  <ul>
    <li>Username: <code>admin</code></li>
    <li>Password: <code>Test@12345</code></li>
  </ul>

  <h2>📄 License</h2>
  <p>This project is licensed under the terms of the <a href="https://github.com/Vexx-bit/Car-Rental/blob/main/LICENSE">MIT License</a>.</p>

  <p>Developed with ❤️ by <a href="https://github.com/Vexx-bit">Samuel Kang'ethe</a></p>

</body>
</html>
