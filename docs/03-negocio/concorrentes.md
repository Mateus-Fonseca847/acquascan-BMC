# Análise de concorrentes — AcquaScan

> **Objetivo:** identificar soluções que já atendem, total ou parcialmente, ao problema de monitoramento de rios, prevenção de enchentes e comunicação de riscos em Petrópolis (RJ). A análise busca entender o posicionamento do AcquaScan, seus diferenciais potenciais, as limitações das alternativas existentes e as oportunidades de validação do modelo de negócio.
>
> **Última revisão:** 14/10/2026  
> **Status da análise:** levantamento documental inicial. As funcionalidades descritas devem ser verificadas nas plataformas oficiais, e os diferenciais do AcquaScan ainda precisam ser comprovados por testes e pesquisa com usuários.

## 1. Resumo executivo

O AcquaScan pretende oferecer uma solução de monitoramento de rios voltada à realidade de Petrópolis, cidade sujeita a chuvas intensas, elevações rápidas do nível dos rios, inundações e interrupções de vias. A proposta combina sensores de baixo custo, transmissão de dados, visualização geográfica e notificações para ajudar os moradores a compreender melhor a situação de risco em sua região.

O mercado já conta com iniciativas públicas relevantes. O Instituto Estadual do Ambiente (INEA) mantém o Sistema de Alerta de Cheias, que monitora chuva e níveis de rios e disponibiliza informações e alertas. A Defesa Civil de Petrópolis divulga avisos meteorológicos e utiliza diferentes canais de comunicação e protocolos de resposta. Também existem serviços de previsão meteorológica, aplicativos de navegação e canais de emergência que resolvem partes do problema.

Assim, o AcquaScan não deve ser apresentado como substituto dos órgãos públicos nem como o primeiro sistema de monitoramento hidrológico. Sua oportunidade está em **integrar informações de interesse local e apresentá-las de maneira simples, geográfica e orientada à tomada de decisão do morador**, desde que a viabilidade técnica e a utilidade dessa integração sejam demonstradas.

Os principais pontos que diferenciam a proposta são:

- Monitoramento local por estações próprias com sensores de nível e vazão, caso a instalação e a calibração sejam validadas.
- Apresentação das condições dos rios em um mapa de Petrópolis.
- Consulta por rua ou região, com possibilidade de notificações relacionadas à localização do usuário.
- Organização de informações de risco e pontos de apoio em uma interface única.
- Possibilidade de complementar os sistemas existentes por meio de integração de dados, sem duplicar desnecessariamente estruturas públicas.

Esses pontos representam **diferenciais pretendidos**, não vantagens competitivas já comprovadas. A cobertura dos sensores, a confiabilidade das medições, a frequência de atualização, a capacidade de antecipação e a aceitação pelos moradores ainda precisam ser testadas.

## 2. Critérios utilizados na análise

Os concorrentes foram avaliados de acordo com os seguintes critérios:

| Critério | O que será analisado |
|---|---|
| Monitoramento hidrológico | Disponibilidade de informações sobre nível dos rios, chuva ou vazão. |
| Cobertura local | Capacidade de representar a situação de Petrópolis e de suas diferentes regiões. |
| Atualização dos dados | Frequência e disponibilidade das informações, incluindo possíveis atrasos ou indisponibilidades. |
| Alertas | Existência de avisos por SMS, notificações, sirenes ou outros canais. |
| Contexto geográfico | Possibilidade de identificar regiões, ruas ou pontos de interesse afetados. |
| Apoio à decisão | Capacidade de ajudar o usuário a entender o risco e saber onde consultar orientações oficiais. |
| Rotas e mobilidade | Informações sobre vias interditadas, bloqueios e deslocamentos. |
| Integração | Possibilidade de reunir dados de diferentes fontes sem comprometer sua origem e confiabilidade. |
| Acessibilidade | Facilidade de uso, clareza das informações e alcance da comunicação. |
| Custo para o usuário | Necessidade de pagamento para acessar as funcionalidades principais. |

A comparação considera o escopo conhecido de cada solução, e não testes práticos de desempenho. A ausência de uma funcionalidade na tabela significa que ela não foi confirmada nas fontes consultadas, e não necessariamente que ela inexiste.

## 3. Concorrentes diretos

