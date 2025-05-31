/*<!DOCTYPE html> */
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Project Manager Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/alpinejs" defer></script>
</head>
<body class="bg-gray-50 text-gray-900">

  <!-- Navbar -->
  <header class="bg-white shadow-md sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-xl font-bold">Abhishek Gupta PM</h1>
      <nav class="space-x-4">
        <a href="#about" class="hover:text-blue-600">About</a>
        <a href="#portfolio" class="hover:text-blue-600">Portfolio</a>
        <a href="#services" class="hover:text-blue-600">Services</a>
        <a href="#blog" class="hover:text-blue-600">Blog</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-blue-50 py-20">
    <div class="max-w-4xl mx-auto text-center px-4">
      <h2 class="text-4xl font-bold mb-4">Helping Teams Deliver Projects on Time & Within Budget</h2>
      <p class="text-lg text-gray-700 mb-6">Project Manager with 10+ years of experience across IT, construction, and SaaS.</p>
      <a href="#contact" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700 transition">Book a Free Consultation</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16 bg-white">
    <div class="max-w-4xl mx-auto px-4">
      <h3 class="text-3xl font-semibold mb-6">About Me</h3>
      <p class="mb-4">I’m a certified PMP® Project Manager with a decade of experience leading cross-functional teams, delivering projects worth over $10M. I specialize in Agile methodologies, risk mitigation, and stakeholder communication.</p>
      <ul class="list-disc pl-5 text-gray-700">
        <li>PMP®, Scrum Master Certified</li>
        <li>50+ projects completed successfully</li>
        <li>Experienced in Jira, MS Project, Asana</li>
      </ul>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="py-16 bg-gray-100">
    <div class="max-w-6xl mx-auto px-4">
      <h3 class="text-3xl font-semibold mb-10 text-center">Portfolio</h3>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-white p-5 rounded-lg shadow-md">
          <h4 class="text-xl font-semibold mb-2">SaaS CRM Rollout</h4>
          <p class="text-gray-700 text-sm">Managed a team of 10 to deploy a CRM system across a 200-person sales team.</p>
        </div>
        <div class="bg-white p-5 rounded-lg shadow-md">
          <h4 class="text-xl font-semibold mb-2">Construction Site PM</h4>
          <p class="text-gray-700 text-sm">Oversaw a $5M commercial construction project from planning to delivery.</p>
        </div>
        <div class="bg-white p-5 rounded-lg shadow-md">
          <h4 class="text-xl font-semibold mb-2">Agile Transformation</h4>
          <p class="text-gray-700 text-sm">Implemented Scrum practices at a fintech startup, increasing sprint velocity by 35%.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="py-16 bg-white">
    <div class="max-w-4xl mx-auto px-4">
      <h3 class="text-3xl font-semibold mb-6 text-center">Consulting Services</h3>
      <ul class="space-y-6">
        <li>
          <h4 class="text-xl font-bold">Project Management Consulting</h4>
          <p>From planning to execution — I help teams deliver successful projects.</p>
        </li>
        <li>
          <h4 class="text-xl font-bold">Agile Coaching</h4>
          <p>Scrum, Kanban, and Agile best practices tailored to your team.</p>
        </li>
        <li>
          <h4 class="text-xl font-bold">Startup PM Support</h4>
          <p>Fractional project management for scaling startups and entrepreneurs.</p>
        </li>
      </ul>
    </div>
  </section>

  <!-- Blog Section -->
  <section id="blog" class="py-16 bg-gray-100">
    <div class="max-w-5xl mx-auto px-4">
      <h3 class="text-3xl font-semibold mb-10 text-center">Latest Blog Posts</h3>
      <div class="space-y-6">
        <article class="bg-white p-6 rounded-lg shadow-md">
          <h4 class="text-xl font-bold mb-2">Top 5 Mistakes in Project Planning</h4>
          <p class="text-gray-700">Avoid these common traps and save your project from unnecessary delays and cost overruns...</p>
          <a href="#" class="text-blue-600 hover:underline mt-2 inline-block">Read more</a>
        </article>
        <article class="bg-white p-6 rounded-lg shadow-md">
          <h4 class="text-xl font-bold mb-2">Jira vs Asana: Which is Right for Your Team?</h4>
          <p class="text-gray-700">Choosing the right PM tool is crucial for team success. Here's a practical comparison...</p>
          <a href="#" class="text-blue-600 hover:underline mt-2 inline-block">Read more</a>
        </article>
      </div>
    </div>
  </section>

  <!-- Contact Section with Calendar -->
  <section id="contact" class="py-16 bg-blue-50">
    <div class="max-w-3xl mx-auto px-4">
      <h3 class="text-3xl font-semibold mb-6 text-center">Get in Touch</h3>
      <form class="space-y-4">
        <input type="text" placeholder="Name" class="w-full p-3 border rounded-lg" required />
        <input type="email" placeholder="Email" class="w-full p-3 border rounded-lg" required />
        <textarea placeholder="Message" rows="5" class="w-full p-3 border rounded-lg" required></textarea>
        <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700">Send Message</button>
      </form>
      <div class="mt-10 text-center">
        <h4 class="text-xl font-bold mb-2">Schedule a Meeting</h4>
        <iframe src="https://calendly.com/your-username/consultation" class="w-full h-96 border rounded-lg" frameborder="0"></iframe>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-white py-6 text-center text-sm text-gray-500">
    <p>&copy; 2025 ABhishek Gupta PM. All rights reserved.</p>
  </footer>

</body>
</html>
