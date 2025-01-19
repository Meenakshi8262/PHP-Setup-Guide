# PHP Project Setup Guide

This guide will help you get your PHP files running on your local machine using XAMPP.

## Prerequisites

1. **Download and Install XAMPP**
   - If you don't have XAMPP installed, download and install it from the following link:  
     [Download XAMPP](https://www.apachefriends.org/download.html)
   
   - XAMPP includes Apache (web server), MySQL (database), and PHP, making it easy to set up a local development environment.

2. **PHP Files**
   - Ensure you have the PHP files (such as `info.php` and `hello_world.php`) in a folder ready to be added to your XAMPP setup.

---

## Steps to Set Up and Run PHP Files

### 1. Install XAMPP
   - Download and install XAMPP from the link above, and follow the installation instructions for your operating system.

### 2. Place PHP Files in the `htdocs` Folder
   - After installing XAMPP, navigate to the folder where you installed XAMPP (typically `C:\xampp` on Windows or `/Applications/XAMPP` on macOS).
   - Open the `htdocs` folder inside the XAMPP installation directory.
   - Copy the PHP files (e.g., `info.php`, `hello_world.php`) from your project folder into the `htdocs` folder.

### 3. Start Apache in XAMPP
   - Open the XAMPP Control Panel.
   - Click **Start** next to the **Apache** module to run the web server.

### 4. Access PHP Files in Your Browser
   - Once Apache is running, open your preferred web browser.
   - Type the following URLs in your browser’s address bar:
     - To check PHP configuration: `http://localhost/info.php`
     - To view the "Hello World" PHP file: `http://localhost/hello_world.php`

   - You should see the output of both PHP files. If everything is set up correctly, you should see:
     - Information about your PHP installation on the `info.php` page.
     - A "Hello World" message or whatever content you have on the `hello_world.php` page.

---

## Troubleshooting

- If you can't access the pages, make sure Apache is running in the XAMPP Control Panel.
- Ensure that the file names are correct, and you are using the right paths.
- If Apache doesn’t start, check if another application is using port 80 and resolve the conflict.

---



