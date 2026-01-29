<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SOLUV RADIO</title>

  <style>
    :root {
      --black: #0b0b0b;
      --dark-gray: #1a1a1a;
      --gray: #2a2a2a;
      --light-gray: #cfcfcf;
      --white: #ffffff;
      --blue: #00b4ff;
      --turquoise: #1de9b6;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: var(--black);
      color: var(--light-gray);
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, var(--dark-gray), var(--black));
      padding: 24px;
      border-bottom: 2px solid var(--blue);
      text-align: center;
    }

    header h1 {
      margin: 0;
      color: var(--white);
      letter-spacing: 2px;
    }

    header p {
      margin: 6px 0 0;
      color: var(--turquoise);
      font-size: 0.95rem;
    }

    header a {
      color: var(--blue);
      text-decoration: none;
      font-weight: bold;
    }

    main {
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }

    section {
      margin-bottom: 40px;
      padding: 24px;
      background: var(--dark-gray);
      border-radius: 10px;
    }

    section h2 {
      margin-top: 0;
      color: var(--white);
      border-left: 4px solid var(--turquoise);
      padding-left: 12px;
    }

    .video-box {
      position: relative;
      padding-top: 56.25%;
      background: #000;
      border: 2px solid var(--blue);
      border-radius: 10px;
      overflow: hidden;
    }

    .video-box iframe {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      border: none;
    }

    .audio-player {
      margin-top: 16px;
      background: var(--gray);
      padding: 16px;
      border-radius: 8px;
      text-align: center;
    }

    .playlist iframe {
      width: 100%;
      height: 380px;
      border-radius: 8px;
      border: none;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
    }

    .grid-3 {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: linear-gradient(135deg, var(--gray), var(--dark-gray));
      padding: 20px;
      border-radius: 10px;
      border: 1px solid var(--blue);
    }

    .card h3 {
      color: var(--turquoise);
      margin-top: 0;
    }

    form input, form textarea, form button {
      width: 100%;
      padding: 12px;
      margin-bottom: 12px;
      background: var(--black);
      color: var(--white);
      border: 1px solid var(--gray);
      border-radius: 6px;
    }

    form button {
      background: var(--blue);
      border: none;
      font-weight: bold;
      cursor: pointer;
    }

    footer {
      background: var(--black);
      padding: 24px;
      text-align: center;
      font-size: 0.85rem;
      color: #888;
      border-top: 1px solid var(--gray);
    }
  </style>
</head>

<body>

<header>
  <h1>SOLUV RADIO</h1>
  <p>Healing Frequencies · Independent Voices · Community Power</p>
  <p>
    Partner Station:
    <a href="https://hits923atlanta.com" target="_blank">
      HITS 92.3 Atlanta
    </a>
  </p>
</header>

<main>

<!-- LIVE BROADCAST -->
<section>
  <h2>Live Broadcast</h2>

  <div class="video-box">
    <iframe src="https://www.youtube.com/embed/live_stream?channel=CHANNEL_ID"></iframe>
  </div>

  <div class="audio-player">
    <p><strong>Audio Stream</strong></p>
    <audio controls src="YOUR_ICECAST_OR_STREAM_URL"></audio>
  </div>
</section>

<!-- MUSIC HUB -->
<section>
  <h2>Music Hub</h2>

  <div class="audio-player">
    <iframe
      width="100%"
      height="150"
      src="https://www.iradeo.com/station/player/174583?compact=true"
      frameborder="0"
      scrolling="no"
      allow="autoplay">
    </iframe>
  </div>
</section>

<!-- MENTAL HEALTH -->
<section>
  <h2>Mental Health & Wellness</h2>
  <ul>
    <li>Pause when your body tells you to.</li>
    <li>Curate your sound environment intentionally.</li>
    <li>Community heals — do not isolate.</li>
    <li>Art is therapy when used consciously.</li>
  </ul>
</section>

<!-- PLAYLIST -->
<section class="playlist">
  <h2>Featured Playlist</h2>
  <iframe src="https://open.spotify.com/embed/playlist/PLAYLIST_ID"></iframe>
</section>

<!-- STATION GALLERY -->
<section>
  <h2>Station Gallery</h2>

  <div class="gallery">
    <div class="video-box">
      <iframe src="https://www.youtube.com/embed/rSU2jL4rgxU" allowfullscreen></iframe>
    </div>

    <div class="video-box">
      <iframe src="https://www.youtube.com/embed/aRp37q-5Mb0" allowfullscreen></iframe>
    </div>

    <div class="video-box">
      <iframe src="https://www.youtube.com/embed/H1uNbv5dUi4" allowfullscreen></iframe>
    </div>

    <div class="video-box">
      <iframe src="https://www.youtube.com/embed/RZIjOmHndyE" allowfullscreen></iframe>
    </div>
  </div>
</section>

<!-- DJ SHOWS -->
<section>
  <h2>DJ Schedule & Shows</h2>
  <div class="grid-3">
    <div class="card"><h3>Morning Soluv</h3><p>Healing + Motivation</p></div>
    <div class="card"><h3>Artist After Dark</h3><p>Interviews & Premieres</p></div>
    <div class="card"><h3>Night Frequency</h3><p>Late-night Sonic Therapy</p></div>
  </div>
</section>

<!-- REQUEST SONG -->
<section>
  <h2>Request a Song</h2>
  <form>
    <input type="text" placeholder="Your Name">
    <input type="text" placeholder="Song & Artist">
    <textarea placeholder="Message"></textarea>
    <button>Send Request</button>
  </form>
</section>

</main>

<footer>
  <p>© 2026 SOLUV RADIO · Healing Through Sound · Hosted on GitHub Pages</p>
</footer>

</body>
</html>
