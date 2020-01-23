<script>
  //component
  import x from "@fortawesome/fontawesome-free/js/all";
  import Navbar from "./components/Navbar.svelte";
  import Title from "./components/Title.svelte";
  import ExpensesList from "./components/ExpensesList.svelte";
  //Data
  import expensesData from "./expenses.js";
  //Variabel
  let expenses = [...expensesData];
</script>

<Navbar />
<div class="container">
  <Title />
  <ExpensesList {expenses} />
</div>
