<script context="module">
  export async function preload({ params, query }) {
    // the `slug` parameter is available because
    // this file is called [slug].svelte
    const res = await this.fetch(`blog/${params.slug}.json`);
    const data = await res.json();

    if (res.status === 200) {
      return { post: data };
    } else {
      this.error(res.status, data.message);
    }
  }
</script>

<script>
  export let post;
</script>

<svelte:head>
  <title>{post.title}</title>
</svelte:head>

  <div class="container">

    <h1 class="text-center">{post.title}</h1>

    <div class="column col-xs-12 col-md-10 col-lg-8 col-6 col-mx-auto">
      {@html post.html}
    </div>

  </div>
