<template>
  <div class="flex bg-black h-screen">
    <!-- sidebar -->
    <div class="bg-zinc-900 w-[516px] p-12 flex flex-col justify-center">
      <Logo />
      <h1 class="text-white font-bold text-lg mt-8">
        Sign up for a free account
      </h1>
      <p class="text-zinc-300 text-sm mt-0.5">
        Already registered?
        <span class="font-bold text-[#FFAC00] underline">Log in</span> to your
        account
      </p>

      <form>
        <div class="mt-6">
          <label
            for="email"
            class="text-zinc-300 text-sm font-normal block mb-0.5"
            >Email Address</label
          >
          <input
            id="email"
            type="email"
            class="block w-full bg-[#27272A] border-[#3F3F46] rounded text-white px-4 py-2 placeholder:text-zinc-500 text-sm"
            placeholder="you@example.com"
            autocomplete="username"
          />
        </div>
        <div class="mt-6">
          <label
            for="password"
            class="text-zinc-300 text-sm font-normal block mb-0.5"
            >Password</label
          >
          <input
            id="password"
            type="password"
            class="block w-full bg-[#27272A] border-[#3F3F46] rounded text-white px-4 py-2 placeholder:text-zinc-500 text-sm"
            placeholder="****************"
            autocomplete="current-password"
          />
        </div>
        <div>
          <button
            class="flex items-center justify-center space-x-2 w-full mt-4 bg-[#FFAC00] rounded-full px-4 py-2 text-sm font-bold"
          >
            <span>Sign Up</span>
            <ArrowRight />
          </button>
        </div>
      </form>
    </div>
    <!-- /sidebar -->

    <!-- note-intro -->
    <div></div>
    <!-- /note-intro -->
  </div>
</template>
