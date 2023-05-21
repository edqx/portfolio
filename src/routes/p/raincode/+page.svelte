<svelte:head>
    <title>Raincode | weakey.es</title>
</svelte:head>

<div class="flex flex-col gap-4">
    <span class="text-2xl">Projects</span>
    <h1 class="text-5xl">Raincode</h1>
    <span class="text-1xl text-slate-600">2023-present</span>

    <p>
        Raincode is a social and game platform for programmers to develop their skills through a philosophy of
        competitive collaboration; where users compete to solve problems related to programming and reason through
        good, performant solutions.
        <br><br>
        I worked on it for an assignment for college, alongside a <em>1700 page</em> report describing
        the analysis, design, development and evaluation stages of the project.
        <br><br>
        It was my first experience designing a system on the back-end that could be easily scaled and entirely modular.
        The front-end was my first experience creating a social atmosphere and understandable, clean UI for ordinary users.
        <br><br>
        I solved many technical challenges for the site, the most proud of which is the fact that the whole site is
        real-time, meaning that updates to lobbies, user profiles, notifications, etc. are broadcasted immediately to
        users on the site.
        <br><br>
        Additionally, I had to consider security issues when it came to executing code, using virtual sandbox environments
        to execute code. There were a lot of challenges here as well, for example figuring out a method that could allow
        the server to communicate with the environment in a secure way to check user's solutions.
        <br><br>
        The site was written in <a href="/l/js">TypeScript</a> and <a href="/t/svelte">Svelte</a> and used
        <a href="https://www.postgresql.org/">Postgres</a> and <a href="https://redis.io/">Redis</a> for the backend.
        <br><br>
        It was also my first time using a remote development environment, which allowed me to work on the project in the
        same way at home, at college and on my laptop while away. Initially I started using <a href="https://github.com/features/codespaces">Codespaces</a>,
        but due to cost concerns I moved to a self-hosted solution with <a href="https://coder.com/">Coder</a>.
        <br><br>
        <a href="https://raincode.midlight.studio">Raincode site</a>
    </p>
</div>