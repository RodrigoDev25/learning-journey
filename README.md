# Learning Journey

Registro do meu aprendizado através de estudo analógico: papel, caneta e livros, com auxílio da IA para resumos e sugestões de melhoria.

## Como funciona

1. Estudo um tópico usando apenas papel, caneta e livros
2. Digitalizo minhas anotações em PDF
3. Uso IA para gerar resumo e sugestões de melhoria
4. Centralizo tudo aqui para tornar meu progresso visível e mensurável

## Estrutura
```
learning-journey/
│   
├── [tema]/
│   ├── notes/
│   │   ├── [tema]-#[n]-[livro]-(dd-mm-yyyy).pdf
│   │   └── (...)
│   │   
│   ├── [tema]-#[n]-[livro]-(dd-mm-yyyy).md
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
**Formato:** `[tema]-#[n]-[livro]-(dd-mm-yyyy)`

- **[tema]**: nome do tema da pasta
- **#[n]**: número sequencial do estudo (#1, #2, #3...)
- **[livro]**: nome curto do livro/fonte
- **(dd-mm-yyyy)**: data do estudo

**Exemplo:**
```
linux/
├── notes/
│   └── linux-#1-Linux_A_Biblia-(11-12-2025).pdf
└── linux-#1-Linux_A_Biblia-(11-12-2025).md
```

### Estrutura do Resumo

Cada arquivo `.md` deve seguir:
```markdown
# [Tema] - Estudo #[n]

**Data:** dd/mm/yyyy  
**Fonte:** [Nome completo do livro]  
**PDF:** [notes/[tema]-#[n]-[livro]-(dd-mm-yyyy).pdf](notes/[tema]-#[n]-[livro]-(dd-mm-yyyy).pdf)

## Estrutura dos resumos da IA

1. Resumo

2. Pontos de atenção e sugestões


## Fluxo de Trabalho

1. Estuda e anota em papel
2. Digitaliza → salva em `[tema]/notes/[tema]-#[n]-[livro]-(dd-mm-yyyy).pdf`
3. Usa prompt padrão da pasta `prompts/` → gera `[tema]/[tema]-#[n]-[livro]-(dd-mm-yyyy).md`
4. Verifica se o link no resumo aponta corretamente para o PDF
5. Commit: `feat([tema]): adiciona estudo #[n]`

## Padrão de Commits

- `feat([tema]): adiciona estudo #[n]`
- `chore(prompts): atualiza/inclui prompt padrão`
- `chore: ajustes na organização`

## Progresso

**Iniciado em:** [DATA]

---

*"O verdadeiro conhecimento só pode vir do estudo profundo."*