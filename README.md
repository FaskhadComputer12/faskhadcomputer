<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FASKHAD COMPUTER TECHNOLOGY</title>
  <style>
    /* CSS styles (header, body, hero, section, footer, etc.) */
   * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f9fafb;
      color: #1f2937;
      line-height: 1.6;
    }
    header {
      background: white;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      padding: 1.5rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      color: #1d4ed8;
      font-size: 1.75rem;
      font-weight: 700;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #1f2937;
      font-weight: 500;
    }
    nav a:hover {
      color: #1d4ed8;
    }
    .hero {
      text-align: center;
      padding: 6rem 2rem;
      background: linear-gradient(to right, #1d4ed8, #2563eb);
      color: white;
    }
    .hero h2 {
      font-size: 3rem;
      font-weight: 700;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.25rem;
      margin-bottom: 2rem;
    }
    .btn-secondary {
      background: white;
      color: #1d4ed8;
      padding: 0.75rem 1.5rem;
      border: none;
      cursor: pointer;
      border-radius: 0.5rem;
      font-weight: 600;
      transition: background 0.3s ease;
    }
    .btn-secondary:hover {
      background: #e0e7ff;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1100px;
      margin: 0 auto;
      text-align: justify;
    }
    h3 {
      font-size: 2rem;
      font-weight: 600;
      margin-bottom: 2rem;
      text-align: center;
    }
    .card-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 2rem;
    }
    .card {
      background: white;
      padding: 1.5rem;
      border-radius: 0.75rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: justify;
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
      border-radius: 0.5rem;
      margin-bottom: 1rem;
    }
    footer {
      background: #0f172a;
      color: white;
      padding: 3rem 2rem;
      text-align: center;
      font-size: 0.9rem;
    }
    .footer-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 2rem;
      margin-bottom: 2rem;
    }
    .footer-grid h4 {
      margin-bottom: 0.75rem;
      font-size: 1.1rem;
    }
    .footer-grid a {
      display: block;
      color: white;
      text-decoration: none;
      margin: 0.4rem 0;
    }
    .footer-grid a:hover {
      text-decoration: underline;
    }
    #chatbot {
      position: fixed;
      bottom: 4rem;
      right: 1rem;
      width: 340px;
      background: #f3f4f6;
      border: 2px solid #1d4ed8;
      border-radius: 0.75rem;
      box-shadow: 0 0 20px rgba(0,0,0,0.2);
      overflow: hidden;
      display: none;
      font-size: 0.95rem;
      z-index: 10000;
    }
    #chatbot-toggle {
      position: fixed;
      bottom: 1rem;
      right: 1rem;
      background: #1d4ed8;
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 9999px;
      cursor: pointer;
      z-index: 9999;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    #chatbot-messages {
      padding: 1rem;
      height: 260px;
      overflow-y: auto;
      background: white;
      color: #111827;
    }
    #chatbot-input {
      display: flex;
      border-top: 1px solid #e5e7eb;
    }
    #chatbot-input input {
      flex: 1;
      padding: 0.75rem;
      border: none;
      border-top-left-radius: 0.75rem;
    }
    #chatbot-input button {
      padding: 0.75rem 1rem;
      background: #1d4ed8;
      color: white;
      border: none;
      border-top-right-radius: 0.75rem;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>FASKHAD COMPUTER TECHNOLOGY</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h2>Empowering Technology for a Better Tomorrow</h2>
    <p>Delivering reliable tech solutions with innovation and integrity.</p>
    <button class="btn-secondary"  onclick="alert('Let’s get started! Contact us @https://wa.me/message/I2UO3SVXSFNAG1 to learn more.')">Get Started</button>
  </section>

  <section id="about">
    <h3>About Us</h3>
    <p>FASKHAD is a dynamic and innovative technology-driven company committed to delivering reliable solutions in Computer Technology, Electronics, and IT Services. With a passion for excellence and a focus on customer satisfaction, we provide a wide range of services including Computer Repairs, Software Installation, Graphic Design, ID Card Printing, Web Design, IT Training, Cybersecurity, Networking, and Sales of Computers & Accessories.<br>

   We also offer trusted support for NIN & BVN registration services, ensuring fast, secure, and compliant processes for individuals and organizations.<br>

  At FASKHAD, we combine technical expertise with creative solutions to empower businesses, schools, and individuals with the tools they need to succeed in today’s digital world. Whether you're looking to build a strong online presence, secure your IT systems, or get reliable tech support — we’re here to help.<br>

 Your satisfaction is our priority. Your success is our mission.

