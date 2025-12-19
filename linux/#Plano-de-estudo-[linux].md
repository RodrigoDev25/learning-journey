# Jornada: Linux

**Do zero ao especialista • Português do Brasil • 100% Analógico**

**Foco:** Domínio completo do sistema operacional Linux, desde conceitos básicos até administração avançada e compreensão profunda da arquitetura de sistemas operacionais.

---

## LIVROS DA TRILHA

### Livro 1 — Fundação
**Linux Para Leigos** — Richard Blum | Alta Books  
Introduz o Linux de forma acessível, ensinando instalação, comandos básicos e uso diário sem exigir conhecimento prévio.

### Livro 2 — Estruturação  
**Fundamentos de Sistemas Operacionais** — Silberschatz, Galvin, Gagne | LTC  
Aprofunda a compreensão teórica sobre como sistemas operacionais funcionam internamente, incluindo processos, memória e gerenciamento de recursos.

### Livro 3 — Especialização
**Linux: A Bíblia** — Christopher Negus | Alta Books  
Transforma em especialista através de administração avançada, servidores, segurança, scripts e configurações complexas do Linux.

**Progressão:** Da interação básica com Linux à compreensão profunda de sistemas operacionais, culminando no domínio completo de administração e configuração avançada.

---

## PLANO DE ESTUDO

### FASE 1 • Livro 1: Linux Para Leigos

**Meta:** Tornar-se confortável usando Linux no dia a dia e compreender seus conceitos fundamentais.

**Conteúdos essenciais:**
- O que é Linux e suas distribuições
- Instalação e configuração inicial
- Interface gráfica e linha de comando
- Estrutura de diretórios do sistema
- Comandos básicos (ls, cd, cp, mv, rm, mkdir)
- Gerenciamento de arquivos e permissões
- Instalação de programas
- Usuários e grupos básicos

**Como estudar (passo a passo claro):**
1. **Ler:** Leia um capítulo por vez, parando para visualizar mentalmente cada comando e resultado descrito. Não pule as explicações que parecem óbvias.
2. **Anotar:** No caderno, crie uma seção "Comandos Linux" e anote cada comando novo com: nome, o que faz, exemplo de uso e quando usar. Desenhe a árvore de diretórios do Linux à mão.
3. **Praticar:** Sem consultar o livro, escreva no papel 10 situações do dia a dia e qual comando usaria em cada uma (ex: "copiar uma pasta" → cp -r). Corrija depois consultando suas anotações.
4. **Revisar:** A cada 3 capítulos, crie uma página resumo conectando os conceitos aprendidos. Desenhe diagramas mostrando como os comandos se relacionam.
5. **Testar:** Escolha 5 comandos aleatórios de suas anotações e escreva, sem consulta, o que cada um faz e um exemplo completo de uso com todas as opções necessárias.

**Domine antes de avançar:**
- [ ] Estrutura completa de diretórios do Linux e função de cada pasta principal
- [ ] 30 comandos básicos com suas opções mais usadas
- [ ] Sistema de permissões (leitura, escrita, execução para dono/grupo/outros)
- [ ] Diferença entre usuário comum e root
- [ ] Como instalar, atualizar e remover programas
- [ ] Navegação fluente entre diretórios usando apenas comandos

**Só avance se:** Conseguir desenhar de memória a árvore de diretórios do Linux e explicar por escrito, sem consulta, o que fazem 20 comandos escolhidos aleatoriamente.

---

### FASE 2 • Livro 2: Fundamentos de Sistemas Operacionais

**Meta:** Compreender profundamente como o Linux (e qualquer sistema operacional) funciona por baixo dos panos.

**Conteúdos essenciais:**
- Conceitos de processos e threads
- Escalonamento de CPU
- Sincronização e deadlocks
- Gerenciamento de memória (paginação, segmentação)
- Memória virtual
- Sistema de arquivos (estrutura, alocação, diretórios)
- Entrada e saída (dispositivos, buffers)
- Proteção e segurança do sistema

