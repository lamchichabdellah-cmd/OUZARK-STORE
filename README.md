<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>الدفع - OUZARK</title>

<style>
body {
    background: #111;
    color: white;
    font-family: Arial;
    text-align: center;
    padding: 20px;
}
input {
    width: 90%;
    padding: 12px;
    margin: 10px 0;
    border: none;
    border-radius: 8px;
}
button {
    padding: 15px;
    width: 95%;
    background: green;
    border: none;
    font-size: 20px;
    color: white;
    border-radius: 8px;
}
</style>

</head>
<body>

<h1>الدفع</h1>
<p>أدخل معلوماتك لإتمام الطلب</p>

<input type="text" placeholder="الاسم الكامل">
<input type="text" placeholder="العنوان">
<input type="number" placeholder="رقم الهاتف">
<button onclick="finish()">إتمام الطلب</button>

<script>
function finish() {
    alert("تم استلام طلبك ❤️");
}
</script>

</body>
</html>
