<script langu="typescript">
  import { onMount } from "svelte";
  import env from "./env";
  onMount(() => {
    console.log("App mounted");
  });
</script>

<h1>Typescript Start Project</h1>

<p>You are in environment {env.ENVIRONMENT} with typescript</p>
