# Fakhru
haii
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fakhru | Professional Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Custom CSS for animations and effects */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .fade-in {
            animation: fadeIn 1s ease forwards;
        }
        
        .delay-1 { animation-delay: 0.2s; }
        .delay-2 { animation-delay: 0.4s; }
        .delay-3 { animation-delay: 0.6s; }
        .delay-4 { animation-delay: 0.8s; }
        
        .gradient-text {
            background: linear-gradient(90deg, #cf63b4ec, #8b5cf6);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(121, 17, 17, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        
        #particles-js {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            z-index: 0;
        }
        
        .content-wrapper {
            position: relative;
            z-index: 1;
        }
    </style>
</head>
<body class="bg-gray-50 font-sans antialiased">
    <!-- Navigation -->
    <nav class="fixed w-full bg-white shadow-sm z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <a href="#" class="text-xl font-bold gradient-text">Fakhru</a>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="text-gray-700 hover:text-blue-600 transition">Home</a>
                    <a href="#about" class="text-gray-700 hover:text-blue-600 transition">About</a>
                    <a href="#skills" class="text-gray-700 hover:text-blue-600 transition">Skills</a>
                    <a href="#projects" class="text-gray-700 hover:text-blue-600 transition">Projects</a>
                    <a href="#experience" class="text-gray-700 hover:text-blue-600 transition">Experience</a>
                    <a href="#contact" class="text-gray-700 hover:text-blue-600 transition">Contact</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="menu-toggle" class="text-gray-700 focus:outline-none">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#home" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Home</a>
                <a href="#about" class="block px-3 py-2 text-gray-700 hover:text-blue-600">About</a>
                <a href="#skills" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Skills</a>
                <a href="#projects" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Projects</a>
                <a href="#experience" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Experience</a>
                <a href="#contact" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative min-h-screen flex items-center justify-center bg-gradient-to-br from-blue-50 to-purple-50 overflow-hidden">
        <div id="particles-js"></div>
        <div class="content-wrapper max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-24">
            <div class="text-center md:text-left grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-6">
                    <h1 class="text-4xl md:text-6xl font-bold text-gray-900 fade-in">
                        Hi, I'm <span class="gradient-text">Fakhru</span>
                    </h1>
                    <h2 class="text-2xl md:text-3xl font-semibold text-gray-700 fade-in delay-1">
                        <span class="typewriter" data-words='["Web Developer", "UI/UX Designer", "Full Stack Engineer", "Tech Enthusiast"]'></span>
                    </h2>
                    <p class="text-lg text-gray-600 max-w-lg fade-in delay-2">
                        I build exceptional digital experiences that are fast, accessible, visually appealing, and responsive.
                    </p>
                    <div class="flex flex-wrap gap-4 justify-center md:justify-start fade-in delay-3">
                        <a href="#contact" class="px-6 py-3 bg-gradient-to-r from-blue-500 to-purple-600 text-white rounded-lg shadow-md hover:shadow-lg transition duration-300">
                            Contact Me
                        </a>
                        <a href="#projects" class="px-6 py-3 border border-gray-300 text-gray-700 rounded-lg hover:bg-gray-100 transition duration-300">
                            View Work
                        </a>
                    </div>
                    <div class="flex justify-center md:justify-start space-x-4 pt-4 fade-in delay-4">
                        <a href="#" class="text-gray-700 hover:text-blue-600 transition">
                            <i class="fab fa-github text-2xl"></i>
                        </a>
                        <a href="#" class="text-gray-700 hover:text-blue-600 transition">
                            <i class="fab fa-linkedin text-2xl"></i>
                        </a>
                        <a href="#" class="text-gray-700 hover:text-blue-600 transition">
                            <i class="fab fa-twitter text-2xl"></i>
                        </a>
                        <a href="#" class="text-gray-700 hover:text-blue-600 transition">
                            <i class="fab fa-instagram text-2xl"></i>
                        </a>
                    </div>
                </div>
                <div class="relative fade-in delay-2">
                    <div class="relative mx-https://phttps://pomf2.lain.la/f/20xabv8z.jpegomf2.lain.la/f/20xabv8z.jpegauto w-64 h-64 md:w-80 md:h-80 rounded-full overflow-hidden border-4 border-white shadow-xl">
                        <img src=

                             alt="Fakhru" class="w-full h-full object-cover">
                    </div>
                    <div class="absolute -bottom-4 -right-4 bg-white p-4 rounded-lg shadow-md">
                        <div class="flex items-center space-x-2">
                            <div class="w-3 h-3 bg-green-500 rounded-full"></div>
                            <span class="text-sm font-medium">Available for work</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">About <span class="gradient-text">Me</span></h2>
                <div class="w-20 h-1 bg-gradient-to-r from-blue-500 to-purple-600 mx-auto"></div>
            </div>
            
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-6">
                    <h3 class="text-2xl font-semibold text-gray-800">Who am I?</h3>
                    <p class="text-gray-600 leading-relaxed">
                        I'm Fakhru, a passionate web developer and UI/UX designer with over 5 years of experience creating digital products that people love. I specialize in building responsive, user-friendly websites and applications with clean, efficient code.
                    </p>
                    <p class="text-gray-600 leading-relaxed">
                        My approach combines technical expertise with an eye for design, ensuring that every project I work on is not only functional but also visually stunning and intuitive to use.
                    </p>
                    <div class="grid grid-cols-2 gap-4 pt-4">
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-user text-blue-500"></i>
                            <span class="text-gray-700">Fakhru</span>
                        </div>
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-envelope text-blue-500"></i>
                            <span class="text-gray-700">fakhru@example.com</span>
                        </div>
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-phone text-blue-500"></i>
                            <span class="text-gray-700">+123 456 7890</span>
                        </div>
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-map-marker-alt text-blue-500"></i>
                            <span class="text-gray-700">Jakarta, Indonesia</span>
                        </div>
                    </div>
                    <div class="pt-4">
                        <a href="#" class="inline-flex items-center px-6 py-3 bg-gradient-to-r from-blue-500 to-purple-600 text-white rounded-lg shadow-md hover:shadow-lg transition duration-300">
                            Download CV <i class="fas fa-download ml-2"></i>
                        </a>
                    </div>
                </div>
                <div class="grid grid-cols-2 gap-4">
                    <div class="bg-gray-50 p-6 rounded-xl border border-gray-200 card-hover">
                        <div class="text-blue-500 text-4xl mb-4">
                            <i class="fas fa-code"></i>
                        </div>
                        <h4 class="font-semibold text-gray-800 mb-2">Web Development</h4>
                        <p class="text-gray-600 text-sm">Building responsive, performant websites with modern technologies.</p>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-xl border border-gray-200 card-hover">
                        <div class="text-purple-500 text-4xl mb-4">
                            <i class="fas fa-paint-brush"></i>
                        </div>
                        <h4 class="font-semibold text-gray-800 mb-2">UI/UX Design</h4>
                        <p class="text-gray-600 text-sm">Creating intuitive interfaces with exceptional user experience.</p>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-xl border border-gray-200 card-hover">
                        <div class="text-green-500 text-4xl mb-4">
                            <i class="fas fa-mobile-alt"></i>
                        </div>
                        <h4 class="font-semibold text-gray-800 mb-2">Mobile Responsive</h4>
                        <p class="text-gray-600 text-sm">Ensuring your site looks great on all devices.</p>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-xl border border-gray-200 card-hover">
                        <div class="text-yellow-500 text-4xl mb-4">
                            <i class="fas fa-rocket"></i>
                        </div>
                        <h4 class="font-semibold text-gray-800 mb-2">SEO Optimization</h4>
                        <p class="text-gray-600 text-sm">Improving visibility and search engine rankings.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">My <span class="gradient-text">Skills</span></h2>
                <div class="w-20 h-1 bg-gradient-to-r from-blue-500 to-purple-600 mx-auto"></div>
            </div>
            
            <div class="grid md:grid-cols-2 gap-12">
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-6">Coding Skills</h3>
                    <div class="space-y-6">
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium text-gray-700">HTML/CSS</span>
                                <span class="text-gray-500">95%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-blue-600 h-2.5 rounded-full" style="width: 95%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium text-gray-700">JavaScript</span>
                                <span class="text-gray-500">90%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-blue-600 h-2.5 rounded-full" style="width: 90%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium text-gray-700">React</span>
                                <span class="text-gray-500">85%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-blue-600 h-2.5 rounded-full" style="width: 85%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium text-gray-700">Node.js</span>
                                <span class="text-gray-500">80%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-blue-600 h-2.5 rounded-full" style="width: 80%"></div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-6">Design Skills</h3>
                    <div class="space-y-6">
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium text-gray-700">UI/UX Design</span>
                                <span class="text-gray-500">90%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-purple-600 h-2.5 rounded-full" style="width: 90%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium text-gray-700">Figma</span>
                                <span class="text-gray-500">85%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-purple-600 h-2.5 rounded-full" style="width: 85%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium text-gray-700">Adobe XD</span>
                                <span class="text-gray-500">80%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-purple-600 h-2.5 rounded-full" style="width: 80%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="font-medium text-gray-700">Photoshop</span>
                                <span class="text-gray-500">75%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-purple-600 h-2.5 rounded-full" style="width: 75%"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="mt-16">
                <h3 class="text-xl font-semibold text-gray-800 mb-6 text-center">Tools & Technologies</h3>
                <div class="flex flex-wrap justify-center gap-6">
                    <div class="flex flex-col items-center p-4 bg-white rounded-lg shadow-sm hover:shadow-md transition duration-300 card-hover">
                        <i class="fab fa-html5 text-4xl text-orange-500 mb-2"></i>
                        <span class="text-gray-700">HTML5</span>
                    </div>
                    <div class="flex flex-col items-center p-4 bg-white rounded-lg shadow-sm hover:shadow-md transition duration-300 card-hover">
                        <i class="fab fa-css3-alt text-4xl text-blue-500 mb-2"></i>
                        <span class="text-gray-700">CSS3</span>
                    </div>
                    <div class="flex flex-col items-center p-4 bg-white rounded-lg shadow-sm hover:shadow-md transition duration-300 card-hover">
                        <i class="fab fa-js text-4xl text-yellow-500 mb-2"></i>
                        <span class="text-gray-700">JavaScript</span>
                    </div>
                    <div class="flex flex-col items-center p-4 bg-white rounded-lg shadow-sm hover:shadow-md transition duration-300 card-hover">
                        <i class="fab fa-react text-4xl text-blue-400 mb-2"></i>
                        <span class="text-gray-700">React</span>
                    </div>
                    <div class="flex flex-col items-center p-4 bg-white rounded-lg shadow-sm hover:shadow-md transition duration-300 card-hover">
                        <i class="fab fa-node-js text-4xl text-green-500 mb-2"></i>
                        <span class="text-gray-700">Node.js</span>
                    </div>
                    <div class="flex flex-col items-center p-4 bg-white rounded-lg shadow-sm hover:shadow-md transition duration-300 card-hover">
                        <i class="fab fa-git-alt text-4xl text-orange-600 mb-2"></i>
                        <span class="text-gray-700">Git</span>
                    </div>
                    <div class="flex flex-col items-center p-4 bg-white rounded-lg shadow-sm hover:shadow-md transition duration-300 card-hover">
                        <i class="fab fa-figma text-4xl text-purple-500 mb-2"></i>
                        <span class="text-gray-700">Figma</span>
                    </div>
                    <div class="flex flex-col items-center p-4 bg-white rounded-lg shadow-sm hover:shadow-md transition duration-300 card-hover">
                        <i class="fas fa-database text-4xl text-blue-600 mb-2"></i>
                        <span class="text-gray-700">MongoDB</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">My <span class="gradient-text">Projects</span></h2>
                <div class="w-20 h-1 bg-gradient-to-r from-blue-500 to-purple-600 mx-auto"></div>
                <p class="mt-4 text-gray-600 max-w-2xl mx-auto">Here are some of my recent projects that showcase my skills and expertise.</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-xl transition duration-300 card-hover">
                    <div class="h-48 overflow-hidden">
                        <img src=
                        
                             alt="Project 1" class="w-full h-full object-cover transition duration-500 hover:scale-105">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-semibold text-gray-800">E-commerce Platform</h3>
                            <div class="flex space-x-2">
                                <a href="#" class="text-blue-500 hover:text-blue-700">
                                    <i class="fas fa-external-link-alt"></i>
                                </a>
                                <a href="#" class="text-gray-500 hover:text-gray-700">
                                    <i class="fab fa-github"></i>
                                </a>
                            </div>
                        </div>
                        <p class="text-gray-600 mb-4">A full-featured e-commerce platform with product listings, cart functionality, and secure checkout.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 text-xs rounded-full">React</span>
                            <span class="px-3 py-1 bg-purple-100 text-purple-800 text-xs rounded-full">Node.js</span>
                            <span class="px-3 py-1 bg-green-100 text-green-800 text-xs rounded-full">MongoDB</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 2 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-xl transition duration-300 card-hover">
                    <div class="h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1467232004584-a241de8bcf5d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1469&q=80" 
                             alt="Project 2" class="w-full h-full object-cover transition duration-500 hover:scale-105">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-semibold text-gray-800">Task Management App</h3>
                            <div class="flex space-x-2">
                                <a href="#" class="text-blue-500 hover:text-blue-700">
                                    <i class="fas fa-external-link-alt"></i>
                                </a>
                                <a href="#" class="text-gray-500 hover:text-gray-700">
                                    <i class="fab fa-github"></i>
                                </a>
                            </div>
                        </div>
                        <p class="text-gray-600 mb-4">A productivity app for managing tasks with drag-and-drop functionality and team collaboration features.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 text-xs rounded-full">Vue.js</span>
                            <span class="px-3 py-1 bg-purple-100 text-purple-800 text-xs rounded-full">Firebase</span>
                            <span class="px-3 py-1 bg-yellow-100 text-yellow-800 text-xs rounded-full">Tailwind CSS</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 3 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-xl transition duration-300 card-hover">
                    <div class="h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1551434678-e076c223a692?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" 
                             alt="Project 3" class="w-full h-full object-cover transition duration-500 hover:scale-105">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-semibold text-gray-800">Social Media Dashboard</h3>
                            <div class="flex space-x-2">
                                <a href="#" class="text-blue-500 hover:text-blue-700">
                                    <i class="fas fa-external-link-alt"></i>
                                </a>
                                <a href="#" class="text-gray-500 hover:text-gray-700">
                                    <i class="fab fa-github"></i>
                                </a>
                            </div>
                        </div>
                        <p class="text-gray-600 mb-4">Analytics dashboard for social media managers with real-time data visualization.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 text-xs rounded-full">React</span>
                            <span class="px-3 py-1 bg-green-100 text-green-800 text-xs rounded-full">D3.js</span>
                            <span class="px-3 py-1 bg-red-100 text-red-800 text-xs rounded-full">Redux</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 4 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-xl transition duration-300 card-hover">
                    <div class="h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1522542550221-31fd19575a2d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" 
                             alt="Project 4" class="w-full h-full object-cover transition duration-500 hover:scale-105">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-semibold text-gray-800">Portfolio Website</h3>
                            <div class="flex space-x-2">
                                <a href="#" class="text-blue-500 hover:text-blue-700">
                                    <i class="fas fa-external-link-alt"></i>
                                </a>
                                <a href="#" class="text-gray-500 hover:text-gray-700">
                                    <i class="fab fa-github"></i>
                                </a>
                            </div>
                        </div>
                        <p class="text-gray-600 mb-4">A responsive portfolio website for a creative professional with animations and contact form.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 text-xs rounded-full">HTML/CSS</span>
                            <span class="px-3 py-1 bg-yellow-100 text-yellow-800 text-xs rounded-full">JavaScript</span>
                            <span class="px-3 py-1 bg-purple-100 text-purple-800 text-xs rounded-full">GSAP</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 5 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-xl transition duration-300 card-hover">
                    <div class="h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1559028012-481c04fa702d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1636&q=80" 
                             alt="Project 5" class="w-full h-full object-cover transition duration-500 hover:scale-105">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-semibold text-gray-800">Restaurant Website</h3>
                            <div class="flex space-x-2">
                                <a href="#" class="text-blue-500 hover:text-blue-700">
                                    <i class="fas fa-external-link-alt"></i>
                                </a>
                                <a href="#" class="text-gray-500 hover:text-gray-700">
                                    <i class="fab fa-github"></i>
                                </a>
                            </div>
                        </div>
                        <p class="text-gray-600 mb-4">An elegant website for a fine dining restaurant with online reservation system.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 text-xs rounded-full">WordPress</span>
                            <span class="px-3 py-1 bg-green-100 text-green-800 text-xs rounded-full">PHP</span>
                            <span class="px-3 py-1 bg-red-100 text-red-800 text-xs rounded-full">MySQL</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 6 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-xl transition duration-300 card-hover">
                    <div class="h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" 
                             alt="Project 6" class="w-full h-full object-cover transition duration-500 hover:scale-105">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-semibold text-gray-800">Corporate Website</h3>
                            <div class="flex space-x-2">
                                <a href="#" class="text-blue-500 hover:text-blue-700">
                                    <i class="fas fa-external-link-alt"></i>
                                </a>
                                <a href="#" class="text-gray-500 hover:text-gray-700">
                                    <i class="fab fa-github"></i>
                                </a>
                            </div>
                        </div>
                        <p class="text-gray-600 mb-4">A professional website for a corporate client with CMS integration.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 text-xs rounded-full">Next.js</span>
                            <span class="px-3 py-1 bg-purple-100 text-purple-800 text-xs rounded-full">Tailwind CSS</span>
                            <span class="px-3 py-1 bg-gray-100 text-gray-800 text-xs rounded-full">Contentful</span>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="inline-flex items-center px-6 py-3 border border-gray-300 text-gray-700 rounded-lg hover:bg-gray-100 transition duration-300">
                    View All Projects <i class="fas fa-arrow-right ml-2"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Work <span class="gradient-text">Experience</span></h2>
                <div class="w-20 h-1 bg-gradient-to-r from-blue-500 to-purple-600 mx-auto"></div>
                <p class="mt-4 text-gray-600 max-w-2xl mx-auto">My professional journey and the companies I've worked with.</p>
            </div>
            
            <div class="relative">
                <!-- Timeline -->
                <div class="border-l-2 border-gray-200 absolute h-full top-0 left-4 md:left-1/2"></div>
                
                <!-- Experience 1 -->
                <div class="mb-8 flex justify-between items-center w-full right-timeline">
                    <div class="order-1 w-5/12"></div>
                    <div class="z-20 flex items-center order-1 bg-gradient-to-r from-blue-500 to-purple-600 shadow-xl w-8 h-8 rounded-full">
                        <h1 class="mx-auto font-semibold text-lg text-white">1</h1>
                    </div>
                    <div class="order-1 bg-white rounded-lg shadow-xl w-5/12 px-6 py-4 card-hover">
                        <h3 class="mb-3 font-bold text-gray-800 text-xl">Senior Frontend Developer</h3>
                        <p class="text-sm text-gray-500 mb-2">Tech Solutions Inc. • 2021 - Present</p>
                        <p class="text-gray-600 leading-relaxed">
                            Lead the frontend development team, implementing new features and optimizing performance for web applications. Mentored junior developers and established coding standards.
                        </p>
                        <div class="mt-3 flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 text-xs rounded-full">React</span>
                            <span class="px-3 py-1 bg-purple-100 text-purple-800 text-xs rounded-full">TypeScript</span>
                            <span class="px-3 py-1 bg-green-100 text-green-800 text-xs rounded-full">GraphQL</span>
                        </div>
                    </div>
                </div>

                <!-- Experience 2 -->
                <div class="mb-8 flex justify-between items-center w-full left-timeline">
                    <div class="order-1 bg-white rounded-lg shadow-xl w-5/12 px-6 py-4 card-hover">
                        <h3 class="mb-3 font-bold text-gray-800 text-xl">Frontend Developer</h3>
                        <p class="text-sm text-gray-500 mb-2">Digital Creative Agency • 2018 - 2021</p>
                        <p class="text-gray-600 leading-relaxed">
                            Developed responsive websites and web applications for various clients. Collaborated with designers to implement UI/UX designs with pixel-perfect accuracy.
                        </p>
                        <div class="mt-3 flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 text-xs rounded-full">Vue.js</span>
                            <span class="px-3 py-1 bg-yellow-100 text-yellow-800 text-xs rounded-full">JavaScript</span>
                            <span class="px-3 py-1 bg-red-100 text-red-800 text-xs rounded-full">Sass</span>
                        </div>
                    </div>
                    <div class="z-20 flex items-center order-1 bg-gradient-to-r from-blue-500 to-purple-600 shadow-xl w-8 h-8 rounded-full">
                        <h1 class="mx-auto font-semibold text-lg text-white">2</h1>
                    </div>
                    <div class="order-1 w-5/12"></div>
                </div>

                <!-- Experience 3 -->
                <div class="mb-8 flex justify-between items-center w-full right-timeline">
                    <div class="order-1 w-5/12"></div>
                    <div class="z-20 flex items-center order-1 bg-gradient-to-r from-blue-500 to-purple-600 shadow-xl w-8 h-8 rounded-full">
                        <h1 class="mx-auto font-semibold text-lg text-white">3</h1>
                    </div>
                    <div class="order-1 bg-white rounded-lg shadow-xl w-5/12 px-6 py-4 card-hover">
                        <h3 class="mb-3 font-bold text-gray-800 text-xl">Junior Web Developer</h3>
                        <p class="text-sm text-gray-500 mb-2">Startup Ventures • 2016 - 2018</p>
                        <p class="text-gray-600 leading-relaxed">
                            Built and maintained company websites and internal tools. Assisted in the development of web applications and implemented responsive designs.
                        </p>
                        <div class="mt-3 flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 text-xs rounded-full">HTML/CSS</span>
                            <span class="px-3 py-1 bg-yellow-100 text-yellow-800 text-xs rounded-full">JavaScript</span>
                            <span class="px-3 py-1 bg-green-100 text-green-800 text-xs rounded-full">PHP</span>
                        </div>
                    </div>
                </div>

                <!-- Experience 4 -->
                <div class="mb-8 flex justify-between items-center w-full left-timeline">
                    <div class="order-1 bg-white rounded-lg shadow-xl w-5/12 px-6 py-4 card-hover">
                        <h3 class="mb-3 font-bold text-gray-800 text-xl">Web Design Intern</h3>
                        <p class="text-sm text-gray-500 mb-2">Creative Studio • 2015 - 2016</p>
                        <p class="text-gray-600 leading-relaxed">
                            Assisted in designing and developing websites for clients. Learned industry best practices and gained hands-on experience with web technologies.
                        </p>
                        <div class="mt-3 flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 text-xs rounded-full">WordPress</span>
                            <span class="px-3 py-1 bg-purple-100 text-purple-800 text-xs rounded-full">Photoshop</span>
                            <span class="px-3 py-1 bg-green-100 text-green-800 text-xs rounded-full">CSS</span>
                        </div>
                    </div>
                    <div class="z-20 flex items-center order-1 bg-gradient-to-r from-blue-500 to-purple-600 shadow-xl w-8 h-8 rounded-full">
                        <h1 class="mx-auto font-semibold text-lg text-white">4</h1>
                    </div>
                    <div class="order-1 w-5/12"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Get In <span class="gradient-text">Touch</span></h2>
                <div class="w-20 h-1 bg-gradient-to-r from-blue-500 to-purple-600 mx-auto"></div>
                <p class="mt-4 text-gray-600 max-w-2xl mx-auto">Have a project in mind or want to discuss potential opportunities? Feel free to reach out!</p>
            </div>
            
            <div class="grid md:grid-cols-2 gap-12">
                <div class="space-y-8">
                    <div class="flex items-start space-x-4">
                        <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full text-blue-600">
                            <i class="fas fa-envelope text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-lg font-semibold text-gray-800">Email Me</h3>
                            <p class="text-gray-600">fakhru@example.com</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start space-x-4">
                        <div class="flex-shrink-0 bg-purple-100 p-3 rounded-full text-purple-600">
                            <i class="fas fa-phone-alt text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-lg font-semibold text-gray-800">Call Me</h3>
                            <p class="text-gray-600">+123 456 7890</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start space-x-4">
                        <div class="flex-shrink-0 bg-green-100 p-3 rounded-full text-green-600">
                            <i class="fas fa-map-marker-alt text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-lg font-semibold text-gray-800">Location</h3>
                            <p class="text-gray-600">Jakarta, Indonesia</p>
                        </div>
                    </div>
                    
                    <div class="pt-4">
                        <h3 class="text-lg font-semibold text-gray-800 mb-4">Follow Me</h3>
                        <div class="flex space-x-4">
                            <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 text-gray-700 rounded-full hover:bg-blue-100 hover:text-blue-600 transition">
                                <i class="fab fa-github"></i>
                            </a>
                            <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 text-gray-700 rounded-full hover:bg-blue-100 hover:text-blue-600 transition">
                                <i class="fab fa-linkedin-in"></i>
                            </a>
                            <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 text-gray-700 rounded-full hover:bg-blue-100 hover:text-blue-600 transition">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 text-gray-700 rounded-full hover:bg-blue-100 hover:text-blue-600 transition">
                                <i class="fab fa-instagram"></i>
                            </a>
                            <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-100 text-gray-700 rounded-full hover:bg-blue-100 hover:text-blue-600 transition">
                                <i class="fab fa-dribbble"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="bg-gray-50 p-8 rounded-xl shadow-sm">
                    <form id="contact-form" class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Full Name</label>
                            <input type="text" id="name" name="name" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition">
                        </div>
                        
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email Address</label>
                            <input type="email" id="email" name="email" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition">
                        </div>
                        
                        <div>
                            <label for="subject" class="block text-sm font-medium text-gray-700 mb-1">Subject</label>
                            <input type="text" id="subject" name="subject" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition">
                        </div>
                        
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
                            <textarea id="message" name="message" rows="5" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition"></textarea>
                        </div>
                        
                        <button type="submit" class="w-full px-6 py-3 bg-gradient-to-r from-blue-500 to-purple-600 text-white rounded-lg shadow-md hover:shadow-lg transition duration-300">
                            Send Message <i class="fas fa-paper-plane ml-2"></i>
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-xl font-bold gradient-text mb-4">Fakhru</h3>
                    <p class="text-gray-400">
                        A passionate web developer and designer dedicated to creating beautiful, functional digital experiences.
                    </p>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-white transition">Home</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-white transition">About</a></li>
                        <li><a href="#skills" class="text-gray-400 hover:text-white transition">Skills</a></li>
                        <li><a href="#projects" class="text-gray-400 hover:text-white transition">Projects</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white transition">Contact</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Newsletter</h3>
                    <p class="text-gray-400 mb-4">Subscribe to my newsletter for the latest updates and articles.</p>
                    <form class="flex">
                        <input type="email" placeholder="Your email" class="px-4 py-2 w-full rounded-l-lg focus:outline-none text-gray-900">
                        <button type="submit" class="bg-gradient-to-r from-blue-500 to-purple-600 px-4 py-2 rounded-r-lg hover:opacity-90 transition">
                            <i class="fas fa-paper-plane"></i>
                        </button>
                    </form>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-12 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 text-sm">© 2023 Fakhru. All rights reserved.</p>
                <div class="flex space-x-6 mt-4 md:mt-0">
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <i class="fab fa-github"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <i class="fab fa-linkedin-in"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <i class="fab fa-twitter"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <i class="fab fa-instagram"></i>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button id="back-to-top" class="fixed bottom-8 right-8 bg-gradient-to-r from-blue-500 to-purple-600 text-white p-3 rounded-full shadow-lg opacity-0 invisible transition-all duration-300">
        <i class="fas fa-arrow-up"></i>
    </button>

    <!-- Scripts -->
    <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
    <script>
        // Mobile menu toggle
        document.getElementById('menu-toggle').addEventListener('click', function() {
            document.getElementById('mobile-menu').classList.toggle('hidden');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
                
                // Close mobile menu if open
                document.getElementById('mobile-menu').classList.add('hidden');
            });
        });

        // Back to top button
        const backToTopButton = document.getElementById('back-to-top');
        
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTopButton.classList.remove('opacity-0', 'invisible');
                backToTopButton.classList.add('opacity-100', 'visible');
            } else {
                backToTopButton.classList.remove('opacity-100', 'visible');
                backToTopButton.classList.add('opacity-0', 'invisible');
            }
        });
        
        backToTopButton.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });

        // Typewriter effect
        class Typewriter {
            constructor(element, words, wait = 3000) {
                this.element = element;
                this.words = words;
                this.txt = '';
                this.wordIndex = 0;
                this.wait = parseInt(wait, 10);
                this.type();
                this.isDeleting = false;
            }

            type() {
                // Current index of word
                const current = this.wordIndex % this.words.length;
                // Get full text of current word
                const fullTxt = this.words[current];

                // Check if deleting
                if (this.isDeleting) {
                    // Remove char
                    this.txt = fullTxt.substring(0, this.txt.length - 1);
                } else {
                    // Add char
                    this.txt = fullTxt.substring(0, this.txt.length + 1);
                }

                // Insert txt into element
                this.element.innerHTML = `<span class="gradient-text">${this.txt}</span>`;

                // Initial type speed
                let typeSpeed = 200;

                if (this.isDeleting) {
                    typeSpeed /= 2;
                }

                // If word is complete
                if (!this.isDeleting && this.txt === fullTxt) {
                    // Make pause at end
                    typeSpeed = this.wait;
                    // Set delete to true
                    this.isDeleting = true;
                } else if (this.isDeleting && this.txt === '') {
                    this.isDeleting = false;
                    // Move to next word
                    this.wordIndex++;
                    // Pause before start typing
                    typeSpeed = 500;
                }

                setTimeout(() => this.type(), typeSpeed);
            }
        }

        // Init typewriter
        document.addEventListener('DOMContentLoaded', () => {
            const element = document.querySelector('.typewriter');
            const words = JSON.parse(element.getAttribute('data-words'));
            const wait = element.getAttribute('data-wait');
            
            // Init Typewriter
            new Typewriter(element, words, wait);
        });

        // Form submission
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Get form values
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const subject = document.getElementById('subject').value;
            const message = document.getElementById('message').value;
            
            // Here you would typically send the data to a server
            console.log({ name, email, subject, message });
            
            // Show success message
            alert('Thank you for your message! I will get back to you soon.');
            
            // Reset form
            this.reset();
        });

        // Initialize particles.js
        particlesJS("particles-js", {
            "particles": {
                "number": {
                    "value": 80,
                    "density": {
                        "enable": true,
                        "value_area": 800
                    }
                },
                "color": {
                    "value": "#3b82f6"
                },
                "shape": {
                    "type": "circle",
                    "stroke": {
                        "width": 0,
                        "color": "#000000"
                    },
                    "polygon": {
                        "nb_sides": 5
                    }
                },
                "opacity": {
                    "value": 0.5,
                    "random": false,
                    "anim": {
                        "enable": false,
                        "speed": 1,
                        "opacity_min": 0.1,
                        "sync": false
                    }
                },
                "size": {
                    "value": 3,
                    "random": true,
                    "anim": {
                        "enable": false,
                        "speed": 40,
                        "size_min": 0.1,
                        "sync": false
                    }
                },
                "line_linked": {
                    "enable": true,
                    "distance": 150,
                    "color": "#3b82f6",
                    "opacity": 0.4,
                    "width": 1
                },
                "move": {
                    "enable": true,
                    "speed": 2,
                    "direction": "none",
                    "random": false,
                    "straight": false,
                    "out_mode": "out",
                    "bounce": false,
                    "attract": {
                        "enable": false,
                        "rotateX": 600,
                        "rotateY": 1200
                    }
                }
            },
            "interactivity": {
                "detect_on": "canvas",
                "events": {
                    "onhover": {
                        "enable": true,
                        "mode": "grab"
                    },
                    "onclick": {
                        "enable": true,
                        "mode": "push"
                    },
                    "resize": true
                },
                "modes": {
                    "grab": {
                        "distance": 140,
                        "line_linked": {
                            "opacity": 1
                        }
                    },
                    "bubble": {
                        "distance": 400,
                        "size": 40,
                        "duration": 2,
                        "opacity": 8,
                        "speed": 3
                    },
                    "repulse": {
                        "distance": 200,
                        "duration": 0.4
                    },
                    "push": {
                        "particles_nb": 4
                    },
                    "remove": {
                        "particles_nb": 2
                    }
                }
            },
            "retina_detect": true
        });

        // Add animation to elements when they come into view
        const animateOnScroll = () => {
            const elements = document.querySelectorAll('.fade-in');
            
            elements.forEach(element => {
                const elementPosition = element.getBoundingClientRect().top;
                const screenPosition = window.innerHeight / 1.2;
                
                if (elementPosition < screenPosition) {
                    element.style.opacity = '1';
                    element.style.transform = 'translateY(0)';
                }
            });
        };

        window.addEventListener('scroll', animateOnScroll);
        window.addEventListener('load', animateOnScroll);
    </script>
</body>
</html>