São considerados concorrentes diretos os sistemas cuja finalidade principal inclui monitorar condições hidrológicas, informar sobre cheias ou alertar a população sobre riscos associados à elevação dos rios.

### 3.1. Sistema Alerta de Cheias — INEA

**Site oficial:** https://alertadecheias.inea.rj.gov.br/  
**Página institucional:** https://www.inea.rj.gov.br/ar-agua-e-solo/alerta-de-cheias/

**Descrição**

O Sistema Alerta de Cheias, mantido pelo Instituto Estadual do Ambiente (INEA), monitora chuvas e níveis de rios por meio de estações telemétricas e radares meteorológicos. As informações são utilizadas para acompanhar as condições hidrometeorológicas e apoiar o envio de alertas à população e às autoridades de Defesa Civil.

O sistema apresenta estágios de situação, incluindo vigilância, atenção, alerta, alerta máximo e transbordamento. O INEA também informa a possibilidade de receber alertas por SMS, mediante o envio do CEP para o número 40199.

**Pontos fortes**

- É uma iniciativa institucional voltada ao monitoramento hidrometeorológico.
- Utiliza estações de monitoramento e radares meteorológicos.
- Disponibiliza informações e alertas por canais oficiais.
- Possui uma estrutura operacional voltada ao acompanhamento das condições dos rios.
- Pode fornecer dados relevantes para estudos e para uma eventual integração com outras soluções.

**Limitações e oportunidades a investigar**

- A facilidade de uso para moradores sem conhecimento técnico precisa ser avaliada diretamente.
- É necessário verificar quais estações estão operacionais atualmente em Petrópolis e quais rios são efetivamente cobertos.
- A cobertura espacial e a frequência de atualização devem ser verificadas para cada estação relevante.
- É preciso avaliar se a apresentação das informações responde às dúvidas práticas de cada morador, como a situação de sua região e onde consultar orientações oficiais.
- A existência de dados públicos não garante automaticamente que eles possam ser integrados por uma API, reutilizados sem restrições ou empregados em um serviço que exija alta disponibilidade.

**Relação com o AcquaScan**

O INEA é a referência institucional mais importante para a análise competitiva do AcquaScan. A proposta não deve duplicar suas funções sem necessidade. Uma estratégia mais consistente é investigar a possibilidade de utilizar dados públicos autorizados e complementar a cobertura local com sensores próprios, quando houver lacunas demonstradas.

O AcquaScan poderá buscar diferenciação na interface geográfica, na organização das informações por região e na experiência de uso. Essa vantagem somente poderá ser afirmada após uma comparação prática com o sistema existente.

### 3.2. Defesa Civil de Petrópolis

**Portal institucional:** https://www.petropolis.rj.gov.br/

**Descrição**

A Defesa Civil municipal atua na prevenção, no monitoramento, na comunicação de riscos e na resposta a situações de emergência. Entre os recursos utilizados no município estão avisos meteorológicos, alertas por diferentes canais, sirenes em áreas contempladas, protocolos operacionais e ações de orientação à população.

A atuação municipal envolve mais do que a transmissão de dados: inclui avaliação de cenários, coordenação de respostas e comunicação de medidas de proteção.

**Pontos fortes**

- Possui responsabilidade institucional pela proteção e orientação da população.
- Atua de acordo com protocolos de contingência e procedimentos de emergência.
- Pode divulgar orientações oficiais sobre situações de risco.
- Tem conhecimento do contexto local e articulação com outros órgãos públicos.
- Pode utilizar diferentes canais para alcançar os moradores.

**Limitações e oportunidades a investigar**

- É necessário avaliar como os moradores encontram, interpretam e acompanham as informações divulgadas.
- A pesquisa com usuários deverá identificar se as informações estão suficientemente centralizadas e acessíveis.
- A cobertura e a disponibilidade de cada canal precisam ser verificadas, sem presumir que todos os moradores recebem todos os avisos.
- É importante entender quais dados podem ser compartilhados ou integrados e quais decisões permanecem exclusivamente sob responsabilidade dos órgãos públicos.

**Relação com o AcquaScan**

A Defesa Civil não deve ser tratada apenas como concorrente comercial. Ela é também uma possível parceira institucional e uma fonte de orientações oficiais.

