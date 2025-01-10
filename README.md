<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Messi Theme</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Welcome to Messi's World!</h1>
    <p>Celebrating the greatest football player of all time.</p>
  </header>

  <section class="content">
    <h2>Messi's Achievements</h2>
    <ul>
      <li>7 Ballon d'Or titles</li>
      <li>Top scorer for Barcelona</li>
      <li>World Cup Champion</li>
      <li>UEFA Champions League winner</li>
    </ul>

    <button class="btn" onclick="changeImage(1)">Messi 1</button>
    <button class="btn" onclick="changeImage(2)">Messi 2</button>
    <button class="btn" onclick="changeImage(3)">Messi 3</button>

    <img id="image" src="messi1.jpg" alt="Lionel Messi" class="image">
    <p id="description">Lionel Messi scoring a stunning free kick.</p>
  </section>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: 'Arial', sans-serif;
  background-color: #f8f8f8;
  color: #333;
  text-align: center;
}

header {
  background-color: #009cde;
  padding: 20px;
  color: white;
}

h1 {
  font-size: 2.5em;
}

h2 {
  font-size: 2em;
}

.content {
  margin: 30px auto;
  padding: 20px;
}

.btn {
  background-color: #009cde;
  color: white;
  padding: 10px 20px;
  margin: 10px;
  cursor: pointer;
  border: none;
  border-radius: 5px;
}

.image {
  max-width: 100%;
  margin-top: 20px;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  font-size: 1.2em;
  margin-bottom: 10px;
}
function changeImage(imageNumber) {
  const image = document.getElementById("image");
  const description = document.getElementById("description");

  switch (imageNumber) {
    case 1:
      image.src = "messi1.jpg";
      description.textContent = "Lionel Messi scoring a stunning free kick.";
      break;
    case 2:
      image.src = "messi2.jpg";
      description.textContent = "Messi celebrating a goal with Barcelona.";
      break;
    case 3:
      image.src = "messi3.jpg";
      description.textContent = "Messi lifting the World Cup trophy.";
      break;
    default:
      break;
  }
}
# Messi Theme

This project is a celebration of Lionel Messi, one of the greatest footballers of all time. The page highlights his achievements, iconic moments, and has an interactive feature to toggle between images of Messi.

## Features
- View different images of Messi by clicking buttons.
- A short description of each image will appear.
- A simple, Messi-themed web design.

## Installation
1. Clone the repository.
2. Open `index.html` in your browser to see the Messi page in action.

## Contributions
Feel free to suggest improvements or add more features related to Messi's career!
