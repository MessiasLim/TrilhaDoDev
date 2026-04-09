# Exercícios de HTML 

**Objetivo:** praticar desde a criação de um documento básico até recursos avançados de HTML5.


## Bloco 1 – Fundamentos

1. **Documento mínimo:** crie um HTML com `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>` e `<title>`.



2. **Idioma e metas:** complete o esqueleto abaixo adicionando `lang="pt-BR"`, `<meta charset="UTF-8">` e `<meta name="viewport" content="width=device-width, initial-scale=1.0">`.



   ```html
   <!DOCTYPE html>
   <html>
   <head>
       <title>Página</title>
   </head>
   <body>
   </body>
   </html>
   ```
3. **Erro estrutural:** identifique e corrija o problema no código abaixo.

   ```html
   <html>
   <head>
   <title>Título</title>
   </head>
   <h1>Conteúdo</h1>
   <body>
   <p>Texto</p>
   </body>
   </html>
   ```
4. Criar hierarquia de títulos do `<h1>` ao `<h4>`.



5. Corrigir a hierarquia incorreta:
   ```html
   <h3>Subtítulo</h3>
   <h1>Título Principal</h1>
   <h4>Detalhe</h4>
   ```
6. Criar uma lista não ordenada com cinco itens.



7. Corrigir a lista mal estruturada:
   ```html
   <ul>
   <li>Item 1
   <li>Item 2</li>
   </ul>
   ```
8. Criar um link externo que abra em nova aba com as proteções `rel="noopener noreferrer"`.



9. Corrigir o link abaixo adicionando o `href` correto:
   ```html
   <a>Google</a>
   ```
10. Criar uma página simples contendo:
    - 1 `<h1>`
    - 2 `<h2>`
    - 3 parágrafos (`<p>`)

## Bloco 2 – Organização

11. Criar layout com três `<div>`: topo, conteúdo e rodapé.



12. Completar estrutura de um card:
    ```html
    <div class="card">
        <h2></h2>
        <p></p>
    </div>
    ```
13. Corrigir o fechamento incorreto:
    ```html
    <div>
    <p>Texto</div>
    </p>
    ```
14. Fazer manualmente quatro cards iguais.



15. Refatorar a estrutura abaixo para melhorar a organização:
    ```html
    <div>
    <div>
    <h2>Título</h2>
    </div>
    <p>Texto</p>
    </div>
    ```
16. Criar um menu de navegação usando uma lista (`<nav><ul>...`).



17. Corrigir o `<nav>` mal estruturado:
    ```html
    <nav>
    <li>Home</li>
    <li>Contato</li>
    </nav>
    ```
18. Criar uma galeria com seis imagens, todas com `alt` apropriado.



19. Corrigir a imagem abaixo adicionando `alt`:
    ```html
    <img src="foto.png">
    ```
20. Montar um layout que contenha `<header>`, `<main>`, `<aside>` e `<footer>` (pode usar `<div>` para simular).




## Bloco 3 – Formulários

21. Criar um formulário simples com campo de nome e botão de envio.



22. Associar corretamente o `label` a um `input`:
    ```html
    <form>
    <label>Nome</label>
    <input>
    </form>
    ```
23. Corrigir o `label` mal associado:
    ```html
    <label>Email</label>
    <input type="email" id="email">
    ```
24. Criar um formulário com campos: nome, email, senha e botão submit.



25. Fazer um grupo de rádios com mesmo `name` para agrupamento.



26. Corrigir rádios não agrupados:
    ```html
    <input type="radio" name="opcao1">
    <input type="radio" name="opcao2">
    ```
27. Criar um `<select>` com quatro opções.



28. Criar um `<textarea>` acompanhado de `<label>`.



29. Montar um formulário completo com: texto, email, senha, rádio, checkbox, select e textarea.



30. Refatorar o formulário anterior usando `<fieldset>` e `<legend>`.




## Bloco 4 – Tabelas

31. Criar tabela simples 3×3.



32. Estruturar tabela com `<thead>` e `<tbody>`.



33. Corrigir tabela incompleta:
    ```html
    <table>
    <tr>
    <td>1</td>
    <td>2</td>
    </table>
    ```
34. Construir tabela com `colspan` e `rowspan`.



35. Adicionar `<caption>` corretamente.




