<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WWW.FAZA.COM</title>
</head>
<body>
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FAZA - Premium Clothing Brand</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            scroll-behavior: smooth;
        }
        .hero-bg {
            background: linear-gradient(135deg, #1f2937 0%, #374151 100%);
        }
        .product-card:hover {
            transform: translateY(-5px);
            transition: transform 0.3s ease;
        }
        .fade-in {
            opacity: 0;
            animation: fadeInUp 1s ease forwards;
        }
        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">
    <!-- Header -->
    <header class="bg-black text-white shadow-lg">
        <div class="container mx-auto flex justify-between items-center py-4 px-6">
            <h1 class="text-3xl font-bold">FAZA</h1>
            <nav>
                <ul class="flex space-x-6">
                    <li><a href="#home" class="hover:text-red-500 transition">Home</a></li>
                    <li><a href="#products" class="hover:text-red-500 transition">Products</a></li>
                    <li><a href="#about" class="hover:text-red-500 transition">About</a></li>
                    <li><a href="#contact" class="hover:text-red-500 transition">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero-bg relative text-white h-screen flex items-center justify-center">
        <div class="absolute inset-0">
            <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/80438cae-8928-4ed5-b756-b2bce60a247b.png" alt="Elegant fashion runway show in a chic urban loft with models wearing trendy dresses, high-fashion hairstyles, dramatic lighting, and a mix of neutral and vibrant colors reflecting modern minimalist style" class="w-full h-full object-cover">
            <div class="absolute inset-0 bg-black bg-opacity-50"></div>
        </div>
        <div class="relative z-10 text-center px-6 fade-in">
            <h2 class="text-5xl md:text-7xl font-extrabold mb-4">Elevate Your Style</h2>
            <p class="text-xl md:text-2xl mb-8">Discover premium clothing that blends comfort and fashion.</p>
            <a href="#products" class="bg-red-500 hover:bg-red-600 text-white py-3 px-8 rounded-full font-semibold transition">Explore Our Collection</a>
        </div>
    </section>

    <!-- Featured Products -->
    <section id="products" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h3 class="text-4xl font-bold text-center mb-12">Featured Products</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="product-card bg-gray-200 p-4 rounded-lg shadow-md overflow-hidden">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/6138adea-69d3-4b1e-8328-bce984a271e8.png" alt="Stylish black leather jacket for men with sleek zipper details in a front view on a mannequin, photographed in a studio with soft lighting and a white background emphasizing the premium material and contemporary design" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h4 class="text-xl font-semibold">Urban Leather Jacket</h4>
                        <p class="text-gray-600 mt-2">$149.99</p>
                    </div>
                </div>
                <div class="product-card bg-gray-200 p-4 rounded-lg shadow-md overflow-hidden">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/d1608cdc-25ad-4e2d-815c-cd75c762a380.png" alt="Elegant red dress for women with flowing skirt and intricate lace patterns in a full-length side view on a model, captured in a trendy boutique setting with warm amber lighting highlighting the luxurious fabric and feminine silhouette" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h4 class="text-xl font-semibold">Chic Red Dress</h4>
                        <p class="text-gray-600 mt-2">$99.99</p>
                    </div>
                </div>
                <div class="product-card bg-gray-200 p-4 rounded-lg shadow-md overflow-hidden">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/74b00d93-67e1-4861-8ba2-f08de66ad86a.png" alt="Casual denim jeans for unisex with distressed patches and straight fit in a hanging display against a brick wall background, photographed in daylight to showcase the durable fabric and trendy worn-in look" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h4 class="text-xl font-semibold">Distressed Denim Jeans</h4>
                        <p class="text-gray-600 mt-2">$79.99</p>
                    </div>
                </div>
                <div class="product-card bg-gray-200 p-4 rounded-lg shadow-md overflow-hidden">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/7256348d-239e-4d80-b2f5-42b0d0c3b271.png" alt="Minimalist white t-shirt for women with subtle graphic print in a close-up torso view, styled against a minimalist room with neutral tones and soft shadows to accentuate the crisp cotton material and versatile design" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h4 class="text-xl font-semibold">Graphic T-Shirt</h4>
                        <p class="text-gray-600 mt-2">$29.99</p>
                    </div>
                </div>
                <div class="product-card bg-gray-200 p-4 rounded-lg shadow-md overflow-hidden">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/ae2390e9-1da3-4dfe-ab69-cec203498d55.png" alt="Classic blazer for men in navy blue with padded shoulders and gold buttons in a professional pose on a model, captured in an office-like environment with dramatic lighting to emphasize the tailored fit and sophisticated style" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h4 class="text-xl font-semibold">Blazer Set</h4>
                        <p class="text-gray-600 mt-2">$129.99</p>
                    </div>
                </div>
                <div class="product-card bg-gray-200 p-4 rounded-lg shadow-md overflow-hidden">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/73ad26ac-9232-43a3-b5d0-41baf692c753.png" alt="Seasonal wool coat for women in beige with belt detail in an outdoor park setting during autumn, photographed to show the warm texture of the fabric, layered look, and earthy color palette perfect for transitioning weather" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h4 class="text-xl font-semibold">Wool Coat</h4>
                        <p class="text-gray-600 mt-2">$189.99</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-8 md:mb-0">
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/87e745fa-7d04-4890-bd50-f35753fd6395.png" alt="Team of diverse fashion designers collaborating in a vibrant design studio with fabric swatches, sketches, and sewing machines on wooden tables, photographed in bright natural light with a creative and inclusive atmosphere" class="rounded-lg shadow-lg">
            </div>
            <div class="md:w-1/2 md:pl-12">
                <h3 class="text-4xl font-bold mb-6">About FAZA</h3>
                <p class="text-lg text-gray-600 mb-6">At FAZA, we believe in timeless fashion that empowers individuals. Our brand combines quality craftsmanship with modern trends to deliver clothing that tells a story. Founded with a passion for style, we're dedicated to sustainable practices and innovative designs.</p>
                <p class="text-lg text-gray-600">From streetwear to formal attire, every piece is designed to make you feel confident and comfortable.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-black text-white">
        <div class="container mx-auto px-6 text-center">
            <h3 class="text-4xl font-bold mb-6">Get In Touch</h3>
            <p class="text-lg mb-8">Ready to transform your wardrobe? Contact us today.</p>
            <form class="max-w-lg mx-auto" onsubmit="alert('Thank you! We\'ll be in touch soon.'); return false;">
                <div class="mb-4">
                    <input type="text" placeholder="Your Name" class="w-full p-3 bg-gray-800 text-white rounded" required>
                </div>
                <div class="mb-4">
                    <input type="email" placeholder="Your Email" class="w-full p-3 bg-gray-800 text-white rounded" required>
                </div>
                <div class="mb-4">
                    <textarea placeholder="Your Message" rows="4" class="w-full p-3 bg-gray-800 text-white rounded" required></textarea>
                </div>
                <button type="submit" class="bg-red-500 hover:bg-red-600 text-white py-3 px-8 rounded-full font-semibold transition">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <p>© 2023 FAZA. All rights reserved.</p>
            <div class="mt-4">
                <a href="#" class="hover:text-red-500 mr-4">Facebook</a>
                <a href="#" class="hover:text-red-500 mr-4">Instagram</a>
                <a href="#" class="hover:text-red-500">Twitter</a>
            </div>
        </div>
    </footer>

    <script>
        // Simple animation on scroll for products
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('fade-in');
                }
            });
        });
        document.querySelectorAll('.product-card').forEach(card => observer.observe(card));
    </script>
</body>
</html>
</content>
</create_file>
</body>
</html>
