<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Redirecting to survey...</title>
  <script>
    const surveys = [
      "https://forms.gle/pindhNophfhWmcPh9",
      "https://forms.gle/Vzi113f3t4YT5uD78",
      "https://forms.gle/MooPEp1MrWdJRVke6",
      "https://forms.gle/KLA9HYkkfYDXYssC9"
    ];

    const randomIndex = Math.floor(Math.random() * surveys.length);
    window.location.href = surveys[randomIndex];
  </script>
</head>
<body>
  Redirecting you to a random survey... please wait.
</body>
</html>
