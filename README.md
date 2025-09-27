<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Inua Nurse Footprint (INF)</title>
  <link rel="stylesheet" href="assets/css/style.css"/>
</head>
<body>
  <header>
    <img src="assets/img/inf-logo.png" alt="INF Logo" height="60"/>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About Us</a>
      <a href="programs.html">Programs</a>
      <a href="events.html">Events</a>
      <a href="get-involved.html">Get Involved</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <section class="hero">
    <h1>Welcome to Inua Nurse Footprint (INF)</h1>
    <p>
      Empowering the next generation of nurses through mentorship, outreach, mental health, and alumni engagement.<br>
      <span style="font-weight:600;">#TheNextGenerationOfNurses</span>
    </p>
    <a href="get-involved.html" class="btn">Get Involved</a>
  </section>

  <main>
    <section>
      <h2>Key Programs</h2>
      <ul>
        <li>🎓 Mentorship & Academic Empowerment</li>
        <li>🧠 Mental Health Desk</li>
        <li>🤝 Alumni Engagement</li>
        <li>🏥 Community Outreach & Health Camps</li>
        <li>💙 Inua Nurse Fund (Student Welfare)</li>
      </ul>
      <p><a href="programs.html" class="btn">Explore Programs</a></p>
    </section>
    <section>
      <h2>Latest News & Events</h2>
      <ul>
        <li>Charity Walk: October 20, 2025</li>
        <li>Alumni Webinar: November 2, 2025</li>
        <li><a href="events.html">View all events</a></li>
      </ul>
    </section>
  </main>
  <footer>
    <p>© 2025 Inua Nurse Footprint | Follow us on socials @InuaNurseFootprint</p>
  </footer>
</body>
</html>:root {
  --primary: #002147;
  --secondary: #ffffff;
  --accent: #00509e;
  --light-bg: #f8f9fa;
}

body {
  font-family: 'Lato', Arial, sans-serif;
  margin: 0;
  background: var(--light-bg);
  color: var(--primary);
}

header {
  background: var(--primary);
  color: var(--secondary);
  padding: 0.5rem 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
}

header img {
  margin-left: 2rem;
}

nav {
  margin-right: 2rem;
}

nav a {
  color: var(--secondary);
  margin: 0 1.1rem;
  font-weight: bold;
  letter-spacing: 1px;
  text-decoration: none;
  transition: color 0.2s;
}

nav a:hover {
  color: var(--accent);
}

.hero {
  text-align: center;
  padding: 60px 10px 40px 10px;
  background: linear-gradient(to right, var(--primary), var(--accent));
  color: var(--secondary);
}

.hero .btn {
  display: inline-block;
  margin-top: 2rem;
  padding: 12px 28px;
  background: var(--secondary);
  color: var(--primary);
  font-weight: bold;
  border-radius: 5px;
  text-decoration: none;
  transition: 0.2s;
  border: none;
}

.hero .btn:hover {
  background: var(--accent);
  color: var(--secondary);
}

main, section {
  margin: 0 auto 32px auto;
  max-width: 900px;
  background: var(--secondary);
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  padding: 32px 24px;
}

section:not(.hero) {
  margin-top: 24px;
}

ul, ol {
  padding-left: 1.2em;
}

footer {
  background: var(--primary);
  color: var(--secondary);
  text-align: center;
  padding: 18px 10px 10px 10px;
  margin-top: 40px;
  font-size: 1rem;
}

footer a {
  color: var(--secondary);
  margin: 0 0.3rem;
}

.btn, button {
  background: var(--primary);
  color: var(--secondary);
  border: none;
  border-radius: 4px;
  padding: 10px 22px;
  font-size: 1em;
  cursor: pointer;
  margin-top: 10px;
  transition: background 0.2s;
}

.btn:hover, button:hover {
  background: var(--accent);
}

form {
  max-width: 500px;
  margin: 0 auto;
  padding: 20px 16px;
  background: var(--light-bg);
  border-radius: 8px;
  box-shadow: 0 1px 4px rgba(0,0,0,0.06);
}

label {
  display: block;
  margin: 10px 0 6px 0;
  font-weight: 600;
}

input, textarea, select {
  width: 100%;
  padding: 8px 10px;
  margin-bottom: 16px;
  border: 1px solid var(--primary);
  border-radius: 4px;
  font-size: 1em;
  background: var(--secondary);
}

@media (max-width: 700px) {
    header, nav {
        flex-direction: column;
        align-items: flex-start;
    }
    header img, nav {
        margin: 0.5rem;
    }
    main, section {
        padding: 14px 7px;
    }
}
