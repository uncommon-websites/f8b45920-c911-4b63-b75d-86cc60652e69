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

<section class="relative min-h-screen flex flex-col justify-center px-6 md:px-12 py-32 bg-white">
  <div class="max-w-5xl mx-auto">
    <h1 class="text-4xl md:text-6xl lg:text-7xl font-medium leading-[1.1] tracking-tight mb-8">
      Marketing for Tomorrow's Billion Dollar Brands
    </h1>
    <p class="text-xl md:text-2xl text-gray-600 leading-relaxed max-w-3xl">
      Fractional CMO leadership and specialist-driven execution that delivers profitable, compounding growth—without the Fortune 500 overhead.
    </p>
  </div>

  <div class="max-w-5xl mx-auto mt-24 pt-12 border-t border-gray-200">
    <p class="text-sm text-gray-500 mb-6">Trusted by world-class brands</p>
    <div class="flex flex-wrap gap-x-12 gap-y-6 items-center opacity-40">
      {#each logos as logo}
        <div class="text-lg font-medium text-gray-900">{logo}</div>
      {/each}
    </div>
  </div>
</section>
