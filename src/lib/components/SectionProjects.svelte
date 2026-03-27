<script lang="ts">
  export let proyectos: {
    titulo: string;
    descripcion: string;
  }[];
</script>

<section class="py-10 text-center">
  <h2 class="text-2xl font-bold">Proyectos</h2>

  <div class="grid md:grid-cols-3 gap-4 mt-6">
    {#each proyectos as p}
      <div class="p-4 bg-white shadow rounded">
        <h3 class="font-bold">{p.titulo}</h3>
        <p>{p.descripcion}</p>
      </div>
    {/each}
  </div>
</section>