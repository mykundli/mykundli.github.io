<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Online Kundli</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Online Kundli</h1>
    <p>Discover your past, present, and future</p>
  </header>

  <main>
    <section id="kundli-form">
      <h2>Generate Your Kundli</h2>
      <form id="kundliForm">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>

        <label for="time">Time of Birth:</label>
        <input type="time" id="time" name="time" required>

        <label for="place">Place of Birth:</label>
        <input type="text" id="place" name="place" required>

        <button type="submit">Generate Kundli</button>
      </form>
    </section>

    <section id="kundli-result">
      <h2>Your Kundli</h2>
      <div id="result">
        <p>Enter your details to generate your Kundli.</p>
      </div>
    </section>

    <section id="features">
      <h2>Features</h2>
      <div class="feature">
        <img src="https://via.placeholder.com/150" alt="Previous Birth">
        <h3>Previous Birth</h3>
        <p>Learn about your past life and karmic influences.</p>
      </div>
      <div class="feature">
        <img src="https://via.placeholder.com/150" alt="Future Forecast">
        <h3>Future Forecast</h3>
        <p>Get insights into your future based on planetary positions.</p>
      </div>
      <div class="feature">
        <img src="https://via.placeholder.com/150" alt="Remedies">
        <h3>Remedies</h3>
        <p>Discover remedies to overcome challenges and improve your life.</p>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 Online Kundli. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
