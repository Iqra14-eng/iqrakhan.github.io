<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Academic Portfolio</title>
    <!-- Tailwind CSS for modern styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-slate-50 text-slate-800 font-sans leading-relaxed">

    <!-- Header / Navigation -->
    <header class="bg-white border-b border-slate-200 sticky top-0 z-50">
        <div class="max-w-4xl mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-xl font-bold tracking-tight text-slate-900">Dr. Your Name</h1>
            <nav class="space-x-6 text-sm font-medium text-slate-600">
                <a href="#about" class="hover:text-blue-600 transition">About</a>
                <a href="#publications" class="hover:text-blue-600 transition">Publications</a>
                <a href="#teaching" class="hover:text-blue-600 transition">Teaching</a>
                <a href="#cv" class="hover:text-blue-600 transition">CV</a>
            </nav>
        </div>
    </header>

    <!-- Main Container -->
    <main class="max-w-4xl mx-auto px-6 py-12 space-y-16">

        <!-- About Section -->
        <section id="about" class="grid md:grid-cols-3 gap-8 items-center">
            <div class="md:col-span-1 flex justify-center">
                <!-- Replace with your photo URL or local image path -->
                <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=400&q=80" 
                     alt="Profile Photo" 
                     class="rounded-full w-48 h-48 object-cover shadow-md border-4 border-white">
            </div>
            <div class="md:col-span-2 space-y-4">
                <h2 class="text-3xl font-extrabold text-slate-900 tracking-tight">Your Full Name</h2>
                <p class="text-lg font-medium text-blue-600">Assistant Professor of Computer Science</p>
                <p class="text-slate-600">
                    I am a researcher focusing on Machine Learning, Artificial Intelligence, and Human-Computer Interaction at [University Name]. My work explores how algorithmic models can be made more interpretable and robust for real-world deployment.
                </p>
                <div class="flex space-x-4 pt-2 text-xl text-slate-600">
                    <a href="mailto:your.email@university.edu" title="Email" class="hover:text-blue-600"><i class="fas fa-envelope"></i></a>
                    <a href="https://scholar.google.com" target="_blank" title="Google Scholar" class="hover:text-blue-600"><i class="fas fa-graduation-cap"></i></a>
                    <a href="https://github.com" target="_blank" title="GitHub" class="hover:text-blue-600"><i class="fab fa-github"></i></a>
                    <a href="https://linkedin.com" target="_blank" title="LinkedIn" class="hover:text-blue-600"><i class="fab fa-linkedin"></i></a>
                    <a href="https://twitter.com" target="_blank" title="Twitter" class="hover:text-blue-600"><i class="fab fa-twitter"></i></a>
                </div>
            </div>
        </section>

        <!-- Publications Section -->
        <section id="publications" class="space-y-6">
            <h2 class="text-2xl font-bold text-slate-900 border-b pb-2">Selected Publications</h2>
            
            <div class="space-y-6">
                <!-- Publication Item 1 -->
                <div class="bg-white p-6 rounded-xl shadow-sm border border-slate-100 space-y-2">
                    <h3 class="text-lg font-semibold text-slate-900">
                        Title of Your First Research Paper Exploring Important Topics
                    </h3>
                    <p class="text-sm text-slate-600">
                        <strong>Your Name</strong>, Co-Author Name, Senior Author
                    </p>
                    <p class="text-sm italic text-slate-500">Conference on Neural Information Processing Systems (NeurIPS), 2025</p>
                    <div class="space-x-3 text-xs font-semibold pt-1">
                        <a href="#" class="text-blue-600 bg-blue-50 px-2.5 py-1 rounded hover:bg-blue-100">PDF</a>
                        <a href="#" class="text-slate-700 bg-slate-100 px-2.5 py-1 rounded hover:bg-slate-200">Code</a>
                        <a href="#" class="text-slate-700 bg-slate-100 px-2.5 py-1 rounded hover:bg-slate-200">BibTeX</a>
                    </div>
                </div>

                <!-- Publication Item 2 -->
                <div class="bg-white p-6 rounded-xl shadow-sm border border-slate-100 space-y-2">
                    <h3 class="text-lg font-semibold text-slate-900">
                        Another Exceptional Study on Scalable Machine Learning Architectures
                    </h3>
                    <p class="text-sm text-slate-600">
                        Co-Author Name, <strong>Your Name</strong>
                    </p>
                    <p class="text-sm italic text-slate-500">Journal of Artificial Intelligence Research (JAIR), 2024</p>
                    <div class="space-x-3 text-xs font-semibold pt-1">
                        <a href="#" class="text-blue-600 bg-blue-50 px-2.5 py-1 rounded hover:bg-blue-100">PDF</a>
                        <a href="#" class="text-slate-700 bg-slate-100 px-2.5 py-1 rounded hover:bg-slate-200">BibTeX</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Teaching Section -->
        <section id="teaching" class="space-y-4">
            <h2 class="text-2xl font-bold text-slate-900 border-b pb-2">Teaching Experience</h2>
            <ul class="list-disc list-inside space-y-2 text-slate-700">
                <li><strong>CS 101:</strong> Introduction to Computer Science (Fall 2025, Spring 2026)</li>
                <li><strong>CS 402:</strong> Advanced Machine Learning Seminar (Fall 2025)</li>
            </ul>
        </section>

        <!-- CV Section -->
        <section id="cv" class="space-y-4">
            <h2 class="text-2xl font-bold text-slate-900 border-b pb-2">Curriculum Vitae</h2>
            <p class="text-slate-600">
                You can download a full, comprehensive version of my academic CV below.
            </p>
            <div>
                <a href="#" class="inline-flex items-center space-x-2 bg-blue-600 text-white font-medium px-4 py-2 rounded-lg shadow hover:bg-blue-700 transition">
                    <i class="fas fa-file-pdf"></i>
                    <span>Download Full CV (PDF)</span>
                </a>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-white border-t border-slate-200 mt-20 py-8 text-center text-sm text-slate-500">
        <p>&copy; 2026 Your Name. Built with Tailwind CSS and GitHub Pages.</p>
    </footer>

</body>
</html>