**Como estudar (passo a passo claro):**
1. **Ler:** Leia devagar, focando em entender conceitos, não decorar. Quando encontrar um algoritmo ou processo, desenhe-o passo a passo no papel. Releia parágrafos complexos.
2. **Anotar:** Crie seções separadas no caderno para cada tema (Processos, Memória, Arquivos, etc.). Para cada conceito, anote: o que é, por que existe, como funciona e onde aparece no Linux do Livro 1.
3. **Praticar:** Pegue exemplos do livro e simule no papel: desenhe como um processo é escalonado, como a memória virtual traduz endereços, como um arquivo é alocado no disco. Faça os exercícios do final dos capítulos.
4. **Revisar:** A cada 2 capítulos, crie uma tabela conectando teoria com Linux: "Como o conceito X se manifesta nos comandos Y que aprendi". Desenhe diagramas de fluxo de cada mecanismo.
5. **Testar:** Escolha um conceito complexo (ex: paginação) e explique por escrito, sem consulta, como ele funciona do início ao fim, incluindo exemplo numérico completo.

**Domine antes de avançar:**
- [ ] Estados de um processo e transições entre eles
- [ ] Pelo menos 3 algoritmos de escalonamento e quando usar cada um
- [ ] Como funciona memória virtual e tradução de endereços
- [ ] Estrutura interna de um sistema de arquivos
- [ ] Diferença entre fragmentação interna e externa
- [ ] Como o sistema operacional gerencia entrada e saída
- [ ] Mecanismos de proteção e segurança do kernel

**Só avance se:** Conseguir explicar por escrito, sem consulta, como um programa vai da execução pelo usuário até aparecer na tela, passando por todos os componentes do sistema operacional (processo, memória, arquivos, I/O).

---

### FASE 3 • Livro 3: Linux: A Bíblia

**Meta:** Tornar-se especialista capaz de administrar sistemas Linux complexos, configurar servidores e resolver problemas avançados.

**Conteúdos essenciais:**
- Administração avançada de usuários e grupos
- Configuração de rede (IP, DNS, DHCP)
- Servidores (Apache, SSH, FTP, Samba)
- Shell scripting avançado
- Agendamento de tarefas (cron)
- Logs do sistema e troubleshooting
- Segurança avançada (firewall, SELinux)
- Gerenciamento de pacotes avançado
- Compilação de software
- Kernel e módulos

**Como estudar (passo a passo claro):**
1. **Ler:** Leia cada seção como um manual de referência. Para configurações, anote cada parâmetro e seu efeito. Para comandos avançados, anote todas as combinações de opções relevantes.
2. **Anotar:** Crie um "Manual Pessoal de Administração Linux" no caderno com seções temáticas. Para cada tarefa administrativa, anote: objetivo, comandos necessários, arquivos envolvidos, ordem de execução e problemas comuns.
3. **Praticar:** Desenhe cenários complexos no papel (ex: "empresa com 3 servidores, 50 usuários, precisa de compartilhamento de arquivos e acesso remoto") e planeje por escrito toda a configuração necessária, comando por comando.
4. **Revisar:** Crie tabelas de referência rápida: "Problema → Comando/Arquivo para verificar → Solução". Conecte conceitos do Livro 2 (ex: como processos funcionam) com ferramentas práticas do Livro 3 (ex: ps, top, kill).
5. **Testar:** Escreva scripts complexos no papel resolvendo problemas reais: backup automático, monitoramento de sistema, gerenciamento de logs. Depois verifique a sintaxe consultando suas anotações.

**Domine antes de avançar:**
- [ ] Configurar rede completa (IP estático, DNS, gateway)
- [ ] Instalar e configurar pelo menos 3 servidores diferentes
- [ ] Escrever scripts shell com estruturas condicionais e loops
- [ ] Interpretar e analisar logs do sistema
- [ ] Configurar firewall e regras de segurança
- [ ] Gerenciar permissões avançadas (ACL)
- [ ] Compilar software a partir do código fonte
- [ ] Entender estrutura do kernel e carregar módulos

**Só avance se:** Conseguir desenhar e documentar por escrito, sem consulta, a configuração completa de um servidor Linux para um cenário complexo (incluindo rede, usuários, serviços, segurança e backup), explicando cada comando e arquivo envolvido.

---

## INTEGRAÇÃO FINAL

**Objetivo:** Unificar os 3 livros em domínio completo, conectando prática básica, teoria profunda e especialização avançada.

**Protocolo (faça em ordem):**
1. **Mapa cruzado:** Crie uma tabela de 3 colunas no caderno: "Comando/Tarefa Prática (L1)" | "Conceito Teórico (L2)" | "Implementação Avançada (L3)". Preencha com pelo menos 20 linhas conectando os 3 níveis (ex: "comando ps" | "conceito de processos" | "monitoramento avançado com ps aux e análise de estados").

