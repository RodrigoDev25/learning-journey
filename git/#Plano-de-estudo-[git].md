# Jornada: GIT

**Do zero ao domínio • Português do Brasil • 100% Analógico**

**Objetivo:** Dominar controle de versão com Git através de um único livro completo e prática manuscrita intensiva.

---

## LIVRO DA TRILHA

### Livro Único — Domínio Completo
**Controlando Versões com Git e GitHub** — Alexandre Aquiles e Rodrigo Ferreira | Casa do Código  

Cobre desde o absoluto básico (o que é controle de versão) até tópicos avançados (branches, merges, conflitos, trabalho remoto, GitHub) de forma progressiva e prática.

**Por que um livro é suficiente:**
- Git é uma ferramenta específica com escopo bem definido
- Este livro cobre 100% do que você precisa: conceitos, comandos e fluxos de trabalho
- A maestria vem da prática intensiva, não de múltiplas fontes teóricas
- 199 páginas focadas são mais eficazes que 3 livros com redundância

**Progressão interna do livro:**
Fundamentos → Trabalho Local → Branches → Trabalho Remoto → GitHub → Casos Avançados

---

## PLANO DE ESTUDO

### FASE 1 • Fundamentos do Controle de Versão

**Meta:** Compreender POR QUE Git existe e como funciona conceitualmente.

**Conteúdos essenciais:**
- O que é controle de versão e por que usar
- História do Git (criado por Linus Torvalds)
- Diferença entre Git e outros sistemas (CVS, SVN)
- Conceito de repositório
- Estados dos arquivos (working directory, staging area, repository)
- Instalação e configuração inicial

**Como estudar (passo a passo):**

1. **Ler:** Capítulos iniciais sobre conceitos. Não pule essa parte teórica! Para cada conceito novo (repositório, commit, staging), pergunte-se: "Por que isso existe? Que problema resolve?"

2. **Anotar:** Crie no caderno uma **PÁGINA DE CONCEITOS FUNDAMENTAIS**:
   - Desenhe um diagrama mostrando os 3 estados (working directory → staging area → repository)
   - Anote definições em suas próprias palavras
   - Crie analogias (exemplo: "staging area é como separar roupas antes de lavar")

3. **Praticar SEM COMPUTADOR:**
   - **Simulação de Estados:** Pegue 3 folhas de papel. Nomeie: "Working", "Staging", "Repository"
   - Escreva nomes de arquivos fictícios em post-its pequenos
   - Simule movendo os post-its entre as folhas conforme você entende os comandos
   - Exemplo: arquivo "index.html" está em Working → você faz `git add` → move para Staging → você faz `git commit` → move para Repository

4. **Revisar:** Escreva uma carta de 1 página explicando para um amigo leigo "o que é Git e por que ele deveria usar". Se conseguir explicar de forma clara, você entendeu.

5. **Testar:** Responda no papel sem consultar:
   - Qual a diferença entre Git e GitHub?
   - Quais são os 3 estados de um arquivo?
   - O que é um commit?
   - O que é staging area?

**Domine antes de avançar:**
- [ ] Explica o que é controle de versão e suas vantagens
- [ ] Diferencia Git de GitHub (Git = ferramenta, GitHub = plataforma web)
- [ ] Desenha de memória o diagrama dos 3 estados
- [ ] Entende o conceito de commit (snapshot do projeto)
- [ ] Conhece a diferença entre Git e sistemas centralizados (SVN)

**Só avance se:** Conseguir desenhar o fluxo completo de um arquivo desde criação até commit, nomeando cada etapa e comando.

---

### FASE 2 • Trabalho Local com Git

**Meta:** Dominar todos os comandos para trabalhar sozinho localmente.

**Conteúdos essenciais:**
- Criar repositório (`git init`)
- Verificar status (`git status`)
- Adicionar arquivos (`git add`)
- Fazer commits (`git commit`)
- Ver histórico (`git log`)
- Desfazer mudanças
- Ver diferenças (`git diff`)
- Ignorar arquivos (`.gitignore`)

