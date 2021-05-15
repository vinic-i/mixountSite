<script>
    import { FAQ } from "../components";
    import Catalog from "../components/home/Catalog.svelte";
    import Contact from "../components/home/Contact.svelte";
    import Features from "../components/home/Features.svelte";
    import Hero from "../components/home/Hero.svelte";
    import OurTeam from "../components/home/OurTeam.svelte";
    import Section from "../components/home/Section.svelte";
    import Services from "../components/home/Services.svelte";
    import Testimonials from "../components/home/Testimonials.svelte";
</script>

<svelte:head><title>Mixou</title></svelte:head>

<!-- 
    
-->
<Hero
    title="Nós oferecemos soluções modernas para o crescimento do seu negócio."
    showButton={false}
/>
<Section />
<Services />
<OurTeam />

<Contact />

<!--
    <Features></Features>
    <Testimonials></Testimonials>
    <Catalog></Catalog>
    <FAQ></FAQ>
 -->