O AcquaScan pode procurar complementar a comunicação existente, facilitando a consulta a dados e informações relevantes. Não deve emitir orientações contraditórias, substituir alertas oficiais nem induzir o usuário a acreditar que o aplicativo garante segurança em determinada região.

### 3.3. Estações e redes públicas de monitoramento hidrometeorológico

**Referência institucional:** https://www.inea.rj.gov.br/ar-agua-e-solo/monitoramento-hidrometeorologico/

**Descrição**

As redes de monitoramento hidrometeorológico reúnem equipamentos que registram variáveis como precipitação e nível da água. Essas medições alimentam análises técnicas, estudos hidrológicos e sistemas de alerta.

Embora não sejam necessariamente aplicativos voltados diretamente ao consumidor, essas redes concorrem com parte da proposta tecnológica do AcquaScan: coletar e disponibilizar informações sobre as condições dos rios.

**Pontos fortes**

- Utilizam infraestrutura de monitoramento dedicada.
- Produzem dados úteis para o acompanhamento hidrológico.
- Podem oferecer séries históricas importantes para análises e calibração.
- Podem servir como fonte de referência para comparação e validação das medições do AcquaScan.

**Limitações e oportunidades a investigar**

- A disponibilidade de dados varia conforme a estação, a variável monitorada e a situação operacional.
- É necessário verificar a cobertura efetiva nos locais de interesse do projeto.
- Os procedimentos para acesso, integração, atribuição de fonte e reutilização dos dados precisam ser confirmados.
- Uma rede própria de sensores exigirá manutenção, calibração e controle de qualidade para que seus resultados sejam confiáveis.

**Relação com o AcquaScan**

O AcquaScan poderá avaliar se existe uma lacuna de cobertura local que justifique a instalação de sensores adicionais. Antes de investir em equipamentos, deve comparar a rede pública existente com os locais de maior interesse para os usuários.

A instalação de novos sensores só representará vantagem se produzir dados úteis, confiáveis e complementares.

## 4. Concorrentes indiretos e soluções substitutas

Os concorrentes indiretos não necessariamente medem o nível dos rios. Entretanto, ajudam os usuários a obter previsões meteorológicas, consultar alertas, verificar condições de deslocamento ou tomar decisões durante eventos de chuva.

### 4.1. Canais de alerta por SMS e Cell Broadcast

**Referência sobre alertas do INEA:** https://www.inea.rj.gov.br/ar-agua-e-solo/alerta-de-cheias/

**Descrição**

Os alertas por SMS e os avisos emergenciais enviados diretamente aos celulares são canais de comunicação de risco. Eles podem alcançar pessoas sem que seja necessário abrir continuamente um aplicativo.

**Pontos fortes**

- Permitem a comunicação de mensagens urgentes.
- Podem alcançar usuários que não acompanham páginas ou aplicativos de meteorologia.
- Funcionam como canais complementares a sistemas de monitoramento e a sirenes.
- Podem transmitir orientações importantes durante eventos críticos.

**Limitações e oportunidades a investigar**

- O formato da mensagem pode limitar a quantidade de contexto geográfico apresentado.
- A entrega e o recebimento dependem das características de cada canal.
- Um alerta não substitui a consulta a orientações oficiais e a avaliação da situação local.
- O AcquaScan precisará evitar notificações excessivas, informações conflitantes e a duplicação desnecessária de avisos.

**Relação com o AcquaScan**

O aplicativo pode complementar esses canais oferecendo uma interface para consultar informações locais e entender o contexto do alerta. Não deve presumir que suas notificações chegarão mais rápido ou serão mais confiáveis que os canais oficiais.

### 4.2. Aplicativos de previsão do tempo

**Exemplos para investigação:** INMET e serviços comerciais de previsão meteorológica.

- INMET: https://portal.inmet.gov.br/

**Descrição**

Aplicativos e portais meteorológicos apresentam previsões, condições atuais, acumulados de chuva e avisos meteorológicos, dependendo do serviço utilizado.

**Pontos fortes**

- Ajudam a acompanhar a previsão de chuva.
- Oferecem informações meteorológicas que podem contribuir para a prevenção.
- São úteis para o planejamento cotidiano.
- Podem disponibilizar mapas, previsões por localidade e notificações.

**Limitações e oportunidades a investigar**