**Como estudar (passo a passo):**

1. **Ler:** Leia cada seção sobre comandos básicos. Para cada comando, anote: (a) o que faz, (b) quando usar, (c) sintaxe, (d) opções comuns.

2. **Anotar:** Crie o **MANUAL DE COMANDOS** no caderno (reserve 10-15 páginas):

   Para cada comando, use este formato de página:
   
   ```
   COMANDO: git add
   
   O QUE FAZ: Move arquivos de working directory para staging area
   
   QUANDO USAR: Antes de fazer commit, para escolher o que incluir
   
   SINTAXE BÁSICA:
   - git add arquivo.txt (adiciona arquivo específico)
   - git add . (adiciona tudo)
   - git add *.js (adiciona todos os .js)
   
   IMPORTANTE:
   - Não adiciona automaticamente ao commit, só prepara
   - Pode adicionar múltiplas vezes antes do commit
   
   FLUXO COMUM:
   1. Modifica arquivo
   2. git add arquivo
   3. git commit -m "mensagem"
   ```

3. **Praticar COM PAPEL (Simulação Manuscrita):**
   
   **Exercício do Projeto Fictício:**
   - Imagine um projeto simples (ex: um site com 3 arquivos: index.html, style.css, script.js)
   - Crie uma tabela com 4 colunas: "Ação", "Comando Git", "Estado dos Arquivos", "Resultado"
   - Simule um fluxo completo no papel:
   
   | Ação | Comando | Estado | Resultado |
   |------|---------|--------|-----------|
   | Criar projeto | git init | Repositório vazio criado | .git/ criado |
   | Criar index.html | [edição] | Working: index.html (new) | Arquivo não rastreado |
   | Adicionar ao stage | git add index.html | Staging: index.html | Pronto para commit |
   | Fazer commit | git commit -m "Adiciona index" | Repository: index.html (v1) | Commit 1 criado |
   | Editar index.html | [edição] | Working: index.html (modified) | Mudanças não staged |
   | [continue...] | | | |
   
   Faça isso para pelo menos 15-20 ações diferentes.

4. **Revisar:** A cada 5 comandos aprendidos, crie um **CHEAT SHEET** visual de 1 página com os comandos mais usados e suas relações.

5. **Testar:** Sem consultar o livro, escreva no papel:
   - Sequência completa de comandos para: criar repo → adicionar 3 arquivos → fazer 2 commits → ver histórico
   - Como desfazer mudanças em cada estado (working, staging, committed)
   - Diferença entre `git diff`, `git diff --staged`, e `git diff HEAD`

**Domine antes de avançar:**
- [ ] Cria repositório do zero (`git init`)
- [ ] Verifica status a qualquer momento (`git status`)
- [ ] Adiciona arquivos seletivamente (`git add`)
- [ ] Faz commits com mensagens claras
- [ ] Visualiza histórico e entende o que vê (`git log`)
- [ ] Desfaz mudanças em diferentes estados
- [ ] Usa `.gitignore` corretamente
- [ ] Entende diferença entre working directory, staging e repository na prática

**Só avance se:** Conseguir simular no papel um fluxo completo de 10 commits com adições, modificações e exclusões de arquivos, escrevendo todos os comandos corretos.

---

### FASE 3 • Branches e Merges

**Meta:** Dominar ramificação e unificação de trabalho paralelo.

**Conteúdos essenciais:**
- O que são branches e por que usar
- Criar branches (`git branch`)
- Trocar de branch (`git checkout`)
- Merge (fusão) de branches
- Conflitos e como resolver
- Estratégias de branching
- Deletar branches

**Como estudar (passo a passo):**

1. **Ler:** Leia a seção de branches. Este é um conceito crucial - releia se necessário até entender completamente.

