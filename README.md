<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dextera - Advanced Assistive Glove</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://unpkg.com/scrollreveal"></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
    .active-link {
      color: #2563eb;
      font-weight: 600;
    }
    /* Smooth hover shadow for cards */
    .card-hover:hover {
      transform: translateY(-5px);
      transition: 0.3s ease;
      box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1),
                  0 10px 10px -5px rgba(0, 0, 0, 0.04);
    }
  </style>
</head>
<body class="bg-gray-100 font-sans text-gray-800">

  <!-- Navbar -->
  <nav class="bg-gray-900 text-white fixed top-0 w-full z-50 shadow-lg">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-blue-500">Dextera</h1>
      <div class="hidden md:flex space-x-6" id="nav-links">
        <a href="#about" class="hover:text-blue-400">About</a>
        <a href="#features" class="hover:text-blue-400">Features</a>
        <a href="#pricing" class="hover:text-blue-400">Pricing</a>
        <a href="#upgrades" class="hover:text-blue-400">Future Upgrades</a>
        <a href="#contact" class="hover:text-blue-400">Contact</a>
      </div>
      <button id="mobile-menu-btn" class="md:hidden focus:outline-none">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
        </svg>
      </button>
    </div>
    <!-- Mobile Menu -->
    <div class="md:hidden hidden px-6 pb-4" id="mobile-menu">
      <a href="#about" class="block py-2 hover:text-blue-400">About</a>
      <a href="#features" class="block py-2 hover:text-blue-400">Features</a>
      <a href="#pricing" class="block py-2 hover:text-blue-400">Pricing</a>
      <a href="#upgrades" class="block py-2 hover:text-blue-400">Future Upgrades</a>
      <a href="#contact" class="block py-2 hover:text-blue-400">Contact</a>
    </div>
  </nav>

  <!-- Hero -->
  <section class="bg-gray-800 text-white h-screen flex items-center pt-28" id="hero">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-5xl md:text-6xl font-bold mb-6">Dextera: Stabilizing Hands, Empowering Lives</h2>
      <p class="text-lg md:text-xl mb-8 max-w-3xl mx-auto">Dextera is the next-generation wearable glove designed to provide advanced tremor stabilization, smart hand guidance, and real-time feedback. Whether for Parkinson’s patients, individuals with essential tremor, or users requiring precision hand control, Dextera transforms hand stability into seamless motion.</p>
      <div class="mt-6">
        <a href="#pricing" class="bg-blue-500 hover:bg-blue-400 text-white px-8 py-4 rounded-full font-semibold shadow-lg transition duration-300">Get Dextera</a>
        <a href="#connect" class="ml-4 border border-blue-500 hover:bg-blue-500 hover:text-white px-8 py-4 rounded-full font-semibold transition duration-300">Connect Glove</a>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="py-24 container mx-auto px-6 pt-28">
    <h3 class="text-4xl font-bold text-center mb-12 text-gray-900">About Dextera</h3>
    <p class="text-lg md:text-xl text-center max-w-4xl mx-auto text-gray-700 leading-relaxed">Dextera is not just a glove—it is a fully integrated assistive device that empowers individuals with hand tremors, motor control difficulties, or fine motor challenges. Using a combination of ultra-lightweight materials, ergonomic design, and intelligent stabilization algorithms, Dextera restores confidence and independence. From eating and writing to using tools or technology, every motion is enhanced with precision. Dextera also connects to a companion app to monitor performance, provide feedback, and adapt to your personal needs over time.</p>
  </section>

  <!-- Features -->
  <section id="features" class="bg-gray-100 py-24">
    <div class="container mx-auto px-6">
      <h3 class="text-4xl font-bold text-center mb-14 text-gray-900">Key Features</h3>
      <div class="grid md:grid-cols-3 gap-10 text-center">
        <div class="p-8 bg-white rounded-xl shadow card-hover">
          <h4 class="text-2xl font-semibold mb-4 text-gray-900">Advanced Tremor Reduction</h4>
          <p class="text-gray-700 leading-relaxed">Dextera uses precision micro-motors, haptic sensors, and gyroscopic stabilization to reduce hand tremors in real-time. Users experience smoother, controlled movements for daily tasks and professional activities alike.</p>
        </div>
        <div class="p-8 bg-white rounded-xl shadow card-hover">
          <h4 class="text-2xl font-semibold mb-4 text-gray-900">Smart Sensor Feedback</h4>
          <p class="text-gray-700 leading-relaxed">Integrated accelerometers and gyroscopes constantly monitor hand motion. Adaptive algorithms correct unintended movements, providing instant feedback through subtle haptic cues.</p>
        </div>
        <div class="p-8 bg-white rounded-xl shadow card-hover">
          <h4 class="text-2xl font-semibold mb-4 text-gray-900">Seamless App Integration</h4>
          <p class="text-gray-700 leading-relaxed">Track your progress, calibrate the glove, and personalize stabilization settings directly through the Dextera companion app. Data visualization and insights help optimize performance and therapy results.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Pricing Plans -->
  <section id="pricing" class="py-24 container mx-auto px-6">
    <h3 class="text-4xl font-bold text-center mb-14 text-gray-900">Pricing Plans</h3>
    <div class="grid md:grid-cols-3 gap-10">
      <div class="bg-white shadow-xl rounded-xl p-8 text-center card-hover">
        <h4 class="text-3xl font-bold mb-4 text-gray-900">Silver</h4>
        <p class="text-gray-700 mb-6">Entry-level stabilization for everyday use. Perfect for students, families, or casual users who need essential tremor support and hand control assistance.</p>
        <p class="text-3xl font-bold mb-6">₹12,500 – ₹16,500</p>
        <a href="#contact" class="bg-blue-500 hover:bg-blue-400 text-white px-8 py-3 rounded-full font-semibold transition duration-300">Buy Now</a>
      </div>
      <div class="bg-white shadow-2xl rounded-xl p-8 text-center card-hover border-2 border-blue-500">
        <h4 class="text-3xl font-bold mb-4 text-gray-900">Gold</h4>
        <p class="text-gray-700 mb-6">Balanced in cost and performance. Includes rechargeable battery, enhanced stabilization, and app tracking features for regular users or therapy centers.</p>
        <p class="text-3xl font-bold mb-6">₹25,000 – ₹33,000</p>
        <a href="#contact" class="bg-blue-500 hover:bg-blue-400 text-white px-8 py-3 rounded-full font-semibold transition duration-300">Buy Now</a>
      </div>
      <div class="bg-white shadow-xl rounded-xl p-8 text-center card-hover">
        <h4 class="text-3xl font-bold mb-4 text-gray-900">Platinum</h4>
        <p class="text-gray-700 mb-6">Premium model for hospitals and research labs. AI-driven adaptive control, cloud-enabled therapy support, wireless charging, and fully customizable hand stabilization.</p>
        <p class="text-3xl font-bold mb-6">₹50,000 – ₹66,000</p>
        <a href="#contact" class="bg-blue-500 hover:bg-blue-400 text-white px-8 py-3 rounded-full font-semibold transition duration-300">Buy Now</a>
      </div>
    </div>
  </section>

  <!-- Future Upgrades -->
  <section id="upgrades" class="bg-gray-100 py-24">
    <div class="container mx-auto px-6 text-center">
      <h3 class="text-4xl font-bold mb-14 text-gray-900">Future Upgrades</h3>
      <div class="grid md:grid-cols-3 gap-10">
        <div class="bg-white p-8 rounded-xl shadow card-hover">
          <h4 class="text-2xl font-semibold mb-4 text-gray-900">Handwriting & Fine Motor Training</h4>
          <p class="text-gray-700 leading-relaxed">Interactive modules will guide users to improve handwriting and fine motor precision through gamified exercises and real-time haptic feedback.</p>
        </div>
        <div class="bg-white p-8 rounded-xl shadow card-hover">
          <h4 class="text-2xl font-semibold mb-4 text-gray-900">Wireless Charging & Dock</h4>
          <p class="text-gray-700 leading-relaxed">Future Dextera models will support sleek wireless charging docks for effortless daily use and cleaner setups without cables.</p>
        </div>
        <div class="bg-white p-8 rounded-xl shadow card-hover">
          <h4 class="text-2xl font-semibold mb-4 text-gray-900">AI Adaptive Motion Training</h4>
          <p class="text-gray-700 leading-relaxed">AI-powered adaptive algorithms will learn each user’s motion patterns to provide maximum tremor suppression and personalized stabilization routines.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-24 container mx-auto px-6">
    <h3 class="text-4xl font-bold text-center mb-12 text-gray-900">Contact Us</h3>
    <div class="max-w-3xl mx-auto">
      <form action="https://formspree.io/f/maykpebj" method="POST" class="bg-white shadow-xl rounded-xl p-8">
        <label class="block mb-6">
          <span class="text-gray-700 font-semibold">Your Name</span>
          <input type="text" name="name" class="mt-2 block w-full border-gray-300 rounded-md shadow-sm p-3" required>
        </label>
        <label class="block mb-6">
          <span class="text-gray-700 font-semibold">Your Email</span>
          <input type="email" name="email" class="mt-2 block w-full border-gray-300 rounded-md shadow-sm p-3" required>
        </label>
        <label class="block mb-6">
          <span class="text-gray-700 font-semibold">Message</span>
          <textarea name="message" rows="5" class="mt-2 block w-full border-gray-300 rounded-md shadow-sm p-3" required></textarea>
        </label>
        <button type="submit" class="bg-blue-500 hover:bg-blue-400 text-white px-8 py-3 rounded-full font-semibold transition duration-300">Contact You</button>
      </form>
      <div class="text-center mt-8 text-gray-700">
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
        const sectionTop = section.offsetTop - 100;
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
