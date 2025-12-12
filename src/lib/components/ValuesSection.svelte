<script lang="ts">
  const differentiators = [
    {
      title: "Enterprise Experience",
      desc: "10+ years managing billions in media for Fortune 500s. Now bringing that operational precision to growth-stage companies."
    },
    {
      title: "Specialist Network",
      desc: "Hand-picked experts for each engagement. We design the blueprint; our specialists handle every build under our supervision."
    },
    {
      title: "Bottom-Line Focus",
      desc: "Every dollar tracked. Every decision grounded in unit economics. Marketing that stays in lockstep with your P&L."
    }
  ];
</script>

<section class="py-32 px-6 md:px-12 bg-white border-t border-gray-200">
  <div class="max-w-6xl mx-auto">
    <div class="max-w-3xl mb-20">
      <h2 class="text-3xl md:text-4xl font-medium mb-6">
        What sets us apart
      </h2>
      <p class="text-xl text-gray-600 leading-relaxed">
        We bridge brand and performance marketing to drive one outcome—profitable, compounding growth. No jargon, no busywork, just the Fortune 500 playbook without the Fortune 500 overhead.
      </p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
      {#each differentiators as item}
        <div>
          <h3 class="text-xl font-medium mb-3">{item.title}</h3>
          <p class="text-gray-600 leading-relaxed">{item.desc}</p>
        </div>
      {/each}
    </div>
  </div>
</section>