2. **Anotar:** Crie **DIAGRAMAS DE BRANCHES** no caderno:

   Use essa notação visual (exemplo):
   ```
   main:     A --- B --- C --- D --- E
                    \           /
   feature:          X --- Y ---
   ```
   
   Para cada cenário do livro, desenhe o diagrama correspondente. Pratique desenhar:
   - Branch simples
   - Merge sem conflito
   - Merge com conflito
   - Branch de branch
   - Múltiplos branches simultâneos

3. **Praticar COM PAPEL (Simulação Visual Intensiva):**

   **Exercício da Árvore de Commits:**
   - Use uma folha grande (ou várias folhas coladas)
   - Simule um projeto com 3 branches: main, feature-login, feature-design
   - Desenhe cada commit como um círculo com letra dentro (A, B, C...)
   - Anote acima de cada commit o que foi feito
   - Desenhe linhas conectando commits (setas para mostrar histórico)
   - Simule merges desenhando as linhas de união
   - Quando houver "conflito", marque em vermelho e anote como resolver
   
   Faça isso para pelo menos 3 cenários diferentes de complexidade crescente.

4. **Revisar:** Crie uma **TABELA DE COMANDOS DE BRANCH**:
   
   | Comando | O que faz | Quando usar |
   |---------|-----------|-------------|
   | git branch nome | Cria branch | Antes de começar nova feature |
   | git checkout nome | Muda para branch | Para trabalhar em branch específico |
   | git merge nome | Traz mudanças de outro branch | Quando feature está pronta |
   | git branch -d nome | Deleta branch | Após merge bem-sucedido |

5. **Testar:** Simule no papel (desenhando toda a árvore):
   - Projeto começa em main com commits A, B, C
   - Crie branch "feature-x" a partir de C
   - Faça commits D e E em feature-x
   - Enquanto isso, commit F acontece em main
   - Faça merge de feature-x em main
   - Resolva o conflito entre E e F
   - Desenhe como fica o histórico final

**Domine antes de avançar:**
- [ ] Cria e navega entre branches fluidamente
- [ ] Entende quando e por que criar branches
- [ ] Faz merges simples
- [ ] Identifica e resolve conflitos (sabe o que são as marcações <<<<, ====, >>>>)
- [ ] Desenha árvores de commits com branches
- [ ] Conhece workflows comuns (feature branch, release branch)
- [ ] Sabe deletar branches após merge

**Só avance se:** Conseguir desenhar uma árvore de commits complexa (3+ branches, 15+ commits, 2+ merges com conflitos) e anotar todos os comandos necessários para criar aquela estrutura.

---

### FASE 4 • Trabalho Remoto e GitHub

**Meta:** Dominar colaboração usando repositórios remotos.

**Conteúdos essenciais:**
- O que são repositórios remotos
- GitHub como plataforma
- Clonar repositório (`git clone`)
- Conectar remoto (`git remote`)
- Enviar mudanças (`git push`)
- Buscar mudanças (`git fetch` e `git pull`)
- Fork e Pull Request
- Colaboração em equipe

**Como estudar (passo a passo):**

1. **Ler:** Leia sobre trabalho remoto. Preste atenção especial nas diferenças entre `fetch` e `pull`.

2. **Anotar:** Crie **MAPA DE REPOSITÓRIOS LOCAIS E REMOTOS**:
   
   Desenhe dois quadros no caderno:
   
   ```
   [COMPUTADOR LOCAL]          [SERVIDOR REMOTO (GitHub)]
   
   Working Directory           origin/main
   Staging Area         ←→     (repositório remoto)
   Local Repository
   ```
   
   Anote ao lado de cada seta qual comando a atravessa:
   - `git push` → envia local para remoto
   - `git fetch` → baixa remoto para local (sem aplicar)
   - `git pull` → baixa e aplica (fetch + merge)
   - `git clone` → copia remoto inteiro para local

