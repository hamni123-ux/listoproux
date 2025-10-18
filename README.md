<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>A. Hameed — Product Listing Specialist</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body { margin:0; font-family:Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; background:#031024; color:#e6f0ff }
    
    /* HERO */
    .hero { min-height:66vh; display:flex; align-items:center; justify-content:center; background-image: url('https://images.unsplash.com/photo-1505691723518-36a9b7d3c4c3?auto=format&fit=crop&w=1600&q=80'); background-size:cover; background-position:center; background-attachment:fixed; position:relative; }
    .hero::after { content:""; position:absolute; inset:0; background:rgba(2,6,23,0.65); backdrop-filter: blur(6px); }
    .overlay { position:relative; z-index:2; background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); padding:36px; border-radius:16px; box-shadow:0 20px 60px rgba(3,8,20,0.7); color:#dbeafe; max-width:1100px; width:92%; display:flex; gap:28px; align-items:center; }

    .left { flex:1 }
    .right { width:180px; flex:0 0 180px; display:flex; align-items:center; justify-content:center }
    .photo { width:160px; height:160px; border-radius:12px; object-fit:cover; border:3px solid rgba(255,255,255,0.06); box-shadow:0 12px 32px rgba(2,6,23,0.6); }

    h1 { font-size:28px; margin:0; color:#eaf5ff }
    .desc { color:#bcd6f8; margin-top:8px; max-width:760px; line-height:1.6 }

    /* Typing */
    .typewrap { display:inline-block; color:#cfe8ff; font-weight:700; font-size:18px }
    .cursor { display:inline-block; width:2px; height:1.18em; background:#60a5fa; margin-left:8px; vertical-align:middle; animation: blink 1s infinite }
    @keyframes blink { 0%,50% { opacity:1 } 50.1%,100% { opacity:0 } }

    /* sections */
    .section { max-width:1100px; margin:40px auto; padding:24px; border-radius:12px; }
    .about { background:#041c40; }
    .services { background:#052a60; }
    .portfolio { background:#0b3b80; }

    /* cards */
    .card { background: #062e54; border:1px solid rgba(255,255,255,0.03); padding:16px; border-radius:12px }

    /* fade animations */
    .fade-up { opacity:0; transform: translateY(18px); transition: all 540ms cubic-bezier(.2,.9,.3,1); }
    .fade-up.show { opacity:1; transform: translateY(0); }

    footer { background: linear-gradient(90deg,#031024,#041c40); text-align:center; color:#9fb0d9; padding:26px 12px; border-radius:12px; }

    @media (max-width:880px){ 
      .overlay{ flex-direction:column; align-items:center } 
      .right{ width:140px } 
      .photo{ width:120px; height:120px } 
    }
    @media (max-width:480px){
      .overlay { padding: 24px; gap:16px; }
      h1 { font-size:24px; }
      .desc { font-size:14px; }
    }
  </style>
</head>
<body>
  <!-- HERO -->
  <section class="hero">
    <div class="overlay">
      <div class="left">
        <h1>A. Hameed</h1>
        <div style="margin-top:10px;">
          <span class="typewrap" id="typed"></span><span class="cursor"></span>
        </div>
        <p class="desc">Experienced Product Uploading & Data Entry Specialist — I help global eCommerce stores manage listings, uploads, and inventory with accuracy and speed.</p>
        <div style="margin-top:16px; display:flex; gap:12px; align-items:center;">
          <a href="mailto:abdulhameedrahimoon46@outlook.com" style="background:#062e54; color:#dbeafe; padding:10px 16px; border-radius:999px; text-decoration:none; font-weight:600; border:1px solid rgba(255,255,255,0.04);">Email Me</a>
          <a href="https://wa.me/923458289378" target="_blank" style="background:#16a34a; color:white; padding:10px 16px; border-radius:999px; text-decoration:none; font-weight:700;">Chat on WhatsApp</a>
        </div>
      </div>

      <div class="right">
        <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxIQEhIQEBASEBAVFhcXFRcVFRUVFRUVFhUXFhUYFRUYHSggGBolHRUVITEhJSkrLi4uFx8zODMsNygtLisBCgoKDg0OFQ8PFSsdFR0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLf/AABEIAK4BIgMBIgACEQEDEQH/xAAcAAEAAgIDAQAAAAAAAAAAAAAABQYBAwQHCAL/xAA7EAACAQIEBAMGBQMFAQAAAAABAgADEQQSITEFBkFRYRMicYGRobHB0QcjQlJicuHxM1Ni8SNSY8L/xAAYAQADAQEAAAAAAAAAAAAAAAAAAQIDBP/EAB0RAAICAgMBAAAAAAAAAAAAAAABAhEDIRIiMWH/2gAMAwEAAhEDEQA/AJ2ioqKioqKioqKioqKioqKioqKioqKioqKioqKioqKiooqqqpKkq1lqEStKqQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQpQq//2Q==" alt="A. Hameed" class="photo" id="profilePic" />
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section class="section about">
    <div class="fade-up" id="about">
      <h2 style="color:#90caf9; font-size:20px; font-weight:700;">About Me</h2>
      <p style="color:#cfe8ff; margin-top:10px; line-height:1.6">Hi! I'm <strong>A. Hameed</strong>, a Product Uploading & Data Entry Specialist with over <strong>5 years</strong> of experience working with global eCommerce stores and local brands. I specialize in Shopify, WooCommerce, Amazon, and eBay listings, bulk CSV uploads, image editing for listings, and inventory management.</p>
    </div>
  </section>

  <!-- SERVICES -->
  <section class="section services">
    <div class="fade-up">
      <h3 style="color:#90caf9; font-weight:700;">Services</h3>
      <div style="display:grid; grid-template-columns: repeat(auto-fit,minmax(260px,1fr)); gap:12px; margin-top:12px;">
        <div class="card"><strong>Product Uploading</strong>
          <div style="color:#bcd6f8; font-size:13px; margin-top:6px;">
            Shopify, WooCommerce, Amazon, eBay — SEO titles, descriptions, images & variants.
          </div>
        </div>
        <div class="card"><strong>Data Entry</strong>
          <div style="color:#bcd6f8; font-size:13px; margin-top:6px;">
            Accurate CSV & Excel work, bulk uploads, and product attribute mapping.
          </div>
        </div>
        <div class="card"><strong>Inventory Updates</strong>
          <div style="color:#bcd6f8; font-size:13px; margin-top:6px;">
            Stock sync, threshold alerts, and daily/weekly reconciliation.
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PORTFOLIO HIGHLIGHTS -->
  <section class="section portfolio">
    <div class="fade-up">
      <h3 style="color:#90caf9; font-weight:700;">Portfolio Highlights</h3>
      <ul style="color:#cfe8ff; margin-top:10px; line-height:1.6;">
        <li>Managed product listings for UK-based fashion and electronics stores</li>
        <li>Uploaded and optimized 500+ products for Shopify and WooCommerce</li>
        <li>Maintained accurate inventory reports for multi-seller marketplaces</li>
      </ul>
    </div>
  </section>

  <footer>
    © 2025 A. Hameed — Product Uploading & Data Entry Specialist • abdulhameedrahimoon46@outlook.com • +92 345 8289378
  </footer>

  <script>
    // Typing animation (type once through phrases)
    const phrases = [
      'Product Listing Expert',
      'E-Commerce Specialist',
      'SEO Optimizer',
      'Digital Catalog Manager'
    ];
    const typedEl = document.getElementById('typed');
    let pIndex = 0, cIndex = 0;
    function typeOnceSimple() {
      if (pIndex >= phrases.length) return;
      const current = phrases[pIndex];
      typedEl.textContent = current.slice(0, cIndex + 1);
      cIndex++;
      if (cIndex < current.length) setTimeout(typeOnceSimple, 60);
      else { pIndex++; cIndex=0; setTimeout(typeOnceSimple, 300); }
    }

    document.addEventListener('DOMContentLoaded', ()=>{
      typeOnceSimple();
      const io = new IntersectionObserver((entries)=>{
        entries.forEach((en, i)=>{
          if(en.isIntersecting){ setTimeout(()=> en.target.classList.add('show'), i*150); }
        });
      }, {threshold:0.12});
      document.querySelectorAll('.fade-up').forEach(el=> io.observe(el));
    });
  </script>
</body>
</html>
