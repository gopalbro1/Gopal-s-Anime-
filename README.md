<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gopal's Anime</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #1e1e2f;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #2b2b4f;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
      font-size: 2.5em;
    }
    .profile-img {
      margin-top: 15px;
    }
    .profile-img img {
      width: 200px;
      height: auto;
      border-radius: 10px;
      border: 3px solid #90caf9;
    }
    .anime-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .anime {
      background-color: #333;
      padding: 15px;
      border-radius: 10px;
    }
    .anime h2 {
      margin-top: 0;
    }
    .details {
      margin-top: 10px;
    }
    .details p {
      margin: 5px 0;
    }
    .episodes {
      margin-top: 10px;
      max-height: 300px;
      overflow-y: auto;
    }
    .episodes a {
      display: block;
      color: #90caf9;
      text-decoration: none;
      margin: 5px 0;
    }
    .episodes a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Gopal's Anime</h1>
    <p>Watch All Episodes of Your Favorite Anime in Hindi, English & Japanese (144p to 1080p)</p>
    <div class="profile-img">
      <img src="/mnt/data/file-Ds4qC8uRSVm9Aygkab76pB" alt="Profile Photo">
    </div>
  </header>  <main class="anime-list">
    <div class="anime">
      <h2>Attack on Titan</h2>
      <div class="details">
        <p>Languages: Hindi, English, Japanese</p>
        <p>Quality: 144p to 1080p</p>
      </div>
      <div class="episodes">
        <script>
          for (let s = 1; s <= 4; s++) {
            document.write(`<strong>Season ${s}</strong>`);
            for (let e = 1; e <= 25; e++) {
              document.write(`<a href="#">Season ${s} - Episode ${e}</a>`);
            }
          }
        </script>
      </div>
    </div><div class="anime">
  <h2>Death Note</h2>
  <div class="details">
    <p>Languages: Hindi, English, Japanese</p>
    <p>Quality: 144p to 1080p</p>
  </div>
  <div class="episodes">
    <script>
      for (let i = 1; i <= 37; i++) {
        document.write(`<a href="#">Episode ${i}</a>`);
      }
    </script>
  </div>
</div>

<div class="anime">
  <h2>Demon Slayer</h2>
  <div class="details">
    <p>Languages: Hindi, English, Japanese</p>
    <p>Quality: 144p to 1080p</p>
  </div>
  <div class="episodes">
    <script>
      let dsEpisodes = [26, 7, 11, 11];
      let dsTitles = ["Season 1", "Mugen Train Arc", "Entertainment District Arc", "Swordsmith Village Arc"];
      for (let i = 0; i < dsEpisodes.length; i++) {
        document.write(`<strong>${dsTitles[i]}</strong>`);
        for (let j = 1; j <= dsEpisodes[i]; j++) {
          document.write(`<a href='#'>${dsTitles[i]} - Episode ${j}</a>`);
        }
      }
    </script>
  </div>
</div>

<div class="anime">
  <h2>Naruto</h2>
  <div class="details">
    <p>Languages: Hindi, English, Japanese</p>
    <p>Quality: 144p to 1080p</p>
  </div>
  <div class="episodes">
    <script>
      for (let i = 1; i <= 220; i++) {
        document.write(`<a href="#">Episode ${i}</a>`);
      }
    </script>
  </div>
</div>

  </main>
</body>
</html># Gopal-s-Anime-
