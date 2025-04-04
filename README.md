<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Redirecting to survey...</title>
  <script>
    const surveys = [
      "https://forms.gle/pindhNophfhWmcPh9",
      "https://forms.gle/s23A8Jsm7aVbQTL38",
      "https://forms.gle/v8q18rCrdr8f9Sii9",
      "https://forms.gle/ecNNjRskADvtWRsc9"
    ];

    const randomIndex = Math.floor(Math.random() * surveys.length);
    window.location.href = surveys[randomIndex];
  </script>
</head>
<body>
  Redirecting you to a random survey... please wait.
</body>
</html>

