<script>
    import "virtual:windi.css";

    import { afterNavigate, disableScrollHandling } from "$app/navigation";
    import { onMount } from "svelte";
    import "../app.css";
    import Click from "../icons/Click.svelte";

    onMount(() => {
        disableScrollHandling();
    });

    afterNavigate(() => {
        disableScrollHandling();
    });
</script>

<div class="py-32 px-8 pb-4 text-slate-800 font-semibold h-screen">
    <div class="flex flex-col gap-8 h-full">
        <div class="flex flex-col gap-8">
            <div class="flex flex-col">
                <span class="text-5xl sm:text-7xl">WEAKEYES</span>
                <span class="text-2xl">Full-stack developer</span>
            </div>
            <div class="flex flex-col">
                <a href="https://github.com/edqx">GITHUB</a>
                <a href="mailto:edward@midlight.studio">CONTACT</a>
            </div>
        </div>
        <div class="w-full h-32 mt-auto arrows">
        </div>
    </div>
    <div class="py-32 px-0 sm:px-16 flex flex-col gap-16">
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 auto-rows-auto gap-16 mb-16">
            <span class="text-2xl max-w-xs">Edward Smale</span>
            <span class="text-2xl max-w-xs">Based in <span class="whitespace-nowrap">North-West</span> England</span>
            <span class="text-2xl max-w-xs">7 years experience</span>
            <span class="text-2xl max-w-xs">Currently working on Edith&nbsp;@ <a href="https://midlight.studio" class="text-blue-800 hover:underline">midlight.studio</a></span>
        </div>
        <div class="flex-col flex lg:flex-row gap-8 lg:gap-16 items-center relative w-full">
            <div class="absolute -left-16 hidden items-center gap-2 learn-more sm:flex">
                <div class="rotate-90">
                    <Click/>
                </div>
                <span>Click to learn more</span>
            </div>
            <div class="flex flex-col self-start">
                <div class="flex flex-col gap-8 sm:gap-16">
                    <div class="flex flex-col">
                        <!-- TODO: Scroll on mobile to the content -->
                        <span class="text-4xl sm:text-7xl">LANGUAGES</span>
                        <a href="/l/js" class="text-slate-800 text-2xl">JavaScript</a>
                        <a href="/l/cs" class="text-slate-800 text-2xl">C#</a>
                        <a href="/l/cpp" class="text-slate-800 text-2xl">C++</a>
                    </div>
                    <div class="flex flex-col">
                        <span class="text-4xl sm:text-7xl">PRIMARY TOOLS</span>
                        <a href="/t/nodejs" class="text-slate-800 text-2xl">Node.js</a>
                        <a href="/t/svelte" class="text-slate-800 text-2xl">Svelte</a>
                        <a href="/t/mocha" class="text-slate-800 text-2xl">Mocha</a>
                        <a href="/t/unity" class="text-slate-800 text-2xl">Unity</a>
                        <a href="/t/git" class="text-slate-800 text-2xl">Git</a>
                    </div>
                    <div class="flex flex-col">
                        <span class="text-4xl sm:text-7xl">PROJECTS</span>
                        <a href="/p/edith" class="text-slate-800 text-2xl">Edith</a>
                        <a href="/p/skeldjs" class="text-slate-800 text-2xl">Skeld.JS</a>
                        <a href="/p/aup" class="text-slate-800 text-2xl">AUProximity</a>
                        <a href="/p/pgg" class="text-slate-800 text-2xl">Polus.GG</a>
                        <a href="/p/swagclan" class="text-slate-800 text-2xl">SwagClan</a>
                        <a href="/p/ryuujin" class="text-slate-800 text-2xl">Ryuujin</a>
                    </div>
                </div>
            </div>
            <div class="h-4 lg:h-auto lg:w-4 self-stretch bg-slate-800"></div>
            <div class="w-full lg:w-2/5 self-stretch">
                <slot />
            </div>
            <!--
            <div class="grid grid-rows-[repeat(16,_minmax(0,_1fr))] grid-cols-[repeat(16,_minmax(0,_1fr))] w-96 h-96">
                <div class="col-start-2 row-start-2 row-span-full bg-slate-800"></div>
                <div class="col-start-2 row-start-2 col-span-full bg-slate-800"></div>
                <div class="col-start-1 row-start-[-3] col-span-full bg-slate-800"></div>
                <div class="col-start-[-3] row-start-1 bg-slate-800" style="grid-row: 1 / -2;"></div>
            </div>
            -->
        </div>
    </div>
</div>

<style>
  .arrows {
      background-image: url(/arrow-down.png);
      background-repeat: repeat-x;
      background-size: 96px;
  }

  .learn-more {
      writing-mode: vertical-lr;
      transform: rotate(180deg);
  }
</style>