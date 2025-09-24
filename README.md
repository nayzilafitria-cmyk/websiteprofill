<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nayzila Fitria R</title>
  <style>
    * {margin:0; padding:0; box-sizing:border-box; font-family:"Poppins",sans-serif;}
    body {
      background:linear-gradient(135deg,#e0f2fe,#ffffff);
      color:#1e293b; line-height:1.6; overflow-x:hidden;
    }

    /* Background Partikel */
    #particles {
      position:fixed; top:0; left:0; width:100%; height:100%;
      z-index:-1; background:linear-gradient(135deg,#dbeafe,#ffffff);
    }

    /* Navbar */
    nav {
      position:fixed; top:0; left:0; width:100%;
      background:rgba(255,255,255,0.9); backdrop-filter:blur(10px);
      box-shadow:0 2px 8px rgba(0,0,0,0.05);
      display:flex; justify-content:space-between; align-items:center;
      padding:15px 10%; z-index:1000;
    }
    nav h1 {color:#3B82F6; font-size:1.5rem;}
    nav ul {list-style:none; display:flex; gap:20px;}
    nav ul li a {text-decoration:none; color:#1e293b; font-weight:500; transition:.3s;}
    nav ul li a:hover {color:#3B82F6;}

    /* Hero */
    header {
      height:100vh; display:flex; flex-direction:column; justify-content:center; align-items:center; text-align:center;
      padding:0 20px; padding-top:70px;
    }
    header img {
      width:170px; height:170px; border-radius:50%; border:5px solid #3B82F6;
      margin-bottom:20px; box-shadow:0 8px 25px rgba(59,130,246,0.4);
    }
    header h2 {font-size:2.3rem; color:#1e293b;}
    header p {font-size:1.3rem; color:#3B82F6; margin-top:10px; min-height:30px;}

    /* Section */
    section {padding:80px 10%; max-width:1200px; margin:auto;}
    section h2 {
      text-align:center; font-size:2rem; margin-bottom:40px; color:#3B82F6;
      position:relative;
    }
    section h2::after {
      content:""; width:60px; height:3px; background:#3B82F6;
      position:absolute; bottom:-10px; left:50%; transform:translateX(-50%);
      border-radius:3px;
    }
    .content {text-align:center; color:#334155;}

    /* Grid Card */
    .grid {
      display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:25px;
    }
    .card {
      background:rgba(255,255,255,0.9); backdrop-filter:blur(10px);
      padding:25px; border-radius:15px;
      box-shadow:0 6px 15px rgba(0,0,0,0.08);
      transition:.3s; text-align:center;
    }
    .card:hover {transform:translateY(-8px) scale(1.03); box-shadow:0 10px 25px rgba(0,0,0,0.15);}
    .card h3 {margin-bottom:10px; color:#3B82F6;}

    /* Skill Bars */
    .skill {margin:20px 0;}
    .skill-name {margin-bottom:5px; font-weight:600;}
    .bar {height:12px; background:#e2e8f0; border-radius:6px; overflow:hidden;}
    .bar-fill {
      height:100%; width:0; background:linear-gradient(90deg,#3B82F6,#60a5fa);
      border-radius:6px; transition:width 2s;
    }

    /* Footer */
    footer {
      text-align:center; padding:20px; background:#3B82F6; color:#fff;
      position:relative; overflow:hidden;
    }
    footer p {margin:0;}
    .marquee {
      margin-top:10px; white-space:nowrap; overflow:hidden;
    }
    .marquee span {
      display:inline-block; padding-left:100%; animation:marquee 12s linear infinite;
    }
    @keyframes marquee {100%{transform:translateX(-100%);}}

  </style>
</head>
<body>

<div id="particles"></div>

<!-- Navbar -->
<nav>
  <h1>Nayzila Fitria</h1>
  <ul>
    <li><a href="#tentang">Tentang Saya</a></li>
    <li><a href="#data">Data Diri</a></li>
    <li><a href="#skills">Kemampuan</a></li>
    <li><a href="#pendidikan">Pendidikan</a></li>
    <li><a href="#hobi">Hobi</a></li>
    <li><a href="#motivasi">Motivasi</a></li>
    <li><a href="#menarik">Hal Menarik</a></li>
    <li><a href="#cita">Cita-cita</a></li>
  </ul>
</nav>

<!-- Hero -->
<header>
  <img src="https://uploads.onecompiler.io/43w7hwn73/43wbrfzfz/WhatsApp%20Image%202025-09-11%20at%2003.40.25.jpeg" alt="Foto Profil">
  <h2>Halo, Saya Nayzila Fitria Ramadani</h2>
  <p id="typing"></p>
</header>

<!-- Tentang Saya -->
<section id="tentang">
  <h2>Tentang Saya</h2>
  <div class="card">
    <p>Saya seorang pelajar jurusan Rekayasa Perangkat Lunak yang penuh semangat untuk terus belajar dan mengembangkan keterampilan dalam dunia teknologi. Saya percaya bahwa setiap tantangan adalah peluang untuk tumbuh dan berkembang.</p>
  </div>
</section>

<!-- Data Diri -->
<section id="data">
  <h2>Data Diri</h2>
  <div class="card">
    <p><b>Nama:</b> Nayzila Fitria Ramadani</p>
    <p><b>Jurusan:</b> Rekayasa Perangkat Lunak</p>
    <p><b>Sekolah:</b> SMK Negeri 7 Batam</p>
    <p><b>Alamat:</b> Legenda</p>
    <p><b>Email:</b> nayzila@gmail.com</p>
  </div>
</section>

<!-- Skills -->
<section id="skills">
  <h2>Kemampuan</h2>
  <h3 style="text-align:center; color:#1e293b; margin-bottom:15px;">Kemampuan Dasar</h3>
  <div class="skill">
    <div class="skill-name"> Menejemen waktu</div>
    <div class="bar"><div class="bar-fill" data-fill="90%"></div></div>
  </div>
  <div class="skill">
    <div class="skill-name">Disiplin dan Bertanggung jawab</div>
    <div class="bar"><div class="bar-fill" data-fill="80%"></div></div>
  </div>
  <h3 style="text-align:center; color:#1e293b; margin:40px 0 15px;">Kemampuan Lanjutan</h3>
  <div class="skill">
    <div class="skill-name">Editing Video</div>
    <div class="bar"><div class="bar-fill" data-fill="75%"></div></div>
  </div>
  <div class="skill">
    <div class="skill-name">Desain Grafis ( Canva,Photpshop Dasar)</div>
    <div class="bar"><div class="bar-fill" data-fill="65%"></div></div>
    </div>
     <div class="skill-name">Public Speaking & Presentasi</div>
    <div class="bar"><div class="bar-fill" data-fill="65%"></div></div>
  </div>
</section>

<!-- Pendidikan -->
<section id="pendidikan">
  <h2>Pendidikan</h2>
  <div class="grid">
    <div class="card"><h3>SD</h3><p> SDIT Al-MUHAJIRIN - 
    Tahun      2016-2022</p></div>
    <div class="card"><h3>SMP</h3><p>SMP NEGREI 12 BATAM -
    Tahun 2022-2025</p></div>
    <div class="card"><h3>SMK</h3><p>SMK NEGERI 7 BATAM - 
    Tahun 2025-Sekarang</p></div>
  </div>
</section>

<!-- Hobi -->
<section id="hobi">
  <h2>Hobi & Minat</h2>
  <div class="grid">
    <div class="card"><h3>🎶 Musik</h3><p>Mendengarkan musik dan menonton film.</p></div>
    <div class="card"><h3>📚 Membaca</h3><p>gemar belajar hal baru.</p></div>
    <div class="card"><h3>🍰 Membuat Kue</h3><p>Kreatif dalam memasak.</p></div>
    <div class="card"><h3>🎥 Editing</h3><p>Mengedit video & konten kreatif.</p></div>
  </div>
</section>

<!-- Motivasi -->
<section id="motivasi">
  <h2>Kata-Kata Motivasi</h2>
  <div class="card">
    <p>"Setiap error adalah guru, jangan takut gagal, karena dari kegagalan lahir keberhasilan." 💡</p>
  </div>
</section>

<!-- Hal Menarik -->
<section id="menarik">
  <h2>Hal Menarik Tentang Saya</h2>
  <div class="card">
    <p>Saya senang mengeksplorasi hal-hal baru, cepat beradaptasi dengan lingkungan, dan selalu berusaha memberikan yang terbaik dalam setiap kesempatan. Saya juga punya jiwa kreatif yang mendorong saya untuk mencoba ide-ide unik dalam kehidupan sehari-hari.</p>
  </div>
</section>

<!-- Cita-cita -->
<section id="cita">
  <h2>Cita-Cita</h2>
  <div class="card">
    <p>Menjadi programmer profesional dan membuat karya teknologi bermanfaat untuk banyak orang 🌍.</p>
  </div>
</section>

<!-- Footer -->
<footer>
  <p>© 2025 Nayzila Fitria | Profil Siswa SMK</p>
  <div class="marquee"><span>Terus belajar, jangan menyerah, masa depan milik mereka yang berusaha! 🌟</span></div>
</footer>

<!-- Script -->
<script>
  // Typing efek
  const typingText = ["KONSENTRASI KEAHLIAN RPL","Web Developer Enthusiast","Siswa SMK Negeri 7 BATAM"];
  let index=0, charIndex=0;
  const typingElement=document.getElementById("typing");
  function type(){
    if(charIndex<typingText[index].length){
      typingElement.textContent+=typingText[index].charAt(charIndex);
      charIndex++; setTimeout(type,100);
    } else {setTimeout(erase,1500);}
  }
  function erase(){
    if(charIndex>0){
      typingElement.textContent=typingText[index].substring(0,charIndex-1);
      charIndex--; setTimeout(erase,50);
    } else {index=(index+1)%typingText.length; setTimeout(type,500);}
  }
  document.addEventListener("DOMContentLoaded",()=>{setTimeout(type,500);});

  // Skills animation
  const bars=document.querySelectorAll(".bar-fill");
  window.addEventListener("scroll",()=>{
    bars.forEach(bar=>{
      const top=bar.getBoundingClientRect().top;
      if(top<window.innerHeight-50){bar.style.width=bar.dataset.fill;}
    });
  });

  // Particles
  const canvas=document.createElement("canvas");
  document.getElementById("particles").appendChild(canvas);
  const ctx=canvas.getContext("2d");
  let w,h,particles=[];
  function init(){
    w=canvas.width=window.innerWidth;
    h=canvas.height=window.innerHeight;
    particles=[];
    for(let i=0;i<70;i++){
      particles.push({x:Math.random()*w,y:Math.random()*h,vx:(Math.random()-0.5)*1,vy:(Math.random()-0.5)*1,r:Math.random()*3+1});
    }
  }
  function draw(){
    ctx.clearRect(0,0,w,h);
    ctx.fillStyle="#3B82F6";
    particles.forEach(p=>{
      ctx.beginPath();
      ctx.arc(p.x,p.y,p.r,0,Math.PI*2);
      ctx.fill();
      p.x+=p.vx; p.y+=p.vy;
      if(p.x<0||p.x>w) p.vx*=-1;
      if(p.y<0||p.y>h) p.vy*=-1;
    });
    requestAnimationFrame(draw);
  }
  init(); draw();
  window.addEventListener("resize",init);
</script>

</body>
</html>
