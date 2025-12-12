<script lang="ts">
  // Client logos - Fortune 500 brands Brett has worked with
  const logos = [
    "Apple",
    "JPMorgan Chase",
    "Samsung",
    "American Express",
    "Comcast"
  ];
</script>

<section class="relative min-h-screen flex flex-col justify-end pb-20 px-6 md:px-12 bg-gradient-to-b from-black via-gray-900 to-white text-black">
  <!-- Gradient overlay/background handling -->
  <div class="absolute inset-0 z-[-1] bg-[linear-gradient(180deg,#000_0%,#1a1a1a_30%,#f5f5f5_80%,#fff_100%)]"></div>

  <div class="max-w-4xl mb-32 pt-40">
    <h1 class="text-3xl md:text-5xl font-medium leading-[1.15] tracking-tight">
      Marketing for Tomorrow's Billion Dollar Brands. <span class="text-gray-500">Fractional CMO leadership and specialist-driven execution that delivers profitable, compounding growth—without the Fortune 500 overhead.</span>
    </h1>
  </div>

  <div class="border-t border-gray-300 pt-8 flex flex-wrap gap-8 md:gap-16 items-center opacity-60 grayscale">
    {#each logos as logo}
      <div class="h-8 flex items-center justify-center font-bold text-xl">{logo}</div>
    {/each}
  </div>
</section>
