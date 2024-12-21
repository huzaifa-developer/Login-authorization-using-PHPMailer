# User Registration with OTP Verification via Email

This project demonstrates a basic user registration system where users can sign up by providing their personal details (name, email, password, contact, age, and address). Upon successful registration, an OTP (One-Time Password) is generated and sent to the user's email for verification.

## Features:
- **User Registration:** Collects user details (username, email, password, contact, age, and address) via a simple form.
- **Database Integration:** The user data is inserted into a MySQL database after form submission.
- **Email Verification:** A one-time OTP is generated and sent to the user's email address to confirm their registration.
- **SMTP Mailer Integration:** Uses PHPMailer to send the OTP to the user's email account via Gmail's SMTP server.

## Technology Stack:
- **Backend:** PHP
- **Database:** MySQL
- **Email Sending:** PHPMailer
- **Frontend:** HTML, Bootstrap

## How it Works:
1. The user submits their details via a form.
2. The details are saved in a MySQL database.
3. An OTP is generated and sent to the provided email address.
4. The user can use this OTP for further verification (not implemented in this version).

## Setup:
1. Ensure you have a working PHP environment and MySQL server.
2. Configure the PHPMailer SMTP settings with your email credentials.
3. Create a database and a `user` table with the required fields (`email`, `password`, `contact`, `age`, `address`, `otp`, `username`).
4. Run the signup process by submitting the form.

## Dependencies:
- PHPMailer library for handling email sending.

