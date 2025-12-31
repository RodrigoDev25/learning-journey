# Jornada: Redes de Computadores

**Do zero ao especialista • Português do Brasil • 100% Analógico**

---

## LIVROS DA TRILHA

### Livro 1 — Fundação
**Redes de Computadores - Curso Completo** — José Gouveia e Alberto Magalhães | FCA  
Constrói do zero os conceitos práticos de redes para leigos: instalação, configuração e gestão básica.

### Livro 2 — Estruturação  
**Redes de Computadores e a Internet: Uma Abordagem Top-Down** — James F. Kurose e Keith W. Ross | Pearson  
Aprofunda nos protocolos e arquitetura das redes partindo das aplicações até a camada física.

### Livro 3 — Especialização
**Redes de Computadores** - Tanenbaum
Especializa com domínio completo da arquitetura, protocolos avançados, segurança e teoria profunda.

**Progressão:** Prática operacional → Arquitetura top-down → Domínio teórico-prático completo (do "fazer funcionar" para "entender profundamente").

---

## PLANO DE ESTUDO

### FASE 1 • Livro 1: Redes de Computadores - Curso Completo

**Meta:** Configurar e gerenciar redes locais com compreensão prática dos componentes e tecnologias.

**Conteúdos essenciais:**
- Fundamentos de redes (topologias, tipos, componentes)
- Modelo OSI e TCP/IP (visão prática)
- Cabeamento e padrões físicos (Ethernet, Wi-Fi, Bluetooth)
- Equipamentos de rede (hubs, switches, routers, access points)
- Configuração de redes locais (LAN)
- Configuração de redes wireless
- Serviços básicos (DHCP, DNS, NAT)
- Configuração de routers e firewalls
- Segurança básica de redes
- Troubleshooting e ferramentas de diagnóstico

**Como estudar (passo a passo claro):**

1. **Ler:** Leia 1 capítulo por sessão. Este livro é prático e direto. Para cada tecnologia descrita, desenhe os equipamentos e conexões no papel. Sublinhe comandos e configurações importantes. Marque exemplos de configuração para praticar depois.

2. **Anotar:** Crie um "Manual Técnico Pessoal" no caderno dividido em seções:  
   - **Conceitos base:** Defina cada termo técnico (hub, switch, router, gateway) em suas palavras  
   - **Topologias:** Desenhe e explique estrela, barramento, anel, mesh  
   - **Camadas OSI/TCP-IP:** Crie tabela com cada camada, função e protocolos  
   - **Configurações:** Anote passo a passo de cada configuração (ex: "Como configurar DHCP")  
   - **Comandos úteis:** Liste comandos de diagnóstico (ping, tracert, ipconfig)

3. **Praticar:** Exercícios no papel:  
   - **Diagramas de rede:** Desenhe 5 cenários diferentes (casa, escritório pequeno, escola) com equipamentos e conexões  
   - **Tabelas de endereçamento:** Crie planos de endereçamento IP para redes /24, /16, /8  
   - **Troubleshooting:** Para cada problema descrito no livro, escreva diagnóstico e solução passo a passo  
   - **Projetos de rede:** Planeje rede completa para um cenário (especifique equipamentos, cabos, configurações)

4. **Revisar:** A cada 3 capítulos, faça "Revisão Integrada":  
   - Liste todos os equipamentos estudados e suas funções  
   - Crie um fluxograma de "como dados viajam" da sua máquina até a internet  
   - Escreva 10 problemas comuns de rede e suas soluções  
   - Desenhe diagrama OSI completo com todos os protocolos em cada camada

5. **Testar:** Projeto final em papel:  
   Projete uma rede completa para escritório de 30 computadores com:  
   - Diagrama físico (salas, cabos, equipamentos)  
   - Diagrama lógico (VLANs, sub-redes, endereçamento)  
   - Lista de equipamentos necessários (modelo, quantidade)  
   - Configuração de cada equipamento (escrita passo a passo)  
   - Plano de segurança (firewall, Wi-Fi seguro)  
   Se conseguir fazer isso sem consultar, dominou a base prática.

**Domine antes de avançar:**
- [ ] Explicar modelo OSI e TCP/IP com exemplos práticos
- [ ] Diferenciar hub, switch, router e suas funções
- [ ] Calcular e planejar sub-redes (CIDR, máscara)
- [ ] Configurar serviços básicos (DHCP, DNS, NAT) passo a passo
- [ ] Desenhar topologias de rede para cenários reais
- [ ] Diagnosticar problemas comuns (sem conexão, lentidão, conflito IP)
- [ ] Configurar segurança básica (firewall, WPA2, filtros)

