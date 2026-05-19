<!DOCTYPE html>
<html>
<head>
  <title>For Queen Aydana 👑</title>

  <style>
    body {
      background: linear-gradient(to right, #ffb6c1, #ffc0cb);
      font-family: Arial, sans-serif;
      text-align: center;
      padding-top: 100px;
      overflow: hidden;
    }

    h1 {
      color: white;
      font-size: 40px;
      padding: 20px;
    }

    .buttons {
      margin-top: 40px;
    }

    button {
      padding: 15px 30px;
      font-size: 22px;
      border: none;
      border-radius: 15px;
      cursor: pointer;
      margin: 10px;
      transition: 0.2s;
    }

    #yesBtn {
      background-color: #4CAF50;
      color: white;
    }

    #noBtn {
      background-color: #ff4d6d;
      color: white;
      position: absolute;
    }

    #message {
      margin-top: 40px;
      font-size: 28px;
      color: white;
      display: none;
      white-space: pre-line;
      padding: 20px;
    }
  </style>
</head>

<body>

  <h1>
    Hey my queen Aydana Targaryen 👑<br><br>
    Will you become my official:<br>
    movie night + language exchange + overthinking partner? 🙈
  </h1>

  <div class="buttons">
    <button id="yesBtn">Yes 💖</button>
    <button id="noBtn">No 😭</button>
  </div>

  <div id="message">
Congrats 😭🤍

You have successfully unlocked:

cozy Sundays,
random hugs,
anime discussions,
and one emotionally chaotic med student 💀
  </div>

<script>
  const noBtn = document.getElementById("noBtn");

  noBtn.addEventListener("mouseover", () => {
    noBtn.style.top = Math.random() * window.innerHeight + "px";
    noBtn.style.left = Math.random() * window.innerWidth + "px";
  });

  document.getElementById("yesBtn").addEventListener("click", () => {
    document.querySelector(".buttons").style.display = "none";
    document.getElementById("message").style.display = "block";
  });
</script>

</body>
</html>