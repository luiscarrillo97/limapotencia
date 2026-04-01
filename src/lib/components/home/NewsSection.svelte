<script lang="ts">
  const news = [
    {
      title: 'Nueva etapa del portal institucional',
      date: '30 Mar 2026',
      text: 'Un rediseño orientado a información, claridad visual y experiencia multiplataforma.'
    },
    {
      title: 'Agenda pública y contenido audiovisual',
      date: '28 Mar 2026',
      text: 'Se incorpora un bloque central de video y nuevos formatos para difundir actividades.'
    },
    {
      title: 'Proyectos urbanos y enfoque territorial',
      date: '25 Mar 2026',
      text: 'La nueva portada prioriza proyectos, regiones y noticias con estructura modular.'
    }
  ];
</script>

<section id="noticias" class="bg-white py-20">
  <div class="mx-auto max-w-7xl px-6">
    <div class="mb-12 text-center">
      <span class="text-sm font-semibold uppercase tracking-[0.2em] text-sky-600">
        Actualidad
      </span>
      <h2 class="mt-3 text-3xl font-black text-slate-900 md:text-5xl">
        Últimas noticias
      </h2>
    </div>

    <div class="grid gap-6 lg:grid-cols-3">
{#each news as item (item.date)}
  <article class="rounded-3xl border border-slate-200 p-7 transition hover:border-sky-300 hover:shadow-lg">
    <p class="text-sm font-semibold uppercase tracking-wide text-sky-600">{item.date}</p>
    <h3 class="mt-3 text-2xl font-bold text-slate-900">{item.title}</h3>
    <p class="mt-4 text-slate-600">{item.text}</p>
    <a href="/noticias" class="mt-6 inline-block font-semibold text-slate-900">
      Leer más →
    </a>
  </article>
{/each}
    </div>
  </div>
</section>