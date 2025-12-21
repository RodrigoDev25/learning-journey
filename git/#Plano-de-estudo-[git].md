# Jornada: Git e GitHub

**Do zero ao especialista • Português do Brasil • 100% Analógico**

**Foco:** Domínio completo de controle de versão através de um único livro brasileiro

---

## LIVRO DA TRILHA

### Livro Único — Domínio Completo
**Controlando Versões com Git e GitHub** — Alexandre Aquiles e Rodrigo Ferreira | Casa do Código  

Este livro brasileiro oferece uma jornada completa: da instalação básica até workflows profissionais, com linguagem clara e exemplos práticos que podem ser simulados no papel.

**Estrutura pedagógica:** Fundamentos → Operações locais → Colaboração remota → Práticas avançadas

---

## PLANO DE ESTUDO

### FASE 1 • Fundamentos do Controle de Versão

**Meta:** Entender O QUE é Git, POR QUÊ usar e COMO funciona a lógica de versionamento.

**Conteúdos essenciais:**
- O que é controle de versão e seus problemas resolvidos
- Diferença entre Git (ferramenta) e GitHub (plataforma)
- Conceitos de repositório, commit, branch
- Estados dos arquivos (untracked, modified, staged, committed)
- Funcionamento interno: snapshots vs diferenças
- Estrutura de árvore de commits

**Como estudar (passo a passo claro):**

1. **Ler:** Leia os capítulos introdutórios SEM pular nada. Pare a cada conceito novo e pergunte: "Consigo explicar isso para alguém?". Releia se necessário.

2. **Anotar:** Crie no caderno uma seção "DICIONÁRIO GIT" com 2 colunas:
   - Coluna 1: Termo técnico (ex: "commit")
   - Coluna 2: Explicação COM SUAS PALAVRAS + exemplo prático

3. **Praticar:** Desenhe no papel:
   - Fluxograma: "Ciclo de vida de um arquivo no Git"
   - Diagrama: "Árvore de commits" (bolinhas conectadas por linhas)
   - Simule 5 commits escrevendo mensagens descritivas reais

4. **Revisar:** A cada 3 conceitos aprendidos, feche o livro e escreva:
   - "O que aprendi hoje"
   - "Como isso se conecta com o que vi antes"
   - "Que dúvida ainda tenho"

5. **Testar:** Sem consultar o livro, responda NO PAPEL:
   - "O que acontece quando faço um commit?"
   - "Desenhe o fluxo: modifico arquivo → commit salvo"
   - "Qual diferença entre Git e GitHub?"

**Domine antes de avançar:**
- [ ] Consigo explicar o que é um commit sem consultar nada
- [ ] Sei desenhar uma árvore de commits com 5 versões
- [ ] Entendo os 4 estados de um arquivo no Git
- [ ] Consigo explicar por que Git é melhor que salvar "arquivo_final_v2.doc"
- [ ] Sei a diferença entre repositório local e remoto

**Só avance se:** Você consegue desenhar do zero (sem consulta) o ciclo de vida completo de um arquivo: desde a criação até virar um commit salvo.

---

### FASE 2 • Operações Locais (Sem GitHub)

**Meta:** Dominar todos os comandos básicos simulando seu funcionamento no papel.

**Conteúdos essenciais:**
- Inicializar repositório (git init)
- Adicionar arquivos à staging area (git add)
- Criar commits (git commit)
- Visualizar histórico (git log)
- Desfazer mudanças (git checkout, git reset)
- Criar e usar branches
- Fazer merges e resolver conflitos
- Tags e anotações

**Como estudar (passo a passo claro):**

1. **Ler:** Para CADA comando do livro:
   - Leia a explicação
   - Veja o exemplo do autor
   - PARE e escreva: "O que esse comando faz internamente?"

2. **Anotar:** Crie no caderno uma seção "COMANDOS" em formato de tabela:
   ```
   | Comando       | O que faz              | Quando usar          | Cuidados        |
   |---------------|------------------------|----------------------|-----------------|
   | git add .     | Prepara todos arquivos | Antes de commitar    | Revise o que vai|
   ```

