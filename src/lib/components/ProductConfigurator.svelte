<script lang="ts">
  let selectedPackage = 'standard';
</script>

<section class="bg-[#f9f9f7] py-24 px-6" id="pricing">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Three service levels. <span class="text-gray-400">One fixed price.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">Standard Clear-Out</h3>
      <p class="text-gray-500 text-sm">Complete property clearing for estates and turnovers.</p>
    </div>

    <!-- Service Visualization -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4">
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="/generated/image-empty-clean-residential-property-interio-1767416890823-0.webp" class="h-[80%] object-contain" alt="Cleared property" />
    </div>

    <!-- Package Options -->
    <div class="flex justify-center gap-4 mb-8">
      <button class="px-4 py-2 rounded-lg bg-primary-100 border-2 border-primary-500 text-primary-900 text-sm font-medium">Standard</button>
      <button class="px-4 py-2 rounded-lg bg-gray-100 text-gray-600 text-sm font-medium hover:bg-gray-200">Express</button>
      <button class="px-4 py-2 rounded-lg bg-gray-100 text-gray-600 text-sm font-medium hover:bg-gray-200">Premium</button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>Complete clear-out</span>
      <span>Donation & recycling</span>
      <span>Final cleaning</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      Fixed pricing from <span class="font-bold text-gray-900">$2,500</span> per property.<br>
      Final quote provided within 24 hours. ⓘ
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">Compare packages</span>
        <span class="text-primary-600">See all service levels</span>
      </button>
      <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"/><polyline points="14 2 14 8 20 8"/></svg>
        Get a custom quote ->
      </button>
    </div>
  </div>
</section>
