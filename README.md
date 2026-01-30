# Tailwindscss
Nope
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Service Solutions | 2026</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .gradient-text {
            background: linear-gradient(90deg, #4F46E5, #06B6D4);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 font-sans">

    <nav class="flex justify-between items-center p-6 max-w-7xl mx-auto">
        <div class="text-2xl font-bold tracking-tight">SOLVE<span class="text-indigo-600">IT.</span></div>
        <div class="hidden md:flex space-x-8 font-medium">
            <a href="#services" class="hover:text-indigo-600 transition">Services</a>
            <a href="#portfolio" class="hover:text-indigo-600 transition">Work</a>
            <a href="#contact" class="bg-indigo-600 text-white px-5 py-2 rounded-full hover:bg-indigo-700 transition">Get Started</a>
        </div>
    </nav>

    <header class="py-20 px-6 text-center max-w-4xl mx-auto">
        <h1 class="text-5xl md:text-7xl font-extrabold mb-6 leading-tight">
            I help businesses <span class="gradient-text">scale faster</span> through expert service.
        </h1>
        <p class="text-xl text-slate-600 mb-10">
            Stop wasting time on tasks that aren't your specialty. I provide high-end, reliable solutions tailored to your specific goals.
        </p>
        <div class="flex flex-col md:flex-row justify-center gap-4">
            <a href="#contact" class="bg-slate-900 text-white px-8 py-4 rounded-xl font-bold text-lg hover:bg-slate-800 transition">Book a Consultation</a>
            <a href="#services" class="bg-white border border-slate-200 px-8 py-4 rounded-xl font-bold text-lg hover:bg-slate-50 transition">View Services</a>
        </div>
    </header>

    <section id="services" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-3xl font-bold mb-12 text-center">My Specialized Services</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="p-8 border border-slate-100 rounded-2xl bg-slate-50 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-indigo-100 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Strategic Consulting</h3>
                    <p class="text-slate-600">Deep dive into your business model to find hidden growth opportunities and efficiency gaps.</p>
                </div>
                <div class="p-8 border border-slate-100 rounded-2xl bg-slate-50 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-indigo-100 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 21l3-1 3 1-.75-4M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Digital Implementation</h3>
                    <p class="text-slate-600">Technical setup and management of your digital infrastructure, from CRMs to AI workflows.</p>
                </div>
                <div class="p-8 border border-slate-100 rounded-2xl bg-slate-50 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-indigo-100 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Content Authority</h3>
                    <p class="text-slate-600">I build your personal brand or company voice through high-quality, research-backed content.</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-slate-900 text-white py-20 px-6">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-4xl font-bold mb-6">Ready to work together?</h2>
            <p class="text-slate-400 mb-10 text-lg">I am currently accepting 2 new clients for February 2026.</p>
            <a href="mailto:your-email@example.com" class="inline-block bg-indigo-600 px-10 py-4 rounded-full font-bold text-xl hover:bg-indigo-500 transition">Email Me Now</a>
            <div class="mt-12 text-sm text-slate-500">
                &copy; 2026 Your Service Name. All rights reserved.
            </div>
        </div>
    </footer>

</body>
</html>
