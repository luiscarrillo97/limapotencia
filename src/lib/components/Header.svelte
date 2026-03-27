<script lang="ts">
  let open = false;
</script>

<header class="bg-primary text-white">
  <div class="flex justify-between p-4">
    <div>
      <h1 class="font-bold">LIMA POTENCIA MUNDIAL</h1>
      <span class="text-xs">Renovación Popular</span>
    </div>

    <button class="md:hidden" on:click={() => open = !open}>
      ☰
    </button>

    <nav class="hidden md:flex gap-4">
      <a href="/">Inicio</a>
      <a href="/proyectos">Proyectos</a>
      <a href="/noticias">Noticias</a>
    </nav>
  </div>

  {#if open}
    <div class="md:hidden p-4 bg-secondary">
      <a href="/" class="block">Inicio</a>
      <a href="/proyectos" class="block">Proyectos</a>
      <a href="/noticias" class="block">Noticias</a>
    </div>
  {/if}
</header>