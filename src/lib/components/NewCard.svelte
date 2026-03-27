<script lang="ts">
  export let titulo: string;
  export let fecha: string;
</script>

<div class="border p-4 rounded">
  <h3 class="font-semibold">{titulo}</h3>
  <span class="text-sm text-gray-500">{fecha}</span>
</div>