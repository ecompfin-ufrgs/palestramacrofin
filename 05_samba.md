---
layout: default
title: 5. O Modelo SAMBA do Banco Central
---

# 🥁 5. O Modelo SAMBA: O Ritmo da Nossa Economia

O **SAMBA** (*Stochastic Analytical Model with a Bayesian Approach*) é o modelo DSGE oficial desenvolvido pelo Banco Central do Brasil. É ele quem roda nos computadores do BC para dar norte às decisões de política monetária (a nossa taxa Selic)!

Para simular o Brasil de forma realista, o modelo consolida a economia em um equilíbrio simultâneo de **10 Mercados Principais**:

## 🏛️ Os 10 Mercados do SAMBA

1. **Mercado de Bens de Consumo Domésticos:** O comércio local do dia a dia.
2. **Mercado de Bens Importados:** Celulares, automóveis e insumos industriais vindos de fora.
3. **Mercado de Trabalho:** Onde as famílias oferecem mão de obra sob termos de rigidez salarial nominal.
4. **Mercado de Capital Físico:** Aluguel de maquinários, prédios e infraestrutura industrial.
5. **Mercado de Títulos Públicos Domésticos:** Papéis da dívida do governo onde se altera a taxa de juros básica.
6. **Mercado de Crédito Bancário:** Empréstimos a firmas e famílias com risco de inadimplência e spreads.
7. **Mercado de Câmbio:** Compra e venda de divisas (Real vs. Dólar), conectando finanças internacionais.
8. **Mercado de Bens de Exportação:** Nossas commodities (soja, minério) e manufaturados vendidos ao exterior.
9. **Mercado de Bens de Investimento:** Produção de novos bens de capital para expandir a indústria.
10. **Mercado de Serviços Governamentais:** Arrecadação de tributos e gastos de custeio público.

## 🕹️ A Regra de Taylor no SAMBA
Para coordenar esses mercados e evitar que a inflação saia do controle, o computador do Banco Central segue uma regra automatizada de resposta:

$$i_t = \rho_i i_{t-1} + (1-\rho_i) \left[ \bar{i} + \gamma_\pi (\pi_t - \pi^*) + \gamma_y y_t \right] + \varepsilon_t^i$$

Se os dados econométricos indicam que a inflação real ($\pi_t$) está subindo além da meta planejada ($\pi^*$), o algoritmo do **SAMBA** dá o alerta matemático: **Hora de subir os juros ($i_t$)!** 🚨
