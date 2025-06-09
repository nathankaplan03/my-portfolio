<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    // Dark mode toggle
    function toggleDarkMode() {
      document.documentElement.classList.toggle('dark');
    }
  </script>
</head>
<body class="bg-white text-gray-900 dark:bg-gray-900 dark:text-white font-sans">
  <!-- Navigation -->
  <header class="sticky top-0 bg-white dark:bg-gray-800 shadow z-10">
    <nav class="max-w-5xl mx-auto flex justify-between items-center p-4">
      <h1 class="text-xl font-bold">Nathan Kaplan</h1>
      <ul class="flex space-x-4 items-center">
        <li><a href="#home" class="hover:underline">Home</a></li>
        <li><a href="#about" class="hover:underline">About</a></li>
        <li><a href="#experience" class="hover:underline">Experience</a></li>
        <li><a href="#projects" class="hover:underline">Projects</a></li>
        <li><a href="#contact" class="hover:underline">Contact</a></li>
        <li><button onclick="toggleDarkMode()" class="bg-gray-200 dark:bg-gray-700 text-sm px-2 py-1 rounded">Toggle Dark</button></li>
      </ul>
    </nav>
  </header>

  <!-- Home -->
  <section id="home" class="relative min-h-screen flex items-center justify-center text-center bg-gradient-to-br from-blue-50 via-white to-blue-100 dark:from-gray-800 dark:via-gray-900 dark:to-gray-800 overflow-hidden">
    <!-- Abstract Background SVG -->
    <svg class="absolute left-0 top-0 w-full h-full opacity-10 dark:opacity-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 600" fill="none">
      <g transform="translate(200,200)">
        <path d="M120,-150C160,-120,180,-80,190,-40C200,0,200,40,180,80C160,120,120,160,80,170C40,180,0,160,-30,140C-60,120,-80,100,-100,80C-120,60,-140,40,-150,10C-160,-20,-160,-60,-140,-90C-120,-120,-80,-140,-40,-160C0,-180,60,-180,120,-150Z" fill="currentColor"/>
      </g>
    </svg>

    <div class="p-6 bg-white dark:bg-gray-800 rounded-xl shadow-lg transition-all duration-500 z-10">
      <h2 class="text-4xl font-semibold">Hi, I'm Nathan Kaplan</h2>
      <p class="mt-4 text-lg text-gray-600 dark:text-gray-300">Business Development and Strategy | Drexel Grad '26</p>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="max-w-3xl mx-auto p-8">
    <h2 class="text-2xl font-bold mb-4">About Me</h2>
    <div class="flex flex-col md:flex-row items-center gap-6">
      <img src="Headshot.jpg" alt="Nathan Kaplan Profile Photo" class="w-32 h-32 rounded-full object-cover">
      <div>
        <p class="text-gray-700 dark:text-gray-300 mb-4">I'm a Business Operations student at Drexel University's LeBow College of Business, pursuing concentrations in Operations & Supply Chain, Legal Studies, and International Business. With hands-on experience at companies like Aramark and Lockheed Martin, I specialize in driving efficiency in supply chains, data analysis, and cross-functional collaboration. I'm passionate about international business and strategy, and I'm always looking to expand my horizons, including through global programs like my upcoming study abroad in Rome.</p>
        <a href="Nathan Kaplan Resume 2024 New Format.pdf" download class="inline-block bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Download Resume</a>
      </div>
    </div>
  </section>

  <!-- Experience -->
  <section id="experience" class="bg-gray-50 dark:bg-gray-800 p-8">
    <div class="max-w-3xl mx-auto">
      <h2 class="text-2xl font-bold mb-8">Experience</h2>
      <div class="border-l-4 border-blue-600 dark:border-blue-400 ml-4">
        <div class="mb-8 ml-4">
          <h3 class="text-lg font-semibold">Analyst, Global Supply Chain Co-op - Aramark</h3>
          <p class="text-sm text-gray-600 dark:text-gray-400">April 2024 - August 2024</p>
          <p>Managed Sysco catalogs for over 6,000 accounts, directed product matching for rebate maximization, and supported culinary innovation efforts. Resolved catalog issues, enhancing ordering efficiency across client locations.</p>
        </div>
        <div class="mb-8 ml-4">
          <h3 class="text-lg font-semibold">Delivery Manager Co-op / Business Analyst - Lockheed Martin RMS</h3>
          <p class="text-sm text-gray-600 dark:text-gray-400">April 2023 - September 2023</p>
          <p>Oversaw 800+ active orders from 97 suppliers, resolved logistics issues, and delivered key reports to upper management daily. Supported production of defense and aerospace systems used by the US and allied nations.</p>
        </div>
        <div class="mb-8 ml-4">
          <h3 class="text-lg font-semibold">Accounting Intern - OWM Integrative Wellness</h3>
          <p class="text-sm text-gray-600 dark:text-gray-400">June 2022 – August 2022</p>
          <p>Tracked income, compiled financial data from QuickBooks, and helped develop digital filing systems for invoicing and expenses.</p>
        </div>
        <div class="ml-4">
          <h3 class="text-lg font-semibold">Co-Founder - It’s Nothin’ Mulch</h3>
          <p class="text-sm text-gray-600 dark:text-gray-400">May 2019 – September 2021</p>
          <p>Co-founded a local landscaping business, managed clients, pricing, branding, and operations while building strong customer and supplier relationships.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="p-8">
    <div class="max-w-5xl mx-auto">
      <h2 class="text-2xl font-bold mb-4">Projects</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <div class="border rounded-lg p-4 shadow hover:shadow-md">
          <h3 class="font-semibold">Mulch Business Analytics</h3>
          <p class="text-sm text-gray-600 dark:text-gray-300">Developed Excel tools to optimize labor-to-profit ratio and manage client relationships efficiently in a seasonal landscaping startup.</p>
        </div>
        <div class="border rounded-lg p-4 shadow hover:shadow-md">
          <h3 class="font-semibold">Supply Chain Optimization at Aramark</h3>
          <p class="text-sm text-gray-600 dark:text-gray-300">Contributed to system improvements and rebate tracking for multimillion-dollar supply chain activities.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="bg-gray-100 dark:bg-gray-900 p-8">
    <div class="max-w-3xl mx-auto text-center">
      <h2 class="text-2xl font-bold mb-4">Contact</h2>
      <p>Email me at <a href="mailto:nk694@drexel.edu" class="text-blue-600 underline">nk694@drexel.edu</a></p>
      <p class="mt-2">Or find me on <a href="https://www.linkedin.com/in/nathan-kaplan-765b35223" class="text-blue-600 underline">LinkedIn</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center p-4 text-sm text-gray-500 dark:text-gray-400">
    © 2025 Nathan Kaplan. All rights reserved.
  </footer>
</body>
</html>
