<script lang="ts">
  type Proyecto = {
    titulo: string;
    descripcion: string;
  };

  type Noticia = {
    titulo: string;
    fecha: string;
  };

  const proyectos: Proyecto[] = [
    {
      titulo: "Modernización del transporte",
      descripcion: "Nuevos corredores"
    }
  ];

  const noticias: Noticia[] = [
    {
      titulo: "Nueva obra en Lima",
      fecha: "2026"
    }
  ];
</script>