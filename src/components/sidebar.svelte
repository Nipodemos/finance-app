<script>
  import Purchase20 from "carbon-icons-svelte/lib/Purchase20";
</script>

<div>Logo</div>

<sidebar>
  <button class="nav"><Purchase20 class="icon" size="24" /> Meus cartões</button
  >
  <button class="nav"><Purchase20 class="icon" size="24" /> Transferir</button>
  <button class="nav"><Purchase20 class="icon" size="24" /> Conta</button>
  <button class="nav"><Purchase20 class="icon" size="24" /> Garantias</button>
  <button class="nav"><Purchase20 class="icon" size="24" /> FAQ</button>
</sidebar>

<style>
  sidebar {
    justify-content: flex-start;
    display: flex;
    flex-direction: column;
    flex-shrink: 1;
    max-width: 240px;
  }
  button.nav {
    border-radius: 8px;
    background: none;
    border: none;
    display: flex;
    padding: 10px 8px;
    margin: 10px;
    font-size: 20px;
    color: white;
  }

  button.nav:hover {
    opacity: 0.4;
  }

  :global(svg.icon) {
    padding-right: 8px;
  }
</style>