</p>
  </section>

  <!-- Services and other sections continue here -->
 <section id="services">
    <h3>Our Services</h3>
    <div class="card-grid">
      <div class="card">
        <img src="Computer Repair.jpg" alt="Computer Repair">
        <h4>Computer Repair</h4>
        <p>We offer fast and reliable computer repair services for desktops, laptops, and other devices. Whether it’s hardware issues, system crashes, or slow performance, our skilled technicians will diagnose and fix the problem efficiently to get your system back in top shape.</p>
      </div>
      <div class="card">
        <img src="Software Installation.jpg" alt="Software Installation">
        <h4>Software Installation</h4>
        <p>Our experts handle the seamless installation and setup of all types of software, from operating systems and office applications to specialized programs. We ensure compatibility, proper licensing, and smooth operation for both personal and business needs.</p>
      </div>
      <div class="card">
        <img src="IT Training.jpg" alt="IT Training">
        <h4>IT Training</h4>
        <p>We provide hands-on IT training tailored for beginners, intermediate learners, and professionals. Our training covers essential computer skills, software applications, networking, and more — empowering individuals and teams to thrive in the digital age.</p>
      </div>
      <div class="card">
        <img src="Cybersecurity.jpg" alt="Cybersecurity">
        <h4>Cybersecurity</h4>
        <p>Protect your digital assets with our comprehensive cybersecurity solutions. We offer services such as antivirus setup, data protection, firewall configuration, and vulnerability assessments to safeguard your systems against threats and cyber attacks.</p>
      </div>
      <div class="card">
        <img src="Networking.jpg" alt="Networking">
        <h4>Networking</h4>
        <p>Our networking services include setup, configuration, and maintenance of wired and wireless networks. We ensure secure, stable, and high-speed connectivity for homes, offices, and institutions.</p>
      </div>
      <div class="card">
        <img src="Web Design.jpg" alt="Web Design">
        <h4>Web Design</h4>
        <p>We create modern, responsive, and user-friendly websites that reflect your brand and engage your audience. Whether it's a personal site, business page, or e-commerce platform, we deliver clean and professional web solutions.</p>
      </div>
      <div class="card">
        <img src="NIN & BVN Services.jpg" alt="NIN & BVN Services">
        <h4>NIN & BVN Services</h4>
        <p>Fast and reliable assistance with National Identification Number (NIN) registration, linking, updates, and Bank Verification Number (BVN) services to keep you compliant and connected.</p>
      </div>
      <div class="card">
        <img src="ID Card Printing.jpg" alt="ID Card Printing">
        <h4>Graphic Design & ID Card Printing</h4>
        <p>We offer creative graphic design services for logos, flyers, and branding materials, alongside professional ID card printing for schools, businesses, and events. Quality designs and prints that make a lasting impression.</p>
      </div>
      <div class="card">
        <img src="Sales of Computers & Accessories.jpg" alt="Software Installation">
        <h4>Sales of Computers & Accessories</h4>
        <p>Explore a wide selection of high-quality computers, laptops, and accessories at competitive prices. We provide trusted brands, expert guidance, and after-sales support to meet your personal, business, or educational technology needs.</p>
      </div>
    </div>
  </section>

  <footer>
    <div class="footer-grid" id="contact">
      <div>
        <h4>Contact Us</h4>
        <a href="mailto:faskhadcomputertechnology@gmail.com">Email: faskhadcomputertechnology@gmail.com</a>
        <a href="tel:09074113307">Phone: 09074113307</a>
        <a href="https://wa.me/message/I2UO3SVXSFNAG1">WhatsApp Chat</a>
      </div>
      <div>
        <h4>Social</h4>
        <a href="https://www.facebook.com/profile.php?id=61570420001736">Facebook</a>
        <a href="https://faskhad.wordpress.com">Blog</a>
      </div>
      <div>
        <h4>Location</h4>
        <a href="https://maps.app.goo.gl/knJUCSTWLHo75WZu9">View on Google Maps</a>
      </div>
    </div>
    <p>&copy; <span id="year"></span> FASKHAD COMPUTER TECHNOLOGY. All rights reserved.</p>
  </footer>
  <!-- CHATBOT SECTION (at bottom of file) -->
  <button id="chatbot-toggle" onclick="toggleChatbot()">Chat</button>
  <div id="chatbot">
    <div id="chatbot-messages">
      <p><strong>Bot:</strong> Hello! I’m here to help you learn about our services and how to contact us.</p>
    </div>
    <div id="chatbot-input">
      <input type="text" id="userInput" placeholder="Ask me anything..."/>
      <button onclick="sendMessage()">Send</button>
    </div>
  </div>
  <style>
    /* Chatbot styles */
  #chatbot {
      position: fixed;
      bottom: 4rem;
      right: 1rem;
      width: 340px;
      background: #f3f4f6;
      border: 2px solid #1d4ed8;
      border-radius: 0.75rem;
      box-shadow: 0 0 20px rgba(0,0,0,0.2);
      overflow: hidden;
      display: none;
      font-size: 0.95rem;
      z-index: 10000;
    }
    #chatbot-toggle {
      position: fixed;
      bottom: 1rem;
      right: 1rem;
      background: #1d4ed8;
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 9999px;
      cursor: pointer;
      z-index: 9999;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    #chatbot-messages {
      padding: 1rem;
      height: 260px;
      overflow-y: auto;
      background: white;
      color: #111827;
    }
    #chatbot-input {
      display: flex;
      border-top: 1px solid #e5e7eb;
    }
    #chatbot-input input {
      flex: 1;
      padding: 0.75rem;
      border: none;
      border-top-left-radius: 0.75rem;
    }
    #chatbot-input button {
      padding: 0.75rem 1rem;
      background: #1d4ed8;
      color: white;
      border: none;
      border-top-right-radius: 0.75rem;
      cursor: pointer;
    }
  </style>
  <script>
    // Chatbot toggle and response logic
   document.getElementById('year').textContent = new Date().getFullYear();

    function toggleChatbot() {
      const bot = document.getElementById('chatbot');
      bot.style.display = bot.style.display === 'none' ? 'block' : 'none';
    }

    function sendMessage() {
      const input = document.getElementById('userInput');
      const messages = document.getElementById('chatbot-messages');
      const userText = input.value.trim();
      if (!userText) return;

      messages.innerHTML += `<p><strong>You:</strong> ${userText}</p>`;
      input.value = '';

      let botReply = 'Sorry, I didn’t get that. For more information, please email us at faskhadcomputertechnology@gmail.com.';
      const text = userText.toLowerCase();

      if (text.includes('services')) {
        botReply = 'We offer computer repair, software installation, IT training, cybersecurity, networking, and web design.';
      } else if (text.includes('location')) {
        botReply = 'We are located here: https://maps.app.goo.gl/knJUCSTWLHo75WZu9';
      } else if (text.includes('contact') || text.includes('phone') || text.includes('email')) {
        botReply = 'You can contact us via email at faskhadcomputertechnology@gmail.com or call 09074113307.';
      } else if (text.includes('facebook')) {
        botReply = 'Here is our Facebook page: https://www.facebook.com/profile.php?id=61570420001736';
      } else if (text.includes('whatsapp')) {
        botReply = 'Reach us on WhatsApp: https://wa.me/message/I2UO3SVXSFNAG1';
      } else if (text.includes('blog')) {
        botReply = 'Check out our blog here: https://faskhad.wordpress.com';
      } else if (text.includes('hello')) {
        botReply = 'Hello, How Was your Day how can we assist you.';
      } else if (text.includes('Hi')){
        botReply = 'Hi, How can we assist you?';
      }

      messages.innerHTML += `<p><strong>Bot:</strong> ${botReply}</p>`;
      messages.scrollTop = messages.scrollHeight;
    }
  </script>
</body>
</html>
