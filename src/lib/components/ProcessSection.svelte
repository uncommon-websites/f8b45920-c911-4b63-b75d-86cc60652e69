<script lang="ts">
  const steps = [
    {
      number: "01",
      title: "Align with Business Objectives",
      text: "We ground every engagement in commercial objectives, market realities, and unit economics. Your marketing engine stays in lockstep with your P&L—no vanity metrics, just dollars that matter."
    },
    {
      number: "02",
      title: "Design Your Growth Blueprint",
      text: "We distill your brand, audience, and customer lifecycle into a clear roadmap. No jargon, no busywork—just a pragmatic plan that bridges brand and performance to drive compounding growth."
    },
    {
      number: "03",
      title: "Deploy the Right Channel Mix",
      text: "We activate the channels that move the needle—PPC, CTV, SEO, Email/SMS—with data-driven dashboards that give you complete visibility into what's working and what's not."
    },
    {
      number: "04",
      title: "Execute with Precision",
      text: "Our hand-picked specialists handle every build under our supervision. We translate strategy into scroll-stopping creative and campaigns that convert attention to revenue—fast."
    }
  ];
</script>

<section class="bg-gray-50 py-32 px-6 md:px-12">
  <div class="max-w-6xl mx-auto">
    <div class="mb-20">
      <h2 class="text-3xl md:text-4xl font-medium mb-4">How we work</h2>
      <p class="text-xl text-gray-600">A proven process that delivers results</p>
    </div>

    <div class="space-y-16">
      {#each steps as step}
        <div class="border-l-2 border-gray-300 pl-8 md:pl-12">
          <div class="flex items-baseline gap-4 mb-4">
            <span class="text-sm font-mono text-gray-400">{step.number}</span>
            <h3 class="text-2xl md:text-3xl font-medium">{step.title}</h3>
          </div>
          <p class="text-lg text-gray-600 leading-relaxed max-w-2xl">{step.text}</p>
        </div>
      {/each}
    </div>
  </div>
</section>