3. **Praticar:** Para cada comando aprendido, simule NO PAPEL um projeto fictício:
   - Escolha um projeto (ex: "site de receitas")
   - Desenhe a estrutura de pastas
   - Simule 10 commits escrevendo: data, mensagem, arquivos modificados
   - Desenhe branches paralelas
   - Simule um merge desenhando a união das árvores

4. **Revisar:** A cada 5 comandos dominados:
   - Crie um "FLUXOGRAMA DE DECISÃO": "Qual comando usar quando..."
   - Exemplo: "Quero desfazer última mudança → git reset? git checkout? git revert?"
   - Conecte com o fluxograma de comandos anteriores

5. **Testar:** Crie 5 "CENÁRIOS-PROBLEMA" e resolva no papel:
   - "Commitei arquivo errado, como desfaço?"
   - "Preciso trabalhar em nova funcionalidade sem afetar o principal"
   - "Duas pessoas mudaram a mesma linha, como resolver?"
   
**Domine antes de avançar:**
- [ ] Consigo desenhar a linha do tempo de 10 commits conectados
- [ ] Sei simular um merge de duas branches no papel
- [ ] Entendo quando usar git reset vs git checkout vs git revert
- [ ] Consigo resolver um conflito de merge desenhando as versões
- [ ] Sei criar e alternar entre branches no meu diagrama
- [ ] Compreendo o que é HEAD e como ele se move

**Só avance se:** Dado um cenário complexo (ex: "você está no branch feature-X, commitou 3 vezes, precisa voltar 2 commits, criar novo branch e fazer merge"), você consegue desenhar e explicar cada passo sem consultar o livro.

---

### FASE 3 • Colaboração com GitHub

**Meta:** Entender workflows de equipe e dominar operações remotas.

**Conteúdos essenciais:**
- Conceito de repositório remoto
- Push, pull, fetch
- Clonando repositórios
- Fork e pull requests
- Workflows de equipe (Gitflow, feature branch)
- Boas práticas de mensagens de commit
- Resolução de conflitos em equipe
- Issues e documentação

**Como estudar (passo a passo claro):**

1. **Ler:** Para cada conceito de colaboração:
   - Imagine VOCÊ e um COLEGA trabalhando juntos
   - Desenhe os dois repositórios (local de cada um + GitHub no meio)
   - Siga a explicação do livro desenhando as setas de comunicação

2. **Anotar:** Crie seção "WORKFLOWS" com diagramas:
   - "Fluxo solo": init → add → commit → push
   - "Fluxo colaborativo": clone → branch → commit → push → pull request → merge
   - "Fluxo com conflito": pull → conflito → resolve → commit → push

3. **Praticar:** Simule equipe fictícia:
   - Desenhe 3 desenvolvedores: Ana, Bruno, Carla
   - Cada um cria um branch diferente (no papel)
   - Simule 15 commits distribuídos entre eles
   - Desenhe quando cada um faz push/pull
   - Crie um conflito proposital e resolva no papel
   - Desenhe todo o processo de pull request até merge final

4. **Revisar:** Crie "ESTUDOS DE CASO":
   - Analise cada workflow do livro
   - Escreva: "Vantagens", "Desvantagens", "Quando usar"
   - Compare: Gitflow vs GitHub Flow vs Trunk-based
   - Crie sua tabela de decisão: "Para projeto X usar workflow Y"

5. **Testar:** Crie 3 cenários complexos e resolva completamente no papel:
   - "Equipe de 5 pessoas, 3 features simultâneas, como organizar?"
   - "Desenvolvedor commitou na main sem querer, como reverter?"
   - "Dois merges simultâneos causaram conflitos, qual ordem resolver?"

**Domine antes de avançar:**
- [ ] Consigo desenhar o fluxo completo: local → remoto → outro local
- [ ] Sei explicar diferença entre fetch, pull e pull request
- [ ] Entendo quando fazer fork vs clone
- [ ] Domino resolução de conflitos em cenários complexos
- [ ] Conheço 3 workflows e sei quando usar cada um
- [ ] Sei escrever mensagens de commit profissionais
- [ ] Entendo o papel de issues e documentação

