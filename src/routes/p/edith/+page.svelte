<svelte:head>
    <title>Edith | weakey.es</title>
</svelte:head>

<div class="flex flex-col gap-4">
    <span class="text-2xl">Projects</span>
    <h1 class="text-5xl">Edith</h1>

    <p>
        Edith is my largest project yet in terms of ambition and timescale. It's a story-driven RPG game made by me, the core
        developer and project manager, and a friend, the main artist and art director.
        <br><br>
        It was my first dive into a new tool <a href="/p/unity">Unity</a>, and has been a challenging architecture project,
        also being my first real <a href="/l/cs">C#</a> project.
        <br><br>
        Aside from a programming perspective, it has also taught me a lot about writing a coherent story, and planning out
        a project's future months and years in advance. It has been one of my only (primarily) creative-driven works, with
        the programming simply being a vehicle for the story.
    </p>
    
    <h2 class="text-4xl">Chronicle</h2>
    <p>
        Talking about Edith wouldn't be complete without talking about Chronicle, an app I am making along-side Edith, taking control
        of conversations between characters, interactions with objects, character portraits, timeline/screenplay and save data. It's
        entirely friendly for non-developers, making it a good tool for development on Edith; working with an artist who otherwise
        would have no other way to write dialogues and interactions directly into the game.
        <br><br>
        I developed integration with <a href="/t/unity">Unity</a> so that the Chronicle files are recognised as ScriptableObjects and assets,
        meaning they can be referenced directly and bundled into the game.
        <br><br>
        Chronicle was a great experience to learn about user interfaces, file-system handling and complex web-based controls so that it
        feels like a native app. It's written in <a href="/l/js">TypeScript</a> and <a href="/t/svelte">Svelte</a>, and built ontop of 
        <a href="https://tauri.app">Tauri</a>. I also used <a href="https://tailwindcss.com">TailwindCSS</a> for the first time.
        <br><br>
        <img alt="a screenshot showing the Chronicle dashboard" src="/chronicle-screenshot.png">
    </p>
</div>