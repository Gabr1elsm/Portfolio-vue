<template>
<header class="bg-gray-300 rounded text-black p-6 w-fit mx-auto">
       <h1 class="font-bold text-xl text-center">Habilidades</h1>
       <h2 class="font-bold text-xl text-center">Soft-skills</h2>
        <p class="text-black text-sm leading-tight max-w-sm mx-auto">Comunicação, trabalho em equipe e organização.</p>
        <h2 class="font-bold text-xl text-center">Hard-skills</h2>
        <p class="text-black text-sm leading-tight max-w-sm mx-auto">HTML, CSS, JavaScript, Python, C# e C++.</p>

       <h1 class="font-bold text-xl text-center">Formação</h1>
        <p class="text-black text-sm leading-tight max-w-sm mx-auto">Estou cursando o meu segundo ano e terceiro semenstre do curso superior de analise e desenvolvimento de sistemas(ADS) na universidade de Marilia, Unimar e tambem estou realizando cursos onlines e presenciais na própria universidade.</p>

        <h1 class="font-bold text-xl text-center">Trajetoria</h1>
        <p class="text-black text-sm leading-tight max-w-sm mx-auto">No terceiro ano do ensino médio eu me encontrava sem saber em oque cursar,após analisar os cursos disponiveis nas universidades proximas de min foi quando me deparei com os cursos de TI, apesar de não ter uma paixão tão profunda pela area na epoca era a que eu mais me identificava, após entrar para o curso de ciencia da computação na Unimar em 2023 foi quando eu descobri que sim, esta erá uma area onde eu me identificava, a cada dia me esforçando durante as aulas e cursos extras para um dia me formar e me tornar um desenvolvedor de software. </p>
    </header>
</template>
<script>
    import Header from './HeaderView.vue'
    export default{
        nome: "about",
        components: {
            Header
        },
    }
</script>