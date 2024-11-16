<script lang="ts">
    import 'altcss/alt.min.css';
    let { children } = $props();
</script>

<svelte:head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Research Nest</title>
    <meta charset="UTF-8">
</svelte:head>

<header>
    <h2>The Research Nest</h2>
    <nav>
        <details>
            <summary><p>Menu</p></summary>
            <div>
                <p><a href="https://medium.com/the-research-nest/trn-guest-blogging-2817c4ca31d3" target="_blank" rel="noopener noreferrer">
                    Write for Us
                </a></p>
                <p><a href="./docs/index.html" target="_blank" rel="noopener noreferrer">
                    Medium
                </a></p>
                <p><a href="https://github.com/aditya-xq/altcss" target="_blank" rel="noopener noreferrer">
                    YouTube
                </a></p>
            </div>
        </details>
        <div>
            <p><a href="https://medium.com/the-research-nest/trn-guest-blogging-2817c4ca31d3" target="_blank" rel="noopener noreferrer">
                Write for Us
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

{@render children?.()}