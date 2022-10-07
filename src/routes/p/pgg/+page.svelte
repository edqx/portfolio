<svelte:head>
    <title>Polus.GG | weakey.es</title>
</svelte:head>

<div class="flex flex-col gap-4">
    <span class="text-2xl">Projects</span>
    <h1 class="text-5xl">Polus.GG</h1>
    <span class="text-1xl text-slate-600">2021-2021</span>

    <p>
        Polus.GG was a very large mod and custom private server for Among Us, and was one of my first work experiences,
        especially with a decent sized team.
        <br><br>
        One of my best examples of working into an existing codebase, I was tasked with maintaining the biggest game mode
        on the platform, implementing user requests and working with artist.
        <br><br>
        Unfortunately the project was cut short due to multiple inevitable failures, as if it collapsed under its own weight.
        Mouthwash.GG was my successor project, written below.
    </p>
    
    <h2 class="text-4xl">Mouthwash.GG</h2>
    <p>
        As a personal project looking to improve of many of the wrong turns taken in the course of Polus.GG's development,
        I created Mouthwash.GG on top of <a href="/p/skeldjs">Hindenburg</a>. It implemented everything from the account system
        to the game server (including each game mode) to the content delivery server (for assets).
        <br><br>
        This is probably one the projects I'm most proud of, and it displays some of my best code and architecture style,
        as focusing on API-driven development was essential to creating the game modes and creating a seamless user experience.
        <br><br>
        Unfortunately this too was cut short, as Among Us released an update that would make it too much of a task for me to
        update the client-side code alone to support the new version.
        <br><br>
        Mouthwash.GG was also one of my best experiences with using a database like <a href="https://www.postgresql.org/">Postgres</a>.
        <br><br>
        <a href="https://github.com/edqx/MouthwashGG">GitHub repo</a>
    </p>
</div>