# Learning Journey

Registro do meu aprendizado através de estudo analógico: papel, caneta e livros. Eventualmente cursos digitais podem complementar, mas o foco permanece em estudos sem tecnologia durante as sessões de aprendizado. IA auxilia apenas na fase de revisão para gerar resumos e sugestões de melhoria.

## Como Funciona

1. Estudo um tópico usando principalmente papel, caneta e livros (ocasionalmente cursos digitais)
2. Digitalizo minhas anotações em PDF
3. Uso IA para gerar resumo e sugestões de melhoria
4. Centralizo tudo aqui para tornar meu progresso visível e mensurável

## Estrutura
```
learning-journey/
│   
├── [tema]/
│   ├── notes/
│   │   ├── [tema]-#[n]-[fonte]-(dd-mm-yyyy).pdf
│   │   └── (...)
│   │   
│   ├── [tema]-#[n]-[fonte]-(dd-mm-yyyy).md
│   └── (...) 
│
├── prompts/
│   └── [prompt].md
│   
└── README.md
```

## Convenções de Nomenclatura

### Pastas de Temas

- Nome em minúsculas com hífens: `wordpress-woocommerce`, `linux`
- Um tema = uma pasta

### Arquivos

**Formato:** `[tema]-#[n]-[fonte]-(dd-mm-yyyy)`

- **[tema]**: nome do tema da pasta
- **#[n]**: número sequencial do estudo (#1, #2, #3...)
- **[fonte]**: nome curto do livro ou curso
- **(dd-mm-yyyy)**: data do estudo

**Exemplo:**
```
linux/
├── notes/
│   └── linux-#1-Linux_A_Biblia-(11-12-2024).pdf
└── linux-#1-Linux_A_Biblia-(11-12-2024).md
```

### Estrutura do Resumo

Cada arquivo `.md` deve seguir:
```markdown
# [Tema] - Estudo #[n]

**Data:** dd/mm/yyyy  
**Fonte:** [Nome completo do livro ou curso]  
**PDF:** [notes/[tema]-#[n]-[fonte]-(dd-mm-yyyy).pdf](notes/[tema]-#[n]-[fonte]-(dd-mm-yyyy).pdf)

## Resumo da IA

[Resumo gerado pela IA]

## Pontos de Atenção e Sugestões

[Pontos de atenção e sugestões da IA]
```

## Fluxo de Trabalho

1. Estuda e anota em papel (ou acompanha curso fazendo anotações)
2. Digitaliza → salva em `[tema]/notes/[tema]-#[n]-[fonte]-(dd-mm-yyyy).pdf`
3. Usa prompt padrão da pasta `prompts/` → gera `[tema]/[tema]-#[n]-[fonte]-(dd-mm-yyyy).md`
4. Verifica se o link no resumo aponta corretamente para o PDF
5. Commit: `feat([tema]): adiciona estudo #[n]`

## Padrão de Commits

- `feat([tema]): adiciona estudo #[n]`
- `chore(prompts): atualiza/inclui prompt padrão`
- `chore: ajustes na organização`

## Progresso

**Iniciado em:** dezembro/2024

---

*"O verdadeiro conhecimento só pode vir do estudo profundo."*