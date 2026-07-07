# btccontpool
A crypto broker that show balance and name and withdraw form 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Broker Dashboard</title>
<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#f4f4f4;
}
.container{
    width:90%;
    max-width:700px;
    margin:40px auto;
}
.card{
    background:#fff;
    padding:20px;
    border-radius:12px;
    box-shadow:0 2px 10px rgba(0,0,0,.1);
    margin-bottom:20px;
}
.balance{
    font-size:36px;
    color:#0a8f3d;
    font-weight:bold;
}
button{
    background:#007bff;
    color:white;
    border:none;
    padding:12px 20px;
    border-radius:8px;
    cursor:pointer;
}
button:hover{
    background:#0056b3;
}
ul{
    list-style:none;
    padding:0;
}
li{
    padding:10px 0;
    border-bottom:1px solid #ddd;
}
</style>
</head>
<body>

<div class="container">

<div class="card">
<h2>Welcome, John Doe</h2>
<p>Account ID: BRK102548</p>
<div class="balance">$25,450.00</div>
</div>

<div class="card">
<h3>Withdrawal Methods</h3>
<ul>
<li>Bank Transfer</li>
<li>USDT (TRC20)</li>
<li>Bitcoin (BTC)</li>
<li>Ethereum (ETH)</li>
</ul>

<button onclick="withdraw()">Request Withdrawal</button>
</div>

</div>

<script>
function withdraw(){
    alert("Withdrawal request submitted successfully.");
}
</script>

</body>
</html>
