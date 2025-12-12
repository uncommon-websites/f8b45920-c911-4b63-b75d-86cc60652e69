<script lang="ts">
  const approaches = [
    {
      title: "Enterprise Experience",
      desc: "10+ years managing billions in media for Fortune 500s. Now bringing that operational precision to growth-stage companies.",
      img: "https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?auto=format&fit=crop&q=80&w=400"
    },
    {
      title: "Specialist Network",
      desc: "Hand-picked experts for each engagement. We design the blueprint; our specialists handle every build under our supervision.",
      img: "https://images.unsplash.com/photo-1522071820081-009f0129c71c?auto=format&fit=crop&q=80&w=400"
    },
    {
      title: "Bottom-Line Focus",
      desc: "Every dollar tracked. Every decision grounded in unit economics. Marketing that stays in lockstep with your P&L.",
      img: "https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&q=80&w=400"
    }
  ];
</script>

<section class="py-24 px-6 md:px-12 bg-white">
  <div class="max-w-xl mb-16">
    <h3 class="text-lg font-bold mb-2">Growth marketing partners to mission-driven founders.</h3>
    <p class="text-gray-500 text-sm leading-relaxed">
      We bridge brand and performance marketing to drive one outcome—profitable, compounding growth. No jargon, no busywork, just the Fortune 500 playbook without the Fortune 500 overhead.
    </p>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
    {#each approaches as approach}
      <div>
        <div class="aspect-[3/4] rounded-lg overflow-hidden mb-4 bg-gray-100">
          <img src={approach.img} alt={approach.title} class="w-full h-full object-cover" />
        </div>
        <h4 class="text-xs font-bold mb-1">{approach.title}</h4>
        <p class="text-[10px] text-gray-500 leading-relaxed">{approach.desc}</p>
      </div>
    {/each}
  </div>
</section>
