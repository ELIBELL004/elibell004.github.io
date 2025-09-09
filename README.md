<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elias's Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts for a clean, modern look -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-200">
<!-- Header & Navigation -->
    <header class="bg-gray-800 shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-3xl font-bold text-emerald-400">Elias</h1>
            <div class="flex space-x-6 text-lg">
                <a href="#about" class="text-gray-400 hover:text-emerald-400 transition duration-300">About</a>
                <a href="#skills" class="text-gray-400 hover:text-emerald-400 transition duration-300">Skills</a>
                <a href="#projects" class="text-gray-400 hover:text-emerald-400 transition duration-300">Projects</a>
                <a href="#contact" class="text-gray-400 hover:text-emerald-400 transition duration-300">Contact</a>
            </div>
        </nav>
    </header>

    <main class="container mx-auto px-6 py-12">

        <!-- About Section -->
        <section id="about" class="py-20 text-center">
            <div class="max-w-3xl mx-auto">
                <h2 class="text-5xl font-extrabold mb-4 text-emerald-400">Hello, I'm Elias</h2>
                <p class="text-xl leading-relaxed text-gray-400">
                    An IT major specializing in cybersecurity. My passion lies in understanding and securing digital landscapes, building robust systems, and proactively defending against threats. I am committed to continuous learning and applying my skills to solve complex problems in the ever-evolving world of technology.
                </p>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-20 bg-gray-800 rounded-xl shadow-lg mt-12 px-8">
            <h3 class="text-4xl font-bold text-center mb-10 text-emerald-400">My Expertise</h3>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Skill Card 1: Cybersecurity -->
                <div class="p-6 rounded-lg border border-gray-700 hover:border-emerald-400 transition duration-300">
                    <h4 class="text-2xl font-semibold mb-2">Cybersecurity</h4>
                    <p class="text-gray-400">
                        Proficient in network security, threat detection, and risk analysis. I have a strong foundation in protecting systems and data from unauthorized access and attacks.
                    </p>
                </div>
                <!-- Skill Card 2: IT Administration -->
                <div class="p-6 rounded-lg border border-gray-700 hover:border-emerald-400 transition duration-300">
                    <h4 class="text-2xl font-semibold mb-2">IT Administration</h4>
                    <p class="text-gray-400">
                        Experienced in system administration, hardware and software troubleshooting, and maintaining IT infrastructure to ensure smooth operations.
                    </p>
                </div>
                <!-- Skill Card 3: Programming -->
                <div class="p-6 rounded-lg border border-gray-700 hover:border-emerald-400 transition duration-300">
                    <h4 class="text-2xl font-semibold mb-2">Programming</h4>
                    <p class="text-gray-400">
                        Skilled in Python for scripting and automation, as well as C++ for building high-performance applications and system tools.
                    </p>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-20">
            <h3 class="text-4xl font-bold text-center mb-10 text-emerald-400">My Projects</h3>
            <div class="max-w-4xl mx-auto text-center">
                <p class="text-xl mb-6 text-gray-400">
                    You can find all of my work and projects on my GitHub profile. I regularly update it with new projects related to cybersecurity and IT.
                </p>
                <a href="https://github.com/ELIBELL004" target="_blank" rel="noopener noreferrer"
                   class="inline-block bg-emerald-400 text-gray-900 font-semibold py-3 px-8 rounded-full shadow-lg hover:bg-emerald-500 transition duration-300">
                    View My GitHub Profile
                </a>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 bg-gray-800 rounded-xl shadow-lg px-8 mt-12">
            <h3 class="text-4xl font-bold text-center mb-6 text-emerald-400">Get in Touch</h3>
            <p class="text-lg text-center text-gray-400 max-w-2xl mx-auto mb-8">
                I am always open to new opportunities and collaborations. Feel free to connect with me.
            </p>
            <div class="flex justify-center space-x-6">
                <!-- A placeholder email link. You can update this. -->
                <a href="mailto:elias@example.com" class="text-gray-400 hover:text-emerald-400 transition duration-300">
                    <svg class="w-10 h-10" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"></path><path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"></path>
                    </svg>
                </a>
                <!-- GitHub Icon Link -->
                <a href="https://github.com/ELIBELL004" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-emerald-400 transition duration-300">
                    <svg class="w-10 h-10" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" d="M10 0C4.477 0 0 4.484 0 10.017c0 4.414 2.865 8.163 6.843 9.488.5.09.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.372-1.34-3.372-1.34-.455-1.157-1.11-1.465-1.11-1.465-.908-.62.069-.608.069-.608 1.004.07 1.532 1.03 1.532 1.03.89 1.529 2.336 1.087 2.903.834.091-.648.349-1.087.633-1.336-2.227-.253-4.567-1.114-4.567-4.964 0-1.096.39-1.993 1.03-2.69a3.6 3.6 0 01.1-2.639s.84-.268 2.75 1.026c.799-.222 1.649-.333 2.5-.333s1.701.111 2.5.333c1.909-1.294 2.748-1.026 2.748-1.026.155.394.275.918.349 1.488.641.698 1.03 1.594 1.03 2.69 0 3.86-.54 4.707-4.577 4.956.35.303.676.91.676 1.841 0 1.336-.012 2.415-.012 2.741 0 .268.18.577.687.487C17.135 18.18 20 14.431 20 10.017c0-5.533-4.477-10.017-10-10.017z" clip-rule="evenodd"></path>
                    </svg>
                </a>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-500 text-center py-6 mt-12 text-sm">
        <p>&copy; 2023 Elias's Portfolio. All Rights Reserved.</p>
    </footer>

</body>
</html>

