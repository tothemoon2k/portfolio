<script>
    import profile from "$lib/assets/profile.jpeg";
    import q from "$lib/assets/screenshots/IdeaEval/MacBook Pro-1710645010766.jpeg";
    import w from "$lib/assets/screenshots/artisanDigital/MacBook Pro-1710645472106.jpeg";
    import e from "$lib/assets/screenshots/artisanDigital/MacBook Pro-1710645508381.jpeg";
    import r from "$lib/assets/screenshots/artisanDigital/MacBook Pro-1710645520910.jpeg";
    import t from "$lib/assets/screenshots/courtBooker/MacBook Pro-1710645852434.jpeg";
    import y from "$lib/assets/screenshots/courtBooker/MacBook Pro-1710645913640.jpeg";
    import u from "$lib/assets/screenshots/courtBooker/MacBook Pro-1710645928951.jpeg";
    import i from "$lib/assets/screenshots/doctorsNote/MacBook Pro-1710645621057.jpeg";
    import o from "$lib/assets/screenshots/petPortraits/MacBook Pro-1710645110975.jpeg";
    import p from "$lib/assets/screenshots/petPortraits/MacBook Pro-1710645137117.jpeg";
    import a from "$lib/assets/screenshots/petPortraits/MacBook Pro-1710645153131.jpeg";
    import s from "$lib/assets/screenshots/petPortraits/MacBook Pro-1710645170980.jpeg";
    import d from "$lib/assets/screenshots/petPortraits/MacBook Pro-1710645170980.jpeg";
    import f from "$lib/assets/screenshots/retroChat/MacBook Pro-1710645724410.jpeg";
    import g from "$lib/assets/screenshots/retroChat/MacBook Pro-1710645785576.jpeg";
    import h from "$lib/assets/screenshots/connectFour/MacBook Pro-1710646176347.jpeg";
</script>