- Uma previsão de chuva não equivale a uma medição direta do nível de um rio.
- A ocorrência de alagamento depende de fatores locais que não podem ser inferidos apenas pelo volume previsto de precipitação.
- A resolução espacial, os intervalos de atualização e os recursos de alerta variam entre serviços.
- O usuário pode precisar consultar outras fontes para compreender a condição hidrológica de uma região.

**Relação com o AcquaScan**

A oportunidade do AcquaScan está em aproximar informações meteorológicas e hidrológicas, quando houver dados confiáveis disponíveis. O projeto não deve apresentar previsões meteorológicas como se fossem previsões garantidas de transbordamento.

### 4.3. Aplicativos de navegação e trânsito

**Exemplos:** Waze e Google Maps.

- Waze: https://www.waze.com/
- Google Maps: https://maps.google.com/

**Descrição**

Aplicativos de navegação auxiliam no planejamento de deslocamentos e podem apresentar informações sobre trânsito, incidentes ou vias afetadas, conforme a disponibilidade de dados.

**Pontos fortes**

- São conhecidos por muitos usuários.
- Facilitam a visualização de ruas e trajetos.
- Podem ajudar na identificação de alterações no trânsito.
- São úteis para planejar deslocamentos cotidianos.

**Limitações e oportunidades a investigar**

- A disponibilidade e a atualização de informações sobre alagamentos ou interdições podem variar.
- Uma rota calculada pelo aplicativo não deve ser considerada automaticamente segura em uma emergência.
- Informações de trânsito não substituem alertas hidrológicos nem instruções da Defesa Civil.
- Não se deve presumir que esses serviços tenham acesso a todos os dados de nível dos rios ou aos protocolos de emergência municipais.

**Relação com o AcquaScan**

O AcquaScan poderá organizar informações de risco e referências geográficas que ajudem o usuário a consultar a situação de sua região. A eventual indicação de rotas seguras é uma funcionalidade de maior risco e exigiria dados atualizados sobre interdições, validação com as autoridades e critérios rigorosos de segurança.

A primeira versão do projeto deve priorizar a apresentação confiável dos dados e a indicação de canais oficiais, antes de prometer rotas de evacuação.

### 4.4. Aplicativos e canais de notícias locais

**Exemplo de referência regional:** Tribuna de Petrópolis — https://tribunadepetropolis.com.br/

**Descrição**

Veículos de comunicação locais divulgam informações sobre chuvas, ocorrências, interdições, medidas públicas e situações que afetam os moradores.

**Pontos fortes**

- Trazem contexto sobre acontecimentos locais.
- Podem divulgar informações relevantes durante eventos críticos.
- Ajudam a população a acompanhar a evolução das ocorrências.
- Complementam os comunicados institucionais.

**Limitações e oportunidades a investigar**

- Notícias são conteúdos editoriais e não substituem a medição contínua do nível dos rios.
- O formato e o momento de publicação dependem de cada ocorrência.
- O usuário pode precisar cruzar informações de várias fontes.
- É necessário distinguir notícias, previsões, alertas oficiais e dados medidos.

**Relação com o AcquaScan**

O AcquaScan pode facilitar o acesso a informações oficiais e dados hidrológicos, desde que suas fontes sejam identificadas. A eventual exibição de notícias deve respeitar os direitos dos produtores de conteúdo e evitar a reprodução indevida de material protegido.

## 5. Matriz comparativa

A tabela abaixo compara o escopo conhecido das soluções. Ela não representa uma avaliação de desempenho realizada em campo.

