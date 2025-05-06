# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
# HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Cyber Tools Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Cyber Tools Store</h1>
            <p>Your One-Stop Shop for Ethical Hacking Hardware</p>
        </header>

        <section class="products">
            <div class="product">
                <img src="rasperi.jpeg" alt="Raspberry Pi 4">
                <h2>Raspberry Pi 4</h2>
                <p>Perfect for building hacking labs, running Kali Linux, or as a portable server.</p>
                <span>$60</span>
            </div>

            <div class="product">
                <img src="usb-analyzer.png" alt="USB Packet Sniffer">
                <h2>USB Packet Sniffer</h2>
                <p>Analyze USB traffic, perfect for hardware reverse engineering.</p>
                <span>$45</span>
            </div>

            <div class="product">
                <img src="wifiadaot.jpg" alt="WiFi Adapter">
                <h2>Alpha WiFi Adapter</h2>
                <p>Compatible with Kali Linux, ideal for WiFi pentesting.</p>
                <span>$35</span>
            </div>
        </section>

        <!-- About Section -->
        <section class="info-section" id="about">
            <h2>About Us</h2>
            <p>We are passionate about cybersecurity and provide the best tools for ethical hackers, students, and professionals. Our mission is to empower you with the hardware needed to learn, test, and grow in the field of cybersecurity.</p>
        </section>

        <!-- Contact Section -->
        <section class="info-section" id="contact">
            <h2>Contact Us</h2>
            <p>Email: cybertools@securemail.com</p>
            <p>Phone: +91-98765-43210</p>
            <p>Instagram: @cybertoolsstore</p>
        </section>

        <footer>
            <p>&copy; 2025 Cyber Tools Store</p>
        </footer>
    </div>
</body>
</html>

```

# CSS:
```
body {
    margin: 0;
    padding: 0;
    font-family: 'Segoe UI', sans-serif;
    background-color: #0d0d0d; /* dark black */
    color: #e0e0e0; /* light grey */
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
    padding: 20px;
}

header {
    text-align: center;
    padding: 20px;
    background-color: #001f3f; /* deep cyber blue */
    color: #00ffff; /* neon cyan */
    border-radius: 10px;
}

.products {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-top: 30px;
    gap: 20px;
}

.product {
    background-color: #1a1a1a;
    border: 1px solid #00ffff;
    padding: 15px;
    border-radius: 10px;
    width: 280px;
    text-align: center;
    box-shadow: 0 0 15px rgba(0, 255, 255, 0.3);
    transition: transform 0.3s;
}

.product:hover {
    transform: scale(1.05);
}

.product img {
    width: 100%;
    border-radius: 5px;
    margin-bottom: 10px;
}

.product h2 {
    color: #00ffff;
    font-size: 20px;
}

.product p {
    font-size: 14px;
    margin-bottom: 10px;
}

.product span {
    font-weight: bold;
    color: #ffffff;
    font-size: 18px;
}

footer {
    margin-top: 40px;
    text-align: center;
    color: #888;
}

```


## OUTPUT

![438646384-d5b39804-148b-486c-a43c-ebc56cd1d7e0](https://github.com/user-attachments/assets/fd30bf99-98b0-43b6-85b0-91657fbf61ec)
![438646490-c812448c-6048-48e2-9762-d1fcdc114ff7](https://github.com/user-attachments/assets/e8c96ebd-afe4-47e1-a1f9-7f449d709c9f)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
