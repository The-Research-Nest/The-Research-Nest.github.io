<style>
    /* Custom styles for smooth transitions */
    .smooth-transition {
        transition: all 0.3s ease-in-out;
    }
    /* Footer link styles */
    .footer-link:hover {
        color: #fff;
    }

    /* Animation for content load */
    @keyframes fadeIn {
        0% {
            opacity: 0;
            transform: translateY(20px);
        }
        100% {
            opacity: 1;
            transform: translateY(0);
        }
    }

    .fade-in {
        animation: fadeIn 1s ease-in-out;
    }

    /* Header link styles */
    .header-link {
        position: relative;
        color: #ffcc00;
    }

    .header-link::after {
        content: '';
        position: absolute;
        width: 0;
        height: 2px;
        background-color: #ffcc00;
        bottom: -4px;
        left: 50%;
        transition: width 0.3s ease, left 0.3s ease;
    }

    .header-link:hover::after {
        width: 100%;
        left: 0;
    }

    /* Headings color */
    .heading {
        color: #ffcc00;
    }
</style>

<div class="min-h-screen bg-black text-gray-100">
    <!-- Header Section -->
    <header class="bg-black shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto py-4 px-4 sm:px-6 lg:px-8 flex items-center justify-between">
            <h1 class="text-2xl font-bold">The Research Nest</h1>
            <nav>
                <ul class="flex space-x-4 md:space-x-6 lg:space-x-8">
                    <li><a href="/about" class="header-link smooth-transition">About</a></li>
                    <li><a href="/initiatives" class="header-link smooth-transition">Research</a></li>
                    <li><a href="https://medium.com/the-research-nest/trn-guest-blogging-2817c4ca31d3" class="header-link smooth-transition">Write With Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Main Content Section -->
    <main>
        <div class="max-w-5xl mx-auto py-12 px-4 sm:px-6 lg:px-8 text-center fade-in">
            <!-- Introduction Section -->
            <section id="about" class="mb-12">
                <p class="text-2xl mx-auto">Independent Research and Applied Engineering in Computer Science and Technology.</p>
            </section>

            <!-- Research Sections -->
            <section class="mb-12 grid grid-cols-1 md:grid-cols-2 gap-6 fade-in">
                <!-- Applied Research Section -->
                <div id="applied-research" class="bg-stone-900 rounded-lg p-6 shadow-effect transition-transform duration-300 hover:scale-105">
                    <h2 class="text-2xl font-bold heading mb-4">🔬 Applied Research</h2>
                    <p class="text-gray-400">Solving real-world challenges with innovative solutions built on top of core research.</p>
                </div>
                <!-- Core Research Section -->
                <div id="core-research" class="bg-stone-900 rounded-lg p-6 shadow-effect transition-transform duration-300 hover:scale-105">
                    <h2 class="text-2xl font-bold heading mb-4">🔎 Core Research</h2>
                    <p class="text-gray-400">Relentlessly pursuing knowledge to uncover fundamental truths.</p>
                </div>
            </section>

            <!-- Initiatives Section -->
            <section id="initiatives" class="mb-12 fade-in">
                <h2 class="text-3xl font-semibold heading mb-4">🚀 Expanding Horizons with our Medium Publication</h2>
                <p class="text-lg mb-6">We’re ramping up our content game. Expect a lot more awesomeness.</p>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <div class="bg-stone-900 rounded-lg p-6 text-center shadow-effect transition-transform duration-300 hover:scale-105">
                        <h3 class="text-xl font-semibold heading mb-2">📝 Tutorials</h3>
                        <p class="text-gray-400">Crystal-clear, step-by-step guides to elevate your skills.</p>
                    </div>
                    <div class="bg-stone-900 rounded-lg p-6 text-center shadow-effect transition-transform duration-300 hover:scale-105">
                        <h3 class="text-xl font-semibold heading mb-2">💭 News Commentary</h3>
                        <p class="text-gray-400">Sharp insights and bold opinions from the frontlines.</p>
                    </div>
                    <div class="bg-stone-900 rounded-lg p-6 text-center shadow-effect transition-transform duration-300 hover:scale-105">
                        <h3 class="text-xl font-semibold heading mb-2">🎙️ Interviews</h3>
                        <p class="text-gray-400">Exclusive conversations with visionaries and trailblazers.</p>
                    </div>
                    <div class="bg-stone-900 rounded-lg p-6 text-center shadow-effect transition-transform duration-300 hover:scale-105">
                        <h3 class="text-xl font-semibold heading mb-2">🔑 Explained</h3>
                        <p class="text-gray-400">Simplifying complex ideas with ease.</p>
                    </div>
                    <div class="bg-stone-900 rounded-lg p-6 text-center shadow-effect transition-transform duration-300 hover:scale-105">
                        <h3 class="text-xl font-semibold heading mb-2">🏫 Bootcamps</h3>
                        <p class="text-gray-400">Quick, smart, hands-on learning experiences.</p>
                    </div>
                </div>
            </section>

            <!-- Contact Section -->
            <section id="contact" class="mb-12 fade-in">
                <h2 class="text-3xl font-semibold heading mb-4">Get in Touch</h2>
                <p class="text-lg">Questions or inquiries? Drop us a line at <a href="mailto:the.research.nest@gmail.com" class="text-blue-400 hover:underline">the.research.nest@gmail.com</a></p>
            </section>
        </div>
    </main>

    <!-- Footer Section -->
    <footer class="bg-black shadow-md mt-12 py-6">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center">
                <div class="text-sm text-gray-400">&copy; 2024 The Research Nest. All rights reserved.</div>
                <div class="flex space-x-4">
                    <a href="https://twitter.com/research_nest" class="text-gray-400 hover:text-white footer-link">Twitter</a>
                    <a href="https://linkedin.com/company/the-research-nest" class="text-gray-400 hover:text-white footer-link">LinkedIn</a>
                </div>
            </div>
        </div>
    </footer>
</div>
