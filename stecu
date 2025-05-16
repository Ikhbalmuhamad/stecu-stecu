<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Lirik Lagu Stecu Lucu</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: url('https://media1.giphy.com/media/cImNa6mdCJ0vUTil84/giphy.gif?cid=6c09b952xp26n00fecx0njzsav94d3o7d0aewur81ira5wet&ep=v1_internal_gif_by_id&rid=giphy.gif&ct=s') no-repeat center center fixed;
      background-size: cover;
      overflow: hidden;
      color: #fff;
    }

    .overlay {
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0, 0, 0, 0.4);
      z-index: 1;
    }

    .container {
      position: relative;
      z-index: 2;
      height: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 40px;
      text-shadow: 0 0 15px #ff99cc, 0 0 30px #ff66cc;
    }

    .lyrics {
      font-size: 1.8em;
      background: rgba(255, 255, 255, 0.2);
      padding: 20px 30px;
      border-radius: 20px;
      box-shadow: 0 0 20px #fff;
      animation: fadeIn 1s ease-in-out;
      min-height: 100px;
      max-width: 90%;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    audio {
      display: none;
    }
  </style>
</head>
<body>
  <div class="overlay"></div>

  <div class="container">
    <h1>🎶 Lirik Lagu Stecu 🎶</h1>
    <div class="lyrics" id="lyricBox">Loading...</div>
  </div>

  <audio id="bgMusic" autoplay loop>
    <source src="stecu.mp3" type="audio/mpeg">
    Browser tidak mendukung audio.
  </audio>

  <script>
    const lyrics = [
      "Jual mahal dikit kan bisa",
      "Coba kase effort-nya saja",
      "Kalo memang cocok bisa datang ke rumah",
      "",
      "Stecu, stecu, stelan cuek baru malu",
      "Aduh, Ade ini mau juga Abang yang rayu",
      "Stecu, stecu, stelan cuek baru malu",
      "Aduh, Ade ini mau juga Abang yang maju"
    ];

    let index = 0;
    const lyricBox = document.getElementById('lyricBox');

    function showNextLine() {
      if (index < lyrics.length) {
        lyricBox.textContent = lyrics[index];
        lyricBox.style.animation = 'none';
        void lyricBox.offsetWidth; // Reset animasi
        lyricBox.style.animation = null;
        index++;
      } else {
        index = 0;
      }
    }

    showNextLine(); // tampilkan pertama
    setInterval(showNextLine, 4000); // ganti setiap 4 detik
  </script>
</body>
</html>
