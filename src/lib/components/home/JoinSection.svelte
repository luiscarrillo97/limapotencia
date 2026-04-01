<section class="bg-slate-100 py-20">
  <div class="mx-auto grid max-w-7xl gap-10 px-6 lg:grid-cols-[1.05fr_0.95fr]">
    <div>
      <span class="text-sm font-semibold uppercase tracking-[0.2em] text-sky-600">
        Participación
      </span>
      <h2 class="mt-3 text-3xl font-black text-slate-900 md:text-5xl">
        Mantente informado
      </h2>
      <p class="mt-4 max-w-2xl text-slate-600 md:text-lg">
        Usa este bloque como formulario de contacto, suscripción o registro.
      </p>
    </div>

    <form class="rounded-3xl bg-white p-8 shadow-lg">
      <div class="grid gap-5">
        <div>
          <label for="nombre" class="mb-2 block text-sm font-semibold text-slate-700">Nombre</label>
          <input id="nombre" class="w-full rounded-xl border border-slate-300 px-4 py-3 outline-none transition focus:border-sky-500" />
        </div>

        <div>
          <label for="correo" class="mb-2 block text-sm font-semibold text-slate-700">Correo</label>
          <input id="correo" type="email" class="w-full rounded-xl border border-slate-300 px-4 py-3 outline-none transition focus:border-sky-500" />
        </div>

        <div>
          <label for="region" class="mb-2 block text-sm font-semibold text-slate-700">Distrito o región</label>
          <input id="region" class="w-full rounded-xl border border-slate-300 px-4 py-3 outline-none transition focus:border-sky-500" />
        </div>

        <div>
          <label for="mensaje" class="mb-2 block text-sm font-semibold text-slate-700">Mensaje</label>
          <textarea id="mensaje" rows="4" class="w-full rounded-xl border border-slate-300 px-4 py-3 outline-none transition focus:border-sky-500"></textarea>
        </div>

        <button class="rounded-xl bg-sky-600 px-6 py-3 font-semibold text-white transition hover:bg-sky-500">
          Enviar
        </button>
      </div>
    </form>
  </div>
</section>