**Só avance se:** Você consegue desenhar e narrar um workflow completo de contribuição open source: desde o fork até o pull request ser aceito, incluindo possíveis conflitos e suas resoluções.

---

### FASE 4 • Técnicas Avançadas e Domínio Profissional

**Meta:** Alcançar fluência de especialista em situações complexas e casos extremos.

**Conteúdos essenciais:**
- Git rebase vs merge (quando usar cada um)
- Cherry-pick de commits específicos
- Stash para trabalho temporário
- Histórico avançado (git reflog, git blame)
- Hooks e automações
- Submódulos e repositórios dentro de repositórios
- Estratégias de versionamento (semantic versioning)
- Debugging com git bisect
- Recuperação de commits perdidos
- Otimização de repositórios grandes

**Como estudar (passo a passo claro):**

1. **Ler:** Para conceitos avançados:
   - Leia uma vez para entender O QUE faz
   - Releia para entender COMO funciona internamente
   - Releia novamente para entender QUANDO usar
   - Identifique conexões com comandos básicos das fases anteriores

2. **Anotar:** Crie seção "TÉCNICAS AVANÇADAS":
   - Para cada técnica: "Problema que resolve"
   - Desenhe: "Antes → Comando → Depois"
   - Anote: "Armadilhas" (o que pode dar errado)
   - Liste: "Alternativas" (outras formas de resolver)

3. **Praticar:** Crie "SIMULAÇÕES EXTREMAS" no papel:
   - Simule um projeto com 50 commits, 5 branches, 3 desenvolvedores
   - Crie problemas propositais:
     * Commit no branch errado
     * Histórico bagunçado que precisa de rebase
     * Código bugado, precisa encontrar qual commit introduziu (bisect)
     * Trabalho não terminado, precisa mudar de tarefa (stash)
   - Resolva cada problema desenhando a solução completa

4. **Revisar:** Integração total das 4 fases:
   - Volte ao "DICIONÁRIO GIT" da Fase 1 e expanda cada termo
   - Conecte comandos básicos com avançados
   - Crie "ÁRVORE DE DECISÃO COMPLETA":
     * Raiz: "Qual seu problema?"
     * Galhos: Comandos básicos → intermediários → avançados
   - Escreva: "Meu Manual Pessoal de Git" (10 páginas manuscritas)

5. **Testar:** Crie e resolva 5 "CASOS EXTREMOS":
   - "Preciso juntar commits 3, 7 e 12 em um só"
   - "Branch principal foi deletada acidentalmente, como recuperar?"
   - "Histórico tem 200 commits bagunçados, como reorganizar?"
   - "Preciso manter um fork atualizado com original + minhas mudanças"
   - "Dois branches divergiram há 30 commits, qual melhor estratégia?"

**Domine antes de avançar:**
- [ ] Sei quando usar rebase vs merge e as consequências de cada um
- [ ] Domino recuperação de commits "perdidos" com reflog
- [ ] Consigo simular cherry-pick de múltiplos commits
- [ ] Entendo o conceito de stash e suas limitações
- [ ] Sei debugar problemas com git bisect
- [ ] Compreendo semantic versioning e estratégias de release
- [ ] Consigo otimizar repositórios grandes
- [ ] Domino todos os comandos destrutivos e seus riscos

**Só avance se:** Você consegue criar, do zero, um "Manual de Emergências Git" com 10 problemas críticos e suas soluções completas, tudo explicado com suas próprias palavras e diagramas, sem consultar o livro.

---

## INTEGRAÇÃO FINAL

**Objetivo:** Unificar todas as 4 fases em domínio completo de Git/GitHub.

**Protocolo (faça em ordem):**

1. **Mapa cruzado:** Crie tabela manuscrita com 4 colunas (uma por fase) e 10 linhas:
   - Linha 1: "Conceito fundamental da fase"
   - Linha 2: "Comando mais importante"
   - Linha 3: "Erro mais comum"
   - Linha 4: "Como se conecta com outras fases"
   - Linha 5: "Caso de uso real"
   - (Continue até linha 10)
   
   **Meta:** Visualizar a evolução do conhecimento e interdependências.

