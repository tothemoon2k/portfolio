<script>
    import profile from "$lib/assets/profile.jpeg";
</script>

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