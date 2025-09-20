<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Dr. Sandal Paul — Official site</title>
  <meta name="description" content="Dr. Sandal Paul — consultant, resort doctor. Contact & professional info." />
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <h1>Dr. Sandal Paul</h1>
    <p class="tag">Registered Doctor in India & Maldives • License: PL 04694</p>
  </header>

  <main class="container">
    <section id="about">
      <h2>About</h2>
      <p>I am Dr. Sandal Paul, a registered doctor in both India and the Maldives. This website serves as my professional profile and a platform to share health awareness talks with the community.</p>
    </section>

    <section id="services">
      <h2>Services</h2>
      <ul>
        <li>Resort medicine / primary care</li>
        <li>Emergency stabilization and transfer</li>
        <li>Health talks and patient education</li>
        <li>Dental and surgical referrals</li>
      </ul>
    </section>

    <section id="health-talks">
      <h2>Health Talks</h2>
      <article>
        <h3>Basic Life Support (BLS) — Step by Step Guide</h3>
        <p>Basic Life Support (BLS) is the immediate care given to a person in a life-threatening situation, such as cardiac arrest or respiratory failure, until advanced medical help is available.</p>
        <h4>Step-by-step BLS procedure:</h4>
        <ol>
          <li><strong>Check responsiveness:</strong> Tap the person’s shoulder and ask loudly, “Are you okay?”</li>
          <li><strong>Call for help:</strong> If no response, shout for help and call emergency services immediately.</li>
          <li><strong>Check breathing:</strong> Look for normal breathing (not gasping) for no more than 10 seconds.</li>
          <li><strong>Begin chest compressions:</strong>
            <ul>
              <li>Place the heel of your hand in the center of the chest, other hand on top.</li>
              <li>Compress hard and fast — at least 100–120 compressions per minute, depth of about 5 cm (2 inches).</li>
              <li>Allow full chest recoil between compressions.</li>
            </ul>
          </li>
          <li><strong>Rescue breaths:</strong> If trained, give 2 rescue breaths after every 30 compressions.
            <ul>
              <li>Tilt the head back, lift the chin, pinch the nose, and breathe into the mouth until chest rises.</li>
            </ul>
          </li>
          <li><strong>Continue CPR:</strong> Keep cycles of 30 compressions and 2 breaths until help arrives or the person starts breathing.</li>
          <li><strong>Use an AED if available:</strong> Turn it on, follow the voice prompts, and deliver shock if advised.</li>
        </ol>
        <p><em>Note: If untrained, perform hands-only CPR (continuous chest compressions without breaths) until help arrives.</em></p>
      </article>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:dr.sandalpaul123@gmail.com">dr.sandalpaul123@gmail.com</a></p>
      <p>Location/Clinic: Kerala, India</p>
    </section>
  </main>

  <footer class="site-footer">
    <p>&copy; <span id="year"></span> Dr. Sandal Paul</p>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>


---

## Updates (added by assistant)

I added a **Health Talks** section (Basic Life Support — step-by-step) and updated contact & doctor information. Below are the updated file contents you can copy into your repository or replace the existing files with.

### Updated `README.md`
```markdown
# dr.sandalpaul.tk

🌐 Official website of **Dr. Sandal Paul**
Hosted with GitHub Pages at [https://dr.sandalpaul.tk](https://dr.sandalpaul.tk)

---

## About
This website serves as an online profile and resource hub for Dr. Sandal Paul.
It includes:
- 🩺 Doctor’s professional profile and credentials (Registered doctor in India and the Maldives)
- 💬 Health talks and public awareness articles — including Basic Life Support (BLS) guidance
- 📞 Contact details for consultation and services

---

## Deployment
This repository is deployed using **GitHub Pages** with a custom domain `dr.sandalpaul.tk`.

### Steps followed:
1. Repository created with the name `dr.sandalpaul.tk`.
2. Added a `CNAME` file with the domain `dr.sandalpaul.tk`.
3. Configured DNS A records to point to GitHub Pages IPs.
4. Enabled HTTPS in GitHub Pages settings.

---

## Health Talks — Basic Life Support
A dedicated Health Talks section on the website contains an easy, step-by-step overview of Basic Life Support (CPR) for adults. This is intended for public education only — it does **not** replace certified in-person training. See the site pages for the full content.

---

## Contact
📧 Email: dr.sandalpaul123@gmail.com  
📍 Location / Clinic: Kerala, India


---

## Customization
- Edit `index.html` to update more doctor details, add articles, or link PDFs/videos for Health Talks.
- Modify `styles.css` for layout and design.
- Add more pages (e.g., Blog, CV, Services) if needed.
```

