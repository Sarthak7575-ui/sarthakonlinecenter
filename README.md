README.md
# Welcom to Sarthak Online Center
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <title>Sarthak Online Center</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f9f9f9; }
        header { background-color: #004aad; color: white; padding: 20px; text-align: center; }
        header img { width: 80px; height: 80px; border-radius: 50%; }
        nav { background: #00338d; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        section { padding: 20px; }
        h2 { color: #004aad; }
        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }
        .card {
            border: 1px solid #ccc;
            padding: 15px;
            background: white;
            border-radius: 8px;
            text-align: center;
        }
        .card h3 { margin-top: 0; }
        .button {
            background: #004aad;
            color: white;
            padding: 8px 12px;
            display: inline-block;
            margin-top: 10px;
            border-radius: 4px;
            text-decoration: none;
        }
        footer {
            background: #00338d;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <img src="https://via.placeholder.com/80x80.png?text=SOC" alt="Logo">
    <h1>Sarthak Online Center</h1>
    <p>Apno Ka Center – Aapke Har Online Kaam Ka Solution</p>
</header>

<nav>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<section id="services">
    <h2>🔧 हमारी सेवाएँ (Our Services)</h2>
    <div class="service-grid">
        <div class="card">
            <h3>PAN Card</h3>
            <a href="#" class="button">Apply Now</a>
        </div>
        <div class="card">
            <h3>Aadhaar Download</h3>
            <a href="https://eaadhaar.uidai.gov.in/" target="_blank" class="button">Download</a>
        </div>
        <div class="card">
            <h3>Samagra ID</h3>
            <a href="https://samagra.gov.in/" target="_blank" class="button">Open</a>
        </div>
        <div class="card">
            <h3>Ayushman Card</h3>
            <a href="https://pmjay.gov.in/" target="_blank" class="button">Get Card</a>
        </div>
        <div class="card">
            <h3>Electricity Bill</h3>
            <a href="#" class="button">Pay Now</a>
        </div>
        <div class="card">
            <h3>Mobile Recharge</h3>
            <a href="#" class="button">Recharge</a>
        </div>
        <div class="card">
            <h3>Job Form</h3>
            <a href="#" class="button">Apply</a>
        </div>
        <div class="card">
            <h3>Scholarship Form</h3>
            <a href="#" class="button">Apply</a>
        </div>
    </div>
</section>

<section id="contact">
    <h2>📞 संपर्क करें (Contact Us)</h2>
    <p>📧 Email: <a href="mailto:sunilsinghr672@gmail.com">sunilsinghr672@gmail.com</a></p>
    <p>📱 Phone: <a href="tel:+917000873075">7000873075</a></p>
</section>

<footer>
    © 2025 Sarthak Online Center | All Rights Reserved
</footer>

</body>
</html>
