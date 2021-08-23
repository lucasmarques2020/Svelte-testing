<script lang="ts">
    function exibir(){
        alert("oi, fui clicado!");
    }
    export let N_btn = '';
</script>

<button class = "botao" on:click={exibir}>{N_btn}</button>

<style>
    .botao{
        padding: 20px;
        height: 20px;
        width: 20px;
        color: white;
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: black;
        transition: 0.3s;
    }
    .botao:hover{
        color: white;
        padding: 20px;
        background-color: rgb(255, 6, 6);
    }
</style>