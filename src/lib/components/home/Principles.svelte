<script lang="ts">
  const items = [
    {
      title: 'Orden urbano',
      text: 'Espacios públicos cuidados, movilidad más eficiente y una ciudad mejor conectada.'
    },
    {
      title: 'Inversión y obra',
      text: 'Proyectos visibles, infraestructura útil y ejecución con enfoque de largo plazo.'
    },
    {
      title: 'Seguridad ciudadana',
      text: 'Tecnología, prevención y capacidad operativa para una ciudad más segura.'
    },
    {
      title: 'Gestión moderna',
      text: 'Comunicación clara, indicadores visibles y servicios digitales más accesibles.'
    }
  ];
</script>

<section class="bg-white py-20">
  <div class="mx-auto max-w-7xl px-6">
    <div class="mx-auto mb-12 max-w-3xl text-center">
      <span class="text-sm font-semibold uppercase tracking-[0.2em] text-sky-600">
        Ejes principales
      </span>
      <h2 class="mt-3 text-3xl font-black text-slate-900 md:text-5xl">
        Una portada con mensaje claro
      </h2>
      <p class="mt-4 text-slate-600 md:text-lg">
        Esta sección reemplaza el bloque de “valores” con una presentación más web y menos afiche.
      </p>
    </div>

    <div class="grid gap-6 md:grid-cols-2 xl:grid-cols-4">
      {#each items as item (item.title)}
  <article class="rounded-2xl border border-slate-200 bg-slate-50 p-6 shadow-sm transition hover:-translate-y-1 hover:shadow-md">
    <h3 class="text-xl font-bold text-slate-900">{item.title}</h3>
    <p class="mt-3 text-slate-600">{item.text}</p>
  </article>
{/each}
    </div>
  </div>
</section>