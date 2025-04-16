
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
            background-color: #003366; /* green */
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
<h >
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VPN MASTER 2025</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #1a1a2e, #16213e);
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
            color: #fff;
            overflow-x: hidden;
        }

        .container {
            text-align: center;
            background: rgba(0, 0, 0, 0.3);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
            width: 85%;
            max-width: 600px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            position: relative;
            overflow: hidden;
            z-index: 1;
        }

        .container::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(106,17,203,0.2) 0%, rgba(37,117,252,0.1) 50%, transparent 70%);
            animation: rotate 20s linear infinite;
            z-index: -1;
        }

        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .title-box {
            background: linear-gradient(45deg, #6a11cb, #2575fc);
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            position: relative;
            overflow: hidden;
        }

        .title-box::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(to bottom right, transparent, rgba(255,255,255,0.2), transparent);
            transform: rotate(30deg);
            animation: shine 3s infinite;
        }

        @keyframes shine {
            0% { left: -100%; }
            20% { left: 100%; }
            100% { left: 100%; }
        }

        h1 {
            font-size: 2.8rem;
            margin: 0;
            text-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
            background: linear-gradient(to right, #fff, #fdd835);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            letter-spacing: 1px;
        }

        .subtitle {
            font-size: 1.3rem;
            color: #a5d6a7;
            margin-top: 10px;
            font-weight: 400;
        }

        .status-box {
            background: rgba(0, 0, 0, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 20px;
            margin: 25px 0;
            position: relative;
        }

        .status-text {
            font-size: 1.4rem;
            margin: 0;
            color: #fdd835;
            font-weight: 700;
        }

        .emoji-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 30px 0;
        }

        .emoji {
            font-size: 2.5rem;
            animation: float 3s ease-in-out infinite;
            text-shadow: 0 0 10px rgba(253, 216, 53, 0.7);
        }

        .emoji:nth-child(1) { animation-delay: 0s; }
        .emoji:nth-child(2) { animation-delay: 0.5s; }
        .emoji:nth-child(3) { animation-delay: 1s; }
        .emoji:nth-child(4) { animation-delay: 1.5s; }
        .emoji:nth-child(5) { animation-delay: 2s; }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }

        .glow {
            animation: glow 2s ease-in-out infinite alternate;
        }

        @keyframes glow {
            from { text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #fdd835, 0 0 20px #fdd835; }
            to { text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #fdd835, 0 0 40px #fdd835; }
        }

        .features {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            margin: 25px 0;
        }

        .feature-box {
            background: rgba(106, 17, 203, 0.2);
            border: 1px solid rgba(106, 17, 203, 0.3);
            border-radius: 8px;
            padding: 15px;
            transition: all 0.3s ease;
        }

        .feature-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(106, 17, 203, 0.4);
            background: rgba(106, 17, 203, 0.3);
        }

        .feature-title {
            font-weight: 700;
            margin-bottom: 5px;
            color: #a5d6a7;
        }

        .feature-desc {
            font-size: 0.9rem;
            color: #e0e0e0;
        }

        .footer {
            margin-top: 30px;
            font-size: 1rem;
            color: rgba(255, 255, 255, 0.7);
        }

        .author {
            color: #fdd835;
            font-weight: 700;
            text-decoration: none;
            position: relative;
        }

        .author::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 0;
            height: 2px;
            background: #fdd835;
            transition: width 0.3s ease;
        }

        .author:hover::after {
            width: 100%;
        }

        .quantum-particles {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .particle {
            position: absolute;
            width: 4px;
            height: 4px;
            background: rgba(253, 216, 53, 0.7);
            border-radius: 50%;
            animation: particle-float linear infinite;
        }

        @keyframes particle-float {
            0% { transform: translateY(0) translateX(0); opacity: 0; }
            10% { opacity: 1; }
            90% { opacity: 1; }
            100% { transform: translateY(-100vh) translateX(20px); opacity: 0; }
        }
    </style>
</head>
<body>
    <div class="quantum-particles" id="particles"></div>
    
    <div class="container">
        <div class="title-box">
            <color="red"</>
            <h1>VPN MASTER</h1>
            <p class="subtitle">Experience the Next Generation AI</p>
        </div>
        
        <div class="status-box">
            <p class="status-text glow">SYSTEM STATUS: IN PROGRESS</p>
        </div>
        
        <div class="emoji-container">
            <div class="emoji">🔥</div>
            <div class="emoji">⚡</div>
            <div class="emoji">💡</div>
            <div class="emoji">✨</div>
            <div class="emoji">🌟</div>
        </div>
        
        <p>Enjoy the all-the vpn master services <span class="glow" style="font-weight:700;">VPN MASTER technology</span> experience!</p>
        
        <div class="features">
            <div class="feature-box">
                <div class="feature-title">Quantum Speed</div>
                <div class="feature-desc">Lightning-fast responses powered by quantum algorithms</div>
            </div>
            <div class="feature-box">
                <div class="feature-title">AI Evolution</div>
                <div class="feature-desc">Continuously learning and improving neural networks</div>
            </div>
            <div class="feature-box">
                <div class="feature-title">Secure</div>
                <div class="feature-desc">Military-grade encryption for all communications</div>
            </div>
            <div class="feature-box">
                <div class="feature-title">24/7 Uptime</div>
                <div class="feature-desc">99.99% availability with global server distribution</div>
            </div>
        </div>
        
        <div class="footer">
            Crafted with <span style="color:#f44336;">❤</span> by <a href="#" class="author">JAFETH FILIMON</a>
        </div>
    </div>

    <script>
        // Create quantum particles
        function createParticles() {
            const particlesContainer = document.getElementById('particles');
            const particleCount = 30;
            
            for (let i = 0; i < particleCount; i++) {
                const particle = document.createElement('div');
                particle.classList.add('particle');
                
                // Random position
                const posX = Math.random() * 100;
                const posY = Math.random() * 100 + 100; // Start below viewport
                particle.style.left = `${posX}%`;
                particle.style.top = `${posY}%`;
                
                // Random size
                const size = Math.random() * 3 + 2;
                particle.style.width = `${size}px`;
                particle.style.height = `${size}px`;
                
                // Random animation duration
                const duration = Math.random() * 10 + 10;
                particle.style.animationDuration = `${duration}s`;
                
                // Random delay
                const delay = Math.random() * 10;
                particle.style.animationDelay = `${delay}s`;
                
                particlesContainer.appendChild(particle);
            }
        }
        
        // Initialize particles
        createParticles();
        
        // Add hover effect to container
        const container = document.querySelector('.container');
        container.addEventListener('mousemove', (e) => {
            const x = e.clientX / window.innerWidth;
            const y = e.clientY / window.innerHeight;
            
            container.style.transform = `perspective(1000px) rotateX(${(y - 0.5) * 5}deg) rotateY(${(x - 0.5) * -5}deg)`;
         
        container.addEventListener('mouseleave', () => {
            container.style.transform = 'perspective(1000px) rotateX(0) rotateY(0)';
        

    <footer>
        <p class="contact-info" onclick="window.location.href='https://wa.me/0623647378'">Contact Us: 0623647378 (WhatsApp)</p>
        <p>Powered by VPN Master</p>
    </footer>

            

    
