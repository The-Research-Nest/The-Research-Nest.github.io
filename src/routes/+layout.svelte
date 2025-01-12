<script lang="ts">
    import 'altcss/alt.min.css';
    let { children } = $props();
</script>

<svelte:head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Research Nest - Research Community Platform</title>
    
    <!-- Primary Meta Tags -->
    <meta name="title" content="The Research Nest - Research Community Platform">
    <meta name="description" content="The Research Nest is a community platform for researchers, academics, and knowledge enthusiasts to share insights, collaborate, and explore research topics.">
    <meta name="keywords" content="research, academic writing, research community, academic collaboration, research platform">
    <meta name="author" content="The Research Nest">
    <meta name="robots" content="index, follow">
    
    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://the-research-nest.github.io/">
    <meta property="og:title" content="The Research Nest - Research Community Platform">
    <meta property="og:description" content="The Research Nest is a community platform for researchers, academics, and knowledge enthusiasts to share insights, collaborate, and explore research topics.">
    <!-- <meta property="og:image" content="[Your OG Image URL]"> -->

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content="https://the-research-nest.github.io/">
    <meta property="twitter:title" content="The Research Nest - Research Community Platform">
    <meta property="twitter:description" content="The Research Nest is a community platform for researchers, academics, and knowledge enthusiasts to share insights, collaborate, and explore research topics.">
    <!-- <meta property="twitter:image" content="[Your Twitter Card Image URL]"> -->

    <!-- Favicon -->
    <!-- <link rel="icon" type="image/x-icon" href="/favicon.ico"> -->
    <link rel="canonical" href="https://the-research-nest.github.io/">
</svelte:head>

<body>
<header>
    <h2>The Research Nest</h2>
    <nav>
        <details>
            <summary><p>Menu</p></summary>
            <div>
                <p><a href="https://medium.com/the-research-nest/trn-guest-blogging-2817c4ca31d3" target="_blank" rel="noopener noreferrer">
                    Write
                </a></p>
                <p><a href="https://medium.com/the-research-nest" target="_blank" rel="noopener noreferrer">
                    Medium
                </a></p>
                <p><a href="https://www.youtube.com/@theresearchnest" target="_blank" rel="noopener noreferrer">
                    YouTube
                </a></p>
            </div>
        </details>
        <div>
            <p><a href="https://medium.com/the-research-nest/trn-guest-blogging-2817c4ca31d3" target="_blank" rel="noopener noreferrer">
                Write
            </a></p>
            <p><a href="https://medium.com/the-research-nest" target="_blank" rel="noopener noreferrer">
                Medium
            </a></p>
            <p><a href="https://www.youtube.com/@theresearchnest" target="_blank" rel="noopener noreferrer">
                YouTube
            </a></p>
        </div>
    </nav>
</header>
</body>

{@render children?.()}