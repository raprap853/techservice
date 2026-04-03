<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tech Services: Microsoft Office & Data Recovery</title>
<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f4f6f9;
    color: #333;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    align-items: center;
    scroll-behavior: smooth;
}
header {
    background: #0a3d62;
    color: white;
    text-align: center;
    padding: 20px;
    width: 100%;
}
nav {
    background: #07407a;
    padding: 10px 20px;
    position: sticky;
    top: 0;
    z-index: 1000;
    width: 100%;
    display: flex;
    justify-content: center;
    gap: 40px;
    flex-wrap: wrap;
}
nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    white-space: nowrap;
}
nav a:hover { text-decoration: underline; }

.center-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 900px;
    margin: auto;
    text-align: center;
    width: 100%;
    gap: 25px;
}

section {
    padding: 40px 20px;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.services {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    align-items: stretch;
}
article.card {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    background: white;
    padding: 20px;
    border-radius: 8px;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    transition: transform 0.4s, box-shadow 0.4s;
    min-width: 200px;
    max-width: 300px;
}
article.card:hover {
    transform: translateY(-10px) scale(1.02);
    box-shadow: 0 10px 20px rgba(0,0,0,0.25);
}

.hero {
    display: inline-block;
    padding: 40px 30px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    text-align: center;
    margin: 20px 0;
    max-width: fit-content;
    transition: transform 0.3s, box-shadow 0.3s;
}
.hero:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.2);
}
.hero img { width: 100px; margin-bottom: 15px; }
.price { font-size: 28px; color: #28a745; margin: 10px 0; font-weight: bold; }
.btn {
    background: #0a3d62;
    color: white;
    padding: 14px;
    border: none;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.3s, transform 0.2s;
    text-decoration: none;
    display: inline-block;
    margin-top: 10px;
}
.btn:hover { background: #07407a; transform: scale(1.02); }

/* Included Apps */
.features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 15px;
    margin-top: 15px;
    list-style: none;
    padding: 0;
    width: auto;
    justify-content: center;
    justify-items: center;
}
.features li {
    background: #f0f4f8;
    padding: 15px;
    border-radius: 8px;
    text-align: center;
    font-weight: 600;
    width: 150px;  /* uniform longer boxes */
    opacity: 0;
    transform: scale(0.9);
    transition: opacity 0.5s, transform 0.5s;
}
.features li.show {
    opacity: 1;
    transform: scale(1);
}

/* Section headings centered */
.section h3 {
    text-align: center;
    margin-bottom: 20px;
}

/* Payment & Policies */
.payment-box, .policies {
    background: white;
    padding: 20px;
    border-radius: 10px;
    margin: 10px auto;
    width: fit-content;
    text-align: center;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    transition: transform 0.3s, box-shadow 0.3s;
}
.payment-box:hover, .policies:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}
.policies ul, .payment-box ul { list-style: none; padding: 0; margin: 0; }
.policies li, .payment-box li { margin-bottom: 8px; }

footer {
    background: #0a3d62;
    color: white;
    text-align: center;
    padding: 15px;
    font-weight: bold;
    width: 100%;
}

@media (max-width: 600px) {
    .services, .features { flex-direction: column; grid-template-columns: 1fr; align-items: center; }
    article.card, .hero, .payment-box, .policies { width: 90%; display: block; }
    .hero img { width: 70px; }
}
</style>
</head>
<body>

<header>
<h1>Tech Services</h1>
<p>Microsoft Office, Windows & Data Recovery</p>
</header>

<nav>
<a href="#office" class="nav-link">Microsoft Office & Windows</a>
<a href="#data-recovery" class="nav-link">Data Recovery</a>
</nav>

<section id="office">
  <div class="center-container">
    <h2>Microsoft Office & Windows Support</h2>
    <div class="services">
      <article class="card"><h3>Windows Activation Assistance</h3><p>Step-by-step help to activate Windows on your PC or laptop.</p></article>
      <article class="card"><h3>Troubleshooting</h3><p>Fix activation errors and system issues for Windows and Office.</p></article>
      <article class="card"><h3>IDM License Assistance</h3><p>Activating a genuine Internet Download Manager license.</p></article>
    </div>

    <div class="hero">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/44/Microsoft_logo.svg" alt="Microsoft Logo">
      <h3>Boost Productivity: Microsoft Office, Windows & IDM</h3>
      <div class="price">₱199</div>
      <a class="btn" href="https://www.facebook.com/share/1CX8kZ4VGk/" target="_blank" rel="noopener">Buy Now via Facebook</a>
    </div>

    <div class="section">
      <h3>Included Apps</h3>
      <ul class="features">
        <li>Word</li>
        <li>Excel</li>
        <li>PowerPoint</li>
        <li>Outlook</li>
        <li>OneNote</li>
        <li>Access</li>
        <li>Publisher</li>
      </ul>
    </div>

    <div class="section">
      <h3>Payment Instructions</h3>
      <div class="payment-box">
        <p><strong>Send to:</strong> 09157406673</p>
        <p><strong>Amount:</strong> ₱199</p>
        <p>Click the "Buy Now via Facebook" button above to send your payment confirmation directly.</p>
      </div>
    </div>

    <div class="section policies">
      <h3>Instructions & Policies</h3>
      <ul>
        <li style="color: #006400; font-weight: bold;">Contact us on Facebook after payment.</li>
        <li>Keep your email updated to receive confirmations if needed.</li>
        <li>If you encounter any issues or errors, please contact us via Facebook.</li>
      </ul>
    </div>
  </div>
</section>

<section id="data-recovery">
<h2>Data Recovery Services</h2>
<div class="services">
    <article class="card"><h3>Deleted File Recovery</h3><p>Recover accidentally deleted files from your computer or laptop.</p></article>
    <article class="card"><h3>Hard Drive Recovery</h3><p>We retrieve data from corrupted hard drives.</p></article>
    <article class="card"><h3>SSD & USB Recovery</h3><p>Recover lost files from SSDs, flash drives, and memory cards.</p></article>
    <article class="card"><h3>System Crash Recovery</h3><p>Get your data back after OS failure or system crash.</p></article>
</div>
</section>

<footer>
JP Mini-Store © 2026
</footer>

<script>
function animateFeaturesStagger() {
    const features = document.querySelectorAll('.features li');
    features.forEach((feature, index) => {
        const rect = feature.getBoundingClientRect();
        if(rect.top < window.innerHeight && rect.bottom >= 0) {
            setTimeout(() => { feature.classList.add('show'); }, index * 150);
        }
    });
}
window.addEventListener('scroll', animateFeaturesStagger);
window.addEventListener('load', animateFeaturesStagger);

document.querySelectorAll('a.nav-link').forEach(link => {
    link.addEventListener('click', function(e){
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if(target){
            target.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }
    });
});
</script>

</body>
</html>