**Só avance se:** Conseguir pegar um cenário qualquer (ex: "pequena empresa com 20 máquinas, 2 impressoras, Wi-Fi e servidor") e desenhar diagrama completo, especificar equipamentos, calcular IPs e escrever roteiro de configuração - tudo no papel, sem consulta.

---

### FASE 2 • Livro 2: Redes de Computadores e a Internet

**Meta:** Dominar arquitetura de redes e protocolos através da abordagem top-down (aplicação → física).

**Conteúdos essenciais:**
- Camada de aplicação (HTTP, FTP, SMTP, DNS, P2P)
- Programação de sockets (conceitos)
- Camada de transporte (TCP, UDP, controle de fluxo, congestionamento)
- Camada de rede (IP, roteamento, ICMP, IPv6)
- Camada de enlace (Ethernet, switches, LANs)
- Camada física (transmissão, modulação)
- Redes sem fio (Wi-Fi, celular)
- Segurança de redes (criptografia, autenticação, VPN)
- Multimídia em rede (streaming, VoIP)
- Gerenciamento de redes (SNMP)

**Como estudar (passo a passo claro):**

1. **Ler:** A abordagem top-down é diferente. Leia 1 seção por vez (seções são menores que capítulos). Para cada protocolo, foque em ENTENDER o "por quê" antes do "como". Faça perguntas: "Por que TCP é diferente de UDP?" "O que acontece se um pacote se perde?" Sublinhe princípios, não apenas fatos.

2. **Anotar:** Crie "Caderno de Protocolos" organizado assim:  
   - **Por camada:** Uma seção para cada camada OSI  
   - **Por protocolo:** Para cada protocolo importante, crie página com:  
     * Propósito (1 frase)  
     * Como funciona (diagrama de sequência manuscrito)  
     * Formato do pacote/mensagem (desenhe os campos)  
     * Exemplo de uso (cenário real)  
     * Vantagens e limitações  
   - **Comparações:** Tabelas comparando protocolos similares (TCP vs UDP, HTTP vs HTTPS, IPv4 vs IPv6)

3. **Praticar:** Exercícios conceituais no papel:  
   - **Trace de pacotes:** Escreva passo a passo o que acontece quando você acessa "www.exemplo.com": DNS lookup, TCP handshake, HTTP request, resposta, renderização  
   - **Diagramas de sequência:** Desenhe troca de mensagens entre cliente e servidor para protocolos (HTTP GET, TCP handshake, DNS query)  
   - **Cálculos:** Resolva todos os exercícios numéricos do livro (throughput, delay, utilização, janela de congestionamento)  
   - **Análise de problemas:** Para cenários do livro, identifique qual camada/protocolo falhou e por quê

4. **Revisar:** A cada camada completa, faça "Síntese de Camada":  
   - Escreva 2 páginas resumindo: principais protocolos, funções, como se relacionam  
   - Crie mapa mental conectando todos os protocolos da camada  
   - Liste 5 problemas que podem ocorrer nessa camada e como detectar  
   - Escreva analogia do mundo real para explicar a camada a um leigo

5. **Testar:** Projeto integrado manuscrito:  
   Analise uma aplicação completa (ex: streaming de vídeo):  
   - **Camada 7 (aplicação):** Que protocolo usa? Como funciona?  
   - **Camada 4 (transporte):** TCP ou UDP? Por quê? Como garante qualidade?  
   - **Camada 3 (rede):** Como os pacotes são roteados? E se mudar de rede (celular→Wi-Fi)?  
   - **Camada 2 (enlace):** Como funciona no Wi-Fi? E na Ethernet?  
   - **Camada 1 (física):** Que meio físico? Velocidades?  
   Escreva análise de 5 páginas integrando TODAS as camadas.

**Domine antes de avançar:**
- [ ] Explicar cada camada OSI com protocolos e funções
- [ ] Traçar completo de um pacote da aplicação até o meio físico
- [ ] Entender TCP profundamente (handshake, controle de fluxo, congestionamento)
- [ ] Diferenciar e escolher entre TCP e UDP conforme aplicação
- [ ] Explicar roteamento IP e algoritmos de roteamento
- [ ] Entender DNS completo (recursivo, iterativo, cache)
- [ ] Dominar segurança básica (HTTPS, VPN, criptografia simétrica/assimétrica)
- [ ] Analisar performance de rede (delay, throughput, perda)

**Só avance se:** Conseguir pegar qualquer aplicação de rede (WhatsApp, Netflix, email) e escrever análise completa de 3-4 páginas explicando como funciona em TODAS as camadas, que protocolos usa, por que foram escolhidos, o que acontece se houver problemas e como otimizar - tudo sem consulta.

