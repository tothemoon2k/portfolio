<script>
    import Header from "$lib/Components/Header.svelte";
    import ss1 from "$lib/assets/screenshots/artisanDigital/MacBook Pro-1710645472106.jpeg";
    import ss2 from "$lib/assets/screenshots/artisanDigital/MacBook Pro-1710645500908.jpeg";
    import ss3 from "$lib/assets/screenshots/artisanDigital/MacBook Pro-1710645508381.jpeg";
    import ss4 from "$lib/assets/screenshots/artisanDigital/MacBook Pro-1710645532216.jpeg";
    import ss5 from "$lib/assets/screenshots/artisanDigital/MacBook Pro-1710645549200.jpeg";
</script>

<div class="bg-white dark:bg-zinc-800">
    <Header />
    <div aria-hidden="true" class="fixed inset-0 h-[200vh] origin-top scale-y-0 bg-gradient-to-b from-gray-100 from-80% to-transparent transition-transform duration-700 dark:scale-y-100 dark:from-zinc-950"></div>
    <main class="relative overflow-hidden pt-16 sm:pt-24 lg:pt-40 xl:pt-32">
        <section>
            <div class="mx-auto max-w-4xl px-6 md:px-12">
                <div class="mt-16">
                    <h1 class="text-3xl font-semibold text-zinc-950 dark:text-white">Artisan Digital - Web Design Agency</h1>
                    <p class="text-sm tracking-wide text-zinc-700 dark:text-zinc-300">Website</p>
                </div>
                <p class="mt-12 text-sm text-zinc-600 dark:text-zinc-200 sm:w-2/3 xl:w-1/2">Autem officiis numquam esse non voluptatem! Commodi modi assumenda laborum necessitatibus reprehenderit hic neque illum, accusantium nam ex ipsum, eius pariatur cumque?</p>
            </div>
            <div class="mx-auto mt-16 max-w-6xl px-1 md:px-12">
                <div class="grid grid-cols-3 gap-1">
                    <img class="col-span-2 h-full w-full rounded-md object-cover" src={ss1} alt="project cover" width="2000" height="1333">
                    <img class="col-span-1 h-full w-full rounded-md object-cover object-left" src={ss2} width="1380" height="1380">
                </div>
            </div>
        </section>
        <section class="my-16">
            <div class="mx-auto h-max max-w-4xl px-6 md:px-12">
                <div class="border-y py-12 dark:border-zinc-800">
                    <h2 class="text-2xl font-bold text-zinc-900 dark:text-white">Customer's problem</h2>
                    <div class="mt-12 grid gap-6 text-sm text-zinc-700 dark:text-zinc-300 sm:grid-cols-2 sm:gap-12">
                        <div class="space-y-6">
                            <p>Full Stack Software Engineer (JavaScript technologies &amp; java) | I believe in Jésus-Christ</p>
                            <p>Deleniti quaerat sequi, itaque magni cumque quisquam vero dolores asperiores sed explicabo dolor tempore.</p>
                        </div>
                        <div class="space-y-6">
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero sapiente possimus magnam id. Quibusdam, necessitatibus culpa placeat quisquam iure, accusamus, molestias aperiam dicta cumque fugiat itaque eos libero impedit quod!</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="mx-auto mt-16 max-w-6xl px-1 md:px-12">
                <div class="grid grid-cols-3 gap-1">
                    <img class="col-span-1 h-full w-full rounded-md object-cover object-left" src={ss2} alt="project cover" width="826" height="1239">
                    <img class="col-span-1 h-full w-full rounded-md object-cover object-left" src={ss3} alt="project cover" width="826" height="1239">
                    <img class="col-span-1 h-full w-full rounded-md object-cover object-left" src={ss4} alt="project cover" width="826" height="1239">
                </div>
            </div>
        </section>
        <section class="my-16">
            <div class="mx-auto max-w-4xl px-6 md:px-12">
                <div class="border-y py-12 dark:border-zinc-800">
                    <h2 class="text-2xl font-bold text-zinc-900 dark:text-white">My solution</h2>
                    <div class="mt-12 grid gap-6 text-sm text-zinc-700 dark:text-zinc-300 sm:grid-cols-2 sm:gap-12">
                        <div class="space-y-6">
                            <p>Full Stack Software Engineer (JavaScript technologies &amp; java) | I believe in Jésus-Christ</p>
                            <p>Deleniti quaerat sequi, itaque magni cumque quisquam vero dolores asperiores sed explicabo dolor tempore.</p>
                        </div>
                        <div class="space-y-6">
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero sapiente possimus magnam id. Quibusdam, necessitatibus culpa placeat quisquam iure, accusamus, molestias aperiam dicta cumque fugiat itaque eos libero impedit quod!</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="mx-auto mt-16 max-w-6xl px-1 md:px-12">
                <div class="grid grid-cols-2 gap-1 lg:grid-cols-3">
                    <img class="col-span-1 h-full w-full rounded-md object-cover object-left" src="/images" alt="project cover" width="1380" height="1380">
                    <img class="col-span-1 h-full w-full rounded-md object-cover" src="/images/projects/foods/food-three.webp" alt="project cover" width="1380" height="1380">
                    <img class="col-span-1 h-full w-full rounded-md object-cover" src="/images/projects/foods/food-two.webp" alt="project cover" width="1380" height="1380">
                    <img class="col-span-1 h-full w-full rounded-md object-cover" src="/images/projects/foods/food-five.webp" alt="project cover" width="1380" height="1380">
                    <img class="col-span-1 h-full w-full rounded-md object-cover" src="/images/projects/foods/food-four.webp" alt="project cover" width="1380" height="1380">
                    <img class="col-span-1 h-full w-full rounded-md object-cover" src="/images/projects/foods/food-six.webp" alt="project cover" width="1380" height="1380">
                </div>
            </div>
        </section>
        <section class="my-16">
            <div class="mx-auto h-max max-w-4xl px-6 py-12">
                <div class="md:px-6 lg:px-12">
                    <h2 class="text-2xl font-bold text-zinc-900 dark:text-white">Changes observed</h2>
                    <p class="mt-2 text-sm text-zinc-700 dark:text-zinc-300">Consectetur qui in labore iusto molestias sequi!</p>
                </div>
                <div class="mt-12 rounded-md bg-zinc-100 px-6 dark:bg-zinc-900 md:px-12">
                    <div class="relative py-12 before:absolute before:inset-x-0 before:bottom-0 before:mx-auto before:h-px before:w-1/2 before:bg-gradient-to-r before:from-transparent before:via-zinc-300 before:to-transparent dark:before:via-white/20">
                        <div class="grid gap-12 divide-zinc-200 dark:divide-zinc-700 sm:-mx-12 sm:grid-cols-3 sm:gap-0 sm:divide-x">
                            <div class="mx-auto w-max space-y-4 text-center sm:px-12 sm:text-left">
                                <h3 class="text-sinc-950 text-4xl dark:text-white sm:text-5xl">73k</h3>
                                <span class="inline-block text-sm text-zinc-600 dark:text-zinc-300">New users</span>
                            </div>
                            <div class="mx-auto w-max space-y-4 text-center sm:px-12 sm:text-left">
                                <h3 class="text-sinc-950 text-4xl dark:text-white sm:text-5xl">434k</h3>
                                <span class="inline-block text-sm text-zinc-600 dark:text-zinc-300">Visites</span>
                            </div>
                            <div class="mx-auto w-max space-y-4 text-center sm:px-12 sm:text-left">
                                <h3 class="text-sinc-950 text-4xl dark:text-white sm:text-5xl">234k</h3>
                                <span class="inline-block text-sm text-zinc-600 dark:text-zinc-300">Social followers</span>
                            </div>
                        </div>
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
</div>