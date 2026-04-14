# hussqin-
anything
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Centrix Construction Pvt Ltd - Building Excellence</title>
    <meta name="description" content="Leading construction company in India. Residential, commercial, infrastructure projects across Delhi NCR, Mumbai. 50+ completed projects.">
    
    <!-- Open Graph / SEO -->
    <meta property="og:title" content="Centrix Construction - Premium Construction Services">
    <meta property="og:description" content="Building dreams with precision across India">
    <meta property="og:image" content="images/hero.jpg">
    <meta property="og:url" content="https://www.centrixconstructionprivatelimited.com/">
    
    <!-- Schema.org JSON-LD -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "ConstructionCompany",
        "name": "Centrix Construction Private Limited",
        "url": "https://www.centrixconstructionprivatelimited.com/",
        "logo": "images/logo.png",
        "address": {
            "@type": "PostalAddress",
            "addressLocality": "Delhi NCR",
            "addressCountry": "IN"
        },
        "telephone": "+91-XXXXXXXXXX"
    }
    </script>
    
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link rel="stylesheet" href="css/styles.css">
</head>
<body class="font-sans bg-gray-50 text-gray-900">
    
    <!-- Navigation -->
    <nav class="fixed w-full bg-white shadow-lg z-50 transition-all duration-300" id="nav">
        <div class="container mx-auto px-6 py-4">
            <div class="flex justify-between items-center">
                <a href="#" class="text-2xl font-bold text-blue-600">Centrix</a>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="hover:text-blue-600 transition">Home</a>
                    <a href="#about" class="hover:text-blue-600 transition">About</a>
                    <a href="#services" class="hover:text-blue-600 transition">Services</a>
                    <a href="#projects" class="hover:text-blue-600 transition">Projects</a>
                    <a href="#contact" class="hover:text-blue-600 transition">Contact</a>
                </div>
                <button class="md:hidden" id="mobile-toggle">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-20 pb-24 bg-gradient-to-r from-blue-600 to-indigo-700 text-white overflow-hidden">
        <div class="container mx-auto px-6 text-center">
            <h1 class="text-5xl md:text-7xl font-bold mb-6 animate-fade-in">Building Excellence</h1>
            <p class="text-xl md:text-2xl mb-12 max-w-3xl mx-auto opacity-90">50+ Projects | 10+ Years | 1000+ Happy Clients</p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center mb-12">
                <a href="#contact" class="bg-white text-blue-600 px-8 py-4 rounded-full font-semibold hover:bg-gray-100 transition transform hover:scale-105">Get Quote</a>
                <a href="#projects" class="border-2 border-white px-8 py-4 rounded-full font-semibold hover:bg-white hover:text-blue-600 transition">View Projects</a>
            </div>
        </div>
    </section>

    <!-- Stats -->
    <section class="bg-white py-20">
        <div class="container mx-auto px-6 grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
            <div class="animate-count">
                <div class="text-4xl font-bold text-blue-600" data-target="50">0</div>
                <div>Projects</div>
            </div>
            <div class="animate-count">
                <div class="text-4xl font-bold text-green-600" data-target="10">0</div>
                <div>Years</div>
            </div>
            <div class="animate-count">
                <div class="text-4xl font-bold text-purple-600" data-target="1000">0</div>
                <div>Clients</div>
            </div>
            <div class="animate-count">
                <div class="text-4xl font-bold text-orange-600" data-target="500">0</div>
                <div>Workers</div>
            </div>
        </div>
    </section>

    <!-- Services -->
    <section id="services" class="py-24 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-20">
                <h2 class="text-4xl md:text-5xl font-bold mb-6">Our Services</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">End-to-end construction solutions with precision engineering</p>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-2xl shadow-xl hover:shadow-2xl transition transform hover:-translate-y-2">
                    <div class="w-20 h-20 bg-blue-100 rounded-2xl flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-building text-3xl text-blue-600"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">Residential</h3>
                    <p class="text-gray-600 mb-6">Luxury apartments, villas, and townhouses built to highest standards.</p>
                </div>
                <!-- Repeat for Commercial, Infrastructure -->
            </div>
        </div>
    </section>

    <!-- Contact CTA -->
    <section id="contact" class="py-24 bg-blue-600 text-white">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl md:text-5xl font-bold mb-6">Ready to Start Your Project?</h2>
            <p class="text-xl mb-12 opacity-90">Get your free consultation today</p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <input type="tel" placeholder="Your Phone Number" class="flex-1 px-6 py-4 rounded-full text-gray-900 focus:outline-none focus:ring-4 focus:ring-white">
                <button class="bg-white text-blue-600 px-8 py-4 rounded-full font-semibold hover:bg-gray-100 transition">Call Now</button>
            </div>
        </div>
    </section>

    <script src="js/main.js"></script>
</body>
</html>