2. **Manual pessoal:** Escreva seu "Git Handbook Manuscrito" (15-20 páginas):
   - Página 1-3: Glossário completo (todos os termos)
   - Página 4-8: Comandos organizados por categoria (local, remoto, avançado)
   - Página 9-12: Workflows completos desenhados
   - Página 13-15: Troubleshooting (20 problemas + soluções)
   - Página 16-18: Estudos de caso (5 cenários reais completos)
   - Página 19-20: Checklist de boas práticas
   
   **Meta:** Ter um guia de referência rápida criado por você.

3. **Teste de coerência:** Analise convergências e divergências:
   - Liste 5 conceitos que o livro explica de formas diferentes em capítulos distintos
   - Identifique: "Por que o autor escolheu explicar assim em cada momento?"
   - Escreva: "Qual a lógica pedagógica do livro inteiro?"
   - Avalie: "Que lacunas o livro deixou?" (se houver)
   
   **Meta:** Visão crítica sobre o próprio material estudado.

4. **Aplicação unificada:** Crie e resolva completamente um "MEGA-PROJETO SIMULADO":
   - Projeto: Sistema de blog com 3 desenvolvedores
   - Duração simulada: 3 meses (60 commits)
   - Inclua: 8 features em branches paralelos
   - Simule: 5 conflitos de merge
   - Use: rebase, cherry-pick, stash, tags
   - Desenhe: toda a árvore de commits do início ao fim
   - Narre: decisões técnicas e justificativas de cada workflow usado
   
   **Meta:** Aplicar TODOS os conhecimentos das 4 fases em um único projeto.

5. **Autoavaliação:** Responda sem consulta:
   - Liste 30 comandos Git e explique cada um
   - Desenhe 5 workflows diferentes e quando usar cada um
   - Crie 10 cenários-problema e resolva todos
   - Escreva: "Carta para mim do passado" explicando Git do zero
   - Avalie: "Qual meu nível atual?" (use a checklist abaixo)
   
   **Meta:** Verificação honesta do domínio alcançado.

**Domínio alcançado:** Fluência completa em controle de versão, capaz de trabalhar em qualquer equipe profissional, resolver problemas complexos e ensinar outros desenvolvedores.

---

## CHECKLIST DE DOMÍNIO

### Fundamentos (Fase 1)
- [ ] Explico o que é Git para um leigo em 2 minutos
- [ ] Desenho a estrutura interna de um repositório
- [ ] Sei diferenciar Git, GitHub, GitLab, Bitbucket
- [ ] Entendo completamente o conceito de commit
- [ ] Domino os 4 estados de arquivos
- [ ] Compreendo a diferença entre snapshot e diff

### Operações Locais (Fase 2)
- [ ] Executo mentalmente qualquer comando básico
- [ ] Desenho árvores de commits complexas
- [ ] Resolvo conflitos de merge no papel
- [ ] Sei quando usar cada comando de "desfazer"
- [ ] Domino estratégias de branching
- [ ] Entendo o conceito de HEAD e como ele se move
- [ ] Sei usar tags para versionamento

### Colaboração (Fase 3)
- [ ] Desenho fluxos completos: local ↔ remoto ↔ local
- [ ] Domino diferenças: fetch vs pull vs pull request
- [ ] Sei quando fazer fork vs clone
- [ ] Resolvo conflitos em cenários de equipe
- [ ] Conheço e aplico diferentes workflows (Gitflow, GitHub Flow, etc)
- [ ] Escrevo mensagens de commit profissionais
- [ ] Uso issues e documentação adequadamente
- [ ] Entendo contribuição open source completa

### Técnicas Avançadas (Fase 4)
- [ ] Sei quando usar rebase vs merge
- [ ] Domino cherry-pick de commits específicos
- [ ] Uso stash estrategicamente
- [ ] Navego pelo histórico com reflog
- [ ] Debugo com git bisect
- [ ] Recupero commits "perdidos"
- [ ] Entendo submódulos e repos aninhados
- [ ] Aplico semantic versioning
- [ ] Otimizo repositórios grandes
- [ ] Conheço todos os riscos de comandos destrutivos

