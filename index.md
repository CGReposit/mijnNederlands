<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>Mijn Nederlands</title>

  <style>
    /* === GLOBAL STYLES === */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #222;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    a {
      color: #0056b3;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }

    /* === HEADER === */
    header {
      background: #f4f4f4;
      padding: 1rem;
      text-align: center;
      font-size: 1.4rem;
      font-weight: bold;
      border-bottom: 2px solid #ddd;
    }

    /* === MAIN LAYOUT === */
    .container {
      display: flex;
      flex: 1;
      gap: 2rem;
      padding: 1rem;
    }

    /* === LEFT NAV === */
    nav {
      min-width: 240px;
      max-width: 280px;
      border-right: 1px solid #ccc;
      padding-right: 1rem;
    }
    nav ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    nav li + li {
      margin-top: 0.6rem;
    }
    nav a {
      display: block;
      padding: 0.35rem 0.5rem;
      border-radius: 4px;
    }
    nav a:hover {
      background: #eef;
    }
    nav .section-title {
      font-size: 1.15rem;
      font-weight: bold;
      margin: 1rem 0 0.5rem;
      text-transform: uppercase;
      border-bottom: 1px solid #ccc;
      padding-bottom: 0.25rem;
    }

    /* === MAIN CONTENT === */
    main {
      flex: 1;
      max-width: 720px;
    }
    h1 {
      margin-top: 0;
    }

    /* === RESPONSIVE === */
    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }
      nav {
        max-width: none;
        border-right: none;
        border-bottom: 1px solid #ccc;
        padding-bottom: 1rem;
      }
    }
  </style>
</head>

<body>

  <header>Mijn Nederlands — Learning Dutch</header>

  <div class="container">

    <nav>
      <div class="section-title">Learn / Topics</div>
      <ul>
        <li><a href="#Dutch-Numeration">Dutch Numeration</a></li>
        <li><a href="#Dutch-Place-Names">Dutch Place Names</a></li>
        <li><a href="#Places-Vocab">Places & Locations Vocab</a></li>
        <li><a href="#History-Dutch-Language">History of Dutch</a></li>
        <li><a href="#Verbs-Intro">Dutch Verbs — Intro</a></li>
        <li><a href="#Verb-System">Dutch Verb System</a></li>
      </ul>
    </nav>

    <main>
      <h1 id="Dutch-Numeration">Dutch Numeration: How to Learn Numbers</h1>
      <p>Welcome to my personal project for learning Dutch. This repository serves both as a structured learning journal and resource library.</p>

      <!-- ADD your sections below as <section id="..."> -->
      <section id="Dutch-Place-Names">
        <h2>Dutch Place Names — Understanding Location Suffixes</h2>
        <p>...</p>
      </section>

      <section id="Places-Vocab">
        <h2>Dutch Places & Locations — Complete Vocabulary Guide</h2>
        <p>...</p>
      </section>

      <section id="History-Dutch-Language">
        <h2>History of the Dutch Language</h2>
        <p>...</p>
      </section>

      <section id="Verbs-Intro">
        <h2>Dutch Verbs — A Comprehensive Introduction</h2>
        <p>...</p>
      </section>

      <section id="Verb-System">
        <h2>The Dutch Verb System — A Deep Dive</h2>
        <p>...</p>
      </section>

    </main>

  </div>

</body>
</html>