2. **Manual pessoal:** Escreva um guia de 30-40 páginas manuscritas intitulado "Meu Sistema Linux Completo", dividido em: Fundamentos (L1), Como Funciona (L2), Como Administrar (L3). Cada seção deve ser escrita com suas próprias palavras, sem copiar dos livros.

3. **Teste de coerência:** Identifique 5 tópicos que aparecem nos 3 livros (ex: processos, memória, arquivos). Para cada um, escreva uma página explicando: como o Livro 1 apresentou, o que o Livro 2 explicou teoricamente, como o Livro 3 aplica na prática. Anote divergências ou ênfases diferentes.

4. **Aplicação unificada:** Desenhe no papel a arquitetura completa de um sistema Linux real (startup, kernel, processos, memória, arquivos, rede). Anote em cada componente: comandos básicos relacionados (L1), funcionamento interno (L2), configuração avançada (L3).

5. **Autoavaliação:** Crie 20 perguntas complexas misturando os 3 livros (ex: "Como o comando 'free' do L1 mostra informações sobre paginação do L2 e como usar essas informações para otimizar um servidor do L3?"). Responda por escrito sem consulta. Depois verifique com os livros.

**Domínio alcançado:** Capacidade de usar Linux fluentemente, explicar seu funcionamento interno profundamente e administrar sistemas complexos com segurança e eficiência.

---

## CHECKLIST DE DOMÍNIO

### Fundamentos (Livro 1)
- [ ] Navegação completa no sistema de arquivos Linux
- [ ] Uso fluente de 30+ comandos básicos
- [ ] Gerenciamento de arquivos, diretórios e permissões
- [ ] Instalação e remoção de programas
- [ ] Compreensão de usuários, grupos e privilégios
- [ ] Uso de editores de texto em linha de comando

### Estrutura (Livro 2)
- [ ] Ciclo de vida completo de processos
- [ ] Algoritmos de escalonamento de CPU
- [ ] Funcionamento de memória virtual e paginação
- [ ] Estrutura interna de sistemas de arquivos
- [ ] Gerenciamento de entrada e saída
- [ ] Mecanismos de proteção e segurança
- [ ] Conceitos de sincronização e deadlocks

### Especialização (Livro 3)
- [ ] Administração avançada de usuários e grupos
- [ ] Configuração completa de rede
- [ ] Instalação e configuração de múltiplos servidores
- [ ] Shell scripting com estruturas complexas
- [ ] Análise e interpretação de logs do sistema
- [ ] Configuração de segurança e firewall
- [ ] Compilação de software e gerenciamento do kernel
- [ ] Automação de tarefas administrativas

### Competências finais
- [ ] Diagnosticar e resolver problemas complexos integrando conhecimento dos 3 níveis
- [ ] Explicar qualquer comando Linux desde a interface até o funcionamento do kernel
- [ ] Projetar e implementar infraestrutura Linux completa para cenários reais
- [ ] Otimizar sistemas baseando-se em compreensão profunda de como funcionam internamente

**Teste final:** Desenhe no papel a arquitetura completa de um servidor Linux de produção (web server + banco de dados + backup automático + monitoramento + segurança), documentando: todos os comandos de configuração, explicação de como cada componente funciona internamente no kernel, justificativa técnica de cada escolha baseada em teoria de sistemas operacionais. Tudo sem consulta aos livros.

---

## REGRAS DE EXECUÇÃO

**ESTUDO 100% ANALÓGICO:**
- Use apenas os livros físicos, caderno e caneta
- Nenhuma técnica exige computador, tablet ou celular
- Todo aprendizado acontece através de leitura, escrita manuscrita e reflexão
- Pratique comandos mentalmente ou desenhando no papel antes de eventualmente testar em computador

**PROGRESSÃO DISCIPLINADA:**
- Um livro por vez, na ordem estabelecida
- Só avance após dominar completamente os critérios de cada fase
- Revise fases anteriores ao avançar para manter conexões
- O objetivo é domínio profundo, não velocidade

**DOCUMENTAÇÃO PESSOAL:**
- Seu caderno é seu segundo cérebro: organize com índice e seções claras
- Reescreva conceitos com suas palavras, não copie dos livros
- Crie seus próprios exemplos e exercícios
- Desenhe diagramas, tabelas e mapas mentais constantemente

**Tempo estimado:** 6-12 meses de estudo consistente para domínio completo (variável conforme dedicação e ritmo pessoal).