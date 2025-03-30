
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karibu NtigaTV - Login</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #003366; /* Ligtblue */
            color: red; /* Red text */
            padding: 20px;
        }
        main {
            padding: 50px 20px;
        }
        form {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 300px;
            margin: 0 auto;
            text-align: left;
        }
        label {
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
            text-align: left;
        }
        input[type="email"], input[type="password"], input[type="tel"], select {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px;
            width: 100%;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #003366; /* Dark Blue */
            color: red; /* Red text */
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
            font-size: 12px;
        }
        .contact-info {
            font-size: 14px;
            margin-top: 10px;
            cursor: pointer;
            text-decoration: underline;
            color: #4CAF50;
        }
        .login-option {
            margin-top: 10px;
        }
        .register-option {
            margin-top: 10px;
            text-align: center;
        }
        .register-option a {
            color: #4CAF50;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Karibu NtigaTV</h1>
        <p>Ingiza maelezo yako ili kuingia kwenye akaunti yako.</p>
    </header>

    <main>
        <h2>Login</h2>
        <form action="login_process.html" method="POST">
            <label for="email">Barua Pepe:</label>
            <input type="email" id="email" name="email" required placeholder="Ingiza barua pepe yako">

            <label for="password">Neno la Siri:</label>
            <input type="password" id="password" name="password" required placeholder="Ingiza neno la siri">

            <label for="phone">Namba ya Simu:</label>
            <div style="display: flex; align-items: center;">
                <select id="country-code" name="country-code" style="width: 30%; padding: 10px;">
                    <option value="+254">Kenya (+254)</option>
                    <option value="+255">Tanzania (+255)</option>
                    <option value="+256">Uganda (+256)</option>
                    <option value="+27">South Africa (+27)</option>
                    <option value="+234">Nigeria (+234)</option>
                    <!-- Add more African countries here -->
                </select>
                <input type="tel" id="phone" name="phone" placeholder="Ingiza namba yako ya simu" required style="width: 70%; padding: 10px;">
            </div>

            <button type="submit">Ingia</button>

            <!-- Option ya kuingia bila kujaza taarifa -->
            <div class="login-option">
                <input type="checkbox" id="no-data" name="no-data">
                <label for="no-data">
                    <a href="https://youtube.com/@ntigatv" target="_blank" style="color: #4CAF50; text-decoration: none;">
                        Ingia bila kujaza taarifa
                    </a>
                </label>
            </div>
        </form>

        <!-- Sehemu ya "Sign Up" -->
        <div class="register-option">
            <p>Huna akaunti? <a href="signup.html">Jisajili hapa</a></p>
        </div>
    </main>

    <footer>
        <p class="contact-info" onclick="window.location.href='https://wa.me/0623647378'">Contact Us: 0623647378 (WhatsApp)</p>
        <p>Powered by VPN Master</p>
    </footer>
</body>
</html>
