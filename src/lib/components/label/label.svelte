<script>
  export let forElement;
</script>

<label
  for={forElement}
  class="block font-medium mb-2 cursor-pointer text-slate-600">
  <slot />
</label>
