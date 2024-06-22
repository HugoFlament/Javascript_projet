<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About Us</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>

    <div id="content">
        <!-- Content will be inserted here -->
    </div>
</body>
</html>

<!-- index.html -->
<div>
    <h1>Welcome to Our Website</h1>
    <p>This is the best place to find information about beautiful places to visit.</p>
</div>

<!-- about.html -->
<div>
    <h1>About Us</h1>
    <p>We are travel enthusiasts who love to explore and recommend amazing destinations around the world.</p>
</div>

<!-- contact.html -->
<div>
    <h1>Contact Us</h1>
    <form action="submit_form.php" method="post">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <input type="submit" value="Submit">
    </form>
</div>

<!-- index.html -->
<div>
    <h2>Beach Recommendations</h2>
    <div class="recommendation">
        <h3>Beach 1</h3>
        <img src="beach1.jpg" alt="Beach 1">
    </div>
    <div class="recommendation">
        <h3>Beach 2</h3>
        <img src="beach2.jpg" alt="Beach 2">
    </div>
</div>

<!-- index.html -->
<div>
    <h2>Temple Recommendations</h2>
    <div class="recommendation">
        <h3>Temple 1</h3>
        <img src="temple1.jpg" alt="Temple 1">
    </div>
    <div class="recommendation">
        <h3>Temple 2</h3>
        <img src="temple2.jpg" alt="Temple 2">
    </div>
</div>

<!-- index.html -->
<div>
    <h2>Country Recommendations</h2>
    <div class="recommendation">
        <h3>Country 1</h3>
        <img src="country1.jpg" alt="Country 1">
    </div>
    <div class="recommendation">
        <h3>Country 2</h3>
        <img src="country2.jpg" alt="Country 2">
    </div>
</div>



