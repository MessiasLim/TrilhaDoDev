# Exercícios de CSS 

Este material apresenta **60 exercícios progressivos** para dominar CSS. Ele acompanha temas que aparecem nos arquivos da pasta `css/` e vai do básico (seletores, cores, box model) até técnicas avançadas (flex, grid, variáveis, responsividade, componentes).

Use-o como roteiro de prática: copie o enunciado em um arquivo `.css` ou dentro de uma `<style>` em HTML e experimente o resultado no navegador.

---

## BLOCO 1 — FUNDAMENTOS

1. Escrever uma regra que deixe todos os `<p>` com `color: blue`.



2. Criar uma classe `.vermelho` que aplica `color: red` e borda sólida.



3. Usar um ID `#principal` para dar `background-color: #eee` a um elemento único.



4. Escrever um seletor combinado para estilizar apenas `<li>` dentro de `<nav>`.



5. Adicionar um pseudo‑classe `:hover` em links para mudarem de cor quando o mouse passar.



6. Aplicar um pseudo‑elemento `::before` num cabeçalho para inserir um marcador decorativo.



7. Definir `display: block`, `inline` e `inline-block` em três `<div>` e observar as diferenças de fluxo.



8. Criar uma caixa `.box` com `width: 200px`, `padding: 10px`, `border: 2px solid` e `margin: 20px`; calcular o tamanho total com `box-sizing: content-box` e depois com `border-box`.



9. Posicionar um elemento com `position: relative` e outro filho com `position: absolute; top: 10px; right: 10px`.



10. Ocultar um elemento usando `display: none` e outro com `visibility: hidden`; explicar o comportamento em cada caso.




## BLOCO 2 — ESTILOS E VARIÁVEIS 

11. Criar duas classes de tamanho de fonte: `.texto-pequeno` (12px) e `.texto-grande` (24px) e aplicá‑las.



12. Definir cores de fundo e texto com valores hexadecimais, RGB e nomes (`#ff0`, `rgb(0`, `orange`).



13. Declarar variáveis CSS em `:root` para `--cor-primaria` e `--espacamento`; usar `var()` em um botão.



14. Sobrescrever uma variável localmente dentro de `.card` para alterar apenas o fundo deste componente.



15. Utilizar `calc()` com variáveis para criar `padding: calc(var(--espacamento) * 2)`.



16. Definir um tema escuro alternando uma classe `.tema-escuro` e mudando variáveis dentro dela.



17. Criar um seletor de atributo `[type="text"]` que dê borda azul a inputs de texto.



18. Aplicar `box-sizing: border-box` globalmente com `*, *::before, *::after`.



19. Usar a pseudo‑classe `:nth-child(odd)` para colorir listras em uma tabela.



20. Adicionar um `:focus-visible` visível a botões para acessibilidade ao teclado.




## BLOCO 3 — LAYOUT 

21. Montar um container `.flex` com `display: flex` e três itens; usar `justify-content: space-between`.



22. Criar uma grade básica com `display: grid` e `grid-template-columns: repeat(2,1fr)`.



23. Usar `flex-wrap: wrap` para transformar os itens flex em linhas quando a largura for pequena.



24. Posicionar um card no centro da página com `.center { display:flex; justify-content:center; align-items:center; height:100vh; }`.



25. Construir um layout de três colunas com Flexbox onde a coluna central cresce (`flex:1`) e as laterais têm largura fixa.



26. Criar um grid de 3×3 e usar `grid-column: span 2` em um item para que ele ocupe duas colunas.



27. Centralizar horizontalmente uma `<div>` com `margin: 0 auto; width: 60%;` e explicar por que precisa definir a largura.



28. Alinhar texto à direita, esquerda, centro e justificar usando `text-align`.



29. Aplicar `vertical-align: middle` em imagens inline-block para alinhá‑las com texto.



30. Usar `position: fixed` para criar um cabeçalho que permanece no topo ao rolar.




## BLOCO 4 — COMPONENTES 

31. Estilizar um botão `.btn` com padding, border‑radius e transição de `background-color`.



32. Criar modificador `.btn--primary` e `.btn--secondary` usando classes adicionais.



33. Adicionar estado `:hover` e `:active` ao botão para alterar a sombra e a cor.



34. Construir um card `.card` com sombra (`box-shadow`), padding e largura fixa.



35. Adaptar o card para `.card--large` com mais padding e `.card--small` com menos.



36. Criar botão com ícone dentro usando `display:inline-flex` e `gap`.



37. Fazer botão com estado `disabled` que reduza `opacity` e `cursor: not-allowed`.



38. Escrever regra `.btn:disabled, .btn[aria-disabled="true"]` para suportar ARIA.



39. Implementar um loader simples com `::after` em `.btn--loading` e animação.



40. Usar variável `--radius` para aplicar o mesmo border-radius em botão e card.




## BLOCO 5 — RESPONSIVIDADE 

41. Criar media query `@media (max-width: 600px)` que muda `flex-direction` para `column`.



42. Ajustar `font-size` usando `clamp()` para escalar entre 16px e 24px.



43. Alterar variáveis (`--space-md`) dentro de uma media query para espaçamento diferenciado.



44. Tornar uma imagem responsiva com `max-width:100%; height:auto;`.



45. Fazer um grid que tenha uma, duas ou três colunas dependendo da largura (media queries em cols).



46. Esconder um menu (`display:none`) em telas pequenas e exibir um botão de hamburger.



47. Utilizar `@media (prefers-reduced-motion: reduce)` para desativar transições.



48. Aplicar `container { width: min(90%, 1200px); margin:0 auto; }` para fluidez.



49. Usar `width: clamp(200px, 50%, 400px)` em uma caixa para restrição responsiva.



50. Criar breakpoint com `@media (min-width: 1024px)` para ajustar layout de nav.




## BLOCO 6 — AVANÇADOS 

51. Usar CSS Grid para criar área nomeada (`grid-template-areas`) e posicionar elementos.



52. Fazer uma animação simples com `@keyframes fade-in` e aplicar a um componente.



53. Escrever `transition: background-color 0.3s ease` em `.btn` e demonstrar o efeito.



54. Implementar `:root { --hue: 200; }` e usar `hsl(var(--hue), 80%, 50%)` para cor dinâmica.



55. Alterar a variável `--hue` com JavaScript e observar a mudança em tempo real.



56. Criar tema escuro claro que responde a `prefers-color-scheme: dark`.



57. Escrever `@supports (display: grid)` para fornecer fallback para navegadores antigos.



58. Usar `:not()` e `:empty` para estilizar elementos que não contêm conteúdo.



59. Explicar e demonstrar diferença entre `visibility:hidden` e `opacity:0` com `pointer-events`.



60. Montar um mini‑projeto: um botão que muda de cor com variável, um card flexível e um layout responsivo usando todas as técnicas aprendidas.




---

**Mais exercícios?** adicione exemplos próprios, combine seletores, experimente valores diferentes e sempre teste no navegador. Boa codificação!