---

### FASE 3 • Livro 3: Redes de Computadores (Tanenbaum)

**Meta:** Alcançar domínio teórico-prático completo com visão acadêmica e profissional de redes.

**Conteúdos essenciais:**
- Camada física (teoria de transmissão, modulação, multiplexação)
- Camada de enlace (detecção/correção de erros, protocolos de acesso múltiplo)
- Camada de rede (algoritmos de roteamento, QoS, redes definidas por software)
- Camada de transporte (teoria de controle de congestionamento)
- Camada de aplicação (web, email, DNS, CDN, P2P)
- Segurança de redes (ataques, defesas, criptografia aplicada)
- Redes sem fio e móveis (celular, ad hoc, sensor)
- Redes multimídia (streaming, VoIP, qualidade de serviço)
- Tópicos avançados (SDN, virtualização, data centers, IoT)

**Como estudar (passo a passo claro):**

1. **Ler:** Este é o livro mais denso e acadêmico. Use estratégia de "três passadas":  
   - **1ª passada (panorama):** Leia capítulo inteiro sem parar, só para entender estrutura  
   - **2ª passada (profundidade):** Releia seção por seção, fazendo anotações detalhadas  
   - **3ª passada (algoritmos):** Foque em algoritmos e protocolos, simulando-os no papel  
   Este livro tem muita teoria matemática. Não pule as fórmulas - resolva os exemplos manuscritos.

2. **Anotar:** Crie "Enciclopédia Pessoal de Redes" de alto nível:  
   - **Teoria de cada camada:** Fundamentos matemáticos, teoremas, limites teóricos  
   - **Algoritmos:** Para cada algoritmo (distância-vetor, estado de enlace, CSMA/CD), escreva:  
     * Pseudocódigo manuscrito  
     * Exemplo passo a passo com valores numéricos  
     * Análise de complexidade  
     * Vantagens e desvantagens  
   - **Comparações críticas:** Compare abordagens diferentes (roteamento estático vs dinâmico, comutação de circuitos vs pacotes)  
   - **Estado da arte:** Anote tecnologias modernas (SDN, NFV, 5G) e como se relacionam com fundamentos

3. **Praticar:** Exercícios avançados manuscritos:  
   - **Simulação de algoritmos:** Execute algoritmos manualmente (Dijkstra para roteamento, CRC para detecção de erros, janela deslizante para TCP)  
   - **Cálculos complexos:** Resolva TODOS os problemas numéricos (capacidade de Shannon, atraso de fila, análise de performance)  
   - **Design de protocolo:** Crie protocolo próprio no papel para cenário específico (ex: "protocolo para rede de drones")  
   - **Análise de trade-offs:** Compare soluções para problema (ex: "IPv4 vs IPv6: análise técnica completa")  
   - **Estudos de caso:** Analise redes reais (internet, rede celular, data center) usando teoria do livro

4. **Revisar:** "Revisão por conceito transversal":  
   - Escolha um conceito (ex: "confiabilidade") e rastreie através de TODAS as camadas  
   - Crie documento de 5 páginas: "Como cada camada contribui para confiabilidade?"  
   - Faça isso para: confiabilidade, segurança, performance, escalabilidade  
   - Crie "mega mapa mental" A3 conectando TODOS os conceitos dos 3 livros  
   - Revise comparando os 3 livros: onde concordam? onde divergem? por quê?

5. **Testar:** Projeto de especialista:  
   Design completo de rede complexa (ex: "Sistema de streaming de vídeo global"):  
   - **Arquitetura física:** Data centers, CDNs, pontos de presença  
   - **Protocolos escolhidos:** Justifique cada escolha com teoria  
   - **Roteamento:** Algoritmos usados internamente e entre domínios (BGP)  
   - **Transporte:** TCP ou QUIC? Controle de congestionamento?  
   - **Segurança:** Ataques possíveis e defesas em cada camada  
   - **Escalabilidade:** Como sistema escala para milhões de usuários?  
   - **Performance:** Análise matemática de throughput e latência  
   - **Custos e trade-offs:** Decisões de engenharia justificadas  
   Documento de 15-20 páginas manuscritas. Se conseguir, você é especialista.

**Domine antes de avançar:**
- [ ] Entender teoria de informação aplicada a redes (Shannon, Nyquist)
- [ ] Dominar algoritmos de roteamento (Dijkstra, Bellman-Ford, BGP)
- [ ] Analisar matematicamente performance de redes
- [ ] Compreender segurança profunda (ataques, defesas, criptografia)
- [ ] Explicar tecnologias modernas (SDN, NFV, 5G, cloud networking)
- [ ] Projetar protocolos customizados para necessidades específicas
- [ ] Avaliar criticamente trade-offs em decisões de design
- [ ] Relacionar teoria acadêmica com implementação prática

