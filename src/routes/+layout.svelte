<svelte:head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Research Nest</title>
    <meta charset="UTF-8">
    <script src="https://cdn.tailwindcss.com"></script>
</svelte:head>

<main class="min-h-screen bg-black text-gray-100">
    <!-- Header Section -->
    <header class="bg-black shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto py-4 px-4 sm:px-6 lg:px-8 flex items-center justify-between flex-col sm:flex-row sm:space-y-0 space-y-2">
            <h1 class="text-2xl font-bold text-yellow-500">The Research Nest</h1>
            <nav class="flex flex-col sm:flex-row space-y-2 sm:space-y-0 sm:space-x-6">
                <ul class="flex space-x-4 md:space-x-6 lg:space-x-8">
                    <li>
                        <a href="https://medium.com/the-research-nest/trn-guest-blogging-2817c4ca31d3" class="relative text-yellow-500 transition-all duration-300 after:content-[''] after:absolute after:w-0 after:h-0.5 after:bg-yellow-500 after:bottom-0.5 after:left-1/2 after:transition-width after:duration-300 hover:after:w-full hover:after:left-0">
                            Write With Us
                        </a>
                    </li>
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
                    <a href="https://twitter.com/research_nest" class="text-gray-400 hover:text-white transition-colors duration-300">Twitter</a>
                    <a href="https://linkedin.com/company/the-research-nest" class="text-gray-400 hover:text-white transition-colors duration-300">LinkedIn</a>
                </div>
            </div>
        </div>
    </footer>
</main>