3. **Praticar COM PAPEL (Simulação de Colaboração):**

   **Exercício de Dois Desenvolvedores:**
   - Imagine dois desenvolvedores (Dev A e Dev B) trabalhando no mesmo projeto
   - Crie 3 colunas: "Dev A", "Servidor", "Dev B"
   - Simule uma sequência de ações:
   
   ```
   Tempo | Dev A | Servidor (origin) | Dev B
   ------+-------+-------------------+-------
   T1    | clone repo | main: A-B-C | clone repo
   T2    | commit D em main | - | commit E em main
   T3    | push (sucesso!) | main: A-B-C-D | -
   T4    | - | - | push (ERRO! desatualizado)
   T5    | - | - | pull (baixa D)
   T6    | - | - | merge local D+E
   T7    | - | - | push (sucesso!)
   T8    | - | main: A-B-C-D-E-MERGE | -
   T9    | pull | - | -
   T10   | agora tem tudo | - | -
   ```
   
   Faça essa simulação para 3 cenários diferentes.

4. **Revisar:** Crie um **GUIA DE RESOLUÇÃO DE PROBLEMAS COMUNS**:
   
   - **Problema:** Push rejeitado (rejected)
     **Causa:** Servidor tem commits que você não tem
     **Solução:** git pull → resolver conflitos → git push
   
   - **Problema:** Mudanças locais conflitam com pull
     **Causa:** Você tem modificações não commitadas
     **Solução:** git stash → git pull → git stash pop
   
   [Continue para outros problemas...]

5. **Testar:** Sem consultar o livro, responda no papel:
   - Diferença entre `git fetch` e `git pull`
   - Sequência de comandos para: clonar repo → criar branch → fazer mudanças → enviar para GitHub
   - Como resolver "push rejected"
   - O que é fork? Diferença entre fork e clone?
   - O que é Pull Request?

**Domine antes de avançar:**
- [ ] Clona repositórios remotos
- [ ] Conecta repositório local a remoto
- [ ] Envia mudanças com push
- [ ] Baixa mudanças com fetch e pull
- [ ] Diferencia fetch de pull
- [ ] Resolve conflitos em colaboração
- [ ] Entende workflow fork + pull request
- [ ] Sabe usar `origin` e outros remotos

**Só avance se:** Conseguir simular no papel uma colaboração completa entre 3 desenvolvedores com 10+ commits, 2+ branches, conflitos resolvidos, e todos os comandos anotados corretamente.

---

### FASE 5 • Tópicos Avançados

**Meta:** Dominar recursos avançados para casos complexos.

**Conteúdos essenciais:**
- Tags (versões)
- Rebase (alternativa ao merge)
- Cherry-pick (aplicar commits específicos)
- Reset e revert (desfazer commits)
- Stash (guardar mudanças temporariamente)
- Reflog (histórico de mudanças)
- Aliases (atalhos)
- Hooks (automações)

**Como estudar (passo a passo):**

1. **Ler:** Leia cada tópico avançado. Não precisa memorizar tudo - foque em entender QUANDO usar cada recurso.

2. **Anotar:** Crie **GUIA DE QUANDO USAR O QUÊ**:
   
   ```
   SITUAÇÃO → COMANDO
   
   Quero marcar versão estável → git tag v1.0
   
   Quero histórico linear (sem merges) → git rebase
   
   Quero aplicar só 1 commit específico → git cherry-pick
   
   Quero desfazer commit mas manter código → git reset --soft
   
   Quero desfazer commit e apagar código → git reset --hard
   
   Quero salvar mudanças sem commit → git stash
   
   Perdi um commit e quero achar → git reflog
   ```

3. **Praticar COM PAPEL:**

   **Exercício de Cenários de Resgate:**
   - Crie 10 "problemas" no papel (ex: "Fiz commit errado na branch errada")
   - Para cada problema, anote a solução com comandos específicos
   - Desenhe o estado antes e depois
   
   Exemplos de problemas para praticar:
   1. Commitei na branch errada → solução com cherry-pick
   2. Quero linearizar histórico → solução com rebase
   3. Preciso voltar 3 commits → solução com reset
   4. Tenho mudanças mas preciso trocar de branch → solução com stash

