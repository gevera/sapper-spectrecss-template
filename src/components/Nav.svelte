<script>
  export let segment;
</script>

<style>
  .tab {
    padding-left: 1rem;
  }
</style>

<nav>
  <ul class="tab">
    <li class="tab-item" class:active={segment === undefined}>
      <a href=".">home</a>
    </li>
    <li class="tab-item" class:active={segment === 'about'}>
      <a href="about">about</a>
    </li>

    <!-- for the blog link, we're using rel=prefetch so that Sapper prefetches
		     the blog data when we hover over the link or tap it on a touchscreen -->
    <li class="tab-item" class:active={segment === 'blog'}>
      <a rel="prefetch" href="blog">blog</a>
    </li>
  </ul>
</nav>
