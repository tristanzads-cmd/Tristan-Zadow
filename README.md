<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Professional Web Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-900 font-sans">

    <nav class="p-6 flex justify-between items-center bg-white shadow-sm">
        <h1 class="text-xl font-bold tracking-tight">DEV<span class="text-blue-600">STUDIO</span></h1>
        <div class="space-x-6">
            <a href="#work" class="hover:text-blue-600">Work</a>
            <a href="#services" class="hover:text-blue-600">Services</a>
            <a href="#contact" class="bg-blue-600 text-white px-5 py-2 rounded-lg hover:bg-blue-700">Hire Me</a>
        </div>
    </nav>

    <header class="py-20 px-6 text-center max-w-4xl mx-auto">
        <h2 class="text-5xl font-extrabold mb-6">I build websites that <span class="text-blue-600">grow your business.</span></h2>
        <p class="text-xl text-gray-600 mb-8">Clean code, modern design, and lightning-fast performance tailored to your brand.</p>
        <div class="flex justify-center gap-4">
            <a href="#contact" class="bg-blue-600 text-white px-8 py-3 rounded-md text-lg font-semibold">Start a Project</a>
            <a href="#work" class="border border-gray-300 px-8 py-3 rounded-md text-lg font-semibold hover:bg-gray-100">View My Work</a>
        </div>
    </header>

    <section id="work" class="py-16 bg-white">
        <div class="max-w-6xl mx-auto px-6">
            <h3 class="text-3xl font-bold mb-10 text-center">Recent Projects</h3>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="border rounded-xl overflow-hidden shadow-sm hover:shadow-md transition">
                    <div class="h-48 bg-gray-200"></div> <div class="p-4">
                        <h4 class="font-bold">E-Commerce Redesign</h4>
                        <p class="text-sm text-gray-500">Increased conversion by 20%</p>
                    </div>
                </div>
                <div class="border rounded-xl overflow-hidden shadow-sm hover:shadow-md transition">
                    <div class="h-48 bg-gray-200"></div>
                    <div class="p-4">
                        <h4 class="font-bold">SaaS Landing Page</h4>
                        <p class="text-sm text-gray-500">Built with React & Tailwind</p>
                    </div>
                </div>
                <div class="border rounded-xl overflow-hidden shadow-sm hover:shadow-md transition">
                    <div class="h-48 bg-gray-200"></div>
                    <div class="p-4">
                        <h4 class="font-bold">Personal Brand Site</h4>
                        <p class="text-sm text-gray-500">SEO Optimized Blog</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-20 bg-gray-900 text-white text-center">
        <h3 class="text-3xl font-bold mb-4">Ready to get started?</h3>
        <p class="mb-8 text-gray-400">Email me at <span class="text-blue-400 font-mono">hello@yourdomain.com</span></p>
        <button class="bg-blue-600 px-10 py-4 rounded-full font-bold hover:scale-105 transition transform">
            Get a Free Quote
        </button>
    </section>

</body>
</html>
