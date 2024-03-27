<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Clothing Donation Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Navigation Bar -->
  <nav>
    <div class="logo">
      <img src="https://i.pinimg.com/736x/82/15/56/821556d35fd814575d7bc445987a57cc--needy-people-hot-clothes.jpg" alt="Logo">
      <h1>Clothing Donation</h1>
    </div>
    <ul class="nav-links">
      <li><a href="index.html">Home</a></li>
      <li><a href="services.html">Services</a></li>
      <li><a href="confirmation.html">Confirmation</a></li>
    </ul>
  </nav>
  <!-- Services Page -->
  <section class="services">
    <h2>Donate Now</h2>
    <form id="donationForm" action="confirmation.html" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      <label for="address">Address:</label>
      <input type="text" id="address" name="address" required>
      <label for="numOfClothes">Number of Clothes:</label>
      <input type="number" id="numOfClothes" name="numOfClothes" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <input type="submit" value="Submit">
    </form>
    <div id="thankYouMessage" style="display: none;">
      <p>Thank you for your donation!</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2024 Clothing Donation. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById("donationForm").addEventListener("submit", function(event) {
      event.preventDefault(); // Prevent the form from submitting
      document.getElementById("donationForm").style.display = "none"; // Hide the form
      document.getElementById("thankYouMessage").style.display = "block"; // Show the thank you message
    });
  </script>
</body>
</html>