**Só avance se:** Conseguir pegar artigo científico sobre redes (IEEE, ACM) e:  
1. Entender completamente o conteúdo técnico  
2. Avaliar criticamente a proposta  
3. Identificar limitações e melhorias possíveis  
4. Escrever análise de 4-5 páginas demonstrando domínio profundo  
Além disso, conseguir explicar qualquer tópico de redes a níveis diferentes: leigo, técnico e especialista.

---

## INTEGRAÇÃO FINAL

**Objetivo:** Unificar prática operacional + arquitetura de protocolos + teoria avançada em maestria completa de redes.

**Protocolo (faça em ordem):**

1. **Mapa cruzado:** Crie tabela manuscrita gigante (use papel A3 ou cole A4):  
   - **Linhas:** Todos os conceitos importantes (endereçamento, roteamento, transporte, aplicação, segurança, etc.)  
   - **Colunas:** Os 3 livros  
   - **Células:** Como cada livro aborda aquele conceito (prático vs teórico vs avançado)  
   Identifique: onde os livros se complementam? onde há perspectivas diferentes? qual a visão mais completa?

2. **Manual pessoal:** Escreva "Guia Definitivo de Redes" de 30-40 páginas manuscritas:  
   - **Parte 1 - Fundamentos práticos:** Configuração, equipamentos, troubleshooting (do Livro 1)  
   - **Parte 2 - Arquitetura de protocolos:** Camadas, protocolos, funcionamento (do Livro 2)  
   - **Parte 3 - Teoria e algoritmos:** Fundamentos matemáticos, algoritmos (do Livro 3)  
   - **Parte 4 - Integração:** Como tudo se conecta na prática  
   - **Parte 5 - Casos práticos:** 5 cenários complexos analisados completamente  
   - **Parte 6 - Referência rápida:** Checklists, comandos, fórmulas essenciais  
   Este é SEU manual profissional de redes.

3. **Teste de coerência:** Pegue 5 tecnologias de rede (ex: VoIP, CDN, VPN, 5G, IoT):  
   Para cada uma, escreva análise de 3 páginas usando os 3 livros:  
   - **Livro 1:** Como configurar/implementar na prática?  
   - **Livro 2:** Que protocolos usa? Como funcionam em cada camada?  
   - **Livro 3:** Qual a teoria subjacente? Algoritmos? Limitações teóricas?  
   Identifique inconsistências ou contradições. Resolva com pesquisa adicional se necessário.

4. **Aplicação unificada:** Projeto final máster:  
   Design completo de infraestrutura de rede para organização complexa (hospital, universidade, empresa multinacional):  
   - **Nível prático (Livro 1):** Equipamentos, cabeamento, configuração física  
   - **Nível arquitetural (Livro 2):** Protocolos, serviços, aplicações, segurança  
   - **Nível teórico (Livro 3):** Análise de performance, escalabilidade, otimizações  
   - **Integração total:** Documento de 25-30 páginas com:  
     * Diagramas físicos e lógicos  
     * Especificação de equipamentos  
     * Configurações detalhadas  
     * Análise de protocolos e camadas  
     * Cálculos de performance  
     * Plano de segurança multicamada  
     * Estratégia de crescimento e manutenção  
   Este projeto deve demonstrar DOMÍNIO COMPLETO de redes.

5. **Autoavaliação:** Sem consultar nada, responda por escrito:  
   - Explique modelo OSI e TCP/IP de memória (todas as camadas, protocolos)  
   - Trace pacote completo de aplicação até meio físico para aplicação complexa  
   - Liste 10 problemas comuns de rede e diagnóstico/solução para cada  
   - Explique 5 algoritmos de roteamento e quando usar cada um  
   - Descreva 5 ataques de rede e defesas em cada camada  
   - Compare 3 tecnologias modernas (SDN, NFV, etc.) com arquitetura tradicional  
   - Projete protocolo customizado para necessidade específica  
   - Analise matematicamente performance de cenário de rede  
   - Liste seus próximos passos (certificações? especialização? área?)

**Domínio alcançado:** Capacidade de projetar, implementar, analisar e otimizar redes de qualquer escala com profundidade técnica e teórica, tomando decisões fundamentadas em princípios sólidos.

---

## CHECKLIST DE DOMÍNIO

