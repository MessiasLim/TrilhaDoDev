# Como Contribuir com o TrilhaDoDev

Obrigado por querer fazer parte do TrilhaDoDev! Este arquivo explica tudo o que você precisa saber para contribuir de forma organizada e profissional.

---

## Índice

1. [Antes de começar](#1-antes-de-começar)
2. [Fluxo de trabalho](#2-fluxo-de-trabalho)
3. [Estrutura do repositório](#3-estrutura-do-repositório)
4. [Padrão de pastas e arquivos](#4-padrão-de-pastas-e-arquivos)
5. [Padrão de commits](#5-padrão-de-commits)
6. [Padrão de Pull Request](#6-padrão-de-pull-request)
7. [Criando uma nova trilha](#7-criando-uma-nova-trilha)
8. [Critérios de qualidade](#8-critérios-de-qualidade)
9. [O que NÃO fazer](#9-o-que-não-fazer)
10. [Dúvidas e contato](#10-dúvidas-e-contato)

---

## 1. Antes de começar

### Pré-requisitos

- Ter uma conta no [GitHub](https://github.com)
- Ter o [Git](https://git-scm.com) instalado na sua máquina
- Ter o [VS Code](https://code.visualstudio.com) ou outro editor de código
- Conhecer o básico de Git (fork, clone, branch, commit, push, pull request)

> **Nunca usou Git?** Sem problema! Comece pelo nosso material em `/fundamentos/git-github/` antes de contribuir.

### Leia antes de qualquer coisa

- [`README.md`](./README.md) — Visão geral do projeto e mapa de trilhas
- [`TEMPLATE.md`](./TEMPLATE.md) — Template obrigatório para criar conteúdo

---

## 2. Fluxo de trabalho

Todo colaborador deve seguir este fluxo. Ele simula o ambiente real de trabalho em empresas de tecnologia.

```
1. Fork  →  2. Clone  →  3. Branch  →  4. Desenvolve  →  5. Commit  →  6. Push  →  7. Pull Request
```

### Passo a passo

**1. Fork**
Clique em "Fork" no repositório oficial para criar uma cópia na sua conta.

**2. Clone**
```bash
git clone https://github.com/SEU-USUARIO/TrilhaDoDev.git
cd TrilhaDoDev
```

**3. Branch**

Crie uma branch com um nome descritivo:
```bash
# Para novo conteúdo
git checkout -b feature/backend-java-introducao

# Para correção de erro
git checkout -b fix/html-semantica-typo

# Para melhoria de conteúdo existente
git checkout -b improve/css-flexbox-exemplos
```

**4. Desenvolva**
Crie ou edite o conteúdo seguindo o [padrão de pastas](#4-padrão-de-pastas-e-arquivos) e os [critérios de qualidade](#8-critérios-de-qualidade).

**5. Commit**
```bash
git add .
git commit -m "feat(backend/java): adiciona introducao e primeiros exemplos"
```
> Veja o [padrão de commits](#5-padrão-de-commits) para mais detalhes.

**6. Push**
```bash
git push origin feature/backend-java-introducao
```

**7. Pull Request**
Abra um Pull Request no repositório original. Siga o [padrão de PR](#6-padrão-de-pull-request).

---

## 3. Estrutura do repositório

```
TrilhaDoDev/
│
├── fundamentos/              # Base obrigatória para todo dev
│   ├── html/
│   ├── css/
│   ├── javascript/
│   ├── git-github/
│   └── exercicios/
│
├── frontend/                 # Frameworks e bibliotecas de interface
│   ├── react/
│   ├── vue/
│   ├── svelte/
│   └── typescript/
│
├── backend/                  # Servidores, APIs e lógica de negócio
│   ├── _conceitos-gerais/    # Teoria agnóstica de linguagem (ex: o que é REST)
│   ├── node-javascript/
│   ├── java/
│   ├── python/
│   ├── csharp/
│   ├── php/
│   └── go/
│
├── mobile/                   # Desenvolvimento de aplicativos
│   ├── react-native/
│   ├── flutter/
│   └── kotlin/
│
├── games/                    # Desenvolvimento de jogos
│   ├── unity-csharp/
│   ├── godot/
│   └── pygame/
│
├── devops/                   # Infraestrutura e automação
│   ├── docker/
│   ├── github-actions/
│   └── deploy/
│
├── banco-de-dados/           # SQL e bancos NoSQL
│   ├── sql/
│   ├── postgresql/
│   └── mongodb/
│
├── inteligencia-artificial/  # IA e Machine Learning
│   ├── python-basico/
│   └── machine-learning/
│
├── CONTRIBUTING.md           # Este arquivo
├── TEMPLATE.md               # Template obrigatório para novo conteúdo
└── README.md                 # Mapa geral do projeto
```

---

## 4. Padrão de pastas e arquivos

Toda pasta de tecnologia ou módulo **deve** seguir esta estrutura. Use o [`TEMPLATE.md`](./TEMPLATE.md) como ponto de partida.

```
trilha/tecnologia/modulo/
├── README.md        # Obrigatório: visão geral do módulo
├── conceito.md      # Explicação teórica clara e objetiva
├── exemplo/         # Código funcional comentado
│   ├── index.html   # (ou o arquivo principal da linguagem)
│   └── README.md    # Explica o que o exemplo faz
└── exercicio.md     # Desafio prático para o leitor resolver
```

### Regras de nomenclatura

| O que | Formato | Exemplo |
|---|---|---|
| Pastas | `kebab-case` | `arrays-objetos`, `apis-rest` |
| Arquivos Markdown | `kebab-case.md` | `conceito.md`, `exercicio.md` |
| Arquivos de código | Siga a convenção da linguagem | `Main.java`, `index.js` |

### Conceitos compartilhados entre linguagens

Se um conceito é o mesmo independente da linguagem (ex: o que é uma API REST, o que é orientação a objetos), coloque a **explicação teórica** em `_conceitos-gerais/` dentro da trilha. Cada pasta de linguagem deve ter apenas a **implementação prática** daquele conceito.

```
backend/
├── _conceitos-gerais/
│   └── o-que-e-api-rest.md     ← teoria aqui (uma vez só)
├── node-javascript/
│   └── apis-rest/              ← implementação em Node
└── java/
    └── apis-rest/              ← implementação em Java
```

---

## 5. Padrão de commits

Usamos o padrão **Conventional Commits**. Ele torna o histórico do projeto legível e profissional.

```
tipo(escopo): descrição curta em minúsculas
```

### Tipos permitidos

| Tipo | Quando usar |
|---|---|
| `feat` | Novo conteúdo ou funcionalidade |
| `fix` | Correção de erro, typo ou informação errada |
| `improve` | Melhoria em conteúdo já existente |
| `docs` | Alteração em README, CONTRIBUTING ou documentação geral |
| `refactor` | Reorganização de pastas ou arquivos sem mudar o conteúdo |
| `chore` | Tarefas de manutenção (ex: atualizar links quebrados) |

### Exemplos

```bash
feat(backend/java): adiciona modulo de introducao com conceito e exemplo
fix(frontend/react): corrige erro no exemplo de useState
improve(fundamentos/css): adiciona mais exemplos ao modulo de flexbox
docs(contributing): atualiza secao de fluxo de trabalho
refactor(mobile): reorganiza estrutura de pastas do flutter
```

---

## 6. Padrão de Pull Request

Ao abrir um PR, preencha o título e a descrição seguindo este modelo:

### Título
```
feat(backend/java): adiciona módulo de introdução
```

### Descrição (cole este template no seu PR)

```markdown
## O que foi feito?
Descreva de forma clara o que você adicionou, corrigiu ou melhorou.

## Trilha afetada
- [ ] fundamentos
- [ ] frontend
- [ ] backend
- [ ] mobile
- [ ] games
- [ ] devops
- [ ] banco-de-dados
- [ ] inteligencia-artificial

## Checklist
- [ ] Segui a estrutura de pastas do CONTRIBUTING.md
- [ ] Usei o TEMPLATE.md como base
- [ ] O conteúdo tem: conceito, exemplo e exercício
- [ ] Os arquivos estão nomeados em kebab-case
- [ ] Testei o código dos exemplos (se houver)
- [ ] Não há erros de português ou informações incorretas

## Observações
Alguma dúvida, contexto extra ou sugestão para o revisor?
```

---

## 7. Criando uma nova trilha

Se quiser propor uma trilha que ainda não existe (ex: `seguranca`, `blockchain`):

1. **Abra uma Issue** antes de qualquer código com o título: `[Nova Trilha] Nome da Trilha`
2. Descreva: o que será ensinado, tecnologias cobertas e quem seria o mentor responsável
3. Aguarde a aprovação do líder do projeto
4. Após aprovação, crie a estrutura seguindo o padrão do repositório e abra o PR

> PRs de novas trilhas sem Issue aprovada prévia serão recusados.

---

## 8. Critérios de qualidade

Todo conteúdo enviado será revisado com base nestes critérios:

### Conteúdo
- ✅ Tem explicação conceitual clara (o "porquê", não só o "como")
- ✅ Tem exemplo de código funcional e comentado
- ✅ Tem exercício prático para o leitor
- ✅ Menciona erros comuns e como evitá-los
- ✅ Português correto e linguagem acessível

### Código
- ✅ Funciona corretamente (testado antes do PR)
- ✅ Está comentado nos pontos importantes
- ✅ Segue as boas práticas da linguagem/tecnologia
- ✅ HTML e CSS seguem padrões de acessibilidade (ARIA, semântica)
- ✅ CSS segue abordagem Mobile-First

### Estrutura
- ✅ Pastas e arquivos nomeados em `kebab-case`
- ✅ Tem `README.md` na pasta do módulo
- ✅ Segue a hierarquia definida neste documento

---

## 9. O que NÃO fazer

- ❌ Não commite direto na branch `main`
- ❌ Não copie conteúdo de outros sites sem adaptar e citar a fonte
- ❌ Não crie pastas com espaços ou letras maiúsculas (`Minha Pasta/` → ❌, `minha-pasta/` → ✅)
- ❌ Não abra PR com conteúdo incompleto (sem exemplo ou sem exercício)
- ❌ Não crie uma nova trilha sem aprovação prévia via Issue
- ❌ Não altere arquivos de outra pessoa sem abrir uma Issue explicando o motivo

---

## 10. Dúvidas e contato

> Ficou com dúvida sobre como usar este template? Abra uma Issue com a tag `duvida` ou entre em contato com o líder do projeto.

