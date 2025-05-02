## Hi there 👋

<!--<!DOCTYPE html>
<html lang="ur" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>کلر ٹریڈنگ سمولیٹر</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Nastaliq+Urdu&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Noto Nastaliq Urdu', serif;
      background: #f5f5f5;
      text-align: center;
      padding: 20px;
    }
    .container {
      background: white;
      padding: 20px;
      border-radius: 12px;
      max-width: 400px;
      margin: auto;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    select, button {
      width: 80%;
      padding: 12px;
      margin: 10px 0;
      font-size: 18px;
      border-radius: 6px;
      border: 1px solid #ccc;
    }
    button {
      background-color: #4CAF50;
      color: white;
      border: none;
    }
    .result {
      margin-top: 20px;
      font-size: 20px;
      font-weight: bold;
      color: #333;
    }
  </style>
</head>
<body>

  <div class="container">
    <h2>کلر ٹریڈنگ سمولیٹر</h2>

    <label>رقم منتخب کریں:</label><br/>
    <select id="amount">
      <option value="50">₹50</option>
      <option value="500">₹500</option>
      <option value="1000">₹1000</option>
      <option value="5000">₹5000</option>
    </select><br/>

    <label>رنگ منتخب کریں:</label><br/>
    <select id="color">
      <option value="Red">ریڈ</option>
      <option value="Green">گرین</option>
      <option value="Blue">بلو</option>
    </select><br/>

    <button onclick="simulateTrade()">اب لگائیں</button>

    <div class="result" id="resultArea"></div>
  </div>

  <!-- Win & Lose Sounds -->
  <audio id="winSound" src="https://www.soundjay.com/human/sounds/applause-8.mp3"></audio>
  <audio id="loseSound" src="https://www.soundjay.com/button/sounds/button-10.mp3"></audio>

  <script>
    function simulateTrade() {
      const amount = parseInt(document.getElementById("amount").value);
      const userColor = document.getElementById("color").value;
      const colors = ["ریڈ", "گرین", "بلو"];
      const winningColor = colors[Math.floor(Math.random() * colors.length)];

      let result = "";
      if (userColor === winningColor) {
        result = `مبارک ہو! آپ نے ${userColor} منتخب کیا اور جیت گئے! آپ کو ₹${amount * 2} ملے۔`;
        document.getElementById("winSound").play();
      } else {
        result = `افسوس! آپ نے ${userColor} منتخب کیا، لیکن نتیجہ آیا ${winningColor}. آپ ₹${amount} ہار گئے۔`;
        document.getElementById("loseSound").play();
      }

      document.getElementById("resultArea").innerText = result;
    }
  </script>

</body>
</html>
**ColourTrading2/ColourTrading2** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