<body class="bg-white dark:bg-zinc-800">
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
                                <a href="/pages/about.html" class="text-sm tracking-wide text-zinc-700 hover:text-zinc-900 dark:text-zinc-300 dark:hover:text-white">About me</a>
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
    <main class="relative pt-16 sm:pt-24 lg:pt-40 xl:pt-32">
        <section>
            <div class="mx-auto max-w-4xl px-6 md:px-12">
                <div class="">
                    <h1 class="mt-16 text-3xl font-semibold text-zinc-950 dark:text-white">Justin Garner</h1>
                    <p class="text-sm tracking-wide text-zinc-700 dark:text-zinc-300">Fullstack Developer</p>

                    <div class="my-12 grid gap-12 border-y py-12 text-base text-zinc-700 dark:border-zinc-800 dark:text-zinc-300 sm:grid-cols-2">
                        <div class="space-y-6">
                            <p>From a young age, I've been driven by an insatiable curiosity to understand how things work and a deep-rooted passion for building. What started as disassembling and reassembling random objects around the house quickly evolved into a lifelong love affair with technology and web development.</p>
                            <p>At the tender age of 14, I embarked on my coding journey by devouring Colt Steele's full stack web developer course, igniting a fire within me that has only grown brighter with each passing year. Since then, I've been relentlessly honing my skills, crafting a diverse portfolio of full-stack projects that showcase my use of cutting-edge technologies and my ability to transform ideas into polished, user-centric digital experiences.</p>
                        </div>
                        <div class="space-y-6">
                            <p>But my ambitions extend far beyond mere web development. I'm a builder at heart, fueled by an unwavering drive to create tech products that genuinely improve people's lives. With each line of code I write, I'm driven by a greater purpose - to build amazing products people truly enjoy using, making their lives easier and more delightful.</p>
                            <p>When I'm not working at the keyboard, weaving together intricate web applications, you'll find me indulging in my other passions: reading interesting books, moving big weight in the gym, and engaging in thought-provoking conversations with friends.</p>
                            <p>So, if you're seeking a hard-working and excited partner to join your team and help bring an amazing product to life, look no further. Let's join forces and create something truly remarkable. Drop me a message, and let's embark on an extraordinary journey together!</p>
                            <div class="flex items-center gap-4 divide-x divide-zinc-200 dark:divide-zinc-800">
                                <div class="flex gap-2">
                                    <a href="https://twitter.com/_justingarner" target="_blank" class="group rounded-md p-2 transition duration-300 hover:bg-zinc-100 dark:hover:bg-zinc-800">
                                        <span class="sr-only">Twitter</span>
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="h-4 w-4 text-zinc-600 group-hover:text-sky-600 dark:text-zinc-300 dark:group-hover:text-white" viewBox="0 0 16 16">
                                            <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"></path>
                                        </svg>
                                    </a>
                                    <a href="https://github.com/tothemoon2k" target="_blank" class="group rounded-md p-2 transition duration-300 hover:bg-zinc-100 dark:hover:bg-zinc-800">
                                        <span class="sr-only">Github</span>
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="h-4 w-4 text-zinc-600 group-hover:text-sky-600 dark:text-zinc-300 dark:group-hover:text-white" viewBox="0 0 16 16">
                                            <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path>
                                        </svg>
                                    </a>
                                    <a href="https://www.linkedin.com/in/justin-garner-76942a29b/" target="_blank" class="group rounded-md p-2 transition duration-300 hover:bg-zinc-100 dark:hover:bg-zinc-800">
                                        <span class="sr-only">LinkedIn</span>
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="h-4 w-4 text-zinc-600 group-hover:text-sky-600 dark:text-zinc-300 dark:group-hover:text-white" viewBox="0 0 16 16">
                                            <path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"></path>
                                        </svg>
                                    </a>
                                </div>
                                <a href="mailto:hello@tailus.io" class="pl-4 text-base tracking-wide text-zinc-600 hover:text-sky-600 dark:text-zinc-400 dark:hover:text-white">justin@justingarner.dev</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="hidden md:block">
            <div data-rellax-speed="-3" class="rellax mb-96 overflow-hidden px-1" style="transform: translate3d(0px, 0px, 0px);">
                <div class="flex items-center justify-center gap-1">
                    <div class="h-96 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96">
                        <img class="h-full w-full object-cover" src={q} alt="Business Idea Evaluator Icon" width="1380" height="1380">
                    </div>
                    <div class="h-80 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96">
                        <img class="h-full w-full object-cover" src={w} alt="lifestyle" width="1380" height="1380">
                    </div>
                    <div class="h-72 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96">
                        <img class="h-full w-full object-cover" src={e} alt="lifestyle" width="826" height="1239">
                    </div>
                    <div class="h-64 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96">
                        <img class="h-full w-full object-cover" src={r} alt="lifestyle" width="826" height="1239">
                    </div>
                    <div class="hidden h-60 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96 sm:block">
                        <img class="h-full w-full object-cover" src={t} alt="lifestyle" width="826" height="1239">
                    </div>
                    <div class="hidden h-56 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96 sm:block">
                        <img class="h-full w-full object-cover" src={y} alt="lifestyle" width="2000" height="1335">
                    </div>
                    <div class="hidden h-52 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96 sm:block">
                        <img class="h-full w-full object-cover" src={u} alt="lifestyle" width="900" height="1261">
                    </div>
                    <div class="hidden h-52 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96 sm:block">
                        <img class="h-full w-full object-cover" src={i} alt="lifestyle" width="2000" height="1330">
                    </div>
                    <div class="hidden h-56 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96 sm:block">
                        <img class="h-full w-full object-cover" src={o} alt="lifestyle" width="996" height="1245">
                    </div>
                    <div class="hidden h-60 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96 sm:block">
                        <img class="h-full w-full object-cover" src={p} alt="lifestyle" width="2000" height="1333">
                    </div>
                    <div class="h-64 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96">
                        <img class="h-full w-full object-cover" src={a} alt="lifestyle" width="826" height="1239">
                    </div>
                    <div class="h-72 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96">
                        <img class="h-full w-full object-cover" src={s} alt="lifestyle" width="1380" height="1380">
                    </div>
                    <div class="h-80 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96">
                        <img class="h-full w-full object-cover" src={f} alt="lifestyle" width="1380" height="1380">
                    </div>
                    <div class="h-96 w-20 overflow-hidden rounded-md transition-all duration-500 hover:w-96">
                        <img class="h-full w-full object-cover" src={g} alt="lifestyle" width="740" height="1110">
                    </div>
                </div>
            </div>
        </section>
    </main>
    <footer class="relative border-t py-6 dark:border-zinc-900">
        <div class="mx-auto max-w-4xl px-6 md:px-12">
            <div class="flex flex-wrap justify-between gap-4">
                <span class="text-sm text-zinc-500 dark:text-zinc-400">© tailus 2021 - Present</span>
                <a href="#" target="_top" class="text-sm text-gray-700 dark:text-white">_top</a>
            </div>
        </div>
    </footer>
    
    <script src="https://cdn.jsdelivr.net/gh/dixonandmoe/rellax@master/rellax.min.js"></script>


</body>