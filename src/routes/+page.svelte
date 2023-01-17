<!--<h1 class="text-3xl font-bold underline">Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<a href="/welcome">Home</a>-->


<div class="flex h-screen w-full items-center justify-center bg-gray-900 bg-cover bg-no-repeat" style="background-image: url('bg2.jpg')">
<section class="text-gray-600 body-font">
    <div class="container px-5 py-24 mx-auto flex flex-wrap items-center">

        <!-- Logo -->
        <div class="lg:w-1/2 md:w-1/2 md:pr-16 lg:pr-16 pr-0">
            <img class="object-cover object-center rounded" alt="hero" src="2.png">
            <p class="leading-relaxed text-sm text-center font-semibold tracking-wider text-teal-600 mt-4">Skip the queue with your number one facilities booking application. </p>
        </div>
        <!-- End Logo -->

        <!-- Login Container -->
        <div class="lg:w-1/2 md:w-1/2 bg-gray-100 rounded-lg p-8 flex flex-col md:ml-auto w-full mt-10 md:mt-0 bg-opacity-50 backdrop-blur-md shadow-2xl">
            <h2 class="text-white text-lg font-semibold tracking-wider title-font mb-5">LOGIN</h2>
            <div class="relative mb-4">
                <label for="email" class="leading-7 text-sm text-gray-600">Email</label>
                <input type="email" id="email" name="email" class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
            </div>
            <div class="relative mb-4">
                <label for="password" class="leading-7 text-sm text-gray-600">Password</label>
                <input type="password" id="password" name="password" class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
            </div>
            <button class="text-white bg-teal-600 tracking-wider border-0 py-2 px-8 focus:outline-none hover:bg-teal-900 rounded text-lg shadow-inner">Sign In</button>
            <p class="text-xs text-gray-800 my-3 text-center">or</p>
            <button class="text-white bg-teal-600 border-0 py-2 px-8 focus:outline-none hover:bg-teal-900 rounded text-lg shadow-inner">Create a New Account</button>
            <p class="text-xs text-gray-800 mt-3 text-center">If you are a new user.</p>
        </div>
        <!-- End Login Container -->

    </div>
</section>
</div>