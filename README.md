<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>St Gerard's Podcast</title>

  <!-- Favicon -->
  <link rel="icon" href="https://www.dropbox.com/scl/fi/9s9claua3v91paeokbyh1/bilis6ww.png?rlkey=5qq0etpja19uenb9f4b09bk78&st=v6w6t7gt&dl=1" type="image/x-icon">

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet" />

  <!-- SEO basics -->
  <meta name="description" content="Welcome to the official St Gerard's School Podcast. Listen to episodes about school life, special guests, and more." />
  <meta name="keywords" content="St Gerard's, School Podcast, Education, Bangor, Podcasts, Students, School News" />
  <meta name="author" content="Rowan Sutcliffe" />

  <style>
    body {
      font-family: 'Noto Sans', sans-serif;
      color:FFFF00 ;
      margin: 0;
      background:
        linear-gradient(rgba(0, 51, 102, 0.6), rgba(0, 51, 102, 0.6)),
        url('https://as2.ftcdn.net/v2/jpg/04/34/74/65/1000_F_434746570_36fmkTrm6q9S5T74P3bOVn2DlYxle9zY.jpg') no-repeat center/cover fixed;
    }

    header {
      background: #003366;
      color: #ffcc00;
      padding: 20px;
      display: flex;
      align-items: center;
      gap: 15px;
      border-radius: 0 0 12px 12px;
      flex-wrap: wrap;
    }

    header img {
      width: 120px;
      height: 120px;
      border-radius: 12px;
      object-fit: contain;
      flex-shrink: 0;
    }

    header h1 {
      flex: 1;
      text-align: center;
      font-size: 28px;
      margin: 0;
      font-weight: 700;
    }

    .container {
      max-width: 900px;
      margin: 20px auto;
      padding: 15px;
      background: rgba(255, 255, 255, 0.95);
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
    }

    h2 {
      text-align: center;
      margin-bottom: 15px;
      font-size: 24px;
    }

    .searchbar {
      text-align: center;
      margin-bottom: 25px;
    }

    #searchInput {
      padding: 10px;
      width: 80%;
      max-width: 500px;
      border: 2px solid #003366;
      border-radius: 6px;
      font-size: 16px;
    }

    .podcast {
      margin-bottom: 30px;
      padding-bottom: 15px;
      border-bottom: 1px solid #ccc;
    }

    audio,
    iframe {
      width: 100%;
      border-radius: 8px;
      margin-top: 10px;
    }

    button {
      background: #003366;
      color: #ffcc00;
      border: none;
      padding: 10px 15px;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background: #002244;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: rgba(0, 51, 102, 0.9);
      color: #fff;
      border-top: 2px solid #ffcc00;
      font-size: 14px;
      margin-top: 30px;
      border-radius: 8px 8px 0 0;
    }

    footer a {
      color: #ffcc00;
      text-decoration: none;
      font-weight: 500;
    }

    footer a:hover {
      text-decoration: underline;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        text-align: center;
      }

      header img {
        width: 100px;
        height: 100px;
      }

      header h1 {
        font-size: 24px;
      }

      #searchInput {
        width: 95%;
      }

      h2 {
        font-size: 22px;
      }
    }
  </style>
</head>

<body>

  <header>
    <img src="https://www.dropbox.com/scl/fi/o00kckls1829t511apmsv/school_logo-removebg-preview.png?rlkey=b4pp497rdevit1ph4hcgxobmq&st=7vki182k&dl=1" alt="St Gerard's School Logo" />
    <h1>St Gerard's School Podcast</h1>
  </header>

  <div class="container">
    <h2>Podcast Library</h2>

    <div class="searchbar">
      <input type="text" id="searchInput" placeholder="Search episodes...">
    </div>

    <div id="podcastList">

      <!-- Podcast entries -->
      <div class="podcast">
        <h3>Episode 1: </h3>
        <iframe src="https://www.youtube.com/embed/5MWT_doo68k" allowfullscreen></iframe>
      </div>
      <div class="podcast">
        <h3>Episode 2: </h3>
        <iframe src="https://www.youtube.com/embed/L_Guz73e6fw" allowfullscreen></iframe>
      </div>
      <div class="podcast">
        <h3>Episode 3: Hugo interview </h3>
        <audio controls src="https://www.dropbox.com/scl/fi/rck6a4xos3r6c3y9yqfbu/hugo.mp3?rlkey=tw9htstmmqv18la2nqe0sf5qv&st=g8gip3ce&dl=1">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="podcast">
        <h3>Episode 4: Rowan intrview </h3>
        <audio controls src="https://www.dropbox.com/scl/fi/7l3wf4y4b3ktucgfala5z/rowan.mp3?rlkey=z98dllpbi1frwd1v682y0pyg7&st=oep0ltdt&dl=1">
          Your browser does not support the audio element.
        </audio>
      </div>

    </div>

    <div class="btn-container" style="text-align:center;">
      <button onclick="alert('More episodes coming soon!')">More Episodes</button>
    </div>
  </div>

  <footer>
    Developed by Rowan Sutcliffe — <a href="mailto:rowan.sutcliffe@outlook.com">Contact Me for Web Development</a> |
    <a href="https://www.st-gerards.org/" target="_blank" rel="noopener">Visit St Gerard's School Website</a>
  </footer>

  <script>
    const searchInput = document.getElementById('searchInput');
    const podcasts = document.querySelectorAll('.podcast');

    searchInput.addEventListener('input', () => {
      const q = searchInput.value.toLowerCase();
      podcasts.forEach(p => {
        const title = p.querySelector('h3').textContent.toLowerCase();
        p.style.display = title.includes(q) ? 'block' : 'none';
      });
    });
  </script>

</body>

</html>

