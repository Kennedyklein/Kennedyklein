<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE SOFT COPY ARCHIVE</title>
    <style>
        /* Basic Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }
        header {
            background-color: #1e90ff;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h2 {
            border-bottom: 2px solid #1e90ff;
            padding-bottom: 10px;
        }
        .downloads {
            margin-bottom: 20px;
        }
        .download-button {
            background-color: #1e90ff;
            color: white;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #1e90ff;
            color: #fff;
        }
        /* Media Queries for Mobile */
        @media(max-width: 600px) {
            nav ul li {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to THE SOFT COPY ARCHIVE</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#downloads">Downloads</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About THE SOFT COPY ARCHIVE</h2>
        <p>Welcome to THE SOFT COPY ARCHIVE! This platform is dedicated to providing you with a wide range of educational PDFs. Feel free to browse and download resources to aid your learning journey. All downloads are free until you reach a maximum of 7 downloads. After that, you will be charged, and the payment will be directed to the account number provided below.</p>
        <a href="#downloads" class="download-button">Start Downloading</a>
    </section>

    <!-- Downloads Section -->
    <section id="downloads">
        <h2>Available Downloads</h2>
        <div class="downloads">
            <h3>PDF 1: Example Educational Material</h3>
            <a href="link_to_pdf1.pdf" class="download-button">Download</a>
        </div>
        <div class="downloads">
            <h3>PDF 2: Another Educational Resource</h3>
            <a href="link_to_pdf2.pdf" class="download-button">Download</a>
        </div>
        <!-- Add more PDFs as needed -->
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions, feel free to reach out:</p>
        <p>Email: <a href="mailto:josephboke33@gmail.com">josephboke33@gmail.com</a></p>
        <p>Phone: 0700328300</p>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Kennedy Clein. All rights reserved. Payments are directed to MPESA account 0700328300.</p>
    </footer>

    <!-- JavaScript for Interactivity -->
    <script>
        // Example feature: track download count and limit to 7 free downloads
        let downloadCount = 0;

        document.querySelectorAll('.download-button').forEach(button => {
            button.addEventListener('click', function(event) {
                if (downloadCount < 7) {
                    downloadCount++;
                    alert('Download started! You have ' + (7 - downloadCount) + ' free downloads remaining.');
                } else {
                    alert('You have reached your free download limit. Please contact Kennedy Clein for further downloads.');
                    event.preventDefault(); // Prevents the download from starting after the limit
                }
            });
        });
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE SOFT COPY ARCHIVE</title>
    <style>
        /* Basic Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }
        header {
            background-color: #1e90ff;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h2 {
            border-bottom: 2px solid #1e90ff;
            padding-bottom: 10px;
        }
        .downloads {
            margin-bottom: 20px;
        }
        .download-button {
            background-color: #1e90ff;
            color: white;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #1e90ff;
            color: #fff;
        }
        /* Media Queries for Mobile */
        @media(max-width: 600px) {
            nav ul li {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to THE SOFT COPY ARCHIVE</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#downloads">Downloads</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About THE SOFT COPY ARCHIVE</h2>
        <p>Welcome to THE SOFT COPY ARCHIVE! This platform is dedicated to providing you with a wide range of educational PDFs. Feel free to browse and download resources to aid your learning journey. All downloads are free until you reach a maximum of 7 downloads. After that, you will be charged, and the payment will be directed to the account number provided below.</p>
        <a href="#downloads" class="download-button">Start Downloading</a>
    </section>

    <!-- Downloads Section -->
    <section id="downloads">
        <h2>Available Downloads</h2>
        <div class="downloads">
            <h3>PDF 1: Example Educational Material</h3>
            <a href="link_to_pdf1.pdf" class="download-button">Download</a>
        </div>
        <div class="downloads">
            <h3>PDF 2: Another Educational Resource</h3>
            <a href="link_to_pdf2.pdf" class="download-button">Download</a>
        </div>
        <!-- Add more PDFs as needed -->
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions, feel free to reach out:</p>
        <p>Email: <a href="mailto:josephboke33@gmail.com">josephboke33@gmail.com</a></p>
        <p>Phone: 0700328300</p>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Kennedy Clein. All rights reserved. Payments are directed to MPESA account 0700328300.</p>
    </footer>

    <!-- JavaScript for Interactivity -->
    <script>
        // Example feature: track download count and limit to 7 free downloads
        let downloadCount = 0;

        document.querySelectorAll('.download-button').forEach(button => {
            button.addEventListener('click', function(event) {
                if (downloadCount < 7) {
                    downloadCount++;
                    alert('Download started! You have ' + (7 - downloadCount) + ' free downloads remaining.');
                } else {
                    alert('You have reached your free download limit. Please contact Kennedy Clein for further downloads.');
                    event.preventDefault(); // Prevents the download from starting after the limit
                }
            });
        });
    </script>
</body>
</html>