| Funcionalidade | AcquaScan — proposta | INEA — Alerta de Cheias | Defesa Civil de Petrópolis | Previsão meteorológica | Navegação e trânsito |
|---|---|---|---|---|---|
| Monitoramento de chuva | A integrar ou validar | Sim | Utiliza dados e monitoramento | Sim, conforme o serviço | Não é a função principal |
| Medição de nível dos rios | Prevista por sensores próprios | Sim, em estações monitoradas | Utiliza informações para monitoramento e resposta | Não é a função principal | Não é a função principal |
| Medição de vazão | Prevista no projeto; precisa ser validada | Existem medições de vazão em parte das estações, conforme o INEA | Não é a função principal | Não | Não |
| Visualização local em mapa | Prevista | Consultar recursos disponíveis no sistema | Consultar canais e ferramentas vigentes | Varia por serviço | Sim, para navegação |
| Alertas à população | Previstos | Sim | Sim, por canais oficiais | Varia por serviço | Alertas de trânsito, conforme a plataforma |
| Consulta por rua ou região | Prevista; precisa ser testada | Verificar recursos disponíveis | Depende do canal e da informação publicada | Varia por serviço | Sim para busca e navegação, mas não necessariamente para risco hidrológico |
| Pontos de apoio | Previstos | Não é o foco principal | Fonte prioritária a consultar | Não é o foco principal | Não é o foco principal |
| Informações sobre vias interditadas | A desenvolver ou integrar | Não é o foco principal | Pode divulgar informações oficiais | Não é o foco principal | Pode apresentar incidentes e alterações de trânsito |
| Integração de diferentes fontes | Objetivo do projeto | Integra dados de monitoramento próprios e fontes pertinentes ao sistema | Articula informações e ações institucionais | Varia por serviço | Varia por plataforma |
| Operação e resposta oficial a emergências | Não é atribuição do projeto | Apoia o sistema de alerta | Sim, dentro das competências do órgão | Não | Não |

**Observação:** funcionalidades como rotas de evacuação, previsão de transbordamento por rua e integração automática com sistemas externos não devem ser tratadas como capacidades existentes do AcquaScan até que sejam implementadas e validadas.

## 6. Análise SWOT competitiva do AcquaScan

A análise SWOT identifica forças, fraquezas, oportunidades e ameaças da proposta em relação às soluções existentes.

### 6.1. Forças potenciais

- Foco específico no contexto geográfico de Petrópolis.
- Possibilidade de apresentar dados hidrológicos em uma interface simples.
- Arquitetura planejada com sensores, transmissão de dados, API, banco de dados geográfico e aplicativo.
- Possibilidade de combinar dados medidos com informações públicas autorizadas.
- Orientação para a consulta por região e para a compreensão do risco pelo morador.
- Potencial para desenvolver uma solução modular, começando com um protótipo de cobertura limitada.

Essas forças dependem da implementação e da validação do sistema. A arquitetura planejada, por si só, não demonstra que o produto já seja confiável ou superior às alternativas.

### 6.2. Fraquezas e desafios

- Projeto ainda em desenvolvimento, com partes do hardware e do aplicativo pendentes de validação.
- Necessidade de calibrar os sensores e verificar sua precisão em condições reais.
- Dependência de conectividade, alimentação elétrica e manutenção dos equipamentos.
- Necessidade de estabelecer procedimentos para identificar falhas, leituras incoerentes e perda de comunicação.
- Ausência, até o momento, de evidências suficientes sobre a aceitação pelos moradores.
- Necessidade de construir confiança em informações que podem influenciar decisões de segurança.
- Custos recorrentes de instalação, manutenção, conectividade, hospedagem e suporte.

### 6.3. Oportunidades

- Investigar áreas onde os dados públicos disponíveis não atendam às necessidades específicas dos usuários.
- Estabelecer parcerias com instituições de ensino, órgãos públicos e organizações locais.
- Validar uma primeira versão com moradores de regiões selecionadas.
- Melhorar a compreensão das informações hidrológicas por meio de visualizações simples.
- Oferecer uma interface complementar a fontes oficiais, mantendo a origem e o horário dos dados.
- Desenvolver indicadores de confiabilidade, disponibilidade e cobertura que possam ser avaliados objetivamente.
- Investigar possibilidades de apoio institucional ou financiamento para infraestrutura de monitoramento.

### 6.4. Ameaças

- Existência de sistemas públicos de monitoramento e alerta já estabelecidos.
- Dificuldade de diferenciar o projeto de serviços que já disponibilizam informações semelhantes.
- Possíveis restrições técnicas, contratuais ou legais para integração de dados externos.
- Falhas de sensores ou conectividade durante os eventos em que o sistema seria mais necessário.
- Risco de interpretação incorreta das medições pelos usuários.
- Responsabilidade e danos potenciais decorrentes de informações imprecisas ou desatualizadas.
- Dificuldade de manter uma rede de equipamentos distribuída geograficamente.
- Mudanças nos protocolos de comunicação, nas plataformas e nos sistemas públicos integrados.

## 7. Diferencial competitivo proposto

