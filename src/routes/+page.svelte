<script>
    import { GradientHeading, AppBar } from "@brainandbones/skeleton";

    let year = new Date().getFullYear();
</script>

<header class="bg-light">
    <div class="" style="height:100vh;">
        <AppBar background="" shadow="shadow-none" padding="p-4 md:px-20">
            <svelte:fragment slot="lead">
                <img src="/logo.png" class="h-10 md:h-14" alt="Forward School Logo">
            </svelte:fragment>
            <svelte:fragment slot="trail">
                <a class="btn btn-sm" href="https://dev.to/forwardschool" target="_blank">Tutorials</a>
            </svelte:fragment>
        </AppBar>

        <div class="flex items-center justify-center text-center px-6" style="height:65vh;">
            <div>
                <h1 class="text-black font-medium leading-tight text-4xl md:text-6xl">
                    Earn your web3 degree.
                </h1>

                <div class="text-black mt-10 mb-11 text-xl md:text-2xl">
                    Learn the skill that matter  in a fast moving world.
                </div>

                <div class="space-y-56">
                    <a href="https://forms.gle/No746TE2veyR7oL88" class="btn !bg-ternary-500 btn-lg !text-white !px-11 !rounded-full !no-underline">Get Early Access</a>
                </div>
            </div>
        </div>
    </div>
</header>

<div class="text-center sm:px-6 bg-white mb-16 bg-white">
    <h2 class="font-bold mb-8">
        Top web3 companies are hiring by ASPIRING Developers from Africa.
    </h2>
    <div>
        <div class="flex items-center justify-center">
            <img src="/company-logos.png" class="object-contain h-48" alt="Tech companies logos" />
        </div>
    </div>
</div>

<div class="sm:px-6 py-16 mb-16">
    <div class="container mx-auto">
        <div class="md:columns-2 md:gap-4 md:flex md:items-center md:justify-center h-96 md:w-2/3 mx-auto text-center">
            <div class="md:w-1/2 md:p-8 mb-8 px-4">
                <h2 class="mb-8 font-bold text-2xl md:text-4xl">Creating the next Generation of Tech talents</h2>
                <div class="text-lg">
                Forward academy is a revolutionary web3 school that will equip anyone aspiring to become a certified web3 engineer in a short time.
                </div>
            </div>
            <div class="md:w-1/2">
                <div class="">
                    <img src="/tech-talents.png" class="object-contain h-1/2" alt="Tech companies logos" />
                </div>
            </div>
        </div>
    </div>
</div>

<div class="sm:px-6 py-16 mb-16 bg-white">
    <div class="container mx-auto px-4">
        <div class="md:columns-2 md:gap-4 md:flex md:items-center md:justify-center h-96 md:w-2/3 mx-auto text-center">
            <div class="md:w-1/2 md:p-8 mb-8">
                <h2 class="mb-8 font-bold text-2xl md:text-4xl">Code stars just like you</h2>
                <div class="text-lg">
                    Read real use of people like you who learnt how to code and are now making impact in the tech industry.
                </div>
            </div>
            <div class="md:w-1/2">
                <div class="">
                    <img src="/code-stars.png" class="object-contain h-1/2" alt="Tech companies logos" />
                </div>
            </div>
        </div>
    </div>
</div>

<!-- <div class="bg-light">
    <div class="container mx-auto px-4">
        <div class="bg-white">
        </div>
    </div>
</div> -->

<div class="text-center sm:px-6 mb-8 pt-16">
    <div class="text-lg font-bold">
        &copy; {year} Forward School Africa
    </div>
</div>
                