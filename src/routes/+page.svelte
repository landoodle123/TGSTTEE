<script lang="js">

</script>

<svelte:head>
    <title>TGSTTEE</title>
    <meta name="description" content="A SvelteKit app for TGSTTEE" />
    <link rel="icon" href="/favicon.ico" />
</svelte:head>

<div class="maingbg">
    <h1>Welcome to TGSTTEE!</h1>
    <p>This is an in-development study tool focused on helping students prepare for exams.</p>
</div>

<style>
    :global(html, body) {
        margin: 0;
        min-height: 100%;
    }

    .maingbg {
        color: #fff;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: flex-start;
        padding-top: 2rem;
        font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        width: 100%;
        min-height: 100vh;
        --s: 200px; /* control the size */
        --c1: #1d1d1d;
        --c2: #4e4f51;
        --c3: #3c3c3c;

        background: repeating-conic-gradient(
                from 30deg,
                #0000 0 120deg,
                var(--c3) 0 180deg
            )
            calc(0.5 * var(--s)) calc(0.5 * var(--s) * 0.577),
            repeating-conic-gradient(
                from 30deg,
                var(--c1) 0 60deg,
                var(--c2) 0 120deg,
                var(--c3) 0 180deg
            );
        background-size: var(--s) calc(var(--s) * 0.577);
    }
</style>