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

    .mental-health ul { padding-left: 20px; }
    .mental-health li { margin-bottom: 10px; }

    .playlist iframe {
      width: 100%;
      height: 380px;
      border-radius: 8px;
      border: none;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 15px;
    }

    .gallery img {
      width: 100%;
      height: 160px;
      object-fit: cover;
      border-radius: 8px;
      border: 1px solid var(--gray);
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

    .card h3 { color: var(--turquoise); margin-top: 0; }

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
</header>

<main>

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

<section class="mental-health">
  <h2>Mental Health & Wellness</h2>
  <p>SOLUV Radio exists to protect the mind, spirit, and creativity of our listeners.</p>
  <ul>
    <li>Pause when your body tells you to.</li>
    <li>Curate your sound environment intentionally.</li>
    <li>Community heals — do not isolate.</li>
    <li>Art is therapy when used consciously.</li>
  </ul>
</section>

<section class="playlist">
  <h2>Featured Playlist</h2>
  <iframe src="https://open.spotify.com/embed/playlist/PLAYLIST_ID"></iframe>
</section>

<section>
  <h2>Station Gallery</h2>
  <div class="gallery">
    <img src="https://via.placeholder.com/400x300" />
    <img src="https://via.placeholder.com/400x300" />
    <img src="https://via.placeholder.com/400x300" />
    <img src="https://via.placeholder.com/400x300" />
  </div>
</section>

<section>
  <h2>Live Community Chat</h2>
  <div class="card">
    <p>Embed Discord, VDO.Ninja, or Chatango here for real-time listener interaction.</p>
  </div>
</section>

<section>
  <h2>DJ Schedule & Shows</h2>
  <div class="grid-3">
    <div class="card"><h3>Morning Soluv</h3><p>Daily · Healing + Motivation</p></div>
    <div class="card"><h3>Artist After Dark</h3><p>Interviews & premieres</p></div>
    <div class="card"><h3>Night Frequency</h3><p>Late night sonic therapy</p></div>
  </div>
</section>

<section>
  <h2>Request a Song</h2>
  <form>
    <input type="text" placeholder="Your Name" />
    <input type="text" placeholder="Song & Artist" />
    <textarea placeholder="Message"></textarea>
    <button>Send Request</button>
  </form>
</section>

<section>
  <h2>Artist Submissions</h2>
  <form>
    <input type="text" placeholder="Artist Name" />
    <input type="url" placeholder="Music Link" />
    <textarea placeholder="Tell us about your work"></textarea>
    <button>Submit Music</button>
  </form>
</section>

<section>
  <h2>Ads & Sponsors</h2>
  <div class="grid-3">
    <div class="card">Sponsor Slot</div>
    <div class="card">Brand Partner</div>
    <div class="card">Advertise With SOLUV</div>
  </div>
</section>

<section>
  <h2>Why SOLUV Radio</h2>
  <div class="grid-3">
    <div class="card"><h3>Mind‑First Media</h3><p>We prioritize wellness over algorithms.</p></div>
    <div class="card"><h3>Independent Artists</h3><p>Real exposure without exploitation.</p></div>
    <div class="card"><h3>Community Ownership</h3><p>This station grows with its listeners.</p></div>
  </div>
</section>

</main>

<footer>
  <p>© 2026 SOLUV RADIO · Healing Through Sound · Hosted on GitHub Pages</p>
</footer>

</body>
</html>

