<script>
    import profile from "$lib/assets/profile.jpeg";
    import bieI from "$lib/assets/screenshots/IdeaEval/MacBook Pro-1710645010766.jpeg";
    import adI from "$lib/assets/screenshots/artisanDigital/MacBook Pro-1710645472106.jpeg";
    import cbI from "$lib/assets/screenshots/courtBooker/MacBook Pro-1710645852434.jpeg";
    import dnI from "$lib/assets/screenshots/doctorsNote/MacBook Pro-1710645621057.jpeg";
    import ppI from "$lib/assets/screenshots/petPortraits/MacBook Pro-1710645110975.jpeg";
    import rcI from "$lib/assets/screenshots/retroChat/MacBook Pro-1710645724410.jpeg";
    import cfI from "$lib/assets/screenshots/connectFour/MacBook Pro-1710646176347.jpeg";
</script> 

<body class="overflow-hidden bg-white dark:bg-zinc-800">
    <header class="absolute inset-x-0 top-8 z-10 sm:top-12 lg:top-20 xl:top-16">
        <div class="mx-auto max-w-4xl px-6 md:px-12">
            <div class="flex items-center justify-between">
                <div class="flex gap-4">
                    <a href="/">
                        <span class="sr-only">Justin Garner</span>
                        <img class="h-14 w-14 rounded-full object-cover" src={profile} alt="Justin Garner" width="400" height="400">
                    </a>
                    <nav>
                        <ul class="flex flex-col gap-1 divide-y divide-zinc-100 dark:divide-zinc-900">
                            <li>
                                <a href="/" class="text-sm tracking-wide text-zinc-700 hover:text-zinc-900 dark:text-zinc-300 dark:hover:text-white">Home</a>
                            </li>
                            <li>
                                <a href="/about" class="text-sm tracking-wide text-zinc-700 hover:text-zinc-900 dark:text-zinc-300 dark:hover:text-white">About me</a>
                            </li>
                        </ul>
                    </nav>
                </div>
                <button aria-label="switch theme" data-themeswitcher-target="switcher" class="switcher group relative flex h-9 w-9 rounded-md before:absolute before:inset-0 before:rounded-md before:bg-zinc-100 before:bg-gradient-to-b before:transition-transform before:duration-300 hover:before:scale-105 active:duration-75 active:before:scale-95 dark:before:bg-zinc-800">
                    <svg xmlns="http://www.w3.org/2000/svg" class="transistion relative m-auto hidden h-5 w-5 fill-zinc-700 duration-300 group-hover:rotate-180 group-hover:fill-yellow-400 dark:block dark:fill-zinc-300" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 2a1 1 0 011 1v1a1 1 0 11-2 0V3a1 1 0 011-1zm4 8a4 4 0 11-8 0 4 4 0 018 0zm-.464 4.95l.707.707a1 1 0 001.414-1.414l-.707-.707a1 1 0 00-1.414 1.414zm2.12-10.607a1 1 0 010 1.414l-.706.707a1 1 0 11-1.414-1.414l.707-.707a1 1 0 011.414 0zM17 11a1 1 0 100-2h-1a1 1 0 100 2h1zm-7 4a1 1 0 011 1v1a1 1 0 11-2 0v-1a1 1 0 011-1zM5.05 6.464A1 1 0 106.465 5.05l-.708-.707a1 1 0 00-1.414 1.414l.707.707zm1.414 8.486l-.707.707a1 1 0 01-1.414-1.414l.707-.707a1 1 0 011.414 1.414zM4 11a1 1 0 100-2H3a1 1 0 000 2h1z" clip-rule="evenodd"></path>
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" class="transistion relative m-auto h-5 w-5 fill-zinc-700 duration-300 group-hover:-rotate-90 group-hover:fill-zinc-900 dark:hidden" viewBox="0 0 20 20" fill="currentColor">
                        <path d="M17.293 13.293A8 8 0 016.707 2.707a8.001 8.001 0 1010.586 10.586z"></path>
                    </svg>
                </button>
            </div>
        </div>
    </header>
    <div aria-hidden="true" class="fixed inset-0 h-[200vh] origin-top scale-y-0 bg-gradient-to-b from-gray-100 from-80% to-transparent transition-transform duration-700 dark:scale-y-100 dark:from-zinc-950"></div>
    <main class="relative overflow-hidden pt-16 sm:pt-24 lg:pt-40 xl:pt-32">
        <section>
            <div class="mx-auto mb-16 max-w-4xl px-6 sm:pb-16 md:px-12">
                <div class="flex h-full flex-col justify-between">
                    <div>
                        <h1 class="mt-16 text-3xl font-semibold text-zinc-950 dark:text-white">Justin Garner</h1>
                        <p class="text-sm tracking-wide text-zinc-700 dark:text-zinc-300">Fullstack Developer</p>

                        <p class="my-12 text-sm text-zinc-700 dark:text-zinc-300 sm:w-2/3 xl:w-1/2">Hi, I'm Justin! I love building useful tech products. Let's chat, shoot me a message!</p>
                        <div class="flex items-center gap-4 divide-x divide-zinc-200 dark:divide-zinc-800">
                            <a href="mailto:justin@justingarner.dev" class="group inline-flex h-8 items-center gap-2.5 rounded-md bg-zinc-950 px-3 transition-all duration-500 dark:bg-zinc-800 dark:hover:bg-zinc-700">
                                <span class="text-sm tracking-wide text-white">Let's talk</span>
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="h-3 w-3 text-white/60 transition duration-300 group-hover:rotate-45 group-hover:text-white">
                                    <path fill-rule="evenodd" d="M8.25 3.75H19.5a.75.75 0 01.75.75v11.25a.75.75 0 01-1.5 0V6.31L5.03 20.03a.75.75 0 01-1.06-1.06L17.69 5.25H8.25a.75.75 0 010-1.5z" clip-rule="evenodd"></path>
                                </svg>
                            </a>
                            <a href="/about" class="pl-4 text-sm tracking-wide text-zinc-700 hover:text-zinc-900 dark:text-zinc-300 dark:hover:text-white">About me</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="relative z-10">
            <div class="marquee-xs sm:marquee-sm lg:marquee w-full">
                <div class="grid h-full w-[500vw] grid-cols-10 place-items-center gap-4 px-6 sm:w-[300vw] xl:w-[200vw]">
                    <a href="/pages/project.html" class="test group relative z-10 transition duration-300 ease-out hover:-translate-y-12">
                        <div class="absolute right-0.5 top-0.5 flex h-9 w-9 origin-top-right scale-75 rounded-sm bg-black/10 opacity-0 transition-all duration-300 group-hover:scale-100 group-hover:rounded-md group-hover:bg-black/20 group-hover:opacity-100">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="m-auto h-4 w-4 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                            </svg>
                        </div>
                        <img class="rounded-md transition duration-500 group-hover:rounded-lg" src={bieI} alt="project cover" width="826" height="1239">
                        <div class="flex items-center justify-between px-2 py-4">
                            <h2 class="text-zinc-700 dark:text-white">Business Idea Evaluator</h2>
                            <span class="text-xs text-zinc-500 dark:text-zinc-300">Web Design</span>
                        </div>
                    </a>
                    <a href="/pages/project.html" class="test group relative z-10 transition duration-300 ease-out hover:-translate-y-12">
                        <div class="absolute right-0.5 top-0.5 flex h-9 w-9 origin-top-right scale-75 rounded-sm bg-black/10 opacity-0 transition-all duration-300 group-hover:scale-100 group-hover:rounded-md group-hover:bg-black/20 group-hover:opacity-100">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="m-auto h-4 w-4 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                            </svg>
                        </div>
                        <img class="rounded-md transition duration-500 group-hover:rounded-lg" src={rcI} alt="project cover" width="1380" height="1380">
                        <div class="flex items-center justify-between px-2 py-4">
                            <h2 class="text-zinc-700 dark:text-white">Retro Chat</h2>
                            <span class="text-xs text-zinc-500 dark:text-zinc-300">Web Design</span>
                        </div>
                    </a>
                    <a href="/pages/project.html" class="test group relative z-10 transition duration-300 ease-out hover:-translate-y-12">
                        <div class="absolute right-0.5 top-0.5 flex h-9 w-9 origin-top-right scale-75 rounded-sm bg-black/10 opacity-0 transition-all duration-300 group-hover:scale-100 group-hover:rounded-md group-hover:bg-black/20 group-hover:opacity-100">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="m-auto h-4 w-4 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                            </svg>
                        </div>
                        <img class="rounded-md transition duration-500 group-hover:rounded-lg" src={adI} alt="project cover" width="826" height="1239">
                        <div class="flex items-center justify-between px-2 py-4">
                            <h2 class="text-zinc-700 dark:text-white">Artisan Digital</h2>
                            <span class="text-xs text-zinc-500 dark:text-zinc-300">Web Design</span>
                        </div>
                    </a>
                    <a href="/pages/project.html" class="test group relative z-10 transition duration-300 ease-out hover:-translate-y-12">
                        <div class="absolute right-0.5 top-0.5 flex h-9 w-9 origin-top-right scale-75 rounded-sm bg-black/10 opacity-0 transition-all duration-300 group-hover:scale-100 group-hover:rounded-md group-hover:bg-black/20 group-hover:opacity-100">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="m-auto h-4 w-4 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                            </svg>
                        </div>
                        <img class="rounded-md transition duration-500 group-hover:rounded-lg" src={ppI} alt="project cover" width="1380" height="1380">
                        <div class="flex items-center justify-between px-2 py-4">
                            <h2 class="text-zinc-700 dark:text-white">Pet Portraits</h2>
                            <span class="text-xs text-zinc-500 dark:text-zinc-300">Web Design</span>
                        </div>
                    </a>
                    <a href="/pages/project.html" class="test group relative z-10 transition duration-300 ease-out hover:-translate-y-12">
                        <div class="absolute right-0.5 top-0.5 flex h-9 w-9 origin-top-right scale-75 rounded-sm bg-black/10 opacity-0 transition-all duration-300 group-hover:scale-100 group-hover:rounded-md group-hover:bg-black/20 group-hover:opacity-100">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="m-auto h-4 w-4 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                            </svg>
                        </div>
                        <img class="rounded-md transition duration-500 group-hover:rounded-lg" src={dnI} alt="project cover" width="826" height="1239">
                        <div class="flex items-center justify-between px-2 py-4">
                            <h2 class="text-zinc-700 dark:text-white">Get a Doctors Note</h2>
                            <span class="text-xs text-zinc-500 dark:text-zinc-300">Web Design</span>
                        </div>
                    </a>
                    <a href="/pages/project.html" class="test group relative z-10 transition duration-300 ease-out hover:-translate-y-12">
                        <div class="absolute right-0.5 top-0.5 flex h-9 w-9 origin-top-right scale-75 rounded-sm bg-black/10 opacity-0 transition-all duration-300 group-hover:scale-100 group-hover:rounded-md group-hover:bg-black/20 group-hover:opacity-100">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="m-auto h-4 w-4 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                            </svg>
                        </div>
                        <img class="rounded-md transition duration-500 group-hover:rounded-lg" src={cbI} alt="project cover" width="2000" height="1333">
                        <div class="flex items-center justify-between px-2 py-4">
                            <h2 class="text-zinc-700 dark:text-white">Court Booker</h2>
                            <span class="text-xs text-zinc-500 dark:text-zinc-300">Web Design</span>
                        </div>
                    </a>
                    <a href="/pages/project.html" class="test group relative z-10 transition duration-300 ease-out hover:-translate-y-12">
                        <div class="absolute right-0.5 top-0.5 flex h-9 w-9 origin-top-right scale-75 rounded-sm bg-black/10 opacity-0 transition-all duration-300 group-hover:scale-100 group-hover:rounded-md group-hover:bg-black/20 group-hover:opacity-100">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="m-auto h-4 w-4 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                            </svg>
                        </div>
                        <img class="rounded-md transition duration-500 group-hover:rounded-lg" src={cfI} alt="project cover" width="826" height="1239">
                        <div class="flex items-center justify-between px-2 py-4">
                            <h2 class="text-zinc-700 dark:text-white">Connect Four</h2>
                            <span class="text-xs text-zinc-500 dark:text-zinc-300">Web Design</span>
                        </div>
                    </a>
                    <a href="/pages/project.html" class="test group relative z-10 transition duration-300 ease-out hover:-translate-y-12">
                        <div class="absolute right-0.5 top-0.5 flex h-9 w-9 origin-top-right scale-75 rounded-sm bg-black/10 opacity-0 transition-all duration-300 group-hover:scale-100 group-hover:rounded-md group-hover:bg-black/20 group-hover:opacity-100">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="m-auto h-4 w-4 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                            </svg>
                        </div>
                        <img class="rounded-md transition duration-500 group-hover:rounded-lg" src={bieI} alt="project cover" width="826" height="1239">
                        <div class="flex items-center justify-between px-2 py-4">
                            <h2 class="text-zinc-700 dark:text-white">Business Idea Evaluator</h2>
                            <span class="text-xs text-zinc-500 dark:text-zinc-300">Web Design</span>
                        </div>
                    </a>
                    <a href="/pages/project.html" class="test group relative z-10 transition duration-300 ease-out hover:-translate-y-12">
                        <div class="absolute right-0.5 top-0.5 flex h-9 w-9 origin-top-right scale-75 rounded-sm bg-black/10 opacity-0 transition-all duration-300 group-hover:scale-100 group-hover:rounded-md group-hover:bg-black/20 group-hover:opacity-100">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="m-auto h-4 w-4 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                            </svg>
                        </div>
                        <img class="rounded-md transition duration-500 group-hover:rounded-lg" src={rcI} alt="project cover" width="1380" height="1380">
                        <div class="flex items-center justify-between px-2 py-4">
                            <h2 class="text-zinc-700 dark:text-white">Retro Chat</h2>
                            <span class="text-xs text-zinc-500 dark:text-zinc-300">Web Design</span>
                        </div>
                    </a>
                </div>
            </div>
        </section>
    </main>
    
    <script src="https://cdn.jsdelivr.net/gh/dixonandmoe/rellax@master/rellax.min.js"></script>


</body>

<style>
    @keyframes test {
        0% {
            transform: translateX(0);
        }
        100% {
            transform: translateX(-100%);
        }
    }

    .test {
        animation: test 20s linear infinite;
        position: relative;
        transition: all 0.3s;
    }
</style>