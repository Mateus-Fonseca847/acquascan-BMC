# · 2. Atividades-Chave

## Introdução

O AquaScan é um sistema de monitoramento de rios que mede o nível da água com sensores de baixo custo e comunica o risco de transbordamento em porcentagem, cor e texto, com tempo estimado, por meio de um aplicativo. Este documento descreve o segundo bloco do Business Model Canvas, as **Atividades-Chave**: quais ações, processos operacionais e frentes técnicas são fundamentais para que o modelo de negócio funcione e entregue sua proposta de valor com alta confiabilidade.

Ao longo do texto são detalhadas as frentes de engenharia de software e arquitetura de nuvem, a operação de hardware e montagem de dispositivos IoT em campo, a análise de dados hidrológicos e gestão de riscos em conjunto com a Defesa Civil, as estratégias de engajamento comunitário e suporte, além das hipóteses que ainda precisam ser validadas. Os demais blocos do canvas devem ser coerentes com o que está descrito aqui.

**Legenda das evidências:** **Verificado** (fonte pública em Referências) · **Vivência** (observação dos integrantes, moradores de Petrópolis, RJ) · **Pesquisa** (levantamento dos integrantes, fontes a anexar) · **Hipótese** (a validar, ver seção 7).

---

## 1. Visão geral

| Categoria | Atividade Principal | Descrição Detalhada |
|---|---|---|
| Engenharia de Software | Desenvolvimento e Evolução da Plataforma | Construção e manutenção da interface web/mobile (HTML, CSS, JavaScript, Java), prototipagem e melhorias contínuas de UX/UI |
| Infraestrutura e Dados | Ingestão e Processamento em Tempo Real | Coleta de APIs externas (meteorológicas/hidrológicas), processamento em nuvem e armazenamento seguro de logs |
| Hardware e IoT | Manutenção e Calibração de Dispositivos | Montagem de protótipos de sensores de baixo custo, testes de bancada, implantação física e suporte corretivo/preventivo em campo |
| Operação e Riscos | Alinhamento com Órgãos de Defesa | Mapeamento contínuo de áreas vulneráveis a enchentes e validação técnica de fluxos de alerta com a Defesa Civil |
| Engajamento | Suporte Comunitário e Parcerias Acadêmicas | Articulação com universidades (UFRJ, UFF, LNCC) para P&D e campanhas de adoção com associações de moradores |

---

## 2. Perguntas-chave

| Pergunta | Resposta |
|---|---|
| Que atividades-chave nossa proposta de valor exige? | Desenvolvimento contínuo de software preditivo, engenharia de hardware IoT de baixo custo e processamento de dados hidrológicos em tempo real |
| Quais atividades nossos canais de distribuição exigem? | Sustentabilidade da API de comunicação, distribuição e atualização do aplicativo nas lojas digitais e manutenção do painel web institucional |
| Quais atividades nosso relacionamento com clientes exige? | Suporte técnico ágil durante episódios de tempestade, calibração periódica dos sensores e canais diretos de feedback com a comunidade |
| Quais atividades nossas fontes de renda exigem? | Instalação, ativação de pontos de monitoramento, suporte contratual recorrente e auditoria de relatórios para órgãos públicos e empresas |

---

## 3. Categorias de Atividades

### 3.1 Desenvolvimento de Software e Experiência do Usuário

- **Foco:** Engenharia de software, front-end e back-end.
- **Atividades detalhadas:** 
  - Codificação, testes e atualização contínua da aplicação web e mobile utilizando tecnologias como HTML, CSS, JavaScript e Java.
  - Implementação de algoritmos de tradução de dados brutos (distância/nível do rio) em métricas intuitivas para a população: porcentagem de risco de transbordamento, alertas visuais por cores (baixo, moderado, alto) e estimativa de tempo para enchente.
  - Gestão rigorosa de versão de código-fonte e controle de ramas através do GitHub.

