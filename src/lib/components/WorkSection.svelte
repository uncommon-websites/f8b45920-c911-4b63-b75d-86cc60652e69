<script lang="ts">
  const services = [
    {
      service: "Advisory",
      desc: "Growth strategy consultation, marketing leadership coaching, and vendor evaluation.",
      bg: "bg-black",
      img: "", 
      dark: true
    },
    {
      service: "Strategy",
      desc: "Marketing audit, investment modeling, and channel prioritization with clear roadmaps.",
      bg: "bg-gray-100",
      img: "https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&q=80&w=800",
      dark: false
    },
    {
      service: "Management",
      desc: "Campaign implementation, ongoing optimization, and specialist recruitment under our supervision.",
      bg: "bg-gray-900",
      img: "",
      dark: true
    },
    {
      service: "Beauty E-Commerce",
      desc: "Nearly 60% revenue growth in Q4 through precise, focused, and strategic execution.",
      bg: "bg-[#f5f5f5]",
      img: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&q=80&w=800",
      dark: false,
      full: true
    },
    {
      service: "Media Activation",
      desc: "Deploy the right channel mix—PPC, CTV, SEO, Email/SMS—with data-driven dashboards.",
      bg: "bg-gray-200",
      img: "https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&q=80&w=800",
      dark: false
    },
    {
      service: "Campaign Execution",
      desc: "Translate strategy into scroll-stopping creative that converts attention to revenue.",
      bg: "bg-gray-100",
      img: "https://images.unsplash.com/photo-1533750349088-cd871a92f312?auto=format&fit=crop&q=80&w=800",
      dark: false
    }
  ];
</script>

<section class="px-6 md:px-12 py-24 bg-white">
  <div class="max-w-3xl mb-16">
    <h2 class="text-2xl md:text-3xl font-medium leading-tight">
      <span class="font-bold">We cut through marketing chaos</span> to focus on growth as the only metric that matters. Fortune 500 expertise on demand, without the overhead.
    </h2>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-2 gap-x-6 gap-y-12">
    {#each services as service}
      <div class="group cursor-pointer {service.full ? 'md:col-span-2' : ''}">
        <div class={`aspect-[4/3] w-full rounded-lg overflow-hidden relative ${service.bg} mb-4 ${service.full ? 'md:aspect-[2.5/1]' : ''}`}>
          {#if service.img}
             <img src={service.img} alt={service.service} class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" />
          {:else}
             <!-- Placeholder for service cards on solid bg -->
             <div class="w-full h-full flex items-center justify-center">
                <span class={`text-2xl font-bold ${service.dark ? 'text-white' : 'text-black'}`}>{service.service}</span>
             </div>
          {/if}
        </div>
        <h3 class="text-sm font-bold mb-1">{service.service}</h3>
        <p class="text-sm text-gray-600">{service.desc}</p>
      </div>
    {/each}
  </div>
</section>
