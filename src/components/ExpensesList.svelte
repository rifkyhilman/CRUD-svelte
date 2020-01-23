<script>
  import SectionTitle from "./Title.svelte";
  import Expenses from "./Expenses.svelte";
  export let expenses = [];
</script>

<div>
  <SectionTitle title="expense List" />
  <ul>
  {#each expenses as expense}
    <Expenses />
  {/each}
  </ul>
</div>
