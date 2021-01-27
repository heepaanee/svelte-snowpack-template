<script lang="ts">
  import Router from "svelte-spa-router";
  import routes from "~/routes";
  import Header from "./components/Header.svelte";
</script>

<Header />

<Router {routes} />

<style lang="scss">
  // If you want to import the `scss/main.scss` file globally,
  // you must add `<style lang="scss">` even if the style content is empty.
</style>
