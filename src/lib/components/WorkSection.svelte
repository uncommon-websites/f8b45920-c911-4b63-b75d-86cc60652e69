<script lang="ts">
  const services = [
    {
      title: "Advisory",
      desc: "Growth strategy consultation, marketing leadership coaching, and vendor evaluation."
    },
    {
      title: "Strategy",
      desc: "Marketing audit, investment modeling, and channel prioritization with clear roadmaps."
    },
    {
      title: "Management",
      desc: "Campaign implementation, ongoing optimization, and specialist recruitment under our supervision."
    }
  ];

  const caseStudy = {
    title: "60% Revenue Growth",
    desc: "A beauty e-commerce retailer saw nearly 60% revenue growth in Q4 after SSP came in with precise, focused, and strategic execution.",
    img: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&q=80&w=1200"
  };
</script>

<section class="px-6 md:px-12 py-32 bg-white">
  <div class="max-w-6xl mx-auto">
    <div class="max-w-3xl mb-20">
      <h2 class="text-3xl md:text-4xl font-medium leading-tight mb-6">
        We cut through marketing chaos to focus on growth as the only metric that matters
      </h2>
      <p class="text-xl text-gray-600">
        Fortune 500 expertise on demand, without the overhead.
      </p>
    </div>

    <!-- Services Grid -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
      {#each services as service}
        <div class="border border-gray-200 rounded-lg p-8 hover:border-gray-400 transition-colors">
          <h3 class="text-xl font-medium mb-3">{service.title}</h3>
          <p class="text-gray-600 leading-relaxed">{service.desc}</p>
        </div>
      {/each}
    </div>

    <!-- Case Study -->
    <div class="border border-gray-200 rounded-lg overflow-hidden">
      <div class="grid md:grid-cols-2 gap-0">
        <div class="p-12 flex flex-col justify-center">
          <p class="text-sm text-gray-500 mb-4">Case Study</p>
          <h3 class="text-3xl font-medium mb-4">{caseStudy.title}</h3>
          <p class="text-lg text-gray-600 leading-relaxed">{caseStudy.desc}</p>
        </div>
        <div class="aspect-[4/3] md:aspect-auto">
          <img src={caseStudy.img} alt="Case study" class="w-full h-full object-cover" />
        </div>
      </div>
    </div>
  </div>
</section>
