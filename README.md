<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Jash Enterprise — Home</title>
  <meta name="description" content="Jash Enterprise — Quality products & services. Contact: 7977659913">
  <style>
    :root{--accent:#0b74de;--bg:#f7f9fc;--card:#ffffff}
    *{box-sizing:border-box}
    body{font-family:Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; margin:0; background:var(--bg); color:#0f172a}
    header{background:linear-gradient(90deg,#0b74de22,#0b74de11);padding:28px 16px}
    .container{max-width:1000px;margin:0 auto;padding:0 16px}
    .brand{display:flex;gap:16px;align-items:center}
    .logo{width:64px;height:64px;border-radius:12px;background:var(--accent);display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:20px}
    h1{margin:0;font-size:22px}
    .grid{display:grid;grid-template-columns:1fr 340px;gap:20px;margin-top:20px}
    main{padding:20px;background:var(--card);border-radius:12px;box-shadow:0 6px 18px rgba(12,18,31,0.06)}
    aside{padding:20px;background:var(--card);border-radius:12px;box-shadow:0 6px 18px rgba(12,18,31,0.04)}
    section{margin-bottom:18px}
    .btn{display:inline-block;padding:10px 14px;border-radius:10px;background:var(--accent);color:white;text-decoration:none;font-weight:600}
    .info-row{display:flex;align-items:flex-start;gap:10px}
    small{color:#475569}
    .card{padding:12px;border-radius:8px;background:#fbfdff;border:1px solid #eef6ff}
    footer{padding:20px;text-align:center;color:#475569;font-size:14px}
    @media (max-width:880px){.grid{grid-template-columns:1fr} .logo{width:56px;height:56px}}
  </style>
</head>
<body>
  <header>
    <div class="container brand">
      <div class="logo">JE</div>
      <div>
        <h1>Jash Enterprise</h1>
        <small>Trust • Quality • Service</small>
      </div>
    </div>
  </header>

  <div class="container" style="margin-top:20px">
    <div class="grid">
      <main>
        <section>
          <h2>About Us</h2>
          <p>Jash Enterprise is a Mumbai-based company offering reliable products and services with customer-first focus. Located in Dahisar East, we serve clients across the city with timely delivery and professional support.</p>
        </section>

        <section>
          <h2>Our Services</h2>
          <ul>
            <li>Society repairs & Maintenance</li>
            <li>Trunky Interior Design and Interior work</li>
            <li>Supply of Construction, Electrical, Plumbing Material</li>
          </ul>
        </section>

        <section>
          <h2>Contact</h2>
          <p class="card">
            <strong>Mobile:</strong> <a href="tel:+917977659913">+91 79776 59913</a><br>
            <strong>Address:</strong> A-11 Labh Sadan CHS, Marath Colony, Dahisar East, Mumbai 400068<br>
            <strong>GST:</strong> 27AKLPD2776R1ZE
          </p>
        </section>

        <section>
          <h2>Send us a message</h2>
          <!-- ✅ Fix: Use Netlify form handling instead of mailto -->
          <form name="contact" method="POST" data-netlify="true">
            <input type="hidden" name="form-name" value="contact">
            <div style="display:flex;flex-direction:column;gap:8px">
              <input name="name" placeholder="Your name" required style="padding:10px;border-radius:8px;border:1px solid #e6eef8">
              <input name="email" type="email" placeholder="Email" required style="padding:10px;border-radius:8px;border:1px solid #e6eef8">
              <textarea name="message" placeholder="Message" rows="5" required style="padding:10px;border-radius:8px;border:1px solid #e6eef8"></textarea>
              <button type="submit" class="btn">Send message</button>
            </div>
          </form>
          <p style="margin-top:8px"><small>Or contact via WhatsApp: <a href="https://wa.me/919777659913" target="_blank">+91 79776 59913</a></small></p>
        </section>
      </main>

      <aside>
        <section>
          <h3>Quick info</h3>
          <p class="info-row"><strong>Company:</strong> Jash Enterprise</p>
          <p class="info-row"><strong>Phone:</strong> <a href="tel:+917977659913">+91 79776 59913</a></p>
          <p class="info-row"><strong>GST:</strong> 27AKLPD2776R1ZE</p>
        </section>

        <section>
          <h3>Location</h3>
          <div class="card">
            <p>A-11 Labh Sadan CHS<br>Marath Colony, Dahisar East<br>Mumbai - 400068</p>
            <p><a href="https://www.google.com/maps/search/?api=1&query=A-11+Labh+Sadan+CHS+Marath+Colony+Dahisar+East+Mumbai+400068" target="_blank" class="btn">Open in Google Maps</a></p>
          </div>
        </section>

        <section>
          <h3>Business Info</h3>
          <div class="card">
            <p>Registration: Proprietorship / Small Business</p>
            <p>GSTIN: 27AKLPD2776R1ZE</p>
          </div>
        </section>
      </aside>
    </div>
  </div>

  <footer>
    © <span id="year"></span> Jash Enterprise — All rights reserved.
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
