<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dextera - Assistive Glove</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://unpkg.com/scrollreveal"></script>
  <style>
    html {
      scroll-behavior: smooth; /* Smooth scrolling */
    }
    .active-link {
      color: #2563eb; /* Electric blue for active section */
      font-weight: 600;
    }
  </style>
</head>
<body class="bg-gray-100 font-sans text-gray-800">

  <!-- Navbar -->
  <nav class="bg-gray-200 shadow-md fixed top-0 w-full z-50">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-gray-900">Dextera</h1>
      <div class="hidden md:flex space-x-6" id="nav-links">
        <a href="#about" class="text-gray-900 hover:text-blue-600">About</a>
        <a href="#features" class="text-gray-900 hover:text-blue-600">Features</a>
        <a href="#pricing" class="text-gray-900 hover:text-blue-600">Pricing</a>
        <a href="#upgrades" class="text-gray-900 hover:text-blue-600">Future Upgrades</a>
        <a href="#contact" class="text-gray-900 hover:text-blue-600">Contact</a>
      </div>
      <button id="mobile-menu-btn" class="md:hidden focus:outline-none">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
        </svg>
      </button>
    </div>

    <!-- Mobile Menu -->
    <div class="md:hidden hidden px-6 pb-4" id="mobile-menu">
      <a href="#about" class="block py-2 text-gray-900 hover:text-blue-600">About</a>
      <a href="#features" class="block py-2 text-gray-900 hover:text-blue-600">Features</a>
      <a href="#pricing" class="block py-2 text-gray-900 hover:text-blue-600">Pricing</a>
      <a href="#upgrades" class="block py-2 text-gray-900 hover:text-blue-600">Future Upgrades</a>
      <a href="#contact" class="block py-2 text-gray-900 hover:text-blue-600">Contact</a>
    </div>
  </nav>

  <!-- Hero -->
  <section class="bg-gray-100 text-gray-900 h-screen flex items-center pt-24" id="hero">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-5xl font-bold mb-6">Dextera: Stabilizing Hands, Empowering Lives</h2>
      <p class="text-lg mb-8">A revolutionary wearable glove designed to support individuals with tremors, autism, and motor difficulties. Dextera blends comfort, smart technology, and elegance into a single assistive device.</p>
      <a href="#pricing" class="bg-blue-600 text-white px-6 py-3 rounded-full font-semibold shadow hover:bg-blue-500">Get Dextera</a>
      <a href="#connect" class="ml-4 border border-blue-600 px-6 py-3 rounded-full font-semibold hover:bg-blue-600 hover:text-white">Connect Glove</a>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="py-20 container mx-auto px-6 pt-24">
    <h3 class="text-3xl font-bold text-center mb-10">About Dextera</h3>
    <p class="text-lg text-center max-w-3xl mx-auto">Dextera is not just a glove—it is an assistive companion crafted with care for people facing hand tremors, Parkinson’s, autism, or challenges in fine motor control. By combining lightweight materials, subtle design, and advanced stabilization technology, Dextera helps individuals regain confidence in daily tasks like writing, eating, or holding objects.</p>
  </section>

  <!-- Features -->
  <section id="features" class="bg-gray-200 py-20">
    <div class="container mx-auto px-6">
      <h3 class="text-3xl font-bold text-center mb-10">Key Features</h3>
      <div class="grid md:grid-cols-3 gap-10 text-center">
        <div class="p-6 bg-white rounded-xl shadow">
          <h4 class="text-xl font-semibold mb-2">Tremor Reduction</h4>
          <p class="text-gray-700">Using smart micro-motors and pressure feedback, Dextera provides stability for shaky hands, giving users the freedom to perform tasks smoothly.</p>
        </div>
        <div class="p-6 bg-white rounded-xl shadow">
          <h4 class="text-xl font-semibold mb-2">Smart Stabilization</h4>
          <p class="text-gray-700">Built-in gyroscope and accelerometer sensors constantly adjust movements, while haptic feedback reassures the wearer of improved precision.</p>
        </div>
        <div class="p-6 bg-white rounded-xl shadow">
          <h4 class="text-xl font-semibold mb-2">Seamless App Integration</h4>
          <p class="text-gray-700">Track progress, monitor hand stability, and personalize settings directly through the Dextera companion app, designed for ease and accessibility.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Pricing Plans -->
  <section id="pricing" class="py-20 container mx-auto px-6">
    <h3 class="text-3xl font-bold text-center mb-10">Pricing Plans</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-white shadow rounded-xl p-6 text-center">
        <h4 class="text-2xl font-semibold mb-2">Silver</h4>
        <p class="text-gray-700 mb-4">A reliable entry-level option offering basic tremor reduction for children, students, and families seeking affordability with functionality.</p>
        <p class="text-3xl font-bold mb-4">₹12,500 – ₹16,500</p>
        <a href="#contact" class="bg-blue-600 text-white px-6 py-2 rounded-full">Buy Now</a>
      </div>
      <div class="bg-white shadow-lg rounded-xl p-6 text-center border-2 border-blue-600">
        <h4 class="text-2xl font-semibold mb-2">Gold</h4>
        <p class="text-gray-700 mb-4">Balanced in cost and performance, the Gold model offers enhanced stabilization, rechargeability, and app tracking for regular users and therapy centers.</p>
        <p class="text-3xl font-bold mb-4">₹25,000 – ₹33,000</p>
        <a href="#contact" class="bg-blue-600 text-white px-6 py-2 rounded-full">Buy Now</a>
      </div>
      <div class="bg-white shadow rounded-xl p-6 text-center">
        <h4 class="text-2xl font-semibold mb-2">Platinum</h4>
        <p class="text-gray-700 mb-4">Designed for hospitals and research institutes, Platinum includes AI-driven adaptive control, customizable strength, wireless charging, and cloud-enabled therapist support.</p>
        <p class="text-3xl font-bold mb-4">₹50,000 – ₹66,000</p>
        <a href="#contact" class="bg-blue-600 text-white px-6 py-2 rounded-full">Buy Now</a>
      </div>
    </div>
  </section>

  <!-- Future Upgrades -->
  <section id="upgrades" class="bg-gray-200 py-20">
    <div class="container mx-auto px-6 text-center">
      <h3 class="text-3xl font-bold mb-10">Future Upgrades</h3>
      <div class="grid md:grid-cols-3 gap-10">
        <div class="bg-white p-6 rounded-xl shadow">
          <h4 class="text-xl font-semibold mb-2">Handwriting Coaching</h4>
          <p class="text-gray-700">Dextera will soon include an interactive module that guides handwriting practice, helping children and elderly improve their fine motor skills with confidence.</p>
        </div>
        <div class="bg-white p-6 rounded-xl shadow">
          <h4 class="text-xl font-semibold mb-2">Wireless Charging</h4>
          <p class="text-gray-700">Future models will support wireless charging docks, eliminating cable clutter and making daily use even more convenient.</p>
        </div>
        <div class="bg-white p-6 rounded-xl shadow">
          <h4 class="text-xl font-semibold mb-2">AI-Adaptive Training</h4>
          <p class="text-gray-700">By learning from the user’s movements, Dextera’s AI system will offer adaptive training for maximum stabilization tailored to each individual.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 container mx-auto px-6">
    <h3 class="text-3xl font-bold text-center mb-10">Contact Us</h3>
    <div class="max-w-2xl mx-auto">
      <form action="https://formspree.io/f/maykpebj" method="POST" class="bg-white shadow-md rounded-xl p-6">
        <label class="block mb-4">
          <span class="text-gray-700">Your Name</span>
          <input type="text" name="name" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm" required>
        </label>
        <label class="block mb-4">
          <span class="text-gray-700">Your Email</span>
          <input type="email" name="email" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm" required>
        </label>
        <label class="block mb-4">
          <span class="text-gray-700">Message</span>
          <textarea name="message" rows="4" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm" required></textarea>
        </label>
        <button type="submit" class="bg-blue-600 text-white px-6 py-2 rounded-full">Contact You</button>
      </form>
      <div class="text-center mt-6 text-gray-700">
        <p><strong>Phone:</strong> +91 9140603064</p>
        <p><strong>Email:</strong> aahankhandelwal12@gmail.com</p>
      </div>
    </div>
  </section>

  <footer class="bg-gray-900 text-white py-6 text-center">
    <p>&copy; 2025 Dextera. All rights reserved.</p>
  </footer>

  <script>
    // ScrollReveal animations
    ScrollReveal().reveal('section', { delay: 200, distance: '50px', origin: 'bottom', interval: 200 });

    // Mobile menu toggle
    const mobileBtn = document.getElementById('mobile-menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    mobileBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });

    // Active link highlighting
    const sections = document.querySelectorAll('section[id]');
    const navLinks = document.querySelectorAll('#nav-links a, #mobile-menu a');

    window.addEventListener('scroll', () => {
      let scrollY = window.pageYOffset;

      sections.forEach(section => {
        const sectionHeight = section.offsetHeight;
        const sectionTop = section.offsetTop - 80; // Adjust for navbar height
        const sectionId = section.getAttribute('id');

        if(scrollY >= sectionTop && scrollY < sectionTop + sectionHeight) {
          navLinks.forEach(link => {
            link.classList.remove('active-link');
            if(link.getAttribute('href') === '#' + sectionId) {
              link.classList.add('active-link');
            }
          });
        }
      });
    });
  </script>
</body>
</html>
