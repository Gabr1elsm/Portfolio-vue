<template>
    <header class="bg-gray-300 rounded text-black p-6 w-fit mx-auto">
       <h1 class="font-bold text-xl text-center">Bem vindo ao meu portfolio</h1>

       <p class="text-black text-sm leading-tight max-w-sm mx-auto">Me chamo <span class="font-bold">Gabriel</span> e sou um aluno do curso superior de analise e desenvolvimento de sistemas na universidade Unimar, aqui você irá descobrir mais sobre minhas <span class="font-bold">habilidades</span>, <span class="font-bold">formação</span> e <span class="font-bold">trajetoria</span> relacionados a area de TI, Para isso acesse a aba<span class="font-bold">"Sobre"</span>.</p>
        
        <p class="text-black text-sm leading-tight max-w-sm mx-auto">E caso deseje entrar em contato comigo, basta acessar <span class="font-bold">"Contato"</span>para mais opções.</p>


    </header>
</template>
<script>
    import Header from './HeaderView.vue'
    export default{
        nome: "home",
        components: {
            Header
        },
    }
</script>