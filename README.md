<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# Calculadora de EDGE para Estratégias de Investimento

<a href="https://colab.research.google.com/github/GeorgeTelles/Calculo_Edge_estrategia/blob/main/Calculo_Edge_estrategia.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Este projeto em Python calcula o **EDGE** de uma estratégia de investimento. O EDGE é uma métrica que ajuda a avaliar a eficácia de uma estratégia de investimento com base na taxa de acerto e no ponto de equilíbrio (break-even).

Observações:
1. Um bom EDGE está entre 5% a 10%
2. EDGE não é rentabilidade!

## Conceitos

### 1. **Taxa de Acerto**
A Taxa de Acerto é a porcentagem de operações que foram bem-sucedidas dentro de uma estratégia de investimento. No cálculo do EDGE, a Taxa de Acerto é um indicador importante, mas não é suficiente por si só para determinar a qualidade da estratégia.

### 2. **Break-Even (Ponto de Equilíbrio)**
O Break-Even é o ponto em que o retorno da estratégia é igual ao risco, sem gerar lucro ou prejuízo. A fórmula para calcular o Break-Even é: `1/(1+(retorno/risco))`
onde:
- **Retorno** é o ganho esperado por operação.
- **Risco** é a perda esperada por operação.

### 3. **EDGE**
O EDGE é a diferença entre a Taxa de Acerto da estratégia e o Break-Even. O cálculo do EDGE é dado por:
`Taxa de acerto - Breakeven`
Os valores bons de EDGE geralmente variam entre 5% e 10%.

Para calcular o EDGE você deve preencher:
1. Retorno
2. Risco
3. Taxa de Acerto da Estratégia

Exemplo:
- **Retorno**: 3
- **Risco**: 1
- **Taxa de Acerto da Estratégia**: 35
