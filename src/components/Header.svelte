<script>
  import SectionWrapper from "./SectionWrapper.svelte";
  import { openModal } from "../store";
</script>

<header class="flex flex-col relative z-20">
  <div
    class="max-w-[1400px] mx-auto w-full flex items-center justify-between p-4 py-6"
  >
    <a href="/">
      <h1 class="font-semibold text-blue-400">
        Lid<span class="text-indigo-800">Tek</span>
      </h1>
    </a>
    <nav class="flex items-center gap-4 md:gap-10 lg:gap-6">
      <a
        href="https://github.com/LidTek"
        class="duration-200 hover:text-blue-600 cursor-pointer"
      >
        <i class="fa-brands fa-github pr-2" />
        Github
      </a>
      <a href="/goal" class="duration-200 hover:text-blue-600 cursor-pointer"
        >About Us</a
      >
      <button class="specialBtn">
        <a href="https://discord.gg/fmYnZss29N">Join Our Discord!</a>
      </button>
    </nav>
  </div>
</header>
