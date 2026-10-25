# about-me-html
About Ki'Anna

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Me | IT Student</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f7fb;
      color: #1f2937;
      line-height: 1.6;
      padding: 24px;
    }

    h1, h2, h3 {
      color: #1d4ed8;
    }

    p {
      margin: 10px 0;
      padding: 0 4px;
    }

    .page-header {
      margin: 20px auto 30px;
      padding: 25px 30px;
      border: 3px solid #1d4ed8;
      border-radius: 12px;
      background: #e0edff;
      text-align: center;
    }

    .main-nav {
      margin: 0 0 25px;
      padding: 12px 18px;
      border: 2px solid #f59e0b;
      border-radius: 10px;
      background: #fff7ed;
    }

    .nav-list {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 18px;
      flex-wrap: wrap;
    }

    .nav-item {
      margin: 6px;
      padding: 8px 12px;
      border: 1px solid #fbbf24;
      border-radius: 8px;
      background: #ffffff;
    }

    .info-card {
      margin: 18px 0;
      padding: 22px 24px;
      border: 2px solid #cbd5e1;
      border-radius: 12px;
      background: #ffffff;
    }

    #about {
      border-left: 6px solid #3b82f6;
      background: #f8fbff;
    }

    #interests {
      border-left: 6px solid #f59e0b;
      background: #fffaf0;
    }

    #goals {
      border-left: 6px solid #22c55e;
      background: #f0fdf4;
    }

    .goal-box {
      margin: 12px 0 18px;
      padding: 18px 20px;
      border: 2px dashed #22c55e;
      border-radius: 10px;
      background: #ecfdf5;
    }

    figure {
      margin: 22px 0 0;
      padding: 12px;
      border: 3px solid #94a3b8;
      border-radius: 12px;
      background: #f8fafc;
      text-align: center;
    }

    img {
      display: block;
      max-width: 100%;
      height: auto;
      margin: 0 auto;
      border: 2px solid #1f2937;
      border-radius: 8px;
    }

    figcaption {
      margin-top: 10px;
      padding: 6px 0;
      color: #475569;
      font-style: italic;
    }

    footer {
      margin-top: 30px;
      padding: 16px 20px;
      border-top: 3px solid #1f2937;
      text-align: center;
      background: #f1f5f9;
    }
  </style>
</head>
<body>
  <header class="page-header">
    <h1>About Me</h1>
    <p>Welcome to my personal webpage!</p>
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
      <p>I am an Information Technology student who is learning about computers, technology, and web development. I enjoy learning new skills that can help me in my education and future career.</p>
      <figure>
        <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=800&q=80" alt="Person using a laptop to work on technology and digital projects" width="409">
        <figcaption>Learning about technology and digital tools.</figcaption>
      </figure>
    </section>

    <section id="interests" class="info-card">
      <h2>My Interests</h2>
      <p>Some topics I enjoy learning about include:</p>
      <ul>
        <li>Computer hardware and software</li>
        <li>Command Prompt and computer systems</li>
        <li>HTML and website development</li>
        <li>Problem-solving and troubleshooting</li>
      </ul>
    </section>

    <section id="goals" class="info-card">
      <h2>My Goals</h2>
      <div class="goal-box">
        <h3>My Education Goals</h3>
        <p>My goal is to continue learning about Information Technology and improve my computer skills.</p>
      </div>
      <div class="goal-box">
        <h3>My Career Goals</h3>
        <p>I want to gain practical experience and develop the skills needed for a successful career in IT.</p>
      </div>
    </section>
  </main>

  <footer>
    <p>Created by an IT student | 2026</p>
  </footer>
</body>
</html>