O posicionamento recomendado é apresentar o AcquaScan como uma **plataforma complementar de informação hidrológica local para Petrópolis**, com foco na acessibilidade dos dados e na compreensão da situação por região.

A proposta de valor pode ser resumida da seguinte maneira:

> O AcquaScan busca transformar dados sobre os rios de Petrópolis em informações locais, acessíveis e compreensíveis, reunindo medições de sensores e fontes confiáveis para apoiar a percepção de risco e facilitar o acesso a orientações oficiais.

Esse posicionamento evita afirmar que o projeto substitui o INEA ou a Defesa Civil, ou que prevê enchentes com certeza.

### 7.1. Diferenciais que devem ser comprovados

| Diferencial proposto | Como validar |
|---|---|
| Maior clareza das informações | Testar a interface com moradores e medir se compreendem corretamente o estado apresentado. |
| Cobertura local útil | Comparar a localização dos sensores com os dados públicos disponíveis e as necessidades levantadas na pesquisa. |
| Atualização confiável | Registrar atrasos, disponibilidade, perda de pacotes e intervalos sem leitura. |
| Precisão das medições | Comparar os sensores com instrumentos ou referências de medição adequados. |
| Utilidade das notificações | Testar compreensão, relevância, tempo de recebimento e excesso de alertas. |
| Consulta por região | Verificar se os usuários conseguem localizar sua área e entender o que os dados significam. |
| Complementaridade com órgãos públicos | Consultar as instituições sobre dados, protocolos, integração e atribuições. |
| Viabilidade econômica | Calcular custo por estação, manutenção, conectividade, hospedagem e operação. |

### 7.2. O que o AcquaScan não deve prometer sem evidências

- Prever com precisão o momento em que um rio vai transbordar.
- Garantir que determinada rua ou rota está segura.
- Cobrir toda a cidade com um número limitado de sensores.
- Entregar alertas sempre antes dos sistemas oficiais.
- Substituir a Defesa Civil ou os protocolos de emergência.
- Funcionar ininterruptamente durante qualquer evento extremo.
- Disponibilizar dados em tempo real sem demonstrar a frequência e a confiabilidade da transmissão.

A comunicação do produto deve apresentar o horário da última leitura, a fonte dos dados e eventuais indisponibilidades. Quando não houver informação suficiente, o aplicativo deve declarar essa limitação em vez de apresentar uma classificação de risco como se fosse conclusiva.

## 8. Estratégia recomendada diante dos concorrentes

A estratégia inicial deve ser a diferenciação por complementaridade, qualidade dos dados e experiência de uso.

**Etapa 1 — Entender a infraestrutura existente**

- Consultar o inventário atualizado das estações do INEA.
- Identificar quais estações monitoram nível dos rios e quais registram somente chuva.
- Confirmar quais equipamentos estão operacionais nas regiões de interesse.
- Verificar os meios autorizados de acesso aos dados e as condições de reutilização.
- Mapear os canais de alerta e os recursos oficiais da Defesa Civil municipal.

**Etapa 2 — Identificar necessidades não atendidas**

- Entrevistar moradores de diferentes regiões.
- Investigar quais informações são difíceis de encontrar durante episódios de chuva intensa.
- Verificar como os moradores interpretam os alertas atuais.
- Identificar dificuldades de acesso, compreensão ou localização de informações.
- Evitar presumir que existe uma lacuna antes de coletar evidências.

**Etapa 3 — Validar o protótipo técnico**

- Testar os sensores em condições controladas.
- Registrar medições e compará-las com referências adequadas.
- Avaliar a comunicação dos equipamentos e o tratamento de dados ausentes.
- Implementar indicadores de qualidade e horário da última atualização.
- Testar a interface com dados reais ou claramente identificados como simulados.

**Etapa 4 — Validar o produto com usuários**

- Avaliar se o mapa facilita a consulta por região.
- Medir se os usuários entendem os níveis de atenção apresentados.
- Testar o funcionamento e a relevância das notificações.
- Investigar se a plataforma complementa os canais oficiais.
- Registrar erros de interpretação e ajustar a linguagem antes de ampliar a distribuição.

**Etapa 5 — Avaliar a expansão**

Somente após a validação inicial devem ser avaliadas a ampliação da rede de sensores, novas integrações, a disponibilização de rotas e outros recursos que aumentem a complexidade e a responsabilidade do sistema.