### 3.2 Infraestrutura de Dados e Computação em Nuvem

- **Foco:** Arquitetura de backend e engenharia de dados.
- **Atividades detalhadas:**
  - Configuração, gerenciamento e escalabilidade de servidores em nuvem para suportar picos de acesso massivo durante ocorrências de tempestades severas.
  - Integração contínua com fontes e APIs meteorológicas externas para cruzamento de dados de precipitação pluviométrica com o nível atual dos rios.
  - Monitoramento da integridade, latência e segurança do fluxo de dados que alimenta tanto o painel da Defesa Civil quanto o aplicativo dos moradores.

### 3.3 Hardware, IoT e Operação de Campo

- **Foco:** Eletrônica aplicada, montagem e engenharia de campo.
- **Atividades detalhadas:**
  - Aquisição, soldagem e montagem de componentes eletrônicos de baixo custo (como módulos de sensores ultrassônicos/radar e placas de microcontroladores) para a criação dos pontos de monitoramento.
  - Execução de testes rigorosos de bancada e calibração de precisão dos dispositivos sob condições simuladas de umidade e variação térmica.
  - Instalação física estruturada em pontes, margens e locais estratégicos de rios urbanos (com base no conhecimento prático da topografia de Petrópolis).
  - Execução de rondas de manutenção preventiva e corretiva para substituição de baterias, limpeza de lentes/sensores e reparo de danos causados por intempéries.

### 3.4 Análise de Riscos, Inteligência e Parcerias Operacionais

- **Foco:** Mitigação de desastres e validação institucional.
- **Atividades detalhadas:**
  - Mapeamento analítico contínuo das zonas históricas de alagamento e bacias hidrográficas críticas da Região Serrana.
  - Alinhamento de relatórios técnicos e cruzamento de métricas com a Defesa Civil municipal para aprimorar a assertividade dos alertas preventivos emitidos à população.

### 3.5 Engajamento Comunitário, Suporte e P&D Acadêmico

- **Foco:** Difusão tecnológica e adoção social.
- **Atividades detalhadas:**
  - Parcerias ativas com centros de pesquisa e universidades (como UFRJ, UFF e o LNCC) para validação científica de modelos preditivos e captação de talentos técnicos.
  - Realização de oficinas, palestras e campanhas educativas junto a associações de moradores de áreas de risco para incentivar o download, a configuração correta do aplicativo e a compreensão dos avisos de segurança.

---

## 4. Fora do foco

| Atividade | Motivo |
|---|---|
| Fabricação própria e fundição de semicondutores e placas brutas de silício | O modelo baseia-se na integração inteligente de componentes comerciais acessíveis de prateleira (off-the-shelf), focando no valor do software e da inteligência dos dados |
| Operação física direta de sirenes de alerta e ações de salvamento e resgate civil | Atividade exclusiva e de competência legal da Defesa Civil e dos bombeiros; o AcquaScan atua estritamente na fase de prevenção, monitoramento preditivo e comunicação antecipada |

---

## 5. Hipóteses a validar

| # | Hipótese | Como testar | Critério |
|---|---|---|---|
| A1 | Os protótipos de sensores de baixo custo mantêm estabilidade de leitura sob chuva torrencial prolongada | Piloto controlado em campo em um ponto crítico de monitoramento | Margem de erro aceitável comparada aos padrões oficiais de medição hidrológica |
| A2 | A infraestrutura de nuvem absorve picos repentinos de acessos simultâneos durante eventos de forte tempestade | Testes de estresse simulados na API e nos servidores de backend | Tempo de resposta do aplicativo inferior a 2 segundos sob alta concorrência de usuários |
| A3 | Os ciclos de manutenção corretiva e preventiva de campo otimizam o tempo de vida útil dos sensores instalados | Acompanhamento do desgaste físico e eletrônico dos dispositivos ao longo dos meses de operação | Frequência média de falhas inferior ao limite projetado para viabilidade operacional |