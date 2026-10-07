# Identidade visual

Definida no mapa mental: **azul e branco**, **acessível**, **interface amigável** e a **capivara como mascote**.

## Paleta (proposta)

| Uso | Cor | Hex | Contraste com branco |
|---|---|---|---|
| Azul principal | Botões, títulos, cabeçalho | `#0B5FA5` | 6,6 : 1 |
| Azul escuro | Textos e ícones | `#083D6B` | 11,1 : 1 |
| Azul claro | Fundos de cartões | `#E8F2FB` | Fundo (texto em azul escuro: 9,8 : 1) |
| Branco | Fundo principal | `#FFFFFF` | — |

### Cores de estado do rio

São a única exceção à paleta azul e branca, porque precisam comunicar risco de imediato.

| Estado | Hex | Contraste com branco | Ícone |
|---|---|---|---|
| Estável | `#1E7B34` | 5,3 : 1 | ✓ |
| Atenção | `#9A5B00` | 5,4 : 1 | ! |
| Crítico | `#B3261E` | 6,5 : 1 | ▲ |

Todas as combinações passam no nível AA das diretrizes de acessibilidade WCAG (mínimo de 4,5 : 1 para texto).

## Acessibilidade

- **Nunca usar só a cor** para indicar o estado. Pessoas com daltonismo podem não distinguir verde de vermelho. Sempre mostrar cor, ícone e texto juntos: `▲ Crítico · 87%`.
- Textos com no mínimo 16 px no app e suporte ao aumento de fonte do celular.
- Botões com área de toque de pelo menos 44 × 44 px.
- Imagens e ícones com descrição para leitores de tela.

## Mascote: capivara

A capivara é um animal que vive na beira de rios e lagos, o que conecta o mascote ao tema do projeto e traz um tom amigável. [PREENCHER: nome do mascote]

**Onde aparece:** tela de boas-vindas, estados vazios ("nenhum alerta na sua região") e materiais do evento.

**Onde não aparece:** em alertas críticos. Numa emergência, a mensagem deve ser direta e séria.

## Arquivos

| Arquivo | Situação |
|---|---|
| `logo.svg` | [PREENCHER] |
| `logo.png` (fundo transparente) | [PREENCHER] |
| `mascote-capivara.svg` | [PREENCHER] |
| `tipografia.md` | [PREENCHER: fonte escolhida, por exemplo uma do Google Fonts com boa leitura em telas] |