## 9. Pesquisa de mercado e validação pendente

A análise documental é o ponto de partida, mas não comprova a demanda nem a superioridade do AcquaScan. Para transformar as hipóteses em evidências, as seguintes atividades devem ser realizadas:

- [ ] Consultar o INEA sobre as estações atualmente operacionais em Petrópolis.
- [ ] Confirmar quais variáveis estão disponíveis por estação: chuva, nível da água e, quando aplicável, vazão.
- [ ] Verificar frequência de atualização, histórico disponível e condições de acesso e integração dos dados.
- [ ] Mapear os canais e recursos oficiais da Defesa Civil de Petrópolis.
- [ ] Comparar as funcionalidades efetivamente disponíveis nas plataformas concorrentes.
- [ ] Realizar entrevistas com moradores de diferentes regiões.
- [ ] Registrar as principais dificuldades relatadas pelos usuários.
- [ ] Testar a compreensão da interface e dos indicadores de risco.
- [ ] Comparar os dados dos sensores do AcquaScan com referências adequadas.
- [ ] Estimar o custo total de instalação e operação da rede de monitoramento.
- [ ] Consultar especialistas sobre os limites técnicos de estimativas de elevação do nível dos rios.
- [ ] Definir procedimentos para falhas, dados desatualizados e comunicação de incerteza.
- [ ] Avaliar possíveis parcerias institucionais.

## 10. Conclusão

A análise identifica concorrentes e soluções substitutas importantes, especialmente o Sistema Alerta de Cheias do INEA e os canais de comunicação da Defesa Civil de Petrópolis. Serviços de previsão meteorológica, alertas por celular, aplicativos de navegação e notícias locais também atendem a necessidades relacionadas, embora não tenham necessariamente o mesmo objetivo principal.

O espaço competitivo do AcquaScan não deve ser definido pela alegação de inexistência de soluções, pois já existe infraestrutura pública de monitoramento e comunicação de riscos. A oportunidade está em investigar se uma plataforma local, com visualização geográfica e informações mais fáceis de consultar, consegue complementar os recursos existentes e atender necessidades concretas dos moradores.

Para sustentar essa proposta, o projeto precisa demonstrar a confiabilidade dos sensores, a qualidade da transmissão, a utilidade da interface, a viabilidade econômica e a compatibilidade com as orientações oficiais. O diferencial competitivo será estabelecido por evidências de uso e desempenho, e não apenas pela lista de funcionalidades planejadas.

## 11. Referências

1. **Instituto Estadual do Ambiente (INEA).** Alerta de Cheias. Disponível em: https://www.inea.rj.gov.br/ar-agua-e-solo/alerta-de-cheias/. Acesso em: 14 out. 2026.
2. **Sistema Alerta de Cheias — INEA.** Sobre o sistema. Disponível em: https://alertadecheias.inea.rj.gov.br/sobre.php. Acesso em: 14 out. 2026.
3. **Instituto Estadual do Ambiente (INEA).** Monitoramento hidrometeorológico. Disponível em: https://www.inea.rj.gov.br/ar-agua-e-solo/monitoramento-hidrometeorologico/. Acesso em: 14 out. 2026.
4. **Instituto Nacional de Meteorologia (INMET).** Portal institucional. Disponível em: https://portal.inmet.gov.br/. Acesso em: 14 out. 2026.
5. **Prefeitura de Petrópolis.** Portal institucional. Disponível em: https://www.petropolis.rj.gov.br/. Acesso em: 14 out. 2026.
6. **Tribuna de Petrópolis.** Portal de notícias regional. Disponível em: https://tribunadepetropolis.com.br/. Acesso em: 14 out. 2026.
7. **Waze.** Portal oficial. Disponível em: https://www.waze.com/. Acesso em: 14 out. 2026.
8. **Google Maps.** Serviço de mapas e navegação. Disponível em: https://maps.google.com/. Acesso em: 14 out. 2026.

**Nota metodológica:** as referências acima identificam as fontes institucionais e os serviços utilizados no levantamento inicial. Antes de apresentar conclusões definitivas, recomenda-se registrar a data de consulta de cada funcionalidade, verificar a disponibilidade atual dos serviços e incluir evidências da pesquisa com usuários e dos testes técnicos do AcquaScan.
