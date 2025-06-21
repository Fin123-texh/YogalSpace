<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yogal Space - Your Posh Sanctuary in Liverpool</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #ffffff; /* Pure white background */
            color: #333333; /* Soft black text for contrast */
        }
        .hero-background {
            background-image: url('https://placehold.co/1920x800/fce7f3/db2777?text=Yogal+Space+Serenity'); /* Soft pink placeholder for serene yoga */
            background-size: cover;
            background-position: center;
            background-blend-mode: overlay; /* Blends with background color */
            background-color: rgba(255, 255, 255, 0.6); /* Semi-transparent white overlay for softness */
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header/Navigation -->
    <header class="bg-white shadow-sm py-4 border-b border-gray-100">
        <nav class="container mx-auto px-6 flex justify-between items-center">
            <a href="#" class="text-3xl font-bold text-rose-500 rounded-lg p-2 hover:bg-rose-50 transition duration-300">Yogal Space</a>
            <div class="hidden md:flex space-x-8">
                <a href="#about" class="text-gray-600 hover:text-rose-500 font-medium transition duration-300 rounded-lg p-2 hover:bg-gray-50">About Us</a>
                <a href="#classes" class="text-gray-600 hover:text-rose-500 font-medium transition duration-300 rounded-lg p-2 hover:bg-gray-50">Classes</a>
                <a href="#schedule" class="text-gray-600 hover:text-rose-500 font-medium transition duration-300 rounded-lg p-2 hover:bg-gray-50">Schedule</a>
                <a href="#contact" class="text-gray-600 hover:text-rose-500 font-medium transition duration-300 rounded-lg p-2 hover:bg-gray-50">Contact</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden text-gray-600 hover:text-rose-500 focus:outline-none">
                <svg class="w-7 h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                </svg>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white px-6 pt-2 pb-4 space-y-2 border-t border-gray-100">
            <a href="#about" class="block text-gray-700 hover:text-rose-500 font-medium rounded-lg p-2 hover:bg-gray-50">About Us</a>
            <a href="#classes" class="block text-gray-700 hover:text-rose-500 font-medium rounded-lg p-2 hover:bg-gray-50">Classes</a>
            <a href="#schedule" class="block text-gray-700 hover:text-rose-500 font-medium rounded-lg p-2 hover:bg-gray-50">Schedule</a>
            <a href="#contact" class="block text-gray-700 hover:text-rose-500 font-medium rounded-lg p-2 hover:bg-gray-50">Contact</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-background text-gray-900 py-24 md:py-40 lg:py-56 flex items-center justify-center text-center rounded-b-3xl shadow-xl">
        <div class="bg-white bg-opacity-70 p-10 rounded-2xl max-w-3xl mx-auto backdrop-blur-sm shadow-2xl">
            <h1 class="text-5xl md:text-7xl font-light mb-4 leading-tight text-rose-600">Discover Your Bloom at <span class="font-bold">Yogal Space</span></h1>
            <p class="text-xl md:text-2xl mb-10 font-light text-gray-700">Nourish your body, calm your mind, and uplift your spirit in the heart of Liverpool.</p>
            <a href="#classes" class="inline-block bg-rose-500 hover:bg-rose-600 text-white font-semibold py-4 px-10 rounded-full shadow-lg transition duration-300 ease-in-out transform hover:scale-105 hover:shadow-xl focus:outline-none focus:ring-4 focus:ring-rose-300 focus:ring-opacity-75">Explore Classes</a>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="container mx-auto px-6 py-20">
        <div class="flex flex-col md:flex-row items-center justify-between space-y-12 md:space-y-0 md:space-x-20">
            <div class="md:w-1/2">
                <img src="https://placehold.co/700x500/fce7f3/e9d5ff?text=Elegant+Yoga+Studio" alt="About Yogal Space" class="rounded-2xl shadow-2xl w-full h-auto object-cover transform hover:scale-105 transition duration-500 ease-in-out">
            </div>
            <div class="md:w-1/2">
                <h2 class="text-4xl font-light text-rose-600 mb-8 leading-snug">A Sanctuary for Modern Women</h2>
                <p class="text-lg text-gray-700 mb-6 leading-relaxed">
                    Yogal Space is more than just a yoga studio; it's a meticulously crafted sanctuary designed to foster holistic well-being, vibrant community, and profound personal growth. Nestled in the dynamic city of Liverpool, we offer a serene and elegant escape from the everyday hustle, a place where you can truly connect with yourself.
                </p>
                <p class="text-lg text-gray-700 leading-relaxed">
                    Our esteemed instructors are deeply passionate about guiding you through your yoga journey, whether you're taking your very first breath on the mat or seeking to deepen an established practice. We champion the belief that yoga is for every unique body, and our thoughtfully curated array of classes embodies this philosophy, ensuring a welcoming, inclusive, and empowering environment for all who walk through our doors.
                </p>
            </div>
        </div>
    </section>

    <!-- Classes Section -->
    <section id="classes" class="bg-rose-50 py-20 rounded-3xl mx-auto my-12 shadow-inner">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl font-light text-rose-600 mb-14">Our Curated Classes</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-12">
                <!-- Class Card 1: Vinyasa Flow -->
                <div class="bg-white rounded-2xl shadow-xl p-10 transform hover:scale-105 transition duration-300 ease-in-out border border-rose-100 flex flex-col items-center">
                    <h3 class="text-2xl font-semibold text-rose-600 mb-4">Vinyasa Flow</h3>
                    <p class="text-gray-700 mb-7 leading-relaxed">
                        Synchronize breath with graceful movement in this dynamic and fluid practice. Cultivate strength, enhance flexibility, and elevate your cardiovascular vitality. Perfect for all levels, from novice to advanced.
                    </p>
                    <a href="#" class="inline-block bg-rose-500 hover:bg-rose-600 text-white font-semibold py-3 px-8 rounded-full shadow-md transition duration-300">Explore</a>
                </div>

                <!-- Class Card 2: Hatha Yoga -->
                <div class="bg-white rounded-2xl shadow-xl p-10 transform hover:scale-105 transition duration-300 ease-in-out border border-rose-100 flex flex-col items-center">
                    <h3 class="text-2xl font-semibold text-rose-600 mb-4">Hatha Yoga</h3>
                    <p class="text-gray-700 mb-7 leading-relaxed">
                        Delve into foundational poses with extended holds, meticulous focus on alignment, and profound breathwork. An excellent choice for beginners and those desiring a slower, more contemplative rhythm.
                    </p>
                    <a href="#" class="inline-block bg-rose-500 hover:bg-rose-600 text-white font-semibold py-3 px-8 rounded-full shadow-md transition duration-300">Explore</a>
                </div>

                <!-- Class Card 3: Restorative Yoga -->
                <div class="bg-white rounded-2xl shadow-xl p-10 transform hover:scale-105 transition duration-300 ease-in-out border border-rose-100 flex flex-col items-center">
                    <h3 class="text-2xl font-semibold text-rose-600 mb-4">Restorative Yoga</h3>
                    <p class="text-gray-700 mb-7 leading-relaxed">
                        Unwind and gently release deep-seated tension through artfully supported poses that encourage profound relaxation and rejuvenation. The ideal balm for stress relief and holistic recovery.
                    </p>
                    <a href="#" class="inline-block bg-rose-500 hover:bg-rose-600 text-white font-semibold py-3 px-8 rounded-full shadow-md transition duration-300">Explore</a>
                </div>

                <!-- Class Card 4: Power Yoga -->
                <div class="bg-white rounded-2xl shadow-xl p-10 transform hover:scale-105 transition duration-300 ease-in-out border border-rose-100 flex flex-col items-center">
                    <h3 class="text-2xl font-semibold text-rose-600 mb-4">Power Yoga</h3>
                    <p class="text-gray-700 mb-7 leading-relaxed">
                        An invigorating and challenging practice meticulously designed to forge exceptional strength, stamina, and agility. Anticipate a dynamic flow and deeply empowering sequences.
                    </p>
                    <a href="#" class="inline-block bg-rose-500 hover:bg-rose-600 text-white font-semibold py-3 px-8 rounded-full shadow-md transition duration-300">Explore</a>
                </div>

                <!-- Class Card 5: Prenatal Yoga -->
                <div class="bg-white rounded-2xl shadow-xl p-10 transform hover:scale-105 transition duration-300 ease-in-out border border-rose-100 flex flex-col items-center">
                    <h3 class="text-2xl font-semibold text-rose-600 mb-4">Prenatal Yoga</h3>
                    <p class="text-gray-700 mb-7 leading-relaxed">
                        A tender and profoundly supportive yoga journey thoughtfully designed for expectant mothers, prioritizing comfort, gentle strength, and graceful preparation for childbirth.
                    </p>
                    <a href="#" class="inline-block bg-rose-500 hover:bg-rose-600 text-white font-semibold py-3 px-8 rounded-full shadow-md transition duration-300">Explore</a>
                </div>

                <!-- Class Card 6: Meditation & Mindfulness -->
                <div class="bg-white rounded-2xl shadow-xl p-10 transform hover:scale-105 transition duration-300 ease-in-out border border-rose-100 flex flex-col items-center">
                    <h3 class="text-2xl font-semibold text-rose-600 mb-4">Meditation & Mindfulness</h3>
                    <p class="text-gray-700 mb-7 leading-relaxed">
                        Cultivate profound inner calm, crystal-clear mental clarity, and a heightened sense of presence through our beautifully guided meditation and mindfulness practices.
                    </p>
                    <a href="#" class="inline-block bg-rose-500 hover:bg-rose-600 text-white font-semibold py-3 px-8 rounded-full shadow-md transition duration-300">Explore</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Schedule Section (Placeholder) -->
    <section id="schedule" class="container mx-auto px-6 py-20">
        <h2 class="text-4xl font-light text-rose-600 mb-14 text-center">Our Harmonious Schedule</h2>
        <div class="bg-white rounded-2xl shadow-xl p-10 border border-rose-100">
            <p class="text-lg text-gray-700 text-center mb-8">
                Our meticulously crafted class schedule will be unveiled here very soon! Please revisit this space for timely updates on class times, esteemed instructors, and exclusive workshops designed just for you.
            </p>
            <div class="flex justify-center">
                <img src="https://placehold.co/900x500/fff0f5/e0a0b0?text=Coming+Soon:+Elegant+Schedule" alt="Schedule Placeholder" class="rounded-xl shadow-lg max-w-full h-auto">
            </div>
            <p class="text-center text-gray-600 mt-8">
                In the interim, please feel empowered to <a href="#contact" class="text-rose-600 hover:underline font-medium">contact our studio</a> for any inquiries.
            </p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-rose-50 py-20 rounded-t-3xl mx-auto shadow-inner">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-light text-rose-600 mb-14 text-center">Connect with Yogal Space</h2>
            <div class="flex flex-col md:flex-row justify-center items-center space-y-12 md:space-y-0 md:space-x-20">
                <!-- Contact Info -->
                <div class="bg-white rounded-2xl shadow-xl p-10 w-full md:w-1/2 lg:w-1/3 border border-rose-100">
                    <h3 class="text-2xl font-semibold text-rose-600 mb-8">Reach Out to Us</h3>
                    <p class="text-gray-700 mb-6 flex items-center">
                        <svg class="w-7 h-7 mr-4 text-rose-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.828 0L6.343 16.657a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                        2 Dunnings Bridge Road, Bootle, L30 6AT
                    </p>
                    <p class="text-gray-700 mb-6 flex items-center">
                        <svg class="w-7 h-7 mr-4 text-rose-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684L10.25 8.252a1 1 0 00.99 1.127l1.127.99a1 1 0 001.127.99l3.498-.718a1 1 0 01.684.948V19a2 2 0 01-2 2H5a2 2 0 01-2-2V5z"></path></svg>
                        +44 151 123 4567
                    </p>
                    <p class="text-gray-700 mb-6 flex items-center">
                        <svg class="w-7 h-7 mr-4 text-rose-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        info@yogalspace.com
                    </p>
                    <a href="https://www.instagram.com/yogalspace?igsh=MTZsMTgzNmNsY2UyNA==" target="_blank" class="text-rose-600 hover:underline font-medium flex items-center mt-6">
                        <svg class="w-7 h-7 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 2c-2.716 0-3.056.012-4.12.06c-1.064.049-1.79.217-2.427.464a4.108 4.108 0 00-1.488.971c-.559.559-.971 1.284-1.464 2.427-.049 1.064-.06 1.404-.06 4.12s.012 3.056.06 4.12c.049 1.064.217 1.79.464 2.427a4.108 4.108 0 00.971 1.488c.559.559 1.284.971 2.427 1.464.06.028.12.057.18.084.637.247 1.363.415 2.427.464 1.064.049 1.404.06 4.12.06s3.056-.012 4.12-.06c1.064-.049 1.79-.217 2.427-.464a4.108 4.108 0 001.488-.971c.559-.559.971-1.284 1.464-2.427.049-1.064.06-1.404.06-4.12s-.012-3.056-.06-4.12c-.049-1.064-.217-1.79-.464-2.427a4.108 4.108 0 00-.971-1.488c-.559-.559-1.284-.971-2.427-1.464-.06-.028-.12-.057-.18-.084-1.064-.049-1.404-.06-4.12-.06zM12 6.5c2.76 0 5 2.24 5 5s-2.24 5-5 5-5-2.24-5-5 2.24-5 5-5zm0 1.5c-1.93 0-3.5 1.57-3.5 3.5s1.57 3.5 3.5 3.5 3.5-1.57 3.5-3.5-1.57-3.5-3.5-3.5zm6.5-5.5c-.828 0-1.5.672-1.5 1.5s.672 1.5 1.5 1.5 1.5-.672 1.5-1.5-.672-1.5-1.5-1.5z"></path>
                        </svg>
                        Follow us on Instagram
                    </a>
                    <!-- Simple map placeholder image -->
                    <div class="mt-8 rounded-xl overflow-hidden shadow-md">
                        <img src="https://placehold.co/450x300/fce7f3/db2777?text=Map+Location" alt="Map Location" class="w-full h-auto">
                    </div>
                </div>

                <!-- Contact Form -->
                <div class="bg-white rounded-2xl shadow-xl p-10 w-full md:w-1/2 lg:w-1/3 border border-rose-100">
                    <h3 class="text-2xl font-semibold text-rose-600 mb-8">Send Us a Cherished Message</h3>
                    <form action="#" method="POST">
                        <div class="mb-6">
                            <label for="name" class="block text-gray-700 text-base font-medium mb-2">Your Name:</label>
                            <input type="text" id="name" name="name" class="shadow-sm appearance-none border border-gray-200 rounded-lg w-full py-3 px-4 text-gray-800 leading-tight focus:outline-none focus:ring-2 focus:ring-rose-200 focus:border-rose-300 transition duration-200" placeholder="Elegant Name" required>
                        </div>
                        <div class="mb-6">
                            <label for="email" class="block text-gray-700 text-base font-medium mb-2">Your Email:</label>
                            <input type="email" id="email" name="email" class="shadow-sm appearance-none border border-gray-200 rounded-lg w-full py-3 px-4 text-gray-800 leading-tight focus:outline-none focus:ring-2 focus:ring-rose-200 focus:border-rose-300 transition duration-200" placeholder="your.email@example.com" required>
                        </div>
                        <div class="mb-8">
                            <label for="message" class="block text-gray-700 text-base font-medium mb-2">Your Message:</label>
                            <textarea id="message" name="message" rows="6" class="shadow-sm appearance-none border border-gray-200 rounded-lg w-full py-3 px-4 text-gray-800 leading-tight focus:outline-none focus:ring-2 focus:ring-rose-200 focus:border-rose-300 resize-none transition duration-200" placeholder="Share your thoughts..."></textarea>
                        </div>
                        <div class="flex justify-center">
                            <button type="submit" class="bg-rose-500 hover:bg-rose-600 text-white font-semibold py-4 px-10 rounded-full shadow-lg transition duration-300 ease-in-out transform hover:scale-105 hover:shadow-xl focus:outline-none focus:ring-4 focus:ring-rose-300 focus:ring-opacity-75">Send Message</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-300 py-10 rounded-b-3xl">
        <div class="container mx-auto px-6 text-center text-sm">
            <p>&copy; 2025 Yogal Space. All rights reserved.</p>
            <p class="mt-3">Crafted with <span class="text-red-400">&hearts;</span> for your well-being.</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });

                // Close mobile menu if open
                const mobileMenu = document.getElementById('mobile-menu');
                if (!mobileMenu.classList.contains('hidden')) {
                    mobileMenu.classList.add('hidden');
                }
            });
        });

        // Toggle mobile menu visibility
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