### Updated `index.html`
```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Dr. Sandal Paul — Official site</title>
  <meta name="description" content="Dr. Sandal Paul — consultant, resort doctor. Contact & professional info." />
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <h1>Dr. Sandal Paul</h1>
    <p class="tag">Resort Doctor • Clinical Educator • <small>Registered doctor in India &amp; the Maldives</small></p>
  </header>

  <main class="container">
    <section id="about">
      <h2>About</h2>
      <p>Welcome — I'm Dr. Sandal Paul. (Edit this paragraph with a short bio, specialties, and contact details.)</p>
    </section>

    <section id="services">
      <h2>Services</h2>
      <ul>
        <li>Resort medicine / primary care</li>
        <li>Emergency stabilization and transfer</li>
        <li>Dental and surgical referrals</li>
      </ul>
    </section>

    <section id="health-talks">
      <h2>Health Talks</h2>
      <article id="bls">
        <h3>Basic Life Support (BLS) — Step by step (overview)</h3>
        <p><strong>Important:</strong> This is a public education summary. Take a certified BLS/CPR course to practice skills and get hands-on feedback.</p>
        <ol>
          <li><strong>Ensure safety &amp; responsiveness</strong> — Make sure the scene is safe. Gently tap the person and shout to see if they respond.</li>
          <li><strong>Call for help</strong> — If no response, shout for help. Ask someone to call emergency services immediately and to bring an AED (automated external defibrillator) if available. If you are alone, call your local emergency number before or as you start CPR depending on local guidance and the situation.</li>
          <li><strong>Check breathing</strong> — Look for normal breathing (not gasping). If the person is not breathing normally, begin CPR.</li>
          <li><strong>Start chest compressions</strong> —
            <ul>
              <li>Place the heel of one hand in the centre of the chest (lower half of the sternum), place your other hand on top and interlock fingers.</li>
              <li>Keep arms straight, shoulders over hands, and push hard and fast: compress at least ~5 cm (about 2 inches) but not more than 6 cm, at a rate of 100–120 compressions per minute.</li>
              <li>Allow full chest recoil after each compression.</li>
            </ul>
          </li>
          <li><strong>Rescue breaths (if trained)</strong> — After 30 compressions, give 2 rescue breaths if you are trained and willing:
            <ul>
              <li>Open the airway with a head‑tilt, chin‑lift, pinch the nose, and give 2 breaths (each about 1 second) watching for chest rise.</li>
              <li>If you are untrained or uncomfortable giving breaths, continue uninterrupted chest compressions (compression‑only CPR).</li>
            </ul>
          </li>
          <li><strong>Continue cycles</strong> — Repeat cycles of 30 compressions and 2 breaths (or continuous compressions if not giving breaths) until advanced help arrives, an AED is ready to use, or the person shows signs of life.</li>
          <li><strong>Use an AED as soon as possible</strong> — Turn on the AED and follow voice prompts. Continue CPR between shocks as instructed by the device.</li>
          <li><strong>Special notes</strong> — If the collapse is witnessed and an AED is immediately available, use it as early as possible. For children and infants, compression depth and ratios differ; seek certified paediatric BLS training for accurate guidance.</li>
        </ol>
        <p class="disclaimer"><em>Disclaimer:</em> This summary is for educational purposes only and does not replace certified training or local protocols. For complete recommendations see official resuscitation guidelines and attend hands-on training.</em></p>
      </article>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:dr.sandalpaul123@gmail.com">dr.sandalpaul123@gmail.com</a></p>
      <p>Location / Clinic: Kerala, India</p>
    </section>
  </main>

  <footer class="site-footer">
    <p>&copy; <span id="year"></span> Dr. Sandal Paul</p>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
```

---

If you'd like, I can now:
- Replace the original `index.html` and `README.md` blocks in the repo file (I can try to update them in the canvas directly), or
- Produce downloadable files (`index.html`, `README.md`) ready to push to GitHub, or
- Create a printable PDF poster of the BLS steps for the clinic.

Tell me which of the above you'd like next and I'll proceed.
