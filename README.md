<style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

    *{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins', sans-serif;}
    body{background:#0f0f0f;color:#eee;line-height:1.6;}

    /* Header */
    header{background:linear-gradient(135deg,#ff004c,#4500ff);color:#fff;padding:60px 20px;text-align:center;}
    header h1{font-size:3rem;animation:fadeInDown 1.2s;}
    header p{font-size:1.3rem;color:#ddd;height:35px;}

    /* Typing effect */
    .typing{
      display:inline-block;
      border-right:3px solid #fff;
      white-space:nowrap;
      overflow:hidden;
      animation:typing 4s steps(30,end), blink .7s step-end infinite alternate;
    }

    @keyframes typing{
      from{width:0;}
      to{width:100%;}
    }
    @keyframes blink{
      50%{border-color:transparent;}
    }

    /* Navbar */
    nav{text-align:center;padding:15px;background:#1c1c1c;position:sticky;top:0;z-index:1000;}
    nav a{margin:0 20px;text-decoration:none;color:#fff;font-weight:bold;transition:.3s;}
    nav a:hover{color:#ff004c;}

    /* Section */
    section{padding:60px 20px;max-width:1100px;margin:auto;}

    /* About */
    .about{display:flex;flex-wrap:wrap;align-items:center;gap:30px;animation:fadeIn 1.5s;}
    .about img{width:230px;border-radius:50%;border:5px solid #ff004c;box-shadow:0 5px 15px rgba(0,0,0,0.6);}
    .about h2{color:#ff004c;}

    /* Skills */
    .skills{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:25px;margin-top:40px;}
    .card{background:#1c1c1c;padding:25px;border-radius:15px;text-align:center;font-size:1.1rem;
      box-shadow:0 4px 12px rgba(0,0,0,0.5);transition:.4s;cursor:pointer;}
    .card:hover{transform:translateY(-10px) scale(1.05);background:#ff004c;color:#fff;}

    /* Portfolio */
    .portfolio{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:25px;margin-top:40px;}
    .portfolio img{width:100%;border-radius:15px;box-shadow:0 5px 15px rgba(0,0,0,0.7);transition:.4s;}
    .portfolio img:hover{transform:scale(1.07);filter:brightness(1.2);}

    /* Contact */
    #contact a{color:#ff004c;text-decoration:none;}
    #contact a:hover{text-decoration:underline;}

    /* Footer */
    footer{background:#1c1c1c;color:#bbb;text-align:center;padding:20px;margin-top:50px;}

    /* Animations */
    @keyframes fadeIn{
      from{opacity:0;transform:translateY(20px);}
      to{opacity:1;transform:translateY(0);}
    }
    @keyframes fadeInDown{
      from{opacity:0;transform:translateY(-30px);}
      to{opacity:1;transform:translateY(0);}
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>🙋‍♂️ Ansh Singh</h1>
    <p><span class="typing">Thumbnail Editor | Graphic Designer | Video Editor | Poster Creator</span></p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About -->
  <section id="about" class="about">
    <img src="https://i.ibb.co/bm3ydRT/profile.jpg" alt="Profile">
    <div>
      <h2>About Me</h2>
      <p>
        Hi, I am <b>Ansh Singh</b>, a creative designer passionate about making 
        eye-catching thumbnails, stunning posters, smooth video edits, and unique graphic designs.  
        My goal is to help brands and creators shine through visuals.
      </p>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>💡 My Skills</h2>
    <div class="skills">
      <div class="card">🎨 Thumbnail Editing</div>
      <div class="card">🖌️ Graphic Designing</div>
      <div class="card">🎬 Video Editing</div>
      <div class="card">📰 Poster Creation</div>
    </div>
  </section>

  <!-- Portfolio -->
  <section id="portfolio">
    <h2>📂 My Works</h2>
    <div class="portfolio">
      <img src="https://i.ibb.co/CBwQKSh/thumb-sample.jpg" alt="Thumbnail Work">
      <img src="https://i.ibb.co/4K5kdkV/poster-sample.jpg" alt="Poster Work">
      <img src="https://i.ibb.co/PrC08hG/graphic-sample.jpg" alt="Graphic Work">
      <img src="https://i.ibb.co/dtzGQGH/video-sample.jpg" alt="Video Work">
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>📞 Contact Me</h2>
    <p>Email: <a href="mailto:anshdesigns@gmail.com">anshdesigns@gmail.com</a></p>
    <p>Instagram: <a href="#">@ansh_designs</a></p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Ansh Singh | All Rights Reserved</p>
  </footer>
</body>
</html>
