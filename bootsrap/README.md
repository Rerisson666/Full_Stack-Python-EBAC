# Bootstrap

- Framework ou biblioteca desenvolvimento
- Modular
- Componentes ricos
- CSS + JS
- Grid System
- Responsivo
- Mobile-first
- Amplamente utilizada
- Cross browser

## Biblioteca x Framework

- Biblioteca: Oferece objetos / classes prontas para uso
- Framework: Oferece um conjunto de bibliotecas
- Biblioteca: Recurso para trabalhar
- Framework: Metodologia de trabalho
- Biblioteca: Te leva ao destino
- Framework: Te ensina a chegar

## Desenvolvimento Ágil

- Metodologia: Scrum, Kambam, XP
- Entrega de valor para o negócio
- Ciclos evolutivos
- Separar grandes projetos em pequenas entregas
- Estar envolvido x comprometido

## Vantagens

- Usar Simples
- Menos código
- Abstração de estilos
- Documentação completa: http://getbootstrap.com/

## Desvantagens

- Uso execisso
Override de estilos (sobreposição)
- Abstração de estilos

### Com Bootstrap

```

 <a class="btn-lg">Botão</a>

```

### Sem Bootstrap

```

 <a class="botao botao-grande>Botão</a>

 <style>
 html {
    font-size: 62.5%
 }

 .botao {
    backgound-color: #ccc;
    border-radius: 2px;
    display: block;
    font-family: sans-serif;
    font-size: 1.6rem;
    padding: 1rem 2rem;
    margin: 5px auto;
    ...
 }

 .botao.grande {
    font-size: 2rem;
 }

 .botao.grande { ... }
 .botao.active { ... }
 .botao.visited { ... }

 </style>

 ## Helpers

 - Funções básicas
 - Incrementos
 - Ajustes