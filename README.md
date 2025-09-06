<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Charity: Water - End the Water Crisis</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: 'Helvetica Neue', Arial, sans-serif;
      background: #fff;
      color: #000;
      line-height: 1.6;
    }

    header {
      background: #FFD200;
      padding: 20px 60px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header img {
      height: 40px;
      background: transparent; /* Ensure no white background */
      display: block;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 25px;
      align-items: center; /* Ensure all nav items are vertically aligned */
      margin: 0;
      padding: 0;
    }

    nav li {
      display: flex;
      align-items: center; /* Vertically center each nav item */
      height: 100%;        /* Make sure all items have equal height */
    }

    nav a {
      text-decoration: none;
      color: #000;
      font-weight: 500;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background: url('Uganda-2018-charitywater-cubbygraham-1769.jpg') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 150px 20px;
      position: relative;
    }

    .hero::after {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.4);
    }

    .hero-content {
      position: relative;
      z-index: 1;
      max-width: 800px;
      margin: auto;
    }

    .hero h2 {
      font-size: 3rem;
      margin-bottom: 20px;
      font-weight: bold;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }

    .btn {
      display: inline-block;
      padding: 14px 28px;
      background: #FFD200;
      color: #000;
      font-weight: bold;
      border-radius: 5px;
      text-decoration: none;
      transition: background 0.3s ease;
    }

    .btn:hover {
      background: #e6be00;
    }

    .impact {
      display: flex;
      justify-content: space-around;
      padding: 60px 20px;
      background: #f5f5f5;
      text-align: center;
    }

    .impact div {
      max-width: 250px;
    }

    .impact h3 {
      font-size: 2rem;
      color: #FFD200;
      margin-bottom: 10px;
    }

    .impact p {
      color: #000; /* Ensure impact text is black for better contrast */
    }

    .section {
      padding: 80px 20px;
      text-align: center;
      max-width: 900px;
      margin: auto;
    }

    .section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }

    .section p {
      font-size: 1.1rem;
      margin-bottom: 30px;
      color: #000; /* Ensure all section paragraphs are black for visibility */
    }

    .stories {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 40px;
    }

    .story {
      background: #fff;
      border: 1px solid #eee;
      border-radius: 8px;
      width: 280px;
      text-align: left;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      overflow: hidden;
    }

    .story img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .story-content {
      padding: 15px;
    }

    .story-content h3 {
      margin-bottom: 10px;
      font-size: 1.2rem;
      color: #000; /* Make story box titles black for better contrast */
    }

    .story-content p {
      font-size: 0.95rem;
      color: #000; /* Changed from #555 to black for better contrast */
    }

    footer {
      background: #000;
      color: #000; /* Changed from white to black */
      text-align: center;
      padding: 40px 20px;
    }

    footer p {
      font-size: 0.9rem;
      color: #333; /* Changed from #ccc to #333 for better contrast */
    }
  </style>
</head>
<body>

  <header>
    <img src="charitywater_logo_vertical_AllBlack.png" alt="Charity: Water Logo">
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Our Work</a></li>
        <li><a href="#">Stories</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>Together, We Can End the Water Crisis</h2>
      <p>Since 2006, we’ve been working to ensure everyone has access to life’s most basic need. With your help, it can happen in our lifetime.</p>
      <a href="#" class="btn">Donate Now</a>
    </div>
  </section>

  <section class="impact">
    <div>
      <h3>186,000+</h3>
      <p>Water projects funded worldwide</p>
    </div>
    <div>
      <h3>29</h3>
      <p>Countries served with clean water</p>
    </div>
    <div>
      <h3>20M+</h3>
      <p>People gaining access to clean water</p>
    </div>
  </section>

  <section class="section">
    <h2>Why Water?</h2>
    <p>Clean water changes everything. It improves health, keeps kids in school, supports economic growth, and empowers women and girls.</p>
    <a href="#" class="btn">See Stories of Change</a>
    <div class="stories">
      <div class="story">
        <img src="eyJidWNrZXQiOiJkcm9wbWFyayIsImtleSI6IjMwMDAxOC9hMTdlNjkyNzM0YjcxOTZkNDMyNWRhOTI3ZDYxODI5OTFhNmUyMjc2Yzc1MzU5YmVlYjZhY2EzZDIwNjM4NWE1L0pUN0E0NTg5LUVkaXQtRWRpdC5qcGciLCJlZGl0cyI6eyJyZXNpemUiOnsid2lkdGgiOjYw.jpg" alt="Hope in Ethiopia">
        <div class="story-content">
          <h3>Hope in Ethiopia</h3>
          <p>A new well transformed life for hundreds of families, giving them clean water close to home.</p>
        </div>
      </div>
      <div class="story">
        <img src="charity_water_Tanzania_TaraShupePhotography_0255.jpg">
        <div class="story-content">
          <h3>Clean Water for Kids</h3>
          <p>Children no longer walk miles each day, and now have time to attend school and play.</p>
        </div>
      </div>
      <div class="story">
        <img src="https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?auto=format&fit=crop&w=600&q=80" alt="Community project">
        <div class="story-content">
          <h3>Empowered Communities</h3>
          <p>Women lead water committees to maintain wells, ensuring sustainability for generations.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="section">
    <h2>100% Model</h2>
    <p>We promise that 100% of your donation goes directly to clean water projects. Private donors fund our operations so every dollar you give helps people in need.</p>
  </section>

  <footer>
    <p>© 2025 charity: water — Ending the global water crisis together</p>
  </footer>

</body>
</html>
