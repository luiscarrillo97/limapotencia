<script lang="ts">
  const regions = [
    'Lima Metropolitana',
    'Lima Norte',
    'Lima Sur',
    'Lima Este',
    'Callao',
    'Regiones'
  ];
</script>

<section class="bg-slate-950 py-20 text-white">
  <div class="mx-auto max-w-7xl px-6">
    <div class="mb-10 max-w-3xl">
      <span class="text-sm font-semibold uppercase tracking-[0.2em] text-sky-400">
        Territorio
      </span>

      <h2 class="mt-3 text-3xl font-black md:text-5xl">
        Presencia por zonas
      </h2>

      <p class="mt-4 text-white/75">
        Cobertura territorial organizada por zonas estratégicas.
      </p>
    </div>

    <div class="grid gap-4 sm:grid-cols-2 lg:grid-cols-3">
    {#each regions as region (region)}
<button
  type="button"
  class="mt-6 inline-block font-semibold text-slate-900"
  aria-label="Leer más noticias"
>
  Leer más →
</button>
      {/each}
    </div>
  </div>
</section>