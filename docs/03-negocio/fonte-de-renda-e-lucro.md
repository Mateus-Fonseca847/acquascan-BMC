# Business Model Canvas · Fonte de Renda e Lucro

## Introdução

Este documento descreve o bloco de **Fonte de Renda e Lucro** do **AcquaScan**, detalhando como o sistema gera faturamento, a diferença entre receita e lucro, a estrutura de custos, margens e a sustentabilidade financeira do negócio frente aos modelos de contratação pública e privada.

**Legenda das evidências:** **Verificado** (fonte pública em Referências) · **Vivência** (observação dos integrantes, moradores de Petrópolis, RJ) · **Pesquisa** (levantamento dos integrantes) · **Hipótese** (a validar, ver seção 5).

---

## 1. Visão geral e conceitos fundamentais

- **Fonte de Renda (Faturamento/Receita):** É o dinheiro total que entra na empresa através da venda de produtos ou da prestação de serviços (**verificado**).
- **Lucro:** É o dinheiro que sobra (o ganho real) depois de subtrair da receita total todos os custos de produção, despesas do negócio (aluguel, salários, insumos) e impostos (**verificado**).
- **Faturamento não é lucro:** Vender muito em um mês não significa que o negócio lucrou, pois os custos operacionais e de fabricação podem ser altos (**verificado**).
- **Pró-labore vs. Lucro:** O lucro da empresa não deve ser misturado com o salário do sócio/fundador (pró-labore); misturar finanças pessoais e empresariais é um dos principais fatores de mortalidade dos negócios (**verificado**).

---

## 2. Perguntas-chave

| Pergunta | Resposta |
|---|---|
| Por qual valor os clientes estão realmente dispostos a pagar? | Pelo fornecimento da estação telemétrica instalada, acesso à API e suporte ao painel de monitoramento preditivo da Defesa Civil ou empresas (**hipótese**). |
| Como eles pagam atualmente e como prefeririam pagar? | Através de contratos públicos anuais de fornecimento/serviço (B2G) ou aquisição de lote fechado para empresas privadas (B2B) (**hipótese**). |
| Quanto cada fonte de renda contribui para a receita total? | A principal fonte provém de contratos de implantação e manutenção com prefeituras; fontes secundárias vêm da venda de estações para o setor privado (**hipótese**). |

---

## 3. Fontes de Renda por Segmento

### 3.1 Contratos de Fornecimento e Licenciamento com o Setor Público (B2G - Principal)
- **Modelo de Receita:** Venda de pacotes de estações de monitoramento acopladas a serviços de licenciamento de software (SaaS) e manutenção anual para Prefeituras e Defesas Civis.
- **Faixa de Entrada (Dispensa de Licitação):** Adequação aos limites de dispensa de licitação previstos pelo Decreto nº 12.807/2025 (**verificado**), permitindo contratações diretas rápidas para implantação inicial em municípios prioritários.
- **Previsibilidade:** Receita recorrente por meio de contratos anuais de manutenção corretiva, preventiva e suporte técnico ao painel de monitoramento da Defesa Civil (**hipótese**).

### 3.2 Venda de Estações Dedicadas para o Setor Privado (B2B - Secundário)
- **Modelo de Receita:** Venda direta de hardware e instalação pontual para empresas com operações de risco próximo a rios (agronegócio, pequenas geradoras de energia, saneamento e condomínios) (**pesquisa**).
- **Composição:** Pagamento único pelo equipamento instalado mais taxa de assinatura opcional para relatórios avançados de vazão e alertas preditivos via API (**hipótese**).

---

## 4. Estrutura de Custos e Margens (Conceito de Lucro)

| Tipo de Lucro / Custo | Descrição no Contexto do AcquaScan |
|---|---|
| **Custos Diretos (CPV)** | Aquisição de módulos ESP32, sensores ultrassônicos e de vazão, baterias, placas solares, gabinetes estanques e montagem física no laboratório (**verificado**). |
| **Lucro Bruto** | Receita total obtida com a venda de estações e contratos menos o custo direto de fabricação e montagem dos sensores (**verificado**). |
| **Despesas Operacionais (Fixas/Variáveis)** | Hospedagem de servidores em nuvem, manutenção de ferramentas de desenvolvimento, suporte técnico de campo, impostos e taxas administrativas (**verificado**). |
| **Lucro Líquido** | O ganho real remanescente após a dedução de todas as despesas operacionais e tributárias, base para reinvestimento ou distribuição de lucros aos sócios (**verificado**). |

---

## 5. Hipóteses a validar

| # | Hipótese | Como testar | Critério |
|---|---|---|---|
| R_H1 | A margem de lucro bruto por estação permite manter a operação saudável mesmo nos limites de dispensa de licitação | Simulação financeira com base nos custos de componentes do ESP32 e sensores | Margem bruta superior a 50% por unidade montada |
| R_H2 | Prefeituras aceitam modelo híbrido de aquisição de hardware com taxa de manutenção anual recorrente | Entrevistas com gestores municipais e análise de editais passados | Aceitação do modelo de suporte anual por pelo menos um órgão público |
| R_H3 | Empresas privadas possuem orçamento discricionário para investir em monitoramento hidrológico preventivo | Abordagem a 5 empresas em áreas de risco em Petrópolis | Identificação de orçamento disponível e interesse na compra |

---

## Referências

- [Decreto Federal nº 12.807/2025: Limites para Dispensa de Licitação](https://effecti.com.br/decreto-12807-de-2025/)
- [Sebrae: Orientações sobre Faturamento, Lucro e Pró-labore](https://www.sebrae.com.br)
- [Repositório do Firmware - Monitoramento Fluxo de Água ESP32](https://github.com/CaiqueRV/Monitoramento-Fluxo-de-Agua-ESP32)