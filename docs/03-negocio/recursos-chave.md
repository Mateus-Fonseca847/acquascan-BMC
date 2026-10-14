# Business Model Canvas · 6. Recursos-Chave

Este bloco mapeia os ativos mais importantes e indispensáveis que o AcquaScan precisa possuir, alugar ou obter por meio de parcerias para fazer o seu modelo de negócio funcionar, entregar a proposta de valor e alcançar os clientes.

**Legenda das evidências:** **Verificado** (fonte pública ou código nos repositórios) · **Vivência** (observação dos integrantes, moradores de Petrópolis, RJ) · **Pesquisa** (levantamento dos integrantes) · **Hipótese** (a validar, ver seção 6).

---

## 1. Visão geral

| Categoria | Recurso-Chave | Finalidade Operacional |
|---|---|---|
| Físicos | Estações de Monitoramento (ESP32 + Sensores) | Coleta telemétrica contínua do nível e vazão dos rios |
| Físicos | Laboratório Técnico e de Calibração | Montagem, calibração, testes e suporte à infraestrutura de campo |
| Intelectuais | Algoritmos e Plataforma de Software | Processamento de risco, estimativa de transbordamento, API e aplicativo |
| Intelectuais | Base de Dados Geográfica e Histórica | Cruzamento de rios, ruas (PostGIS) e pontos de apoio oficiais |
| Humanos | Equipe Multidisciplinar Especializada | Engenharia de software, ciência de dados, campo e atendimento institucional |
| Financeiros | Capital de Giro e Investimento Inicial | Sustentabilidade operacional durante o ciclo de contratação pública e desenvolvimento |

---

## 2. Perguntas-chave

| Pergunta | Resposta |
|---|---|
| Quais recursos a nossa proposta de valor exige? | Sensores telemétricos hidrológicos calibrados, algoritmo de estimativa de transbordamento e aplicativo acessível para a população. |
| De que precisamos para abastecer os nossos canais de distribuição? | Infraestrutura de nuvem resiliente, lojas de aplicativos (App Store / Google Play) e logística de campo para instalação física nas calhas urbanas. |
| Quais ativos são fundamentais para manter o relacionamento com os clientes e gerar receita? | Painel Web de monitoramento para a Defesa Civil, sistema de notificações push para o cidadão e canal de atendimento técnico especializado para contratos públicos. |

---

## 3. Tipos de Recursos-Chave

### 3.1 Físicos (Bens tangíveis)
- **Rede de Estações Telemétricas:** Microcontroladores ESP32 integrados a sensores de nível ultrassônicos e sensores de vazão (YF-S201), equipados com módulos de comunicação e fontes de energia resilientes para operação contínua nas calhas dos rios de Petrópolis (**verificado no firmware**).
- **Laboratório Técnico:** Espaço físico em Petrópolis (RJ) para armazenamento, montagem, bancada de testes hidrológicos, calibração e manutenção corretiva/preventiva dos equipamentos (**pesquisa / plano operacional**).
- **Logística e Infraestrutura de Campo:** Veículo leve para deslocamento das equipes técnicas responsáveis pelo mapeamento, instalação e vistoria periódica das estações nos pontos críticos da bacia (**pesquisa**).
- **Servidores e Equipamentos de Rede:** Computadores e infraestrutura local para a central de monitoramento e suporte operacional aos técnicos (**verificado**).

### 3.2 Intelectuais (Ativos intangíveis, marcas, dados e softwares)
- **Algoritmo de Risco e Estimativa de Transbordamento:** Regras de cálculo proprietárias que convertem a distância medida em porcentagem de cota crítica e calculam o tempo estimado para extravasamento com base na velocidade de subida do rio (`estável`, `atenção`, `crítico`) (**verificado no código da arquitetura**).
- **Base de Dados Georreferenciada (PostGIS + OpenStreetMap):** Mapeamento que associa cada rua de Petrópolis à estação de rio correspondente, além do cadastro georreferenciado dos pontos de apoio oficiais da Prefeitura (**verificado**).
- **Plataforma e Código-Fonte Proprietário:** Código-fonte da API em Node.js/Fastify, aplicativo móvel em React Native e Painel Web para a Defesa Civil (**verificado nos repositórios**).
- **Marca e Propriedade Intelectual:** Marca registrada *AcquaScan* e documentação técnica necessária para habilitação em licitações e parcerias públicas (**hipótese**).

