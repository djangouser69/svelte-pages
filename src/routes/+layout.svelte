<script>
  const { children } = $props();
</script>

<nav>
  <a href="/">index</a>
  <a href="/about">about</a>
  <a href="/test">test</a>
  <a href=""></a>
</nav>

{@render children()}
