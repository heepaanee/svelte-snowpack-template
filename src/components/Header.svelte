<script lang="ts">
  import { link } from "svelte-spa-router";
  import active from "svelte-spa-router/active";
  import Logo from "~/components/Logo.svelte";
</script>

<header>
  <Logo />
  <a use:link use:active={"/"} href="/"> home </a>
  <a use:link use:active={"/about"} href="/about">about</a>
</header>

<style lang="scss">
  header :global(a.active) {
    color: red;
  }
</style>
