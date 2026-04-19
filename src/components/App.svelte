<script lang="ts">
  import { bruinBucks } from "../game/state";
</script>

<main>
  <p>{$bruinBucks} Bruin Bucks</p>
  <button onclick={() => bruinBucks.update((n) => n + 1)}>
    <img src="/ucla-logo.png" alt="Bruin" width="150" />
  </button>
</main>

<style>
  button {
    background: none;
    border: none;
    padding: 0;
    cursor: pointer;
  }
</style>
