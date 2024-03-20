# PHP Learning Journey Lesson: Day 1 - Introduction to PHP

Welcome to Day 1 of your PHP learning journey! Today, we'll dive into the basics of PHP and set up your development environment to start writing PHP code.

## Goals:
- Understand what PHP is and its role in web development.
- Set up a local development environment to run PHP scripts.
- Write and execute your first "Hello World" PHP script.

## 1. Understanding PHP:
PHP (Hypertext Preprocessor) is a widely-used server-side scripting language that is especially suited for web development. It can generate dynamic page content, interact with databases, and handle forms, among other things. PHP code is executed on the server, generating HTML output that is sent to the client's web browser.

## 2. Setting Up Environment:
To write and run PHP code, you'll need a local development environment. Here are the steps to set up a basic environment using XAMPP (cross-platform Apache, MySQL, PHP, and Perl):

- **Download XAMPP:** Visit the [XAMPP website](https://www.apachefriends.org/index.html) and download the appropriate version for your operating system.

- **Install XAMPP:** Follow the installation instructions provided for your operating system. Once installed, launch the XAMPP Control Panel.

- **Start Apache Server:** In the XAMPP Control Panel, start the Apache server. This will allow you to run PHP scripts locally.

## 3. Writing Your First Script:
Now that you have your development environment set up, let's write a simple "Hello World" PHP script.

1. Open a text editor (such as Notepad, Visual Studio Code, or Sublime Text).
2. Create a new file and save it with a `.php` extension (e.g., `hello.php`).
3. Write the following PHP code in your file:

    ```php
    <?php
    echo "Hello, world!";
    ?>
    ```

4. Save the file in the `htdocs` directory within your XAMPP installation folder (typically located at `C:\xampp\htdocs` on Windows or `/Applications/XAMPP/htdocs` on macOS).
5. Open your web browser and navigate to `http://localhost/hello.php`. You should see the text "Hello, world!" displayed in your browser.

Congratulations! You've successfully written and executed your first PHP script.

## Next Steps:
Now that you've set up your development environment and written your first PHP script, take some time to explore PHP further. In the next lessons, we'll dive deeper into PHP syntax, variables, and basic operations.

Feel free to experiment with PHP code, explore online tutorials, and start thinking about the exciting web projects you can build with PHP.

Happy coding! 🚀
