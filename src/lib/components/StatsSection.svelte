<script lang="ts">
  const stats = [
    {
      label: "$2B+ Media Managed",
      desc: "Brett has managed over $2 billion in media spend across his career, working with Fortune 500 brands including Apple, JPMorgan Chase, Samsung, American Express, and Comcast. This enterprise-grade expertise now powers growth-stage companies.",
      img: "https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&q=80&w=200"
    },
    {
      label: "60% Revenue Growth",
      desc: "A beauty e-commerce retailer saw nearly 60% revenue growth in Q4 after SSP came in with precise, focused, and strategic execution. We deliver rapid results that matter to your bottom line.",
      img: "https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&q=80&w=200"
    },
    {
      label: "New York, NY",
      desc: "Headquartered at 1178 Broadway in New York City, we bring Fortune 500 playbooks to ambitious growth-stage brands. Our hand-picked network of specialists spans the country, delivering expertise where you need it.",
      img: "https://images.unsplash.com/photo-1496442226666-8d4d0e62e6e9?auto=format&fit=crop&q=80&w=200"
    },
    {
      label: "Fractional CMO Model",
      desc: "Get enterprise-level strategy at a fraction of the cost of a full-time CMO. Flexible engagements that scale with your needs—from advisory to full campaign management with specialist oversight.",
      img: "https://images.unsplash.com/photo-1552664730-d307ca884978?auto=format&fit=crop&q=80&w=200"
    }
  ];
</script>

<section class="py-24 px-6 md:px-12 bg-white border-t border-gray-100">
  <div class="mb-16">
    <p class="text-gray-500 max-w-xl">
      The numbers tell the story. Here's what sets Sullivan Street Projects apart in the growth marketing landscape.
    </p>
  </div>

  <div class="space-y-16">
    {#each stats as stat}
      <div class="flex flex-col md:flex-row md:items-start justify-between gap-8 border-b border-gray-100 pb-16 last:border-0">
        <h3 class="text-2xl md:text-4xl font-medium w-full md:w-1/3">{stat.label}</h3>
        <div class="w-full md:w-1/3">
           <p class="text-xs leading-relaxed text-gray-500">{stat.desc}</p>
        </div>
        <div class="w-full md:w-1/6 flex justify-end">
           <img src={stat.img} alt={stat.label} class="w-20 h-20 object-cover rounded bg-gray-100" />
        </div>
      </div>
    {/each}
  </div>
</section>