4. **Revisar:** Crie uma **ÁRVORE DE DECISÃO**:
   
   ```
                    Preciso desfazer algo?
                          /    \
                       SIM     NÃO → [outra ação]
                        |
                Já fez commit?
                  /          \
                SIM          NÃO
                 |            |
          Quer apagar?    git restore
            /      \
          SIM      NÃO
           |        |
      git reset  git revert
       --hard     (cria novo commit)
   ```

5. **Testar:** Para cada comando avançado, escreva:
   - O que faz
   - Quando usar
   - Perigos/cuidados
   - Exemplo de uso

**Domine antes de avançar:**
- [ ] Cria e usa tags para versões
- [ ] Entende diferença entre merge e rebase
- [ ] Sabe quando usar reset vs revert
- [ ] Usa stash para salvar trabalho temporário
- [ ] Recupera commits "perdidos" com reflog
- [ ] Aplica commits específicos com cherry-pick
- [ ] Cria aliases úteis
- [ ] Conhece pelo menos 2 hooks úteis

**Só avance se:** Conseguir resolver no papel 10 cenários de problemas complexos (commits errados, branches bagunçadas, histórico confuso) usando comandos avançados.

---

## INTEGRAÇÃO FINAL

**Objetivo:** Consolidar todo conhecimento em domínio prático completo.

**Protocolo de integração (faça em ordem):**

### 1. MANUAL PESSOAL COMPLETO (10-12 páginas manuscritas)

Escreva seu próprio **"Git: Guia Completo"** contendo:

**Parte 1 - Fundamentos (2 páginas)**
- O que é Git e controle de versão
- Conceitos essenciais (repositório, commit, staging)
- Diagrama dos 3 estados
- Configuração inicial

**Parte 2 - Trabalho Local (2-3 páginas)**
- Fluxo básico completo (init → add → commit → log)
- Todos os comandos essenciais com exemplos
- Como desfazer em cada estado
- Uso de .gitignore

**Parte 3 - Branches (2 páginas)**
- O que são e por que usar
- Comandos de branch
- Merge vs Rebase
- Resolução de conflitos

**Parte 4 - Trabalho Remoto (2 páginas)**
- Git vs GitHub
- Clone, push, pull, fetch
- Workflow de colaboração
- Fork e Pull Request

**Parte 5 - Comandos Avançados (1-2 páginas)**
- Tags, stash, reflog
- Reset e revert
- Cherry-pick
- Quando usar cada um

**Parte 6 - Meu Cheat Sheet (1 página)**
- Os 20 comandos que você mais usa
- Atalhos e dicas pessoais

### 2. MAPA MENTAL GIGANTE (1 folha grande)

Crie um mapa mental visual de TODO o Git:
- Centro: "GIT"
- Ramos principais: Fundamentos, Local, Branches, Remoto, Avançado
- Sub-ramos de cada um
- Use cores diferentes para cada área
- Inclua comandos, conceitos e conexões

### 3. PROJETO SIMULADO COMPLETO (5-7 páginas)

Simule no papel um projeto completo do início ao fim:

**Projeto:** Site de Portfólio (3 páginas: index.html, style.css, script.js)

**Requisitos da simulação:**
- Mínimo de 20 commits
- 3 branches: main, feature-about, feature-contact
- 2 merges com conflito (simule e resolva)
- 1 colaborador remoto (simule ações dele)
- 1 release com tag (v1.0)
- 1 uso de stash
- 1 uso de reset/revert
- 1 uso de rebase

**Para cada ação, anote:**
- Timestamp (T1, T2, T3...)
- Ação realizada
- Comando(s) Git usado(s)
- Estado resultante (desenhe árvore de commits)

