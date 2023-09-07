# Certificate Automation

Certificate Automation is a PHP web application that simplifies the process of importing student data from Excel files, generating completion certificates in both image and PDF formats, and automatically sending these certificates to recipients via email. This application is designed for educational institutions and organizations that need to efficiently manage and distribute certificates to their students.

## Features

- **Excel File Import:** Easily import Excel files (.xls) containing student data.
- **Search Functionality:** Quickly search for students by email address.
- **Certificate Generation:** Automatically generate completion certificates in image (JPG) and PDF formats.
- **Download Certificates:** Download generated certificates with one click.
- **Email Integration:** Send certificates to individual students via email.
- **Bulk Email Sending:** Send certificates to all students in one go.

## Usage

1. Clone this repository to your web server.
2. Configure your database connection in `config.php`.
3. Install the required libraries: [FPDF](http://www.fpdf.org/), [TCPDF](https://tcpdf.org/), and [PHPMailer](https://github.com/PHPMailer/PHPMailer).
4. Access the application through a web browser.
5. Upload an Excel file containing student information.
6. Search for specific students if needed.
7. Download individual certificates in JPG and PDF formats.
8. Send certificates to students via email.
9. Optionally, use the "Send Email to All" feature to send certificates to all students in the database.

## Configuration


- Database connection settings (`require 'config.php'` and `require '../config.php'`).
- SMTP configuration settings (SMTP server, username, password, etc.) in the email sending scripts.
- HTML email body template to match your organization's branding in the email sending scripts.

## Requirements

- PHP with a valid database connection.
- [FPDF](http://www.fpdf.org/) library for PDF generation.
- [TCPDF](https://tcpdf.org/) for advanced PDF handling.
- [PHPMailer](https://github.com/PHPMailer/PHPMailer) library for email sending.
- Web server (e.g., Apache) to host the application.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
