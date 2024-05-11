![1885548](https://github.com/Kamandepolo/Kamandepolo.github.io/assets/152022350/02aae40e-e338-48ac-8be5-a2df658ae156)
<!The Don html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Questionnaire with Live Background</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="background"></div>
  <div class="container">
    <h1>Welcome to Our Questionnaire</h1>
    <form id="questionForm">
      <label for="origin">Where are you from?</label>
      <input type="text" id="origin" name="origin">

      <label for="age">How old are you?</label>
      <input type="number" id="age" name="age">

      <label for="feedback">Any feedback for us?</label>
      <textarea id="feedback" name="feedback"></textarea>

      <button type="submit">Submit</button>
    </form>
  </div>

  <script src="script.js"></script>
</body>
</html>