### Competências Finais
- [ ] Consigo ensinar Git do zero para outra pessoa
- [ ] Resolvo qualquer problema de versionamento que apareça
- [ ] Escolho o workflow ideal para cada tipo de projeto
- [ ] Leio e entendo o histórico de qualquer repositório
- [ ] Contribuo profissionalmente em projetos open source
- [ ] Crio e mantenho estratégias de branching em equipes
- [ ] Domino troubleshooting de problemas complexos
- [ ] Tenho visão crítica sobre boas práticas
- [ ] Sintetizo todo o conhecimento em explicações claras

**Teste final:** Pegue um projeto real de código aberto no GitHub (escolha um que você gosta). Desenhe no papel: (1) A estratégia de branching que eles usam, (2) Como você contribuiria com uma nova feature, (3) Como resolveria um conflito se aparecer, (4) Como organizaria o histórico se você fosse o mantenedor. Se você conseguir fazer tudo isso com confiança e justificar cada decisão, você domina Git/GitHub.

---

## TÉCNICAS DE ESTUDO APLICADAS

Este plano usa ciência cognitiva:

**🧠 Spaced Repetition:** Revisões a cada fase + consolidação final conectando tudo.

**🎯 Active Recall:** Testes "sem consulta" forçam busca ativa na memória.

**🔗 Elaborative Interrogation:** "Por que isso funciona assim?" conecta conceitos profundamente.

**✏️ Dual Coding:** Texto + diagramas + simulações = múltiplas representações mentais.

**📊 Interleaving:** Mistura comandos básicos e avançados na integração final.

**🪞 Metacognição:** Checklists obrigam você a avaliar honestamente seu domínio.

---

## TEMPO ESTIMADO

**Ritmo sugerido (adaptável ao seu tempo):**

- **Fase 1:** 1-2 semanas (fundamentos precisam ser sólidos)
- **Fase 2:** 2-3 semanas (muitos comandos para dominar)
- **Fase 3:** 2-3 semanas (workflows exigem prática)
- **Fase 4:** 2-3 semanas (conceitos avançados requerem maturidade)
- **Integração Final:** 1 semana (consolidação intensiva)

**Total:** 8-12 semanas para domínio completo.

**Importante:** NÃO apresse. Domínio real > velocidade artificial.

---

## MATERIAIS NECESSÁRIOS

✅ **Livro:** Controlando Versões com Git e GitHub (Casa do Código)  
✅ **Caderno:** A4 ou maior (você vai desenhar MUITAS árvores)  
✅ **Canetas:** 3-4 cores (para diferenciar branches, conflitos, etc)  
✅ **Régua:** Para desenhar diagramas limpos  
✅ **Post-its:** Para marcar páginas importantes do livro

❌ **NÃO PRECISA:** Computador, internet, aplicativos, nada digital!

---

## DICAS FINAIS

**Para maximizar o aprendizado analógico:**

1. **Desenhe tudo:** Git é visual. Quanto mais você desenhar árvores de commits, melhor vai entender.

2. **Simule cenários reais:** Não estude comandos isolados. Sempre crie um "projeto fictício" e aplique.

3. **Explique em voz alta:** Fale sozinho explicando conceitos. Se travar, estude mais aquele ponto.

4. **Conecte constantemente:** Sempre pergunte "Como isso se relaciona com o que aprendi antes?"

5. **Não pule fases:** A tentação de avançar rápido é grande. Resista. Fundamentos fracos = casa na areia.

6. **Revise espacialmente:** A cada 3 dias de estudo, revise todo o caderno rapidamente.

7. **Crie seu próprio livro:** Seu caderno vai virar seu manual personalizado. Capriche nele.

---

**Pronto para começar sua jornada rumo ao domínio de Git e GitHub? 🚀**

*Este plano transforma o livro da Casa do Código em uma experiência de aprendizado profundo, metódica e 100% analógica. Boa jornada!*