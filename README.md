<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Login</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="logo">
            <img src="netflix-logo.png" alt="Netflix Logo">
        </div>
        <form id="login-form">
            <h2>Sign In</h2>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required><br><br>
            <input type="submit" value="Sign In">
        </form>
        <p>Don't have an account? <a href="#">Sign up now</a></p>
    </div>

    <script src="script.js"></script>
</body>
</html>