### 4. GUIA DE TROUBLESHOOTING (2-3 páginas)

Crie um guia de "Como Resolver Problemas Comuns":

Liste 15-20 problemas e suas soluções:
1. Commitei no branch errado
2. Preciso desfazer último commit
3. Push rejeitado
4. Conflito no merge
5. Perdi um commit
6. Mudanças não aparecem
7. Quero mudar mensagem do commit
8. Branch divergiu do remoto
[continue...]

Para cada problema:
- Descrição clara
- Diagnóstico (comandos para verificar)
- Solução passo a passo
- Comandos exatos

### 5. AUTOAVALIAÇÃO FINAL

Crie e responda 25 questões desafiadoras, divididas em:

**Conceituais (5 questões):**
- Ex: "Explique a diferença entre Git e GitHub"
- Ex: "Por que staging area existe?"

**Comandos (10 questões):**
- Ex: "Qual a diferença entre git reset --soft e --hard?"
- Ex: "Como desfazer um commit já enviado ao servidor?"

**Cenários (10 questões):**
- Ex: "Você commitou arquivo com senha. Como remover do histórico?"
- Ex: "Dois devs fizeram push simultâneo. Como resolver?"

**Responda sem consultar nada. Depois corrija usando livro e anotações.**

Se errar mais de 5, revise os tópicos específicos antes de se considerar expert.

---

## TESTE FINAL DE DOMÍNIO

### PROJETO PRÁTICO SIMULADO COMPLETO
**Prazo: 1 dia intensivo • Sem consultar livro ou anotações**

**DESAFIO:**

Simule no papel (com diagramas, comandos e explicações) um projeto completo de desenvolvimento de software:

**Contexto:**
Você é líder técnico de uma equipe de 4 desenvolvedores criando um aplicativo web. Todos usam Git e GitHub.

**Requisitos (todos devem ser simulados no papel):**