### 3.3 Humanos (Equipe e capital intelectual)
- **Engenharia de Software e Firmware:** Desenvolvimento e manutenção do código embarcado do ESP32, da API de comunicação e do aplicativo móvel.
- **Ciência de Dados e Hidrologia:** Modelagem matemática, tratamento das séries temporais e calibração dos limiares de alerta em parceria com a Defesa Civil.
- **Técnicos de Campo:** Profissionais responsáveis pela instalação física nas pontes e estruturas urbanas, inspeções e manutenção preventiva dos equipamentos.
- **Gestão B2G e Atendimento Institucional:** Responsável por negociações com órgãos públicos, participação em licitações, gestão de contratos e suporte ao cliente.

### 3.4 Financeiros (Dinheiro em caixa, linhas de crédito e capital de giro)
- **Capital de Giro Operacional:** Mínimo reservado para cobrir custos fixos e operacionais durante o ciclo de contratação pública, que costuma ser longo (**verificado no plano financeiro**).
- **Investimento Inicial:** Recursos alocados para a produção do primeiro lote de sensores e estruturação do laboratório (estimado em R$ 580.000,00 no plano financeiro original, **verificado**).
- **Reserva para Insumos e Manutenção:** Fluxo de caixa destinado à aquisição imediata de componentes eletrônicos, baterias e reposições sem interromper a operação.

---

## 4. Matriz de Dependência dos Recursos

| Recurso-Chave | Origem do Recurso | Risco de Indisponibilidade | Ação de Mitigação |
|---|---|---|---|
| Módulos ESP32 e Sensores | Compra / Importação | Médio (falta de componentes no mercado) | Manutenção de estoque crítico de peças de reposição no laboratório |
| Servidores e Banco de Dados | Nuvem (Hostinger / AWS) | Baixo (instabilidade de servidor) | Arquitetura redundante e rotinas de backup automatizadas |
| Equipe Técnica de Campo | Própria / Contratada | Médio (rotatividade de pessoal) | Padronização dos manuais de instalação e calibração das estações |
| Pontes e Estruturas Urbanas | Permissão da Prefeitura/INEA | Alto (burocracia ou negação de acesso) | Acordo formal e termos de cooperação prévios com os órgãos públicos |

---

## 5. Hipóteses a validar

| # | Hipótese | Como testar | Critério |
|---|---|---|---|
| RC_H1 | O sensor ultrassônico e o módulo ESP32 mantêm a precisão em condições climáticas extremas (chuva forte e umidade) | Teste de bancada e campo por 30 dias em Petrópolis | Variação de leitura inferior a 3% sem perda de sinal |
| RC_H2 | O custo unitário da estação permite enquadramento em compras diretas por dispensa de licitação | Levantamento de cotações de componentes e montagem | Custo total por ponto montado inferior ao teto de dispensa municipal |
| RC_H3 | A base do OpenStreetMap integrável ao PostGIS é suficiente para mapear todas as ruas de risco de Petrópolis | Validação amostral de 20 ruas históricas do Centro e distritos | Cobertura superior a 95% das vias mapeadas corretamente |

---

## Referências

- [Repositório do Firmware - Monitoramento Fluxo de Água ESP32](https://github.com/CaiqueRV/Monitoramento-Fluxo-de--gua-ESP32)
- [Repositório do Aplicativo AcquaScan (React Native)](https://github.com/Mateus-Fonseca847/acquascan-app)
- [Decreto Federal nº 12.807/2025: Limites para Dispensa de Licitação](https://effecti.com.br/decreto-12807-de-2025/)