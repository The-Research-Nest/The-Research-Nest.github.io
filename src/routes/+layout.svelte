<svelte:head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Research Nest</title>
    <meta charset="UTF-8">
    <script src="https://cdn.tailwindcss.com"></script>
</svelte:head>

<main class="min-h-screen bg-black text-gray-100">
    <!-- Header Section -->
    <header class="bg-black shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto py-4 px-4 sm:px-6 lg:px-8 flex items-center justify-between header-content">
            <h1 class="text-2xl font-bold">The Research Nest</h1>
            <nav>
                <ul class="flex space-x-4 md:space-x-6 lg:space-x-8 nav-links">
                    <li><a href="https://medium.com/the-research-nest/trn-guest-blogging-2817c4ca31d3" class="header-link smooth-transition">Write With Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <slot/>

    <!-- Footer Section -->
    <footer class="bg-black shadow-md mt-12 py-6">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col sm:flex-row justify-between items-center">
                <div class="text-sm text-gray-400 mb-4 sm:mb-0">&copy; 2024 The Research Nest. All rights reserved.</div>
                <div class="flex space-x-4">
                    <a href="https://twitter.com/research_nest" class="text-gray-400 hover:text-white footer-link">Twitter</a>
                    <a href="https://linkedin.com/company/the-research-nest" class="text-gray-400 hover:text-white footer-link">LinkedIn</a>
                </div>
            </div>
        </div>
    </footer>
</main>

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

    :global(.fade-in) {
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
    :global(.heading) {
        color: #ffcc00;
    }

    /* Responsive adjustments */
    .header-content {
        flex-direction: column;
        align-items: center;
    }

    .header-content nav {
        margin-top: 8px;
    }

    .nav-links {
        flex-direction: column;
        gap: 10px;
    }

    @media (min-width: 640px) {
        .header-content {
            flex-direction: row;
            justify-content: space-between;
        }

        .nav-links {
            flex-direction: row;
            gap: 20px;
        }
    }
</style>