1. **Setup Inicial:**
   - Crie repositório no GitHub (desenhe)
   - Configure .gitignore
   - Estruture branches: main, develop, feature/*

2. **Desenvolvimento de 3 Features Paralelas:**
   - Dev 1: feature-login
   - Dev 2: feature-dashboard  
   - Dev 3: feature-api
   - Você: coordena e faz code review
   - Mínimo de 25 commits total
   - Desenhe toda árvore de commits

3. **Problemas que Devem Ocorrer (e você resolve):**
   - 2 conflitos de merge (mostre resolução)
   - 1 commit errado (use cherry-pick ou reset)
   - 1 dev precisa voltar código (use revert)
   - 1 mudança emergencial (use stash)

4. **Processo de Release:**
   - Merge de develop para main
   - Crie tag v1.0.0
   - Escreva release notes

5. **Hotfix Urgente:**
   - Bug crítico encontrado em produção
   - Crie hotfix branch a partir de main
   - Corrija, teste, mergeia de volta
   - Tag v1.0.1

**Entregáveis (tudo manuscrito):**

1. **Diagrama Completo de Commits** (1-2 páginas)
   - Todos os branches
   - Todos os commits (círculos com letras/números)
   - Todos os merges
   - Tags marcadas

2. **Timeline de Comandos** (3-4 páginas)
   - Tabela com: Momento | Dev | Comando | Resultado
   - Todos os comandos executados em ordem
   - Explicação de decisões críticas

3. **Documentação do Workflow** (2 páginas)
   - Como a equipe trabalha
   - Regras de branch
   - Processo de review
   - Estratégia de merge

4. **Análise Final** (1 página)
   - O que funcionou bem
   - Onde Git ajudou
   - Lições aprendidas

### CRITÉRIOS DE DOMÍNIO ALCANÇADO:

Você domina Git se seu projeto simulado:
- [ ] Usa corretamente 30+ comandos diferentes
- [ ] Demonstra compreensão de workflows reais
- [ ] Resolve problemas complexos com comandos apropriados
- [ ] Mostra decisões técnicas fundamentadas
- [ ] Diagrama está correto e completo
- [ ] Comandos estão na ordem lógica certa
- [ ] Resoluções de conflito fazem sentido
- [ ] Estratégia de branching é profissional

**Se você conseguir criar esse projeto simulado completo, com coerência e correção, sem consultar materiais, você é um expert em Git.**

---

## CHECKLIST FINAL DE DOMÍNIO

### Fundamentos
- [ ] Explica controle de versão claramente
- [ ] Diferencia Git de GitHub
- [ ] Desenha diagrama dos 3 estados de memória
- [ ] Entende o que são commits (snapshots)

### Trabalho Local
- [ ] Cria repositórios (`git init`)
- [ ] Adiciona arquivos seletivamente (`git add`)
- [ ] Faz commits com mensagens descritivas
- [ ] Visualiza histórico (`git log`)
- [ ] Desfaz mudanças em qualquer estado
- [ ] Usa `.gitignore` apropriadamente

### Branches e Merges
- [ ] Cria e navega branches
- [ ] Faz merges
- [ ] Resolve conflitos
- [ ] Entende merge vs rebase
- [ ] Desenha árvores de commits complexas
- [ ] Implementa workflows de branch

### Trabalho Remoto
- [ ] Clona repositórios
- [ ] Conecta remotos
- [ ] Faz push e pull
- [ ] Diferencia fetch de pull
- [ ] Trabalha com fork e pull request
- [ ] Colabora em equipe

### Comandos Avançados
- [ ] Usa tags para versões
- [ ] Faz rebase quando apropriado
- [ ] Usa reset e revert corretamente
- [ ] Gerencia stash
- [ ] Recupera commits com reflog
- [ ] Aplica cherry-pick

### Competências Integradas
- [ ] Resolve problemas complexos rapidamente
- [ ] Escolhe comandos apropriados para cada situação
- [ ] Implementa workflows profissionais
- [ ] Colabora efetivamente em equipe
- [ ] Entende internals do Git (como funciona por baixo)
- [ ] Ensina Git para outros

**Teste absoluto:** Se você consegue simular no papel um projeto completo de 4 pessoas, 30+ commits, 5+ branches, conflitos, releases, hotfixes, e tudo está tecnicamente correto - você domina Git.

---

## RESULTADO ESPERADO

Ao concluir esta jornada com um único livro e prática intensiva, você terá:

✅ **Domínio completo** de Git para qualquer projeto  
✅ **Confiança** para trabalhar em equipes reais  
✅ **Capacidade** de resolver qualquer problema  
✅ **Compreensão profunda** de como Git funciona  
✅ **Habilidade** de ensinar outros  

**Você não apenas saberá usar Git. Você pensará em controle de versão como um expert.**

---

## TEMPO ESTIMADO

**Fase 1 (Fundamentos):** 3-5 dias  
**Fase 2 (Trabalho Local):** 5-7 dias  
**Fase 3 (Branches):** 5-7 dias  
**Fase 4 (Remoto):** 4-6 dias  
**Fase 5 (Avançado):** 4-5 dias  
**Integração Final:** 3-4 dias  
**Teste Final:** 1 dia  

**TOTAL:** 25-35 dias (3-5 semanas) de estudo dedicado para domínio completo.

---

## NOTA IMPORTANTE

Git é uma ferramenta que se domina PRATICANDO. Este plano usa papel para simular porque você estará em ambiente sem computador, mas a verdadeira maestria virá quando você puder aplicar isso em projetos reais.

Quando tiver acesso a um computador novamente:
1. Releia suas anotações manuscritas
2. Execute tudo que simulou no papel
3. Crie projetos de teste
4. Contribua para projetos open source

Suas simulações em papel construirão o modelo mental correto. A prática posterior consolidará em músculo.

**Comece hoje. Abra o livro. Leia o primeiro capítulo. Faça seu primeiro diagrama. A jornada começa agora.**