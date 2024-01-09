<img src="/contributions.svg" style="max-width: 100%;">

- 👋 Hi, I’m stan alam
- 👀 I’m interested in ... Rust
- 🌱 I’m currently learning ... Powershell 7. (in a month of lunches), and Ancient Egyptian Hieroglyphs( 5,122 years of lunches )
- 💞️ I’m looking to collaborate on ... music
- 📫 How to reach me ...

<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Display current date and time</title>
  </head>
  <body>
    <h1>Current date and time:</h1>
    <span id="datetime"></span>

    <script>
      // create a function to update the date and time
      function updateDateTime() {
        // create a new `Date` object
        const now = new Date();

        // get the current date and time as a string
        const currentDateTime = now.toLocaleString();

        // update the `textContent` property of the `span` element with the `id` of `datetime`
        document.querySelector('#datetime').textContent = currentDateTime;
      }

      // call the `updateDateTime` function every second
      setInterval(updateDateTime, 1000);
    </script>
  </body>
</html>

<!---
stan-alam/stan-alam is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
