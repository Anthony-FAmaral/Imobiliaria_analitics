# Análise Descritiva Imobiliários 

Este projeto tem como objetivo explorar um conjunto de dados imobiliários por meio de **análises descritivas**, utilizando Python e bibliotecas como **Pandas**, **Seaborn** e **Matplotlib**.

---

## 🔍 Objetivos da Análise

Através de perguntas orientadoras, buscamos identificar padrões, relações e possíveis influências sobre o preço de imóveis. As questões abordadas foram:

-  Qual a distribuição de preços de casas?
-  Existe relação entre o preço e a área do imóvel?
-  A localização afeta o preço?
-  Quartos e banheiros influenciam o valor?
-  Aquecimento de água impacta no preço?
-  Estar mobiliado influencia o valor?
-  Quais variáveis têm maior correlação com o preço?

---

## 🧠 Apresentação dos Insights

A partir das análises gráficas, extraímos os seguintes **insights resumidos** para orientar decisões e modelagens futuras:

- **Área** e **número de banheiros** são as variáveis com **maior correlação com o preço**.
- A **distribuição dos preços** é assimétrica, com **concentração entre R$ 2M e R$ 6M** e presença de **outliers acima de R$ 10M**.
- Existe uma **tendência de aumento no preço conforme a área aumenta**, mas com **alta dispersão**, indicando a influência de outros fatores.
- Imóveis **com aquecimento de água ou mobiliados** apresentam **valores médios mais altos**.
- A variável **garagem** tem pouca influência direta no valor do imóvel.

> 🔎 *Esses pontos ajudam a filtrar variáveis relevantes para futuros modelos preditivos ou para decisões de negócio no setor imobiliário.*

---

## 📌 Principais Insights (Resumo Rápido)

- **Distribuição de Preços:** A maioria dos imóveis está concentrada entre R$ 2.000.000 e R$ 6.000.000.
- **Área x Preço:** Relação positiva – quanto maior a área, maior tende a ser o preço.
- **Quartos e Banheiros:** Imóveis com mais cômodos tendem a custar mais.
- **Aquecimento de Água:** Imóveis com essa comodidade têm preços médios mais altos.
- **Mobilia:** Imóveis mobiliados geralmente têm maior valor.
- **Correlação:** A variável **Área** apresenta a maior correlação com o preço.

---

## 📈 Gráficos Utilizados

- **Histograma**: Distribuição de preços.
- **Gráfico de Dispersão**: Relação entre área e preço.
- **Boxplot (Catplot)**: Comparações de preço por quartos, banheiros, aquecimento e mobilia.
- **Mapa de Calor (Heatmap)**: Correlação entre variáveis numéricas.
