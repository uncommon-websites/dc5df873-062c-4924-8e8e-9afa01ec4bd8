<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Get a quote",
      desc: "Contact us with your property details. We provide a fixed-price quote within 24 hours—no surprises, no hourly billing.",
      img: "/generated/image-estate-professional-or-property-manager--1767416902324-3.webp"
    },
    {
      num: "02",
      title: "Site visit",
      desc: "We visit your property to confirm scope, timeline, and any special requirements. You sign off, and we handle the rest.",
      img: "/generated/image-professional-crew-member-in-work-uniform-1767416895171-1.webp"
    },
    {
      num: "03",
      title: "Clear-out",
      desc: "Our insured crew systematically clears, sorts, donates, recycles, and disposes. You receive progress updates—no micromanaging needed.",
      img: "/generated/image-organized-moving-truck-or-work-vehicle-w-1767416915901-7.webp"
    },
    {
      num: "04",
      title: "Final walkthrough",
      desc: "Property cleared, cleaned, and ready. We document the work and provide disposal receipts. Typical timeline: days, not weeks.",
      img: "/generated/image-clean-empty-house-interior-with-keys-on--1767416908996-5.webp"
    }
  ];
</script>

<section class="bg-white py-24 px-6" id="process">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Complete clear-outs in four simple steps. Finished in days, not weeks.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-black text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
            {step.num}
          </div>
          <h3 class="text-xl font-normal mb-2">{step.title}</h3>
          <p class="text-gray-500 text-sm leading-relaxed mb-6 min-h-[80px]">{step.desc}</p>
          <div class="rounded-xl overflow-hidden h-[200px] bg-gray-100">
            <img src={step.img} alt={step.title} class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500" />
          </div>
        </div>
      {/each}
    </div>

    <div class="bg-[#f9f9f7] rounded-2xl p-12 flex flex-col md:flex-row items-center justify-between gap-8">
      <div>
        <h3 class="text-2xl font-light mb-2">Ready to get started?</h3>
        <p class="text-gray-500 text-sm">Get a fixed-price quote for your property clear-out.</p>
      </div>
      <div class="flex gap-4">
        <button class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          See pricing
        </button>
        <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
          Schedule a call
        </button>
      </div>
    </div>
  </div>
</section>
