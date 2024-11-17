# Higherscoreweb<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HigherScore Educational Institute</title>
    
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>
    
    <style>
        html {
            scroll-behavior: smooth;
        }
        .gradient-text {
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            background-image: linear-gradient(45deg, #0284c7, #0ea5e9);
        }
        .hover-scale {
            transition: transform 0.3s ease;
        }
        .hover-scale:hover {
            transform: scale(1.02);
        }
        .fade-in {
            animation: fadeIn 0.5s ease-in-out;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between items-center py-4">
                <div class="flex items-center">
                    <h1 class="text-2xl font-bold gradient-text">HIGHERSCORE</h1>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="text-gray-600 hover:text-blue-500">Home</a>
                    <a href="#classes" class="text-gray-600 hover:text-blue-500">Courses</a>
                    <a href="#about" class="text-gray-600 hover:text-blue-500">About</a>
                    <a href="#contact" class="text-gray-600 hover:text-blue-500">Contact</a>
                </div>
                <button class="md:hidden">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-24 pb-12 px-4">
        <div class="max-w-7xl mx-auto">
            <div class="text-center fade-in">
                <h2 class="text-4xl md:text-6xl font-bold mb-6 gradient-text">Unlock Your Learning Potential</h2>
                <p class="text-xl text-gray-600 mb-8">Expert tutoring and comprehensive courses to help you achieve academic excellence</p>
                <button class="bg-blue-500 text-white px-8 py-3 rounded-full hover:bg-blue-600 hover-scale">
                    Get Started
                </button>
            </div>
        </div>
    </section>

    <!-- Classes Section -->
    <section id="Classes" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 gradient-text">Our Classes</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Course Card 1 -->
                <div class="bg-white rounded-lg shadow-lg p-6 hover-scale">
                    <div class="text-blue-500 mb-4">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Mathematics</h3>
                    <p class="text-gray-600">Master complex mathematical concepts with our expert tutors.</p>
                </div>

                <!-- Course Card 2 -->
                <div class="bg-white rounded-lg shadow-lg p-6 hover-scale">
                    <div class="text-blue-500 mb-4">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Sciences</h3>
                    <p class="text-gray-600">Explore the wonders of science through practical experiments and theory.</p>
                </div>

                <!-- Course Card 3 -->
                <div class="bg-white rounded-lg shadow-lg p-6 hover-scale">
                    <div class="text-blue-500 mb-4">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5h12M9 3v2m1.048 9.5A18.022 18.022 0 016.412 9m6.088 9h7M11 21l5-10 5 10M12.751 5C11.783 10.77 8.07 15.61 3 18.129"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-2">English</h3>
                    <p class="text-gray-600">Our English language is so elastic that you can find another word to say the same thing.</p>
                </div>
            </div>
        </div>
    </section>


<!-- Class Card 4 (ICT) -->
    <div class="bg-white rounded-lg shadow-lg p-6 hover-scale w-64 h-72">
        <div class="text-blue-500 mb-4">
            <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
            </svg>
        </div>
        <h3 class="text-xl font-bold mb-2">ICT</h3>
        <p class="text-gray-600">
            The new information technology. Internet and e-mail. have practically eliminated the physical costs of communications.
        </p>
    </div>
</section>

 <!-- Class Card 5 (New Tamil Card) -->
                <div class="bg-white rounded-lg shadow-lg p-6 hover-scale">
                    <div class="text-blue-500 mb-4">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Tamil</h3>
                    <p class="text-gray-600">Learn Tamil language with experienced teachers and traditional methods.</p>
                </div>
            </div>
        </div>
    </section>


    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 gradient-text">Get in Touch</h2>
            <div class="max-w-lg mx-auto">
                <form class="space-y-6">
                    <div>
                        <label class="block text-gray-700 mb-2" for="name">Name</label>
                        <input type="text" id="name" class="w-full px-4 py-2 rounded-lg border focus:outline-none focus:ring-2 focus:ring-blue-500">
                    </div>
                    <div>
                        <label class="block text-gray-700 mb-2" for="email">Email</label>
                        <input type="email" id="email" class="w-full px-4 py-2 rounded-lg border focus:outline-none focus:ring-2 focus:ring-blue-500">
                    </div>
                    <div>
                        <label class="block text-gray-700 mb-2" for="message">Message</label>
                        <textarea id="message" rows="4" class="w-full px-4 py-2 rounded-lg border focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
                    </div>
                    <button type="submit" class="w-full bg-blue-500 text-white py-2 rounded-lg hover:bg-blue-600 hover-scale">
                        Send Message
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">HigherScore</h3>
                    <p class="text-gray-400">Empowering students to achieve their academic goals.</p>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-white">Home</a></li>
                        <li><a href="#courses" class="text-gray-400 hover:text-white">Courses</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-white">About</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white">Contact</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Contact Info</h3>
                    <ul class="space-y-2 text-gray-400">
                        <li>Sri Manhindanahimi Road,Middeniya</li>
                        <li>Middeniya, Sri Lanka</li>
                        <li>Phone: +94123456789</li>
                        <li>Email: info@higherscore.edu</li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // GSAP Animations
        gsap.registerPlugin(ScrollTrigger);

        // Animate course cards
        gsap.utils.toArray('.hover-scale').forEach(card => {
            gsap.from(card, {
                scrollTrigger: {
                    trigger: card,
                    start: "top bottom-=100",
                    toggleActions: "play none none reverse"
                },
                y: 50,
                opacity: 0,
                duration: 0.8,
                ease: "power2.out"
            });
        });
    </script>
</body>
</html>
