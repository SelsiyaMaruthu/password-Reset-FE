


# Password-Reset

The "Password Reset" project is a web application built using the MERN (MongoDB, Express.js, React, Node.js) stack that facilitates user authentication functionalities such as signup, login, and a password reset mechanism.
## Table of Contents

1.Overview

2.Features

3.Installation

4.Usage

5.Technologies Used

6.Contributing

7.License
## OverView:

The project focuses on providing a secure and user-friendly system for managing user accounts and passwords. It includes the following key functionalities:

1. Signup Page: Allows users to create new accounts by providing necessary details like username, email, and password.

2. Login Page: Provides authentication for registered users to access their accounts securely.

3. Forgot Password Request via Email: Allows users who have forgotten their passwords to request a password reset. An email with a unique reset link is sent to their registered email address for verification.

4. Password Reset: Once the user clicks on the reset link received via email, they're directed to a page where they can securely reset their password.
## Features:

* User-friendly interface for signup and login functionalities.

* Security measures implemented for storing passwords (hashing, salting) in the database.

* Utilization of Node Mailer for sending password reset emails securely.

* A secure and straightforward process for users to reset their passwords.
## Technologies Used:

* Frontend: React
* Backend: Node.js, Express.js
* Database: MongoDB
* Additional Libraries/Tools: Node Mailer (for sending emails), bcrypt (for password hashing), etc.
