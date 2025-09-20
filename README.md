<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dextera - Assistive Glove</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://unpkg.com/scrollreveal"></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
    .active-link {
      color: #4A90E2; /* muted blue for active link */
      font-weight: 600;
    }
    /* Hover animation for cards */
    .card-hover:hover {
      transform: translateY(-5px);
      transition: 0.3s ease;
      box-shadow: 0 15px 25px rgba(0,0,0,0.1);
    }
    body {
      background-color: #FFF8F0; /* main off-white/cream */
      color: #333;
    }
  </style>
</head>
<body class="font-sans">

  <!-- Navbar -->
  <nav class="bg-[#D9C4B0] fixed top-0 w-full z-50 shadow-md">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-[#B9987E]">Dextera</h1>
      <div class="hidden md:flex space-x-6" id="nav-links">
        <a href="#about" class="hover:text-[#4A90E2]">About</a>
        <a href="#features" class="hover:text-[#4A90E2]">Features</a>
        <a href="#pricing" class="hover:text-[#4A90E2]">Pricing</a>
        <a href="#upgrades" class="hover:text-[#4A90E2]">Future Upgrades</a>
        <a href="#contact" class="hover:text-[#4A90E2]">Contact</a>
      </div>
      <button id="mobile-menu-btn" class="md:hidden focus:outline-none">
        <svg class="w-6 h-6" fill="none" stroke="#B9987E" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
        </svg>
      </button>
    </div>
    <!-- Mobile Menu -->
    <div class="md:hidden hidden px-6 pb-4" id="mobile-menu">
      <a href="#about" class="block py-2 hover:text-[#4A90E2]">About</a>
      <a href="#features" class="block py-2 hover:text-[#4A90E2]">Features</a>
      <a href="#pricing" class="block py-2 hover:text-[#4A90E2]">Pricing</a>
      <a href="#upgrades" class="block py-2 hover:text-[#4A90E2]">Future Upgrades</a>
      <a href="#contact" class="block py-2 hover:text-[#4A90E2]">Contact</a>
    </div>
  </nav>

  <!-- Hero -->
  <section class="bg-[#FFF8F0] text-[#333] h-screen flex items-center pt-28" id="hero">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-5xl md:text-6xl font-bold mb-6">Dextera: Stabilizing Hands, Empowering Lives</h2>
      <p class="text-lg md:text-xl mb-8 max-w-3xl mx-auto">Dextera is a premium wearable glove that combines comfort, intelligent stabilization, and real-time feedback for individuals with tremors, autism, or motor difficulties. Crafted with precision, Dextera brings independence and confidence to daily activities.</p>
      <div class="mt-6">
        <a href="#pricing" class="bg-[#B9987E] hover:bg-[#A87A61] text-white px-8 py-4 rounded-full font-semibold shadow transition duration-300">Get Dextera</a>
        <a href="#connect" class="ml-4 border border-[#B9987E] hover:bg-[#B9987E] hover:text-white px-8 py-4 rounded-full font-semibold transition duration-300">Connect Glove</a>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="py-24 container mx-auto px-6 pt-28">
    <h3 class="text-4xl font-bold text-center mb-12 text-[#B9987E]">About Dextera</h3>
    <p class="text-lg md:text-xl text-center max-w-4xl mx-auto leading-relaxed">Dextera is designed to bring comfort, stability, and confidence to individuals with tremors or motor difficulties. Lightweight, ergonomic, and elegantly designed with a leather-inspired look, the glove enhances natural movement while providing precise tremor reduction. With a companion app, users can track progress, calibrate settings, and benefit from real-time adaptive stabilization.</p>
  </section>

  <!-- Features -->
  <section id="features" class="py-24">
    <div class="container mx-auto px-6">
      <h3 class="text-4xl font-bold text-center mb-14 text-[#B9987E]">Key Features</h3>
      <div class="grid md:grid-cols-3 gap-10 text-center">
        <div class="p-8 rounded-xl card-hover" style="background-color:#D9C4B0;">
          <h4 class="text-2xl font-semibold mb-4 text-[#333]">Advanced Tremor Reduction</h4>
          <p class="text-[#333] leading-relaxed">Micro-motors and gyroscopic stabilization minimize tremors in real-time, enhancing smoothness and precision for all hand tasks.</p>
        </div>
        <div class="p-8 rounded-xl card-hover" style="background-color:#D9C4B0;">
          <h4 class="text-2xl font-semibold mb-4 text-[#333]">Smart Sensor Feedback</h4>
          <p class="text-[#333] leading-relaxed">Integrated accelerometers detect movement and correct unintended motion with haptic feedback for immediate stability awareness.</p>
        </div>
        <div class="p-8 rounded-xl card-hover" style="background-color:#D9C4B0;">
          <h4 class="text-2xl font-semibold mb-4 text-[#333]">Seamless App Integration</h4>
          <p class="text-[#333] leading-relaxed">Personalize glove behavior, track progress, and view insights through the companion app for full adaptive control.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Pricing -->
  <section id="pricing" class="py-24 container mx-auto px-6">
    <h3 class="text-4xl font-bold text-center mb-14 text-[#B9987E]">Pricing Plans</h3>
    <div class="grid md:grid-cols-3 gap-10">
      <div class="p-8 rounded-xl card-hover" style="background-color:#D9C4B0;">
        <h4 class="text-3xl font-bold mb-4 text-[#333]">Silver</h4>
        <p class="text-[#333] mb-6 leading-relaxed">Essential tremor support for daily use, ideal for students or casual users seeking affordability and functionality.</p>
        <p class="text-3xl font-bold mb-6">₹12,500 – ₹16,500</p>
        <a href="#contact" class="bg-[#B9987E] hover:bg-[#A87A61] text-white px-8 py-3 rounded-full font-semibold transition duration-300">Buy Now</a>
      </div>
      <div class="p-8 rounded-xl card-hover border-2 border-[#B9987E]" style="background-color:#D9C4B0;">
        <h4 class="text-3xl font-bold mb-4 text-[#333]">Gold</h4>
        <p class="text-[#333] mb-6 leading-relaxed">Enhanced stabilization, rechargeable battery, and app tracking for regular users or therapy centers.</p>
        <p class="text-3xl font-bold mb-6">₹25,000 – ₹33,000</p>
        <a href="#contact" class="bg-[#B9987E] hover:bg-[#A87A61] text-white px-8 py-3 rounded-full font-semibold transition duration-300">Buy Now</a>
      </div>
      <div class="p-8 rounded-xl card-hover" style="background-color:#D9C4B0;">
        <h4 class="text-3xl font-bold mb-4 text-[#333]">Platinum</h4>
        <p class="text-[#333] mb-6 leading-relaxed">AI adaptive control, cloud-enabled therapy support, wireless charging, and fully customizable stabilization for research and hospitals.</p>
        <p class="text-3xl font-bold mb-6">₹50,000 – ₹66,000</p>
        <a href="#contact" class="bg-[#B9987E] hover:bg-[#A87A61] text-white px-8 py-3 rounded-full font-semibold transition duration-300">Buy Now</a>
      </div>
    </div>
  </section>

  <!-- Future Upgrades -->
  <section id="upgrades" class="py-24">
    <div class="container mx-auto px-6 text-center">
      <h3 class="text-4xl font-bold mb-14 text-[#B9987E]">Future Upgrades</h3>
      <div class="grid md:grid-cols-3 gap-10">
        <div class="p-8 rounded-xl card-hover" style="background-color:#D9C4B0;">
          <h4 class="text-2xl font-semibold mb-4 text-[#333]">Handwriting & Fine Motor Training</h4>
          <p class="text-[#333] leading-relaxed">Interactive exercises to improve precision and control with adaptive haptic guidance.</p>
        </div>
        <div class="p-8 rounded-xl card-hover" style="background-color:#D9C4B0;">
          <h4 class="text-2xl font-semibold mb-4 text-[#333]">Wireless Charging & Dock</h4>
          <p class="text-[#333] leading-relaxed">Convenient charging solutions designed for daily use without cable clutter.</p>
        </div>
        <div class="p-8 rounded-xl card-hover" style="background-color:#D9C4B0;">
          <h4 class="text-2xl font-semibold mb-4 text-[#333]">AI Adaptive Motion Training</h4>
          <p class="text-[#333] leading-relaxed">Personalized AI routines learn user movement patterns for maximum tremor suppression.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-24 container mx-auto px-6">
    <h3 class="text-4xl font-bold text-center mb-12 text-[#B9987E]">Contact Us</h3>
    <div class="max-w-3xl mx-auto">
      <form action="https://formspree.io/f/maykpebj" method="POST" class="p-8 rounded-xl card-hover" style="background-color:#D9C4B0;">
        <label class="block mb-6">
          <span class="font-semibold text-[#333]">Your Name</span>
          <input type="text" name="name" class="mt-2 block w-full rounded-md p-3 border-gray-300" required>
        </label>
        <label class="block mb-6">
          <span class="font-semibold text-[#333]">Your Email</span>
          <input type="email" name="email" class="mt-2 block w-full rounded-md p-3 border-gray-300" required>
        </label>
        <label class="block mb-6">
          <span class="font-semibold text-[#333]">Message</span>
          <textarea name="message" rows="5" class="mt-2 block w-full rounded-md p-3 border-gray-300" required></textarea>
        </label>
        <button type="submit" class="bg-[#B9987E] hover:bg-[#A87A61] text-white px-8 py-3 rounded-full font-semibold transition duration-300">Send Message</button>
      </form>
      <div class="text-center mt-8 text-[#333]">
        <p><strong>Phone:</strong> +91 9140603064</p>
        <p><strong>Email:</strong> aahankhandelwal12@gmail.com</p>
      </div>
    </div>
  </section>

  <footer class="bg-[#B9987E] text-white py-6 text-center">
    <p>&copy; 2025 Dextera. All rights reserved.</p>
  </footer>

  <script>
    // ScrollReveal animations
    ScrollReveal().reveal('section', { delay: 200, distance: '50px', origin: 'bottom', interval: 200 });

    // Mobile menu toggle
    const mobileBtn = document.getElementById('mobile-menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    mobileBtn.addEventListener('click', () => mobileMenu.classList.toggle('hidden'));

    // Active link highlighting
    const sections = document.querySelectorAll('section[id]');
    const navLinks = document.querySelectorAll('#nav-links a, #mobile-menu a');
    window.addEventListener('scroll', () => {
      let scrollY = window.pageYOffset;
      sections.forEach(section => {
        const sectionHeight = section.offsetHeight;
        const sectionTop = section.offsetTop - 100;
        const sectionId = section.getAttribute('id');
        if(scrollY >= sectionTop && scrollY < sectionTop + sectionHeight) {
          navLinks.forEach(link => {
            link.classList.remove('active-link');
            if(link.getAttribute('href') === '#' + sectionId) link.classList.add('active-link');
          });
        }
      });
    });
  </script>
</body>
</html>
