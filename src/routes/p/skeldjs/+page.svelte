<svelte:head>
    <title>SkeldJS | weakey.es</title>
</svelte:head>

<div class="flex flex-col gap-4">
    <span class="text-2xl">Projects</span>
    <h1 class="text-5xl">SkeldJS</h1>

    <p>
        SkeldJS was my largest project in terms of scope, and has possibly taught me the most out of any of them. It was a
        multi-package ecosystem of tools and libraries related to the game Among Us, implementing the game client code and
        networking in JavaScript for Node.JS, allowing you to write custom programmable clients or entire real-time servers for
        the game.
        <br><br>
        It was my first experience using <a href="/l/js">TypeScript</a> as well as being my first project made for a game,
        and gave me a great deal of knowledge about how game protocols generally work, and the DTLS transport protocol, which
        I made an implementation for.
        <br><br>
        A great application and real world use-case for SkeldJS can be both found in Hindenburg below, my work on
        <a href="/p/aup">AUProximity</a> and my re-creation of the <a href="/p/pgg">Polus.GG server, Mouthwash.GG</a>.
        <br><br>
        I was a part of lots of communities for SkeldJS, and was the basis for lots of other experiments and smaller projects.
        <br><br>

        <a href="https://skeld.js.org">SkeldJS documentation</a>
        <br>
        <a href="https://github.com/skeldjs/skeldjs">GitHub monorepo</a>
    </p>
    
    <h2 class="text-4xl">Hindenburg</h2>
    <p>
        As a step up from SkeldJS, Hindenburg was built on-top as a modern, extensible game server for Among Us. It intended
        to provide an alternative to <a href="https://github.com/impostor/Impostor">Impostor</a>.
        <br><br>
        Hindenburg was a good experience for providing direct and active feedback and development for users, where updates were
        urgent. I also had experience building a load balancer and GUI for Hindenburg, allowing me to connect it to other
        pieces of software, such as <a href="https://redis.io">Redis</a>
        <br><br>
        It powered the <a href="/p/pgg">Mouthwash.GG</a> game server, and many other people's private servers for modding and playing
        with friends.
        <br><br>
        
        <a href="https://skeldjs.github.io/Hindenburg">Hindenburg documentation</a>
        <br>
        <a href="https://github.com/skeldjs/hindenburg">GitHub repo</a>
    </p>

    <h2 class="text-4xl">Pen-testing</h2>
    <p>
        SkeldJS has also been, for me, a brief introduction into pen testing and finding security-critical bugs in software. I compiled
        lists of several crash-related and hack exploits and reported them directly to the lead developer on the Innersloth team.
    </p>
</div>