<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Assignment</title>
  <style>
    /* Part 1: CSS Basics - Selectors, Properties, and Values */
    /* Element Selector */
    h1, h2 {
      font-size: 24px;
    }

    /* Class Selector */
    .special-section {
      background-color: lightblue;
    }

    /* ID Selector */
    #unique-div {
      border: 2px solid black;
    }

    /* Part 2: Inline, Internal, and External CSS */
    /* Internal CSS */
    h1 {
      font-family: Arial, sans-serif;
      color: darkblue;
    }

    .section {
      background-color: lightgreen;
      padding: 20px;
    }

    #special-card {
      border: 1px solid gray;
      padding: 15px;
    }

    /* Part 3: Basic Styling Properties */
    /* Set background and text colors */
    body {
      background-color: #e0f7fa;
      color: #333;
    }

    /* Styling the card component */
    .card {
      background-color: #ffffff;
      padding: 20px;
      margin: 15px;
      border: 1px solid #ccc;
      width: 300px;
      box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    }

    .card-title {
      font-family: 'Arial', sans-serif;
      font-size: 22px;
      font-weight: bold;
      text-align: center;
      color: #00796b;
    }

    .card-description {
      text-align: justify;
      font-size: 16px;
      color: #555;
    }

    /* Padding and margin styling */
    h1, p {
      margin: 10px 0;
      padding: 5px;
    }

    /* Style links with hover effects */
    a {
      color: darkgreen;
      text-decoration: none;
    }

    a:hover {
      color: red;
    }
  </style>
</head>
<body>

  <!-- Part 1: CSS Basics -->
  <h1>This is a heading 1</h1>
  <h2>This is a heading 2</h2>
  <p class="special-section">This is a paragraph in a special section.</p>
  <div id="unique-div">This is a unique div with an ID.</div>

  <!-- Part 2: Inline, Internal, and External CSS -->
  <h1 style="color: red;">This is an inline styled heading</h1>

  <div class="section">
    <p>This is a section with internal CSS applied.</p>
  </div>

  <div id="special-card">
    <p>Special card with some internal styling.</p>
  </div>

  <!-- Part 3: Basic Styling Properties -->
  <div class="card">
    <h1 class="card-title">Card Title</h1>
    <p class="card-description">This is a description inside a card component. It gives brief information about the content of the card.</p>
  </div>

</body>
</html>
