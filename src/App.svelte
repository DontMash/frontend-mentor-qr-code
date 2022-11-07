<script lang="ts">
  import Footer from './lib/Footer.svelte';
</script>

<main class="flex justify-center items-center min-h-screen p-6">
  <h1 class="sr-only">QR Component</h1>
  <article class="max-w-xs p-4 bg-white rounded-2xl shadow-xl">
    <picture class="block rounded-xl overflow-hidden">
      <img src="/images/image-qr-code.png" alt="QR Code" width="576" height="576" />
    </picture>
    <div class="p-6 text-center space-y-4">
      <h2 class="text-xl text-dark-blue font-bold"> Improve your front-end skills by building projects </h2>
      <p class="text-sm">
        Scan the QR code to visit Frontend Mentor and take your coding skills to the next
        level
      </p>
    </div>
  </article>
</main>
<Footer />
