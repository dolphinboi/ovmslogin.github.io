# ovmslogin.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login Page</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #ffffff; /* Set background color to white */
    margin: 0; /* Remove default margin */
    padding: 0; /* Remove default padding */
  }
</style>
</head>
<body>

<script>
// Prompt the user for username
var username = prompt("Please enter your username:");

// Check if the username is correct
if (username === "Evyn") {
  var password = prompt("Please enter your password:");
  
  // Check password if username is correct
  if (password === "Zhao") {
    // Redirect to another website
    window.location.href = "bit.ly/infmapi";
  } else {
    // Close the tab if password is incorrect and redirect to another link
  window.location.href = "https://www.youtube.com/watch?v=OyDyOweu-PA";
  }
} else {
  // Close the tab if username is incorrect and redirect to another link
  window.location.href = "https://www.youtube.com/watch?v=OyDyOweu-PA";
}
</script>

</body>
</html>
