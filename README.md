# mbartolott.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MFA Dashboard Mockup</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        nav {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
        }
        .placeholder {
            background-color: #eee;
            border: 1px dashed #aaa;
            height: 150px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 20px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #333;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin: 10px 0;
        }
        .button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav>
        <a href="#">Login</a>
        <a href="#">Create Account</a>
        <a href="#">Dashboard</a>
        <a href="#">Settings</a>
        <a href="#">Logs</a>
    </nav>

    <!-- Landing Page -->
    <div class="container">
        <h1>Welcome to the MFA Dashboard</h1>
        <div class="placeholder">[Landing Page Placeholder]</div>
        <a href="#" class="button">Enable New Method</a>
        <a href="#" class="button">View Logs</a>
    </div>

    <!-- Sample Secondary Page: Settings -->
    <div class="container">
        <h2>Settings</h2>
        <div class="placeholder">[Settings Section Placeholder]</div>
        <a href="#" class="button">Save Changes</a>
    </div>

    <!-- Sample Secondary Page: Logs -->
    <div class="container">
        <h2>Logs</h2>
        <div class="placeholder">[Logs Table Placeholder]</div>
        <a href="#" class="button">Export Logs</a>
    </div>
</body>
</html>