## Bloco 5 – HTML Semântico

36. Converter um layout baseado em `<div>` para usar `<header>`, `<main>` e `<footer>`.



37. Incluir um `<nav>` dentro do `<header>`.



38. Criar três `<section>` dentro de `<main>`.



39. Inserir `<article>` dentro de uma `<section>`.



40. Criar layout com `<aside>` posicionado corretamente (lado do conteúdo principal).



41. Corrigir a estrutura semântica abaixo:
    ```html
    <header>
    <section>
    <nav></nav>
    </section>
    </header>
    ```
42. Criar um artigo com `<header>`, `<time>` e `<footer>` internos.



43. Completar a estrutura de um `<article>`:
    ```html
    <article>
    <header>
    <h2></h2>
    <time></time>
    </header>
    <p></p>
    <footer></footer>
    </article>
    ```
44. Criar um `<figure>` com `<figcaption>`.



45. Corrigir a ordem incorreta:
    ```html
    <figure>
    <figcaption>Descrição</figcaption>
    <img src="img.png">
    </figure>
    ```
46. Criar outro formulário usando `fieldset` e `legend`.



47. Refatorar uma página removendo `<div>` desnecessárias.



48. Montar uma página FAQ usando `section` e `article`.



49. Estruturar um blog com três artigos (`<article>`).



50. Refatorar um site completo aplicando semântica (header, nav, main, section, article, aside, footer, figure, time, fieldset).




## Bloco 6 – Avançados

51. Player de áudio com duas fontes (`mp3` e `ogg`) e texto de fallback.



52. Vídeo responsivo com `<video>` usando `controls`, `poster` e `width="100%"`.



53. Legendas em vídeo criando arquivo `.vtt` e usando `<track srclang="pt">`.



54. Incorporar vídeo do YouTube com `<iframe>` (sandbox + lazy loading).



55. Inserir um PDF usando `<embed>` com parágrafo de fallback.



56. Mostrar PDF com `<object>` e mensagem alternativa.



57. Aplicar atributos globais: `id`, `class` múltiplas, `style` inline e dois `data-*`.



58. Menu com links de âncora interna (`href="#id"`).



59. Elemento com `hidden` e script para remover o atributo ao clicar em botão.



60. Imagem responsiva usando `srcset` e `sizes` para várias larguras.



61. `<picture>` oferecendo `webp` e `jpeg` com media queries.



62. Ativar lazy loading em imagem e iframe e explicar benefício.



63. `<head>` com meta tags básicas: charset, viewport, description.



64. Adicionar meta tags SEO: `robots noindex`, `canonical`, `keywords`.



65. Conjunto mínimo de meta tags Open Graph (`og:title`, `og:description`, `og:image`).



66. Meta tags Twitter Card (`twitter:card`, `twitter:title`).



67. Refatorar parágrafo substituindo `<b>`/`<i>` por `<strong>`/`<em>`.



68. Texto curto com `<mark>`, `<small>` e `<abbr title="...">`. 
69. Componente de cartão com ARIA: `role="button"`, `aria-label`, `aria-hidden="true"`, `aria-live="polite"`.



70. No `<head>`, `<link rel="preload" as="font" href="/font.woff2" crossorigin">` e `<link rel="dns-prefetch" href="//cdn.example.com">`.



71. Campo com `pattern` para CEP brasileiro `00000-000`.



72. Campo `number` com `min="1"` e `max="10"`.



73. Formulário com `required` e `type="email"`.



74. Refatorar checkboxes em um `fieldset` com `legend` e labels.



75. Identificar/corrigir erro em `<iframe>` sem protocolo.



76. Link externo abrindo em nova aba seguro (`target="_blank" rel="noopener noreferrer"`).



77. Tabela de calendário usando `thead`, `tbody`, `colspan` e `rowspan`.



78. Lista ordenada aninhada sem pular níveis.



79. Aplicar `title` para tooltips em elementos diversos.



80. Script usando `dataset` para ler `data-` e exibir no console.



81. Expandir Emmet `nav>ul>li*5>a{Link $}` e descrever cada parte.



82. Gerar com Emmet `form>label+input:text[name=nome]+button{Enviar}` explicando a abreviação.




---

**Use este arquivo como referência e pratique até sentir conforto com cada conceito. Boa codificação!**

