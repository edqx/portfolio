<svelte:head>
    <title>Ryuujin | weakey.es</title>
</svelte:head>

<div class="flex flex-col gap-4">
    <span class="text-2xl">Projects</span>
    <h1 class="text-5xl">Ryuujin</h1>
    <span class="text-1xl text-slate-600">2020-2021</span>

    <p>
        One of my most humble and private projects, Ryuujin was a fully-fledged custom desktop client for the <a href="https://www.teamsatchel.com/products/smhw.html">SMHW</a>
        platform used by my teachers in high school.
        <br><br>
        It was built on top of a previous library I made, <a href="https://github.com/edqx/node-smhw">node-smhw</a>, which allowed you to interact
        with the undocumented HTTP REST API. It had several extra features in order to query and aggregate data in certain ways, such as processing
        other students' submission statuses to find the percentage that homeworks got submitted.
        <br><br>
        While mostly a project for fun, and it included some pretty serious security-breaking featurtes such as reading other students' private comments
        and submission responses. Unfortunately I was unable to find a way to get the actual submissions submitted by other users.
        <br><br>
        There are 2 versions of Ryuujin, the first one written in HTML and JS — where I quickly learned it was not feasible to write scalable apps with
        <em>just</em> HTML5. The second one is written in Svelte, making it possibly my first real project which used it.
        <br><br>
        <a href="https://github.com/edqx/Ryujin-SMHW">GitHub repo for v1</a><br>
        <a href="https://github.com/edqx/Ryujin-SMHW-v2">GitHub repo for v2</a> 
    </p>
</div>