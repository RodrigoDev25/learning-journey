# Learning Journey

> **Registro estruturado de aprendizado autodidata profundo, conduzido majoritariamente sem ferramentas digitais.**

---

## Visão Geral

Este projeto documenta um processo de aprendizado autodidata conduzido majoritariamente sem o uso de ferramentas digitais. O estudo é realizado com papel, caneta e livros físicos, com exceções pontuais para alguns cursos. As anotações são analisadas por IA **exclusivamente na fase de revisão**, e o progresso é versionado com Git e mantido no GitHub.

> **Uso de IA:** restrito à análise, síntese e sugestões de melhoria durante a revisão.

---

## Objetivo

Documentar o progresso de estudo de forma **clara, rastreável e mensurável**. Este repositório registra um percurso real de aprendizado.

---

## Como Funciona

1. Geração de plano de estudo por meio de prompt especializado
2. Estudo com papel, caneta e livros físicos
3. Digitalização das anotações manuscritas em PDF
4. Análise do material pela IA e geração de resumo estruturado
5. Registro e versionamento de todo o conteúdo no repositório

---

## Estrutura do Repositório

```text
learning-journey/
│
├── prompts/
│   └── [prompt].md
│
├── [tema]/
│   ├── notes/
│   │   └── [tema]-#[n]-[fonte]-(dd-mm-yyyy).pdf
│   │
│   ├── #Plano-de-estudo.md
│   └── [tema]-#[n]-[fonte]-(dd-mm-yyyy).md
│
└── README.md
```

---

## Nomenclatura

### Pastas

* Letras minúsculas com hífens
  Exemplos: `linux`, `wordpress-woocommerce`
* Um tema por pasta

### Arquivos de Estudo

Formato:

```
[tema]-#[n]-[fonte]-(dd-mm-yyyy)
```

**Componentes:**

* `[tema]` — nome da pasta
* `#[n]` — número sequencial do estudo
* `[fonte]` — nome curto do livro ou curso
* `(dd-mm-yyyy)` — data da sessão de estudo

**Exemplo:**

```text
linux/
├── notes/
│   └── linux-#1-Linux_A_Biblia-(11-12-2024).pdf
│
├── #Plano-de-estudo.md
└── linux-#1-Linux_A_Biblia-(11-12-2024).md
```

---

## Estrutura dos Arquivos de Revisão

Cada sessão de estudo gera um arquivo `.md` padronizado, com apoio da IA:

```markdown
# [Tema] — Estudo #[n]

**Data:** dd/mm/yyyy  
**Fonte:** [Nome completo]  
**PDF:** [notes/[arquivo].pdf](notes/[arquivo].pdf)

---

## Resumo
[Síntese objetiva do conteúdo]

---

## Progressão
[Evolução em relação a estudos anteriores]

---

## Visão Macro
[Avaliação do estágio atual do aprendizado]

---

## Pontos de Atenção
- [Conceitos que exigem revisão]
- [Possíveis lacunas]

---

## Sugestões
- [Próximos tópicos]
- [Exercícios recomendados]
```

---

## Fluxo com Git

1. Estudo e anotações em papel
2. Digitalização → `notes/[arquivo].pdf`
3. Análise via IA → `[arquivo].md`
4. Verificação de links e consistência
5. Commit semântico

### Padrão de Commits

* `feat([tema]): adiciona estudo #[n]`
* `chore(prompts): atualiza prompt`
* `chore: ajustes de organização`

---

## Progresso

**Iniciado em:** dezembro/2025

Este repositório cresce de forma incremental, refletindo um processo de aprendizado **real, contínuo e verificável**.

---

> *“O verdadeiro conhecimento nasce do estudo profundo e disciplinado.”*
