<script lang="ts">
  const projects = [
    {
      title: 'Ciudad Bicentenario',
      text: 'Una pieza visual fuerte para explicar visión urbana, vivienda, conectividad e infraestructura.',
      image: '/ciudad-bicentenario.jpg'
    },
    {
      title: 'Movilidad y transporte',
      text: 'Sección para mostrar corredores, accesos, puentes, intercambios y obras clave.',
      image: '/placeholder-transporte.jpg'
    },
    {
      title: 'Espacio público',
      text: 'Parques, recuperación urbana, limpieza, iluminación y activación de zonas estratégicas.',
      image: '/placeholder-espacio-publico.jpg'
    }
  ];
</script>

<section id="proyectos" class="bg-slate-100 py-20">
  <div class="mx-auto max-w-7xl px-6">
    <div class="mb-12 flex flex-col justify-between gap-6 md:flex-row md:items-end">
      <div class="max-w-2xl">
        <span class="text-sm font-semibold uppercase tracking-[0.2em] text-sky-600">
          Proyectos
        </span>
        <h2 class="mt-3 text-3xl font-black text-slate-900 md:text-5xl">
          Iniciativas destacadas
        </h2>
      </div>

      <button
  type="button"
  class="mt-6 inline-block font-semibold text-slate-900"
  aria-label="Leer más noticias"
>
  Leer más →
</button>
    </div>

    <div class="grid gap-6 lg:grid-cols-3">
     {#each projects as project (project.title)}
  <article class="overflow-hidden rounded-3xl bg-white shadow-sm transition hover:-translate-y-1 hover:shadow-xl">
    <img src={project.image} alt={project.title} class="h-60 w-full object-cover" />
    <div class="p-6">
      <h3 class="text-2xl font-bold text-slate-900">{project.title}</h3>
      <p class="mt-3 text-slate-600">{project.text}</p>
      <a href="" class="mt-5 inline-block font-semibold text-sky-700">
        Conocer más →
      </a>
    </div>
  </article>
{/each}
    </div>
  </div>
</section>