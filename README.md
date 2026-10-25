<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About Me | Ki'Anna</title>
  <style>
    :root {
      --shadow: rgba(15, 23, 42, 0.08);
      box-sizing: border-box;
    html {
      scroll-behavior: smooth;
    }
 body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(180deg, #eef5ff 0%, var(--bg) 100%);
      color: var(--text);
      line-height: 1.7;
      padding: 24px;
    }
a {
      color: var(--primary);
      text-decoration: none;
    }
 a:hover,
    a:focus {
      text-decoration: underline;
    }.container {
      max-width: 980px;
      margin: 0 auto;
    }
.page-header {
      background: #e0edff;
      border: 3px solid var(--primary);
      border-radius: 18px;
      padding: 36px 24px;
      text-align: center;
      box-shadow: 0 8px 20px var(--shadow);
    }
 .page-header h1 {
      margin: 0 0 12px;
      color: var(--primary);
      font-size: clamp(2.2rem, 4vw, 3.2rem);
    }.page-header p {
      margin: 0;
      font-size: 1.1rem;
      color: var(--muted);
    } .main-nav {
      margin: 24px 0 28px;
      padding: 16px 20px;
      background: #fff7ed;
      border: 2px solid var(--secondary);
      border-radius: 12px;
      box-shadow: 0 6px 18px rgba(245, 158, 11, 0.08);
    }nav-list {
      list-style: none;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 14px;
      padding: 0;
      margin: 0;
    }.nav-item {
      background: #fff;
      border: 1px solid #fbbf24;
      border-radius: 10px;
      padding: 10px 14px;
      transition: transform 0.2s ease;
    }.nav-item:hover {
      transform: translateY(-2px);
    }.info-card {
      background: var(--card);
      border: 2px solid var(--border);
      border-radius: 16px;
      padding: 26px 24px;
      margin: 22px 0;
      box-shadow: 0 8px 20px var(--shadow);
    }#about {
      border-left: 6px solid #3b82f6;
      background: #f8fbff;
    }#interests {
      border-left: 6px solid var(--secondary);
      background: #fffaf0;
    }#goals {
      border-left: 6px solid var(--success);
      background: #f0fdf4;
    }h2,
    h3 {
      color: var(--primary);
      margin-top: 0;
    }ul {
      margin: 12px 0 0 20px;
      padding: 0;
    }li {
      margin-bottom: 8px;
    }.goal-box {
      background: #ecfdf5;
      border: 2px dashed var(--success);
      border-radius: 12px;
      padding: 18px 20px;
      margin-top: 16px;
    } figure {
      margin: 22px 0 0;
      padding: 16px;
      background: #f8fafc;
      border: 3px solid #94a3b8;
      border-radius: 14px;
      text-align: center;
    }img {
      display: block;
      max-width: 100%;
      height: auto;
      margin: 0 auto;
      border-radius: 10px;
      border: 2px solid #1f2937;
    } figcaption {
      color: var(--muted);
      font-style: italic;
      margin-top: 12px;
    }footer {
      margin-top: 30px;
      padding: 18px 20px;
      background: #f1f5f9;
      border-top: 3px solid #1f2937;
      text-align: center;
      border-radius: 12px 12px 0 0;
    }@media (max-width: 600px) {
      body {
        padding: 16px;
      } .info-card {
        padding: 20px 18px;
      }.main-nav {
        padding: 12px 14px;
      }.nav-list {
        gap: 10px;
  </style>
</head>
<body>
  <div class="container">
    <header class="page-header">
      <h1>About Me</h1>
      <p>Welcome to my personal webpage—thank you for visiting!</p>
    </header>
 <nav class="main-nav" aria-label="Main navigation">
      <ul class="nav-list">
        <li class="nav-item"><a href="#about">About Me</a></li>
        <li class="nav-item"><a href="#interests">My Interests</a></li>
        <li class="nav-item"><a href="#goals">My Goals</a></li>
      </ul>
    </nav>
    <main>
      <section id="about" class="info-card">
        <h2>About Me</h2>
        <p>
          I am an Information Technology student with a growing interest in computers,
          technology, and web development. I enjoy learning new skills, exploring digital tools,
          and building projects that help me improve both my education and future career.
        </p><figure>
          <img
            src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=800&q=80"
            alt="A person working on a laptop while learning about technology"
            width="600"
          />
          <figcaption>Learning, building, and growing in the world of technology.</figcaption>
        </figure>
      </section>
 <section id="interests" class="info-card">
        <h2>My Interests</h2>
        <p>Some of the topics I enjoy learning about include:</p>
        <ul>
          <li>Computer hardware and software</li>
          <li>Operating systems and command-line tools</li>
          <li>HTML, CSS, and website development</li>
          <li>Problem-solving and troubleshooting</li>
          <li>Technology that improves daily life and productivity</li>
        </ul>
      </section><section id="goals" class="info-card">
        <h2>My Goals</h2>
<div class="goal-box">
          <h3>Education Goals</h3>
          <p>
            My goal is to continue expanding my knowledge in Information Technology,
            improve my technical skills, and build confidence in working with modern tools.
          </p>
        </div><div class="goal-box">
          <h3>Career Goals</h3>
          <p>
            I want to gain hands-on experience, strengthen my problem-solving abilities,
            and prepare myself for a successful career in IT.
          </p>
        </div>
      </section>
    </main>
<footer>
      <p>Created by Ki'Anna | 2026</p>
    </footer>
  </div>
</body>
</html>
