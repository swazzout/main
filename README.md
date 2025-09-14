<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JASON VŨ | Multidisciplinary Artist</title>
    <link rel="icon" type="image/x-icon" href="/static/favicon.ico">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.waves.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;700&family=Playfair+Display:wght@400;600&display=swap');
        body {
            font-family: 'Montserrat', sans-serif;
        }
        .hero-text {
            font-family: 'Playfair Display', serif;
        }
        .vanta-bg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }
        .content-section {
            backdrop-filter: blur(8px);
            background-color: rgba(255, 255, 255, 0.85);
        }
        .nav-link:hover {
            color: #f59e0b;
            transform: translateY(-2px);
        }
        .social-icon:hover {
            transform: scale(1.2);
            color: #f59e0b;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-900">
    <!-- Vanta.js Background -->
    <div id="vanta-bg" class="vanta-bg"></div>

    <!-- Navigation -->
    <nav class="fixed w-full z-50 bg-black bg-opacity-80 text-white">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold hover:text-amber-400 transition">JASON VŨ</a>
            <div class="hidden md:flex space-x-8">
                <a href="#about" class="nav-link transition">About</a>
                <a href="#work" class="nav-link transition">Work</a>
                <a href="#content" class="nav-link transition">Content</a>
                <a href="#contact" class="nav-link transition">Contact</a>
            </div>
            <button class="md:hidden focus:outline-none">
                <i data-feather="menu"></i>
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="min-h-screen flex items-center justify-center relative overflow-hidden">
        <div class="container mx-auto px-6 py-20 text-center">
            <h1 class="hero-text text-5xl md:text-7xl font-bold mb-6" data-aos="fade-down">
                JASON <span class="text-amber-500">VŨ</span>
            </h1>
            <p class="text-xl md:text-2xl mb-8 max-w-2xl mx-auto" data-aos="fade-up" data-aos-delay="200">
                Actor • Singer • Dancer • Voice Artist • Content Creator
            </p>
            <div class="flex justify-center space-x-4" data-aos="fade-up" data-aos-delay="400">
                <a href="#work" class="px-8 py-3 bg-amber-500 text-white rounded-full font-medium hover:bg-amber-600 transition">
                    Explore My Work
                </a>
                <a href="#contact" class="px-8 py-3 border-2 border-white text-white rounded-full font-medium hover:bg-white hover:text-black transition">
                    Get In Touch
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 content-section">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold mb-12 text-center" data-aos="fade-up">About Me</h2>
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-8 md:mb-0" data-aos="fade-right">
                    <img src="http://static.photos/black/640x360/42" alt="Jason Vũ" class="rounded-lg shadow-xl w-full max-w-md mx-auto">
                </div>
                <div class="md:w-1/2 md:pl-12" data-aos="fade-left" data-aos-delay="200">
                    <p class="text-lg mb-6">
                        I'm Jason Vũ, a Black-Vietnamese multidisciplinary artist exploring the intersections of performance, storytelling, and everyday human experiences.
                    </p>
                    <p class="text-lg mb-6">
                        My work is deeply personal yet universally relatable - capturing the nuances of cultural identity, social interactions, and the beautiful mess of being human.
                    </p>
                    <p class="text-lg">
                        Whether through acting, singing, dancing, or voice work, I aim to create authentic connections and challenge perspectives through my art.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Work Section -->
    <section id="work" class="py-20 bg-gray-900 text-white">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold mb-12 text-center" data-aos="fade-up">My Work</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Acting -->
                <div class="bg-gray-800 rounded-lg overflow-hidden shadow-xl" data-aos="zoom-in">
                    <div class="h-48 bg-cover bg-center" style="background-image: url('http://static.photos/black/640x360/43');"></div>
                    <div class="p-6">
                        <h3 class="text-2xl font-bold mb-3">Acting</h3>
                        <p class="mb-4">From stage to screen, I bring characters to life with emotional depth and authenticity.</p>
                        <a href="#" class="text-amber-400 hover:text-amber-300 font-medium">View Projects →</a>
                    </div>
                </div>
                <!-- Music -->
                <div class="bg-gray-800 rounded-lg overflow-hidden shadow-xl" data-aos="zoom-in" data-aos-delay="200">
                    <div class="h-48 bg-cover bg-center" style="background-image: url('http://static.photos/black/640x360/44');"></div>
                    <div class="p-6">
                        <h3 class="text-2xl font-bold mb-3">Music</h3>
                        <p class="mb-4">Original songs that blend R&B, soul, and Vietnamese influences to tell my story.</p>
                        <a href="#" class="text-amber-400 hover:text-amber-300 font-medium">Listen Now →</a>
                    </div>
                </div>
                <!-- Voice -->
                <div class="bg-gray-800 rounded-lg overflow-hidden shadow-xl" data-aos="zoom-in" data-aos-delay="400">
                    <div class="h-48 bg-cover bg-center" style="background-image: url('http://static.photos/black/640x360/45');"></div>
                    <div class="p-6">
                        <h3 class="text-2xl font-bold mb-3">Voice Work</h3>
                        <p class="mb-4">Commercials, animation, and narration with versatile vocal range and emotional resonance.</p>
                        <a href="#" class="text-amber-400 hover:text-amber-300 font-medium">Hear Samples →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Content Section -->
    <section id="content" class="py-20 content-section">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold mb-12 text-center" data-aos="fade-up">My Content</h2>
            <p class="text-xl text-center max-w-3xl mx-auto mb-12" data-aos="fade-up" data-aos-delay="200">
                I create raw, unfiltered content about everyday life - the awkward moments, cultural observations, and personal reflections that make us human.
            </p>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Content Card 1 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-lg" data-aos="fade-up">
                    <div class="h-64 bg-cover bg-center" style="background-image: url('http://static.photos/black/640x360/46');"></div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">"Mixed Feelings" Series</h3>
                        <p class="text-gray-600 mb-4">Exploring the biracial experience through humor and vulnerability.</p>
                        <div class="flex space-x-4">
                            <a href="#" class="social-icon"><i data-feather="instagram"></i></a>
                            <a href="#" class="social-icon"><i data-feather="youtube"></i></a>
                            <a href="#" class="social-icon"><i data-feather="twitter"></i></a>
                        </div>
                    </div>
                </div>
                <!-- Content Card 2 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-lg" data-aos="fade-up" data-aos-delay="200">
                    <div class="h-64 bg-cover bg-center" style="background-image: url('http://static.photos/black/640x360/47');"></div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Everyday Observations</h3>
                        <p class="text-gray-600 mb-4">Short skits about those relatable daily interactions we all experience.</p>
                        <div class="flex space-x-4">
                            <a href="#" class="social-icon"><i data-feather="instagram"></i></a>
                            <a href="#" class="social-icon"><i data-feather="tiktok"></i></a>
                        </div>
                    </div>
                </div>
                <!-- Content Card 3 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-lg" data-aos="fade-up" data-aos-delay="400">
                    <div class="h-64 bg-cover bg-center" style="background-image: url('http://static.photos/black/640x360/48');"></div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Behind The Scenes</h3>
                        <p class="text-gray-600 mb-4">Raw footage of my creative process and artistic journey.</p>
                        <div class="flex space-x-4">
                            <a href="#" class="social-icon"><i data-feather="youtube"></i></a>
                            <a href="#" class="social-icon"><i data-feather="patreon"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-900 text-white">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold mb-12 text-center" data-aos="fade-up">Let's Connect</h2>
            <div class="max-w-2xl mx-auto">
                <form class="space-y-6" data-aos="fade-up" data-aos-delay="200">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div>
                            <label for="name" class="block mb-2">Name</label>
                            <input type="text" id="name" class="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded focus:outline-none focus:ring-2 focus:ring-amber-500">
                        </div>
                        <div>
                            <label for="email" class="block mb-2">Email</label>
                            <input type="email" id="email" class="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded focus:outline-none focus:ring-2 focus:ring-amber-500">
                        </div>
                    </div>
                    <div>
                        <label for="subject" class="block mb-2">Subject</label>
                        <input type="text" id="subject" class="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded focus:outline-none focus:ring-2 focus:ring-amber-500">
                    </div>
                    <div>
                        <label for="message" class="block mb-2">Message</label>
                        <textarea id="message" rows="5" class="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded focus:outline-none focus:ring-2 focus:ring-amber-500"></textarea>
                    </div>
                    <button type="submit" class="w-full md:w-auto px-8 py-3 bg-amber-500 text-white rounded font-medium hover:bg-amber-600 transition">
                        Send Message
                    </button>
                </form>
                <div class="mt-12 flex justify-center space-x-8" data-aos="fade-up" data-aos-delay="400">
                    <a href="#" class="social-icon"><i data-feather="instagram"></i></a>
                    <a href="#" class="social-icon"><i data-feather="twitter"></i></a>
                    <a href="#" class="social-icon"><i data-feather="youtube"></i></a>
                    <a href="#" class="social-icon"><i data-feather="tiktok"></i></a>
                    <a href="#" class="social-icon"><i data-feather="linkedin"></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 bg-black text-white text-center">
        <div class="container mx-auto px-6">
            <p>&copy; 2023 Jason Vũ. All rights reserved.</p>
            <p class="mt-2 text-gray-400">Multidisciplinary Artist & Storyteller</p>
        </div>
    </footer>

    <script>
        // Initialize Vanta.js waves background
        VANTA.WAVES({
            el: "#vanta-bg",
            mouseControls: true,
            touchControls: true,
            gyroControls: false,
            minHeight: 200.00,
            minWidth: 200.00,
            scale: 1.00,
            scaleMobile: 1.00,
            color: 0x0,
            shininess: 35.00,
            waveHeight: 15.00,
            waveSpeed: 0.75,
            zoom: 0.65
        });

        // Initialize AOS and Feather Icons
        AOS.init({
            duration: 800,
            easing: 'ease-in-out',
            once: true
        });
        feather.replace();
    </script>
</body>
</html>
