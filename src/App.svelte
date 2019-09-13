<script>
  import { greeting } from "./greeting-store";

  export let name;
</script>

<style>
  h1 {
    color: rebeccapurple;

    &:hover {
      color: black;
    }
  }
</style>

<div>
  <h1>{$greeting} {name}!</h1>
</div>
