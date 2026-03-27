<script lang="ts">
  import Hero from '$lib/components/Hero.svelte';
  import SectionProjects from '$lib/components/SectionProjects.svelte';
  import NewsCard from '$lib/components/NewsCard.svelte';

  const proyectos = [
    { titulo: "Transporte", descripcion: "Mejora urbana" }
  ];

  const noticias = [
    { titulo: "Nueva obra", fecha: "2026" }
  ];
</script>

<Hero />

<SectionProjects {proyectos} />

<section class="p-6">
  <h2 class="text-2xl font-bold">Noticias</h2>

  <div class="grid md:grid-cols-2 gap-4 mt-4">
    {#each noticias as n}
      <NewsCard {...n} />
    {/each}
  </div>
</section>