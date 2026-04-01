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
        Este bloque toma la lógica territorial del sitio de referencia, pero adaptada a una organización por zonas y cobertura local. :contentReference[oaicite:1]{index=1}
      </p>
    </div>

    <div class="grid gap-4 sm:grid-cols-2 lg:grid-cols-3">
    {#each regions as region (region)}
  <a
    href="/territorio"
    class="rounded-2xl border border-white/10 bg-white/5 px-6 py-5 text-lg font-semibold text-white/90 backdrop-blur transition hover:bg-sky-500 hover:text-white"
  >
    {region}
  </a>
{/each}
    </div>
  </div>
</section>