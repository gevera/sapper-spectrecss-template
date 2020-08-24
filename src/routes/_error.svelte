<script>
  export let status;
  export let error;

  const dev = process.env.NODE_ENV === "development";
</script>

<svelte:head>
  <title>{status}</title>
</svelte:head>

<div class="flex-centered">
  <div class="container">
    <h1 class="text-center">{status}</h1>

    <p class="text-center">{error.message}</p>

    {#if dev && error.stack}
      <pre>{error.stack}</pre>
    {/if}
  </div>
</div>
