<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Redirecting to survey...</title>
  <script>
    const surveys = [
      "https://forms.gle/pindhNophfhWmcPh9",
      "https://forms.gle/DVHFMUiVXGuUG1Cx7",
      "https://forms.gle/ChxZxKpaNvgGtZgi9",
      "https://forms.gle/4x8o9NUQwMLbvXSWA"
    ];

    const randomIndex = Math.floor(Math.random() * surveys.length);
    window.location.href = surveys[randomIndex];
  </script>
</head>
<body>
  Redirecting you to a random survey... please wait.
</body>
</html>
