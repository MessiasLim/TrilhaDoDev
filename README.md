# Trilha do Dev — Material de Referência

> Este é um **material educacional e de referência** que eu organizo e mantenho. 

**Propósito**: Recurso de aprendizado estruturado  
**Não é**: Um portfólio project (veja meus outros repositórios)

---

## Como usar este material

Este repositório é útil se você está:
- Aprendendo fundamentos de web
- Procurando material de referência organizado
- Preparando conteúdo educacional

**Para ver meus projetos de produção**, procure nos meus [repositórios](https://github.com/MessiasLim?tab=repositories) no meu perfil.

---

## Estrutura do Repositório

```
.
├── html/                    # Fundamentos de HTML & padrões avançados
│   ├── estrutura-basica/
│   ├── semantica/
│   ├── forms/               # Padrões de formulários com validação & acessibilidade
│   ├── acessibilidade/      # ARIA, leitores de tela, HTML semântico
│   └── seo-meta-tags/       # Boas práticas de SEO
├── css/                     # Layouts em CSS & padrões de componentes
│   ├── fundamentos/         # Seletores, box-model, posicionamento
│   ├── layout/              # Flexbox, Grid, técnicas responsivas
│   ├── componentes/         # Botões, cards e formulários reutilizáveis
│   ├── animacoes/           # Transições & animações
│   └── responsivo/          # Media queries mobile-first
├── javascript/              # Fundamentos de JavaScript
│   ├── sintaxe/             # Variáveis, operadores, fluxo de controle
│   ├── dom/                 # Padrões de manipulação do DOM
│   ├── eventos/             # Boas práticas com eventos
│   └── arrays-objetos/      # Estruturas de dados & métodos
├── git-github/              # Versionamento com Git e GitHub
│   └── curso-git-github.md
├── exercicios/              # Desafios progressivos
│   ├── exercicios-html/
│   ├── exercicios-css/
│   └── exercicios-js/
└── README.md                # Guia de referência
```

---

Aqui está a versão direta, focando exclusivamente em clonar e rodar o projeto na máquina:

---

## Instalação Local

Siga os passos abaixo para baixar o código e abrir o projeto no seu computador:

### 1. Clone o repositório
Abra o terminal do seu computador e execute o comando abaixo para baixar o projeto:

```bash
git clone https://github.com/MessiasLim/TrilhaDoDev.git
```

### 2. Acesse a pasta do projeto
Entre no diretório que acabou de ser criado:

```bash
cd TrilhaDoDev
```

---

## Como Executar o Projeto

Agora que você já tem o código na sua máquina, escolha uma das opções abaixo para abrir o projeto no navegador:

### Opção 1: Live Server (VS Code)

```bash
# Abra a pasta do projeto no VS Code (code .)
# Instale a extensão "Live Server"
# Clique com o botão direito no arquivo index.html -> "Open with Live Server"
```

### Opção 2: Servidor HTTP com Node.js

```bash
npx http-server . -c-1 -p 8080
# Abra no navegador: http://localhost:8080
```

## Caminho de Aprendizado

**Progressão recomendada:**

1. **Semana 1-2**: Fundamentos de HTML + semântica
2. **Semana 3-4**: Fundamentos de CSS + Flexbox
3. **Semana 5-6**: CSS Grid + Design responsivo
4. **Semana 7-8**: Sintaxe de JavaScript + DOM
5. **Semana 9+**: Construir projetos combinando os três

Cada seção inclui:

* Conceitos com exemplos
* Casos de uso reais
* Boas práticas & armadilhas comuns
* Exercícios progressivos

---

## Principais Tópicos Abordados

### HTML5

* Elementos semânticos (`<article>`, `<section>`, `<nav>`, etc.)
* Formulários com validação & acessibilidade
* Roles e atributos ARIA
* Meta tags de SEO & dados estruturados
* Otimização de performance (`loading="lazy"`, imagens responsivas)

### CSS3

* Layouts modernos: **Flexbox** & **CSS Grid**
* Padrões de design responsivo
* Variáveis CSS & propriedades customizadas
* Animações & transições
* Abordagem mobile-first

### JavaScript ES6+

* Variáveis & escopo (`let`, `const`)
* Funções & arrow functions
* Manipulação do DOM & eventos
* Conceitos básicos de assíncrono (callbacks, introdução a promises)
* Métodos de array (`map`, `filter`, `reduce`)

---

## Por que este repositório?

* **2 Anos de Prática**: Refinado com base em cenários reais
* **Aprendizado Estruturado**: Evolução do básico ao avançado
* **Boas Práticas**: Padrões da indústria com foco em acessibilidade
* **Prático**: Todo conceito tem exemplos funcionais
* **Sem Enrolação**: Focado no que você realmente usa em produção

---

## Recursos & Ferramentas

### Ferramentas Recomendadas

* **Live Server** — Visualização em tempo real
* **Prettier** — Formatação de código (consistência)
* **Extensões VS Code**: Auto Rename Tag, CSS Peek, ES7+ snippets

### Links de Referência

* [Mozilla](https://developer.mozilla.org/en-US/docs/Web/HTML/Guides) — Documentação de referência para HTML
* [Mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides) — Documentação de referência para CSS
* [Mozilla](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide) — Documentação de referência para JavaScript
* [LeetCode](https://leetcode.com/problemset/) — Estrutura dos exercicíos

---

## Para quem é isso?

- **Iniciantes** começando no desenvolvimento web
- **Autodidatas** construindo uma base sólida
- **Alunos de bootcamp** que precisam de referência
- **Pessoas em transição de carreira** aprendendo fundamentos
- **Educadores** buscando conteúdo bem organizado

---

## Recursos Especiais

### Complexidade Progressiva

Cada seção começa simples e evolui gradualmente. Você pode seguir a ordem ou ir direto ao ponto.

### Exemplos do Mundo Real

O código reflete padrões reais usados em produção, não apenas teoria.

### Abordagem Mobile-First

Todos os exemplos seguem práticas modernas de responsividade.

### Acessibilidade desde o início

HTML e CSS já incluem padrões ARIA e semântica desde a base.

---

## Como usar

### Para Aprender

1. Escolha um tema (HTML → CSS → JS recomendado)
2. Leia a explicação
3. Estude os exemplos
4. Faça os exercícios

### Para Referência

Use a busca do navegador (Ctrl+F):

* "flexbox" → todos os padrões de flexbox
* "form" → exemplos de formulários
* "event" → manipulação de eventos

### Para Ensinar

Você pode reutilizar os conteúdos diretamente no seu material.

---

## Resultados de Aprendizado

Ao concluir esta trilha, você será capaz de:

* Escrever HTML semântico e acessível
* Criar layouts responsivos com Flexbox e Grid
* Manipular o DOM e lidar com eventos
* Estruturar CSS de forma profissional
* Aplicar padrões e boas práticas da web

---

## Observações sobre o conteúdo

Este repositório representa **2 anos de aprendizado acumulado**, refinado na prática. Inclui:

* Explicações conceituais
* Exemplos práticos
* Erros comuns e como evitá-los
* Boas práticas para código em produção
* Links para aprofundamento

---

## Próximos Passos

Depois de dominar essa base:

1. **Crie projetos**: Combine HTML + CSS + JS
2. **Aprenda um framework**: React, Vue ou Svelte
3. **Back-end**: Node.js, bancos de dados, APIs
4. **Deploy**: GitHub Pages, Vercel, Netlify

---

## Licença

Este conteúdo é disponibilizado como material educacional. Sinta-se livre para usar, compartilhar e evoluir.

---

## Achou útil?

Se essa trilha te ajudou, deixe uma estrela no repositório! Isso ajuda outras pessoas a encontrarem conteúdo de qualidade no GitHub.

---

**Última atualização**: Maio de 2026
**Status**: Ativo e sendo atualizado regularmente
