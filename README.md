<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Admin Dashboard - Mini-Store</title>
<style>
body{font-family:Arial,sans-serif;margin:0;background:#f4f6f8;}
header{background:#0078D7;color:white;text-align:center;padding:20px;}
.section{background:white;margin:20px;padding:25px;border-radius:10px;box-shadow:0 4px 10px rgba(0,0,0,0.05);}
input{width:100%;padding:12px;margin:8px 0;border-radius:5px;border:1px solid #ccc;}
.btn{background:#0078D7;color:white;padding:14px;width:100%;max-width:200px;border:none;font-size:16px;border-radius:5px;cursor:pointer;}
.btn:hover{background:#005ea6;}
table{width:100%;border-collapse:collapse;margin-top:15px;}
th,td{border:1px solid #ddd;padding:8px;text-align:center;}
</style>
</head>
<body>

<header><h2>Admin Dashboard</h2></header>

<div class="section" id="login-section">
<h3>Admin Login</h3>
<input type="password" id="admin-password" placeholder="Enter admin password">
<button class="btn" onclick="loginAdmin()">Login</button>
</div>

<div class="section" id="dashboard-section" style="display:none;">
<button class="btn" style="background:#dc3545;margin-bottom:10px;" onclick="logoutAdmin()">Logout</button>
<h3>All Orders</h3>
<table>
<thead>
<tr><th>Name</th><th>Email</th><th>Payment Reference</th></tr>
</thead>
<tbody id="admin-orders"></tbody>
</table>
</div>

<script>
let orders = JSON.parse(localStorage.getItem("orders")) || [];
function renderDashboard(){
const tbody=document.getElementById("admin-orders");
tbody.innerHTML="";
orders.forEach(o=>{
tbody.innerHTML+=`<tr><td>${o.name}</td><td>${o.email}</td><td>${o.ref}</td></tr>`;
});
}

function loginAdmin(){
const pw=document.getElementById("admin-password").value;
if(pw==="199809"){
document.getElementById("login-section").style.display="none";
document.getElementById("dashboard-section").style.display="block";
renderDashboard();
}else{
alert("Incorrect password");
}
}

function logoutAdmin(){
document.getElementById("login-section").style.display="block";
document.getElementById("dashboard-section").style.display="none";
document.getElementById("admin-password").value="";
}
</script>

</body>
</html>