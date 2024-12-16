
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Profile of Neha Chaudhari - Software Engineer and Graduate Student at Clark University.">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha384-k6RqeWeci5ZR/Lv4MR0sA0FfDOMqeG1NhZrX5mGYJtx2W3apKUea7r9fZfbwFGW9" crossorigin="anonymous">
</head>
<body class="bg-gray-100 text-gray-800">
  <!-- Navbar -->
  <header class="bg-blue-600 text-white">
    <div class="container mx-auto flex justify-between items-center py-4 px-6">
      <h1 class="text-2xl font-bold">Neha Chaudhari</h1>
      <nav>
        <a href="#about" class="px-4 hover:text-gray-200">About</a>
        <a href="#skills" class="px-4 hover:text-gray-200">Skills</a>
        <a href="#projects" class="px-4 hover:text-gray-200">Projects</a>
        <a href="#contact" class="px-4 hover:text-gray-200">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-gray-200 py-20 text-center">
    <div class="container mx-auto">
      <h2 class="text-5xl font-bold text-blue-700">Hi, I'm Neha Chaudhari</h2>
      <p class="text-2xl mt-4 text-gray-800">Software Engineer | Backend Specialist | Tech Enthusiast</p>
      <a href="#contact" class="mt-8 inline-block bg-blue-700 text-white px-6 py-3 rounded hover:bg-blue-800">Get in Touch</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="bg-white py-12">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold text-gray-900 mb-4">About Me</h2>
      <p class="text-lg text-gray-700 leading-relaxed">
        I'm a software engineer with 5+ years of experience in backend development, API integration, and building scalable systems. Currently pursuing my Master's in Computer Science at Clark University, I specialize in turning ideas into impactful solutions.
      </p>
      <p class="text-lg text-gray-700 leading-relaxed mt-4">
        My journey is fueled by curiosity and a commitment to innovation. I thrive on challenges, whether optimizing system performance, creating efficient backend APIs, or contributing to user-focused solutions.
      </p>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="bg-gray-100 py-12">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold text-gray-900 mb-4">Technical Skills</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <div class="p-6 bg-white shadow rounded text-center">
          <h3 class="text-xl font-semibold text-blue-700">Programming Languages</h3>
          <p class="text-gray-700 mt-2">Ruby, Python, Java, JavaScript, C++, C</p>
        </div>
        <div class="p-6 bg-white shadow rounded text-center">
          <h3 class="text-xl font-semibold text-green-700">Frameworks & Technologies</h3>
          <p class="text-gray-700 mt-2">Ruby on Rails, React.js, Django, Flask</p>
        </div>
        <div class="p-6 bg-white shadow rounded text-center">
          <h3 class="text-xl font-semibold text-yellow-700">Databases</h3>
          <p class="text-gray-700 mt-2">PostgreSQL, MySQL, MongoDB</p>
        </div>
        <div class="p-6 bg-white shadow rounded text-center">
          <h3 class="text-xl font-semibold text-purple-700">Tools</h3>
          <p class="text-gray-700 mt-2">Git, Docker, Jenkins, REST APIs</p>
        </div>
        <div class="p-6 bg-white shadow rounded text-center">
          <h3 class="text-xl font-semibold text-red-700">Specializations</h3>
          <p class="text-gray-700 mt-2">Backend Development, API Design, System Optimization</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="bg-white py-12">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold text-gray-900 mb-4">Projects</h2>
      <div class="space-y-6">
        <div class="p-6 bg-gray-100 rounded shadow">
          <h3 class="text-xl font-semibold text-gray-800">E-commerce Indoor Plant</h3>
          <p class="text-gray-700 mt-2">
            Designed a robust e-commerce platform integrating payment system, ensuring seamless user experiences.
          </p>
          <a href="http://18.117.242.182/" target="_blank" class="text-blue-600 font-semibold underline">View Project</a>
        </div>
        <div class="p-6 bg-gray-100 rounded shadow">
          <h3 class="text-xl font-semibold text-gray-800">Weather Status API</h3>
          <p class="text-gray-700 mt-2">
            Built a Flask-based API to provide real-time weather updates, integrating third-party services for accurate data.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="bg-blue-600 text-white py-12">
    <div class="container mx-auto text-center">
      <h2 class="text-4xl font-bold mb-4">Contact Me</h2>
      <p class="text-lg">I'm open to new opportunities and collaborations.</p>
      <a href="mailto:nchaudhari@clarku.edu" class="mt-6 inline-block bg-white text-blue-600 px-6 py-3 rounded hover:bg-gray-100">
        Send an Email
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white py-6 text-center">
    <p></p>
  </footer>
</body>
</html>
