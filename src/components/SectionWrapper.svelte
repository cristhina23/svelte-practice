<script>
  export let id;
</script>
<section id={id} class="min-h-screen flex flex-col p-4">

  <div class="flex flex-col flex-1 max-w-350 mx-auto w-full">
    <slot />
  </div>
</section>
