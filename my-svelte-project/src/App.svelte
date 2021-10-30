<script lang="ts">
  import Button from "./Button.svelte";
  import Logo from "./Logo.svelte";
  import Tailwind from "./Tailwind.svelte";
</script>

<Tailwind />

<main class="font-headline flex items-center flex-col">
  <div class="bg-red-500 w-full text-white text-5xl p-10 text-center">SBB</div>
  <p class="text-center p-10">Test paragraph</p>
  <div class="w-20">
    <Button>A Button</Button>
  </div>
</main>
