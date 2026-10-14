# 1. Relacionamento com o Cliente, Canais e Estratégia de Atendimento

O modelo de relacionamento com o cliente do **AcquaScan** foi desenhado para atender a uma dualidade complexa: de um lado, clientes institucionais e governamentais que garantem a viabilidade financeira e a implantação da infraestrutura; do outro, cidadãos em áreas de risco, cuja adoção em massa do aplicativo é o principal indicador de sucesso do propósito social da startup.

---

## 1.1. Segmentação Detalhada do Público-Alvo

### A. Cliente Direto e Institucional (Governo)
* **Quem são:** Órgãos públicos municipais e estaduais, com foco inicial na Prefeitura de Petrópolis e na Defesa Civil, expandindo futuramente para outros municípios da Região Serrana e do estado do Rio de Janeiro.
* **Necessidades:** Reduzir o tempo de resposta a emergências, otimizar o uso de sirenes e equipes de campo, e obter dados precisos sobre o comportamento dos rios (como os rios Quitandinha e Piabanha) com antecedência superior a 30 minutos.
* **Proposta de Valor:** Modernização da gestão de riscos climáticos, relatórios automatizados, conformidade com metas de proteção civil e redução drástica de perdas humanas e patrimoniais.

### B. Usuário Final (Cidadãos e Comunidades)
* **Quem são:** População residente em áreas de vulnerabilidade hidrológica, encostas e margens de rios em Petrópolis (como bairros historicamente afetados: Centro, Coronel Veiga, Alto da Serra, Bingen, entre outros).
* **Necessidades:** Informações claras, sem jargões técnicos complexos, sobre o nível da água perto de sua residência, alertas rápidos no celular e orientações inequívocas sobre para onde ir (pontos de apoio) e quais rotas de evacuação seguir.
* **Proposta de Valor:** Autonomia e segurança diante de temporais, transformando o medo em preparo por meio de um aplicativo gratuito e de fácil acesso.

### C. Parceiros de Receita Secundária (Setor Privado)
* **Quem são:** Seguradoras de veículos e residências, além de grandes empresas e indústrias da região serrana que possuem ativos expostos a eventos climáticos extremos.
* **Necessidades:** Dados hidrológicos históricos e em tempo real para modelagem de risco, tarifação de seguros mais justa e planejamento logístico preventivo.
* **Proposta de Valor:** Fornecimento de relatórios analíticos especializados e feeds de dados via API corporativa.

---

## 1.2. Canais de Venda, Distribuição e Comunicação

A estratégia de canais do AcquaScan difere conforme o público atendido:

| Canal | Tipo de Público | Finalidade e Descrição |
|---|---|---|
| **Vendas Diretas e Institucionais** | Órgãos Públicos / Prefeituras | Negociações B2G (Business-to-Government), reuniões técnicas presenciais com a Defesa Civil e participação ativa em licitações públicas para fornecimento do sistema completo (hardware + software). |
| **Lojas de Aplicativos (App Stores)** | Usuário Final (Cidadãos) | Disponibilização gratuita do aplicativo móvel multiplataforma nas lojas oficiais (Google Play para Android e App Store para iOS). |
| **Instalação Física e Campo** | Infraestrutura Urbana | Atuação da equipe de engenharia e técnicos de campo para a instalação, calibração e manutenção periódica da rede de sensores inteligentes nas bacias hidrográficas. |
| **Marketing Institucional e B2B** | Empresas e Seguradoras | Apresentação de cases de sucesso, relatórios técnicos demonstrando a eficácia dos alertas de 30 minutos e captação de parcerias corporativas e fundos ESG. |
| **Campanhas de Educação Pública** | População Geral | Ações presenciais e digitais em parceria com a Prefeitura e escolas, promovendo simulações de evacuação, divulgação de pontos de apoio e treinamento comunitário. |

---

## 1.3. Política de Precificação e Modelo de Receita

O modelo comercial combina sustentabilidade financeira com o cumprimento da missão social da startup:

1. **Implementação Inicial (Cobrança Única):** Referente ao custo de instalação da rede física de sensores (ex: projeto inicial com módulos nas bacias), customização do back-end, integração com o PostGIS e configuração do sistema para as especificidades geográficas do município.
2. **Contrato Anual de Serviço e Manutenção (SaaS / Recorrente):** Cobrança anual prestada à prefeitura/órgãos públicos para cobrir atualizações contínuas do sistema, suporte técnico 24/7, manutenção preventiva dos sensores e melhorias no aplicativo orientadas por IA.
3. **Licenciamento Corporativo:** Planos mensais direcionados a empresas parceiras e seguradoras que necessitam de acesso a painéis avançados de monitoramento de risco.
4. **Venda de Dados Especializados:** Contratos de fornecimento de relatórios hidrometeorológicos estruturados para entidades de gestão de recursos hídricos.

---

## 1.4. Estratégias para Mitigar Riscos de Relacionamento (Análise FOFA aplicada)

Para garantir que o relacionamento com o cliente e a adoção do sistema sejam bem-sucedidos, o projeto adota medidas preventive claras baseadas em suas vulnerabilidades:

* **Combate à Baixa Adoção Popular:** O aplicativo não atua isoladamente; ele é complementado por programas contínuos de educação pública, engajamento comunitário e simulações de evacuação. A população passa a ser tratada como parceira ativa do sistema, e não apenas usuária passiva.
* **Credibilidade Inegociável dos Alertas:** Para evitar alarmes falsos que destruam a confiança da população e dos órgãos públicos, a equipe de desenvolvimento e análise de dados prioriza alta precisão algorítmica na conversão de distâncias e vazões em estados de alerta (estável, atenção, crítico).
* **Mitigação de Ciclos de Venda Longos com o Governo:** Proposta de modelos contratuais baseados em Serviço as a Service (com suporte e manutenção inclusos) e busca por parcerias como subcontratadas de grandes construtoras ou players de infraestrutura já contratados pelo Estado, facilitando a entrada institucional.