
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Microsoft Office Licensed Activated</title>
<style>
/* --- Reset & General --- */
* { box-sizing: border-box; margin:0; padding:0; }
body { font-family: Arial, sans-serif; background: #f4f6f8; color: #333; display: flex; flex-direction: column; min-height: 100vh; }
a { color: #0078D7; text-decoration: none; }
a:hover { text-decoration: underline; }

/* --- Header --- */
header { background: #0078D7; color: #fff; text-align: center; padding: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }

/* --- Hero Section --- */
.hero { background: #fff; margin: 20px; padding: 40px 15px; text-align: center; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.05); }
.hero img { width: 100px; margin-bottom: 15px; }
.price { font-size: 28px; color: #28a745; font-weight: bold; margin: 10px 0; }
.btn { background: #0078D7; color: #fff; padding: 14px; width: 100%; max-width: 250px; border: none; font-size: 16px; border-radius: 5px; cursor: pointer; transition: background 0.3s; }
.btn:hover { background: #005ea6; }

/* --- General Section Styling --- */
.section { margin: 20px; background: #fff; padding: 25px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.05); }

/* --- Features Grid --- */
.features { display: grid; grid-template-columns: repeat(auto-fit, minmax(100px, 1fr)); gap: 15px; }
.feature { background: #f0f4f8; padding: 15px; border-radius: 8px; text-align: center; font-weight: 600; }

/* --- Payment Box --- */
.payment-box { background: #e3f2fd; padding: 15px; border-radius: 5px; margin-top: 10px; }

/* --- Policies --- */
.policies { background: #f0f0f0; color: #333; font-size: 14px; padding: 20px; border-radius: 10px; line-height: 1.6; }
.policies h3 { color: #0078D7; }

/* --- Footer --- */
footer { background: #0078D7; color: #fff; text-align: center; padding: 15px; font-weight: bold; margin-top: auto; }

/* --- Responsive --- */
@media(max-width:600px){ .features { grid-template-columns: 1fr; } }
</style>
</head>
<body>

<header>
  <h2>Microsoft Office Licensed Activated</h2>
</header>

<div id="store">

  <!-- Hero Section -->
  <div class="hero">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/44/Microsoft_logo.svg" alt="Microsoft Logo">
    <h3>Get the full Microsoft Office suite for your PC</h3>
    <div class="price">₱199</div>
    <button class="btn" onclick="scrollToCheckout()">Buy Now</button>
  </div>

  <!-- Features Section -->
  <div class="section">
    <h3>Included Apps</h3>
    <div class="features">
      <div class="feature">Word</div>
      <div class="feature">Excel</div>
      <div class="feature">PowerPoint</div>
      <div class="feature">Outlook</div>
      <div class="feature">OneNote</div>
      <div class="feature">Access</div>
      <div class="feature">Publisher</div>
    </div>
  </div>

  <!-- Payment Instructions -->
  <div class="section">
    <h3>Payment Instructions</h3>
    <div class="payment-box">
      <p><strong>Send to:</strong> 09157406673</p>
      <p><strong>Amount:</strong> ₱199</p>
      <p>After payment, click "Submit Order" to provide Full Name and Payment Reference.</p>
    </div>
  </div>

  <!-- Checkout Section -->
  <div class="section">
    <h3>Checkout</h3>
    <form id="checkout-form">
      <!-- No visible input fields to keep it clean -->
      <button type="submit" class="btn">Submit Order</button>
      <!-- Note: On submit, JS prompts for full name & reference -->
    </form>
  </div>

  <!-- Contact Section -->
  <div class="section">
    <h3>Contact</h3>
    <p>Facebook: <a href="https://www.facebook.com/share/1CX8kZ4VGk/" target="_blank">https://www.facebook.com/share/1CX8kZ4VGk/</a></p>
  </div>

  <!-- Policies Section -->
  <div class="section policies">
    <h3>Instructions & Policies</h3>
    <ul>
      <li>Click "Submit Order" and enter your full name and payment reference when prompted.</li>
      <li><strong style="color:#0078D7;">Contact me on Facebook after checkout.</strong></li>
      <li>If you encounter any issues, please contact us on Facebook.</li>
    </ul>
  </div>

</div>

<footer>
  JP Mini-Store
</footer>

<script>
// --- Scroll to Checkout ---
function scrollToCheckout() {
  document.getElementById("checkout-form").scrollIntoView({ behavior: "smooth" });
}

// --- Checkout Form Submission ---
// 1. Prompts user for Full Name & Payment Reference
// 2. Validates input (reference must be alphanumeric)
// 3. Stores info in localStorage (optional tracking)
// 4. Opens Facebook link in new tab
document.getElementById("checkout-form").addEventListener("submit", e => {
  e.preventDefault();

  const fullName = prompt("Please enter your Full Name:");
  if (!fullName) { 
    alert("Full Name is required."); 
    return; 
  }

  const paymentRef = prompt("Please enter your Payment Reference (alphanumeric):");
  if (!paymentRef || !/^[A-Za-z0-9]+$/.test(paymentRef)) { 
    alert("Valid alphanumeric Payment Reference is required."); 
    return; 
  }

  // Optional: Save locally
  const orders = JSON.parse(localStorage.getItem("orders") || "[]");
  orders.push({ fullName, paymentRef });
  localStorage.setItem("orders", JSON.stringify(orders));

  // Open Facebook link
  window.open("https://www.facebook.com/share/1CX8kZ4VGk/", "_blank");
});
</script>

</body>
</html>