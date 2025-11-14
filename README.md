<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sustainable Tomorrow - Initiative Template</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Lucide Icons for aesthetic vectors -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        /* Custom styles and font import */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        :root {
            --color-primary: #10b981; /* Emerald 500 */
            --color-secondary: #059669; /* Emerald 600 */
        }
        body {
            font-family: 'Inter', sans-serif;
            color: #374151; /* Gray 700 */
        }
        .text-gradient {
            background-clip: text;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-image: linear-gradient(to right, #059669, #10b981);
        }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'primary': '#10b981',
                        'secondary': '#059669',
                        'bg-light': '#f0fdf4', /* Emerald 50 */
                        'bg-dark': '#064e3b', /* Emerald 900 */
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-white">

    <!-- Header & Navigation -->
    <header class="sticky top-0 z-50 bg-white/95 backdrop-blur-md shadow-lg rounded-b-xl">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo/Site Name -->
                <a href="#" class="flex items-center space-x-2 text-2xl font-bold text-secondary">
                    <i data-lucide="leaf" class="w-6 h-6 text-primary"></i>
                    <span>Recycling Future</span>
                </a>
                <!-- Desktop Navigation -->
                <nav class="hidden md:flex space-x-8">
                    <a href="#vision" class="text-gray-600 hover:text-primary transition duration-150 font-medium">Our Vision</a>
                    <a href="#focus" class="text-gray-600 hover:text-primary transition duration-150 font-medium">Focus Areas</a>
                    <a href="#impact" class="text-gray-600 hover:text-primary transition duration-150 font-medium">Our Impact</a>
                </nav>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-button" class="md:hidden p-2 text-gray-700 hover:text-primary focus:outline-none rounded-md transition duration-150">
                    <i data-lucide="menu" class="w-6 h-6"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Menu (Hidden by default) -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-xl">
            <nav class="pt-2 pb-3 space-y-1 px-2 sm:px-3">
                <a href="#vision" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:bg-bg-light hover:text-primary">Our Vision</a>
                <a href="#focus" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:bg-bg-light hover:text-primary">Focus Areas</a>
                <a href="#impact" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:bg-bg-light hover:text-primary">Our Impact</a>
            </nav>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="vision" class="py-16 md:py-24 bg-bg-light">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight mb-4">
                   Recycling future
                    <span class="text-gradient">EDI group project. Egor , Davis , Illia</span>
                </h1>
                <p class="mt-4 text-xl text-gray-500 max-w-3xl mx-auto">
                    The issue our group is aiming to tackle is the amount of waste products from the increasing popularity of 3D printers .
                    Due to the large increase in the popularity of 3D printers , which cause a major increase in the amount of waste coming from them.

                </p>
                <div class="mt-8 flex justify-center space-x-4">
                    <a href="#focus" class="px-8 py-3 border border-transparent text-base font-medium rounded-full text-white bg-primary hover:bg-secondary md:py-4 md:text-lg md:px-10 shadow-lg transform hover:scale-[1.02] transition duration-300">
                        Explore Our Strategy
                    </a>
                    <a href="#impact" class="px-8 py-3 text-base font-medium rounded-full text-primary bg-white border border-primary hover:bg-primary/10 md:py-4 md:text-lg md:px-10 shadow-md transition duration-300">
                        See Our Impact
                    </a>
                </div>
            </div>
        </section>

        <!-- Focus Areas Section -->
        <section id="focus" class="py-16 md:py-24 bg-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-3xl sm:text-4xl font-bold text-center mb-12">Our main objectives</h2>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
                    <!-- Card 1: Renewable Energy -->
                    <div class="bg-white p-6 rounded-2xl shadow-xl border border-gray-100 transform hover:shadow-2xl hover:scale-[1.02] transition duration-300">
                        <div class="p-3 inline-flex rounded-full bg-primary/10 text-primary mb-4">
                            <i data-lucide="zap" class="w-8 h-8"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3 text-gray-800">Recyclibng the waste</h3>
                        <p class="text-gray-500">
                            We will try to turn the waste products into the usefull materials that can be used in the everyday life . 
                        </p>
                        <img src="web/1.webp"><img>
                        <p>--------------------------------------------------------------------------------------</p>
                        <img src="web/R.jfif"><img>
                    </div>

                    <!-- Card 2: Waste Reduction -->
                    <div class="bg-white p-6 rounded-2xl shadow-xl border border-gray-100 transform hover:shadow-2xl hover:scale-[1.02] transition duration-300">
                        <div class="p-3 inline-flex rounded-full bg-primary/10 text-primary mb-4">
                            <i data-lucide="recycle" class="w-8 h-8"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3 text-gray-800">Help to the society</h3>
                        <p class="text-gray-500">
                            We want children to inherit a healthy planet. We’re determined to play our part in making that happen and there’s no time to waste. Climate change is affecting life on Earth for plants, animals and people. Each year, we receive hundreds of letters from children with great ideas about how we can make a difference in the world and help care for the environment. We want them to know that we are listening, and that we are working hard to play our part in building a sustainable future and a more inclusive world. ---- Quote from oficial Lego.com
                        </p>
                        <img src="web/L.jpg"><img>
                    </div>

                    <!-- Card 3: Water Stewardship -->
                    <div class="bg-white p-6 rounded-2xl shadow-xl border border-gray-100 transform hover:shadow-2xl hover:scale-[1.02] transition duration-300">
                        <div class="p-3 inline-flex rounded-full bg-primary/10 text-primary mb-4">
                            <i data-lucide="droplets" class="w-8 h-8"></i>
                        </div>

                        <h3 class="text-xl font-bold mb-3 text-gray-800">Inoventive 3D</h3>
                        <a href="https://www.inoventive3d.com/3D">https://www.inoventive3d.com/3D \</a>
                        <p class="text-gray-500">
                            Additive manufacturing is using recycled plastic as its raw material for many 3D Printing machines. This method is particularly suitable for brands wanting to make their supply chain more sustainable, especially in combination with 3D printing technology for production on an industrial scale. Compared to virgin material, the filament using recycled material has a lower carbon footprint. The product is also more durable and meets industry-specific requirements.
                        </p>
                        <img src="web/b.jpg"><img>
                    
                    </div>
                </div>
            </div>
        </section>

        <!-- Impact Metrics Section -->
        <section id="impact" class="py-16 md:py-24 bg-bg-light">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-12">
                    <span class="text-primary text-sm font-semibold uppercase tracking-wider">Other information</span>
                    <h2 class="mt-2 text-3xl sm:text-4xl font-bold text-gray-800">Expected results</h2>
                </div>

                <div class="grid grid-cols-2 lg:grid-cols-4 gap-8 text-center">
                    <!-- Metric 1: Carbon Reduction -->
                    <div class="p-6 bg-white rounded-xl shadow-lg border border-primary/20">
                        <p class="text-4xl sm:text-5xl font-extrabold text-primary" id="metric-co2">0</p>
                        <p class="mt-2 text-lg font-medium text-gray-600">Amount of plastic items saved per person daily </p>
                    </div>

                    <!-- Metric 2: Renewable Share -->
                    <div class="p-6 bg-white rounded-xl shadow-lg border border-primary/20">
                        <p class="text-4xl sm:text-5xl font-extrabold text-primary" id="metric-renewable">0</p>
                        <p class="mt-2 text-lg font-medium text-gray-600">Amount of plastic items saved per person daily with our compaign</p>
                    </div>

                    <!-- Metric 3: Waste Diversion -->
                    <div class="p-6 bg-white rounded-xl shadow-lg border border-primary/20">
                        <p class="text-4xl sm:text-5xl font-extrabold text-primary" id="metric-waste">0</p>
                        <p class="mt-2 text-lg font-medium text-gray-600">Amoount of plastic items wasted per person daily</p>
                    </div>

                    <!-- Metric 4: Community Projects -->
                    <div class="p-6 bg-white rounded-xl shadow-lg border border-primary/20">
                        <p class="text-4xl sm:text-5xl font-extrabold text-primary" id="metric-projects">0</p>
                        <p class="mt-2 text-lg font-medium text-gray-600">Amoount of plastic items wasted per person daily after our compaign</p>
                    </div>
                </div>

                <div class="mt-12 text-center max-w-xl mx-auto">
                    <p class="text-gray-500">Thank you</p>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-100">
        <div class="max-w-7xl mx-auto py-8 px-4 sm:px-6 lg:px-8">
            <div class="text-center text-gray-600">
                <p>&copy; 2025 Recycling future.</p>
                <div class="mt-2 space-x-4 text-sm">
                    <a href="#" class="hover:text-primary text-gray-500">Privacy Policy</a>
                    <a href="#" class="hover:text-primary text-gray-500">Terms of Use</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- JavaScript for Interactivity -->
    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // 1. Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            const icon = mobileMenuButton.querySelector('i');
            if (mobileMenu.classList.contains('hidden')) {
                icon.setAttribute('data-lucide', 'menu');
            } else {
                icon.setAttribute('data-lucide', 'x');
            }
            lucide.createIcons(); // Re-render icon
        });

        // Close mobile menu when a link is clicked
        mobileMenu.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                mobileMenuButton.querySelector('i').setAttribute('data-lucide', 'menu');
                lucide.createIcons();
            });
        });

        // 2. Simple Counter Animation for Metrics
        function animateCounter(id, finalValue, duration = 2000, isPercentage = false) {
            const element = document.getElementById(id);
            let startTimestamp = null;
            const step = (timestamp) => {
                if (!startTimestamp) startTimestamp = timestamp;
                const progress = Math.min((timestamp - startTimestamp) / duration, 1);
                
                let value = Math.floor(progress * finalValue);
                
                if (isPercentage) {
                    element.textContent = value + '%';
                } else {
                    element.textContent = value.toLocaleString();
                }

                if (progress < 1) {
                    window.requestAnimationFrame(step);
                }
            };
            window.requestAnimationFrame(step);
        }

        // Delay the animation until after the page loads
        window.onload = function() {
            // Set your desired final metric values here
            animateCounter('metric-co2', 6, 2500);
            animateCounter('metric-renewable', 10, 2000);
            animateCounter('metric-waste', 8, 2200);
            animateCounter('metric-projects', 2, 1800);
        };
    </script>
</body>
</html>
