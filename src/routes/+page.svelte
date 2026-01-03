<script lang="ts">
  import TopBanner from "$lib/components/TopBanner.svelte";
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Intro from "$lib/components/Intro.svelte";
  import ValueProp from "$lib/components/ValueProp.svelte";
  import Contrast from "$lib/components/Contrast.svelte";
  import FlagshipOffer from "$lib/components/FlagshipOffer.svelte";
  import SavingsMoney from "$lib/components/SavingsMoney.svelte";
  import ModularServices from "$lib/components/ModularServices.svelte";
  import WhoThisIsFor from "$lib/components/WhoThisIsFor.svelte";
  import FinalCTA from "$lib/components/FinalCTA.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<div class="font-sans antialiased text-gray-900 bg-white">
  <TopBanner />
  <Navbar />
  <main>
    <Hero />
    <Intro />
    <ValueProp />
    <Contrast />
    <FlagshipOffer />
    <SavingsMoney />
    <ModularServices />
    <WhoThisIsFor />
    <FinalCTA />
  </main>
  <Footer />
</div>

