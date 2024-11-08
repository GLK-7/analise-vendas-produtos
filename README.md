# **Análise de Vendas de Produtos**

---

Autor: **Gabriel Lino**

<div style="display: flex; gap: 10px;"> 
  <a href="mailto:gabriel.godoitb@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/glgodoi" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>  
  <a href="https://github.com/GLK-7" target="_blank"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>  
</div>

---
[![Kaggle Notebook](https://img.shields.io/badge/Kaggle-Notebook-blue?logo=kaggle)](https://www.kaggle.com/code/glgodoi/projeto-an-lise-de-vendas-de-produtos)

Neste projeto foi realida uma análise estatística e visual das vendas de um supermercado, utilizando um dataset com informações detalhadas sobre transações realizadas em diferentes filiais e categorias de produtos dos meses: janeiro, fevereiro e março de 2019 de três filiais. O dataset está disponível neste link: [supermarket-sales](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales). O foco está em entender padrões de consumo, identificar os produtos mais vendidos, comparar o comportamento de compra entre diferentes tipos de clientes e explorar a distribuição de métodos de pagamento.

## **1. Coleta de Dados**

Nesta etapa, foi realizada a coleta e preparação dos dados utilizados na análise. Foi carregado o dataset de vendas de supermercado, depois feita a limpeza dos dados, e então as transformações necessárias para garantir a qualidade e integridade das informações que foram analisadas.

## **2. Modelagem**

Nesta seção, foram aplicados métodos estatísticos para investigar as principais questões levantadas na análise dos dados de vendas. A modelagem estatística e a análise exploratória tiveram como objetivo identificar padrões de comportamento e verificar hipóteses com base em aspectos específicos das colunas do dataset, como:

- **Filial e Cidade**: Analisamos o volume de vendas por filial e cidade para identificar as regiões de maior desempenho.
- **Tipo de Cliente**: Comparamos os clientes `Member` e `Normal` para avaliar qual tipo de cliente apresentou maior ticket médio e frequência de compra.
- **Linha de Produto**: Verificamos as categorias de produtos mais populares e comparamos o ticket médio entre diferentes linhas de produtos.
- **Método de Pagamento**: Analisamos os métodos de pagamento mais utilizados e sua correlação com o valor total das compras.
- **Análise Temporal**: Identificamos padrões de vendas em determinados dias e horários de pico.
- **Lucro Bruto**: Calculamos a lucratividade média por produto e por categoria para entender o desempenho financeiro.

## **3. Conclusões**

A análise dos dados revelou padrões consistentes no comportamento de compra dos clientes e no desempenho das filiais, permitindo uma visão mais estratégica para decisões de negócio. Abaixo estão os principais insights encontrados durante a análise, que englobam o equilíbrio nas vendas entre filiais, preferências de pagamento, e comportamento de compras em relação a dias e períodos específicos. Podemos destacar os seguintes pontos: 

- **Equilíbrio de Vendas entre Filiais**: As três filiais mantêm um equilíbrio no valor total de vendas, com uma leve variação na filial C, que apresentou cerca de 4 mil a mais em vendas em comparação com as demais. Esse equilíbrio pode indicar uma distribuição uniforme de clientes e demanda entre as filiais.
- **Tipo de Cliente e Programa de Fidelidade**: A análise da média de vendas por tipo de cliente sugere que membros do programa de fidelidade ou com acesso a descontos representam um ticket médio maior. Esse padrão indica que clientes fidelizados tendem a gastar mais em cada transação.
- **Métodos de Pagamento**: A distribuição de métodos de pagamento mostra uma leve predominância, mas bastante equilibrada, entre os tipos disponíveis. O cartão de crédito aparece como o método menos utilizado, embora a diferença entre os métodos seja pequena, indicando uma preferência diversificada dos clientes.
- **Categorias de Produto**: A média de vendas por categoria de produtos é equilibrada, com a categoria "Casa e Bem-Estar" destacando-se levemente como a de maior ticket médio. Esse dado sugere uma demanda consistente em várias linhas de produto, com preferência ligeiramente maior por produtos de uso doméstico e de bem-estar.
- **Médias de Lucro**: As médias de lucro seguem um padrão semelhante às médias de valor de vendas, indicando um equilíbrio entre as margens de lucro das diferentes categorias de produto. Esse fator contribui para uma estabilidade na lucratividade do supermercado.
- **Padrões de Compra ao Longo do Tempo**: Observamos um pico significativo de vendas entre os dias 20 e 27 de janeiro, seguido de uma leve queda no início de fevereiro. Uma tendência similar é identificada ao longo dos meses, com uma diminuição nas últimas semanas de fevereiro e março. Esse padrão sugere que os clientes tendem a concentrar suas compras nas primeiras semanas de cada mês. O comportamento atípico observado em janeiro, com um volume maior de vendas, possivelmente reflete o período de férias e o início do ano, quando muitos consumidores dispõem de mais tempo e necessidade para realizar compras.

Esses insights podem auxiliar na formulação de estratégias para otimizar o estoque e o atendimento ao cliente, além de auxiliar na criação de campanhas de fidelização e promoção em períodos específicos do mês, maximizando o volume de vendas e a lucratividade.
