# Assignment-02-Building-and-Hosting-Your-Personal-Website<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Tashif Ghumman | Personal Website</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0d0d0d;
      color: #f2f2f2;
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 50px 20px;
      background: #111;
      border-bottom: 1px solid #333;
    }

    header h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 18px;
      color: #ccc;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: #1a1a1a;
      border-radius: 10px;
      border: 1px solid #333;
    }

    h2 {
      border-bottom: 1px solid #444;
      padding-bottom: 8px;
      margin-bottom: 15px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      background: #222;
      padding: 10px;
      margin: 8px 0;
      border-radius: 6px;
      border: 1px solid #333;
    }

    footer {
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      color: #777;
      font-size: 14px;
    }
  </style>
</head>

<body>

  <header>
    <h1>Tashif Ghumman</h1>
    <p>Finance & Business Economics Student · York University</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>
      I’m a first-year student at York University studying Finance and Business Economics.
      I enjoy playing basketball, golf, and tennis, and I also train in MMA. I love traveling
      and exploring new places. I’m currently an intern at an AI-based automation company,
      learning how technology and finance connect.
    </p>
  </section>

  <section>
    <h2>Projects & Experience</h2>
    <ul>
      <li>
        <strong>AI Automation Internship</strong><br>
        Working at an AI-based automation company, gaining experience in how AI tools
        improve business efficiency and decision-making.
      </li>
      <li>
        <strong>Personal Finance Learning</strong><br>
        Studying financial markets, investing basics, and economic trends to build a strong
        foundation for future finance roles.
      </li>
    </ul>
  </section>

  <section>
    <h2>Skills</h2>
    <ul>
      <li>Finance & Economics (Foundational)</li>
      <li>Analytical Thinking</li>
      <li>AI & Automation Awareness</li>
      <li>Teamwork & Communication</li>
      <li>Discipline & Resilience (MMA)</li>
      <li>Time Management</li>
    </ul>
  </section>

  <section>
    <h2>Interests</h2>
    <ul>
      <li>Basketball</li>
      <li>Golf</li>
      <li>Tennis</li>
      <li>MMA Training</li>
      <li>Traveling</li>
    </ul>
  </section>

  <footer>
    © <span id="year"></span> Tashif Ghumman — Personal Website Project
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>

</body>
</html>
