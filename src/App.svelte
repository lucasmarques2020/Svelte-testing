<script lang="ts">
import Botao from "./components/Botao.svelte";

</script>

<main>
	<Botao N_btn="7"></Botao>
	<Botao N_btn="8"></Botao>
	<Botao N_btn="9"></Botao>
	<Botao N_btn="4"></Botao>
	<Botao N_btn="5"></Botao>
	<Botao N_btn="6"></Botao>
	<Botao N_btn="1"></Botao>
	<Botao N_btn="2"></Botao>
	<Botao N_btn="3"></Botao>
</main>

<style>
	*{
		padding: 0;
		margin: 0;
	}
	main {
		display: flex;
		justify-content: center;
		align-items: center;
		background-color: blue;
		height: 100%;
		width: 100%;
		text-align: center;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>