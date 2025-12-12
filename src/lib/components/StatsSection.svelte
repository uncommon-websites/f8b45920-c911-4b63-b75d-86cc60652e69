<script lang="ts">
  const stats = [
    {
      number: "$2B+",
      label: "Media Managed",
      desc: "Brett has managed over $2 billion in media spend across his career, working with Fortune 500 brands including Apple, JPMorgan Chase, Samsung, American Express, and Comcast."
    },
    {
      number: "60%",
      label: "Revenue Growth",
      desc: "A beauty e-commerce retailer saw nearly 60% revenue growth in Q4 after SSP came in with precise, focused, and strategic execution."
    },
    {
      number: "10+",
      label: "Years Experience",
      desc: "Brett brings over a decade of experience across startups and global brands, including leading demand generation at Navan, a travel and expense management unicorn."
    }
  ];
</script>

<section class="py-32 px-6 md:px-12 bg-gray-50">
  <div class="max-w-6xl mx-auto">
    <div class="mb-20">
      <h2 class="text-3xl md:text-4xl font-medium mb-4">By the numbers</h2>
      <p class="text-xl text-gray-600">The track record speaks for itself</p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
      {#each stats as stat}
        <div class="border-t-2 border-gray-900 pt-6">
          <div class="text-5xl md:text-6xl font-medium mb-2">{stat.number}</div>
          <div class="text-lg font-medium mb-3">{stat.label}</div>
          <p class="text-gray-600 leading-relaxed">{stat.desc}</p>
        </div>
      {/each}
    </div>
  </div>
</section>