### Fundamentos Práticos (Livro 1)
- [ ] Configurar redes locais (LAN, Wi-Fi)
- [ ] Especificar e conectar equipamentos (switches, routers)
- [ ] Calcular e implementar planos de endereçamento
- [ ] Configurar serviços básicos (DHCP, DNS, NAT)
- [ ] Implementar segurança básica (firewall, WPA2)
- [ ] Diagnosticar e resolver problemas comuns

### Arquitetura de Protocolos (Livro 2)
- [ ] Dominar modelo OSI e TCP/IP
- [ ] Entender protocolos de cada camada profundamente
- [ ] Traçar fluxo completo de dados através das camadas
- [ ] Analisar TCP (handshake, controle de fluxo, congestionamento)
- [ ] Compreender roteamento IP e algoritmos
- [ ] Dominar segurança de redes (criptografia, VPN, HTTPS)
- [ ] Avaliar performance e otimizar redes

### Teoria Avançada (Livro 3)
- [ ] Aplicar teoria de informação a redes
- [ ] Implementar algoritmos de roteamento manualmente
- [ ] Realizar análises matemáticas de performance
- [ ] Entender segurança profunda (ataques, defesas)
- [ ] Dominar tecnologias modernas (SDN, 5G, cloud)
- [ ] Projetar protocolos customizados
- [ ] Avaliar criticamente decisões de design

### Competências Finais
- [ ] Projetar redes complexas do zero
- [ ] Integrar prática, arquitetura e teoria em soluções
- [ ] Diagnosticar problemas em qualquer camada
- [ ] Justificar tecnicamente decisões de design
- [ ] Analisar performance e otimizar redes
- [ ] Implementar segurança multicamada
- [ ] Avaliar e adotar novas tecnologias criticamente
- [ ] Comunicar conceitos técnicos em múltiplos níveis

**Teste final:** Apresente-se a um cenário real: "Empresa está expandindo de 50 para 500 funcionários em 3 locais diferentes, precisa de rede segura, confiável e escalável." Você deve:  
1. Projetar arquitetura completa (física e lógica)  
2. Especificar todos os equipamentos e configurações  
3. Justificar escolha de protocolos e tecnologias  
4. Analisar matematicamente performance esperada  
5. Implementar segurança em todas as camadas  
6. Planejar crescimento futuro  
7. Documentar tudo manuscrito (30-35 páginas)  

Se conseguir fazer isso com confiança e qualidade profissional, você dominou completamente redes de computadores.

---

## NOTAS FINAIS

**Tempo estimado:** 10-18 meses (redes é área extensa e complexa)

**Materiais necessários:**
- Os 3 livros físicos
- 3-4 cadernos grandes (300+ páginas cada)
- Papel extra (muitos diagramas e cálculos)
- Papel A3 ou cartolina (para diagramas grandes)
- Lápis, caneta, borracha (desenhos técnicos)
- Régua e compasso (diagramas de rede)
- Canetas coloridas (para destacar camadas, protocolos)

**Observação sobre prática:**  
Assim como em programação, redes é área que tradicionalmente requer prática com equipamentos reais ou simuladores. O estudo analógico desenvolve compreensão profunda dos conceitos, mas:

**Para validação prática futura:**
- Após cada fase, considere laboratório prático (física ou virtual)
- Configure equipamentos reais ou use simuladores (Packet Tracer, GNS3)
- Capture e analise tráfego real com ferramentas como Wireshark
- Isso revelará nuances que só aparecem na prática

**Por enquanto, no método analógico:**
- Desenhe TUDO: topologias, pacotes, sequências de mensagens
- Simule algoritmos manualmente (trace cada passo)
- Calcule valores numéricos extensivamente
- Crie cenários hipotéticos e resolva no papel

**Progressão dos livros:**
- **Livro 1:** Prático e direto, perfeito para começar
- **Livro 2:** Abordagem top-down pedagógica excelente
- **Livro 3:** Denso e acadêmico, mas essencial para profundidade

**Dica de ouro:** Redes é sobre CAMADAS e PROTOCOLOS. Sempre pense:  
"Que camada? Que protocolo? Como as camadas interagem?"  
Crie diagramas de sequência para TUDO.

**Diferencial desta trilha:**
- Livro 1 te faz FAZER (prática)
- Livro 2 te faz ENTENDER (arquitetura)
- Livro 3 te faz DOMINAR (teoria)
- A integração te faz ESPECIALISTA

**Certificações futuras (após domínio):**
- CompTIA Network+
- Cisco CCNA
- Juniper JNCIA
- Certificações avançadas conforme especialização

---

**Sua jornada para dominar redes de computadores começa agora. Pegue o Livro 1 e desenhe sua primeira topologia! 🌐✍️**
