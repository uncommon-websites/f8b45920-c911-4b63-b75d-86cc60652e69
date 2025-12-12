<script lang="ts">
  const principles = [
    {
      title: "Your Marketing General Contractor",
      desc: "We're not a traditional agency. We design the blueprint and hand-pick specialists for each engagement—all under our supervision."
    },
    {
      title: "We Measure Success in Dollars",
      desc: "No vanity metrics. Every decision is grounded in unit economics and what actually moves your bottom line."
    },
    {
      title: "Custom Teams for Your Challenge",
      desc: "No one-size-fits-all solutions. We build the right team with the right expertise for your specific growth challenge."
    }
  ];
</script>

<section class="py-32 px-6 md:px-12 bg-white border-t border-gray-200">
  <div class="max-w-6xl mx-auto">
    <div class="max-w-3xl mb-20">
      <h2 class="text-3xl md:text-4xl font-medium mb-6">
        A different approach to growth marketing
      </h2>
      <p class="text-xl text-gray-600 leading-relaxed">
        Modern marketing is a mess. Too many platforms, vendors, and agencies. We cut through the chaos to focus on challenges actually worth solving.
      </p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
      {#each principles as principle}
        <div>
          <h3 class="text-xl font-medium mb-3">{principle.title}</h3>
          <p class="text-gray-600 leading-relaxed">{principle.desc}</p>
        </div>
      {/each}
    </div>
  </div>
</section>
