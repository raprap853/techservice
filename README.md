
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tech & Computer Services</title>
<meta name="description" content="JP Mini-Store provides Microsoft Office, Windows activation, computer service, and data recovery solutions at affordable prices.">
<style>
:root {
    --primary-color: #0a3d62;
    --hover-color: #07407a;
    --green: #28a745;
    --bg-color: #f4f6f9;
    --transition: 0.3s;
    --shadow-light: rgba(0,0,0,0.1);
    --shadow-dark: rgba(0,0,0,0.2);
}

body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: var(--bg-color);
    color: #333;
    scroll-behavior: smooth;
}

/* Header */
header {
    background: var(--primary-color);
    color: white;
    text-align: center;
    padding: 20px;
}
header h1 { margin: 0; }
header p { margin: 5px 0 0; }

/* Navigation */
nav {
    background: var(--hover-color);
    padding: 10px 20px;
    position: sticky;
    top: 0;
    z-index: 1000;
    text-align: center;
    box-shadow: 0 2px 6px var(--shadow-light);
}
nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    margin: 0 15px;
}
nav a:hover { text-decoration: underline; }

/* Sections */
.section {
    padding: 40px 20px;
    text-align: center;
}
.section h2 { margin-bottom: 25px; }

/* Services Grid */
.services {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    justify-items: center;
}
.card {
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 8px var(--shadow-light);
    transition: transform var(--transition), box-shadow var(--transition);
}
.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px var(--shadow-dark);
}
.card h3 { color: var(--primary-color); }

/* Hero Section */
.hero {
    display: inline-block;
    padding: 40px 30px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 10px var(--shadow-light);
    text-align: center;
    margin: 20px auto;
    max-width: 400px;
    transition: transform var(--transition), box-shadow var(--transition);
}
.hero:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px var(--shadow-dark);
}
.hero img { width: 100px; margin-bottom: 15px; }
.price { font-size: 28px; color: var(--green); margin: 10px 0; font-weight: bold; }
.btn {
    background: var(--primary-color);
    color: white;
    padding: 12px 18px;
    border: none;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
}
.btn:hover { background: var(--hover-color); transform: scale(1.02); }

/* Features Grid */
.features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 15px;
    list-style: none;
    padding: 0;
    margin: 20px 0 0;
    justify-items: center;
}
.features li {
    background: #f0f4f8;
    padding: 15px;
    border-radius: 8px;
    font-weight: 600;
    width: 150px;
    opacity: 0;
    transform: scale(0.9);
    transition: opacity 0.5s, transform 0.5s;
}
.features li.show {
    opacity: 1;
    transform: scale(1);
}

/* Payment & Policies */
.payment-box, .policies {
    background: white;
    padding: 20px;
    border-radius: 10px;
    margin: 20px auto;
    width: fit-content;
    box-shadow: 0 4px 10px var(--shadow-light);
    text-align: center;
}
.payment-box ul, .policies ul { list-style: none; padding: 0; margin: 0; }
.payment-box li, .policies li { margin-bottom: 8px; }

/* Footer */
footer {
    background: var(--primary-color);
    color: white;
    text-align: center;
    padding: 15px;
    font-weight: bold;
}

/* Responsive */
@media (max-width: 800px) {
    .services { grid-template-columns: 1fr; }
    .card, .hero, .payment-box, .policies { width: 90%; }
}
</style>
</head>
<body>

<header>
<h1>Tech & Computer Services</h1>
<p>Microsoft Office, Windows, Data Recovery & Computer Support</p>
</header>

<nav>
<a href="#office">Office & Windows</a>
<a href="#computer-services">Computer Service</a>
<a href="#data-recovery">Data Recovery</a>
</nav>

<!-- Microsoft Office Section -->
<section class="section" id="office">
<h2>Microsoft Office & Windows Support</h2>
<div class="services">
    <div class="card">
        <h3>Windows Activation Assistance</h3>
        <p>Step-by-step help to activate Windows on your PC or laptop.</p>
    </div>
    <div class="card">
        <h3>Troubleshooting</h3>
        <p>Fix activation errors and system issues for Windows and Office.</p>
    </div>
    <div class="card">
        <h3>IDM License Assistance</h3>
        <p>Activating a genuine Internet Download Manager license.</p>
    </div>
</div>

<div class="hero">
<img src="https://upload.wikimedia.org/wikipedia/commons/4/44/Microsoft_logo.svg" alt="Microsoft logo" loading="lazy">
<h3>Boost Productivity: Microsoft Office, Windows & IDM</h3>
<div class="price">₱199</div>
<a class="btn" href="https://www.facebook.com/share/1CX8kZ4VGk/" target="_blank" rel="noopener noreferrer">Buy Now via Facebook</a>
</div>

<ul class="features" role="list">
    <li>Word</li>
    <li>Excel</li>
    <li>PowerPoint</li>
    <li>Outlook</li>
    <li>OneNote</li>
    <li>Access</li>
    <li>Publisher</li>
</ul>

<div class="payment-box">
<ul>
<li><strong>Send to:</strong> 09157406673</li>
<li><strong>Amount:</strong> ₱199</li>
<li>Click the "Buy Now via Facebook" button above to send your payment confirmation directly.</li>
</ul>
</div>

<div class="policies">
<ul>
<li style="color:#006400;font-weight:bold;">Contact us on Facebook after payment.</li>
<li>Keep your email updated to receive confirmations.</li>
<li>If you encounter any issues or errors, please contact us via Facebook.</li>
</ul>
</div>
</section>

<!-- Computer Service Section -->
<section class="section" id="computer-services">
<h2>Computer Service</h2>
<div class="services">
    <div class="card">
        <h3>Hardware Installation</h3>
        <p>Install RAM, hard drives, GPUs, and other components safely.</p>
    </div>
    <div class="card">
        <h3>Virus Removal</h3>
        <p>Clean malware and secure your system.</p>
    </div>
    <div class="card">
        <h3>System Installation</h3>
        <p>Install OS, drivers, and essential software.</p>
    </div>
    <div class="card">
        <h3>Networking</h3>
        <p>Setup WiFi, LAN, and troubleshoot networks.</p>
    </div>
</div>
</section>

<!-- Data Recovery Section -->
<section class="section" id="data-recovery">
<h2>Data Recovery Services</h2>
<div class="services">
    <div class="card">
        <h3>Deleted File Recovery</h3>
        <p>Recover accidentally deleted files from your computer or laptop.</p>
    </div>
    <div class="card">
        <h3>Hard Drive Recovery</h3>
        <p>Retrieve data from corrupted hard drives.</p>
    </div>
    <div class="card">
        <h3>SSD & USB Recovery</h3>
        <p>Recover lost files from SSDs, flash drives, and memory cards.</p>
    </div>
    <div class="card">
        <h3>System Crash Recovery</h3>
        <p>Get your data back after OS failure or system crash.</p>
    </div>
</div>
</section>

<footer>
JP Mini-Store © 2026
</footer>

<script>
// Smooth scroll
document.querySelectorAll('nav a').forEach(link => {
    link.addEventListener('click', e => {
        e.preventDefault();
        document.querySelector(link.getAttribute('href'))
            .scrollIntoView({ behavior: 'smooth', block: 'start' });
    });
});

// Features animation
const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
        if(entry.isIntersecting){
            entry.target.classList.add('show');
            observer.unobserve(entry.target);
        }
    });
}, { threshold: 0.5 });
document.querySelectorAll('.features li').forEach(li => observer.observe(li));
</script>

</body>
</html>