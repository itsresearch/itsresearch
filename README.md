<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Research Devkota - Full-Stack Developer</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
  <style>
    body {
      background: linear-gradient(135deg, #f7fafc 0%, #edf2f7 100%);
      color: #2d3748;
      font-family: 'Poppins', sans-serif;
      overflow-x: hidden;
    }
    .card {
      background: white;
      border-radius: 1rem;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
    }
    .icon {
      transition: transform 0.3s ease, filter 0.3s ease;
    }
    .icon:hover {
      transform: scale(1.3);
      filter: drop-shadow(0 0 8px rgba(0, 0, 0, 0.3));
    }
    .social-link {
      transition: color 0.3s ease, transform 0.3s ease;
    }
    .social-link:hover {
      color: #f56565;
      transform: translateY(-3px);
    }
    .section {
      opacity: 0;
      transform: translateY(50px);
    }
    .gradient-text {
      background: linear-gradient(90deg, #f56565, #ed8936);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
  </style>
</head>
<body class="min-h-screen flex flex-col items-center">
  <!-- Hero Section -->
  <header class="section w-full max-w-6xl mx-auto pt-16 pb-12 text-center">
    <div class="card p-8">
      <h1 class="text-5xl font-bold mb-4">
        Hey, I'm <span class="gradient-text">Research Devkota</span> 👋
      </h1>
      <h3 class="text-2xl text-gray-600">
        Full-Stack Developer from Nepal | Python | Django | React Enthusiast
      </h3>
    </div>
  </header>

  <!-- About Section -->
  <section class="section w-full max-w-6xl mx-auto py-12">
    <div class="card p-8">
      <h2 class="text-3xl font-semibold text-gray-800 mb-6 text-center">🔭 About Me</h2>
      <p class="text-lg text-gray-600 text-center max-w-3xl mx-auto">
        I'm passionate about crafting scalable, user-friendly web applications. With expertise in both frontend and backend development, I love turning creative ideas into seamless digital experiences. My current focus is on building robust solutions with Python Django and modern JavaScript frameworks like React and Vue.js.
      </p>
    </div>
  </section>

  <!-- Skills Section -->
  <section class="section w-full max-w-6xl mx-auto py-12">
    <div class="card p-8">
      <h2 class="text-3xl font-semibold text-gray-800 mb-8 text-center">🚀 Skills & Technologies</h2>
      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-6 justify-center">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" class="w-12 h-12 icon mx-auto" />
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-original.svg" alt="django" class="w-12 h-12 icon mx-auto" />
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" class="w-12 h-12 icon mx-auto" />
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" class="w-12 h-12 icon mx-auto" />
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" class="w-12 h-12 icon mx-auto" />
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain.svg" alt="bootstrap" class="w-12 h-12 icon mx-auto" />
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" class="w-12 h-12 icon mx-auto" />
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original.svg" alt="vuejs" class="w-12 h-12 icon mx-auto" />
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="sql" class="w-12 h-12 icon mx-auto" />
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" class="w-12 h-12 icon mx-auto" />
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="section w-full max-w-6xl mx-auto py-12">
    <div class="card p-8">
      <h2 class="text-3xl font-semibold text-gray-800 mb-8 text-center">📫 Let's Connect</h2>
      <p class="text-lg text-gray-600 text-center mb-6">
        I'm always excited to collaborate on projects, explore opportunities, or just chat about tech!
      </p>
      <div class="flex flex-wrap justify-center gap-6">
        <a href="mailto:researchofficial55@gmail.com" class="text-lg text-gray-600 social-link">Email: researchofficial55@gmail.com</a>
        <a href="https://linkedin.com/in/research-devkota" class="text-lg text-gray-600 social-link">LinkedIn: research-devkota</a>
        <a href="https://fb.com/research.devkota" class="text-lg text-gray-600 social-link">Facebook: research.devkota</a>
        <a href="https://instagram.com/re._.search1" class="text-lg text-gray-600 social-link">Instagram: re._.search1</a>
      </div>
    </div>
  </section>

  <!-- GitHub Stats Section -->
  <section class="section w-full max-w-6xl mx-auto py-12">
    <div class="card p-8">
      <h2 class="text-3xl font-semibold text-gray-800 mb-8 text-center">📈 GitHub Stats</h2>
      <div class="flex flex-col md:flex-row justify-center gap-6">
        <img src="https://github-readme-stats.vercel.app/api?username=itsresearch&show_icons=true&hide_border=true&theme=light" alt="GitHub Stats" class="w-full max-w-md" />
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=itsresearch&layout=compact&hide_border=true&theme=light" alt="Top Languages" class="w-full max-w-md" />
      </div>
    </div>
  </section>

  <!-- Footer Quote -->
  <footer class="section w-full max-w-6xl mx-auto py-12 text-center">
    <div class="card p-6">
      <h4 class="text-xl text-gray-600 italic">
        "Consistency and passion fuel success in software development."
      </h4>
    </div>
  </footer>

  <!-- GSAP Animations -->
  <script>
    gsap.utils.toArray(".section").forEach((section, i) => {
      gsap.fromTo(
        section,
        { opacity: 0, y: 50 },
        {
          opacity: 1,
          y: 0,
          duration: 1.2,
          ease: "power3.out",
          scrollTrigger: {
            trigger: section,
            start: "top 85%",
            toggleActions: "play none none none",
          },
        }
      );
    });

    gsap.utils.toArray(".card").forEach((card, i) => {
      gsap.fromTo(
        card,
        { scale: 0.95, opacity: 0 },
        {
          scale: 1,
          opacity: 1,
          duration: 0.8,
          delay: i * 0.2,
          ease: "back.out(1.7)",
          scrollTrigger: {
            trigger: card,
            start: "top 90%",
          },
        }
      );
    });
  </script>
</body>
</html>
