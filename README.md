# Aprendizagem de Máquina

### Aluno: Frederico Augusto Fernandes Silveira

## Trabalho 01 - Regressão

#### Descrição

Com mais de 1.200 restaurantes de serviço rápido em todo o mundo, a TFI é a empresa por trás de algumas das marcas mais conhecidas do mundo: Burger King, Sbarro, Popeyes, Usta Donerci e Arby’s. Eles empregam mais de 20.000 pessoas na Europa e na Ásia e fazem investimentos diários significativos no desenvolvimento de novos sites de restaurantes.

Neste momento, decidir quando e onde abrir novos restaurantes é, em grande parte, um processo subjetivo baseado no julgamento pessoal e na experiência das equipes de desenvolvimento. Esses dados subjetivos são difíceis de extrapolar com precisão entre as geografias e culturas.

Novos sites de restaurantes levam grandes investimentos de tempo e capital para se levantar e correr. Quando o local errado para uma marca de restaurante é escolhido, o site fecha dentro de 18 meses e as perdas operacionais são incorridas.

Encontrar um modelo matemático para aumentar a eficácia dos investimentos em novos restaurantes permitirá que a TFI invista mais em outras importantes áreas de negócios, como sustentabilidade, inovação e treinamento para novos funcionários. Usando dados demográficos, imobiliários e comerciais, esta competição desafia você a prever as vendas anuais de restaurantes de 100.000 locais regionais.

A TFI (Tab Food Investiment) forneceu um conjunto de dados com 137 restaurantes no conjunto de treinamento e um conjunto de teste de 100.000 restaurantes. As colunas de dados incluem a data de abertura, o local, o tipo de cidade e três categorias de dados ofuscados: dados demográficos, dados imobiliários e dados comerciais. A coluna de receita indica uma receita (transformada) do restaurante em um determinado ano e é o alvo da análise preditiva.


##### Arquivos

- train.csv - o conjunto de treinamento.
- test.csv - o conjunto de testes. Para impedir previsões manuais de "adivinhação", Kaggle suplementou o conjunto de testes com dados "ignorados" adicionais. Estes não são contados na pontuação.
- sampleSubmission.csv - um arquivo de envio de amostra no formato correto

##### Campos de dados

- Id: id restaurante.
- Data de abertura: data de abertura de um restaurante
- Cidade: Cidade em que o restaurante está. Observe que há unicode nos nomes.
- Grupo da Cidade: Tipo da cidade. Grandes cidades ou outros.
- Tipo: Tipo do restaurante. FC: Praça de Alimentação, IL: Inline, DT: Drive Thru, MB: Mobile
- P1, P2 - P37: Existem três categorias desses dados ofuscados. Os dados demográficos são coletados de provedores de terceiros com sistemas GIS. Estes incluem a população em qualquer área, distribuição por idade e sexo, escalas de desenvolvimento. Os dados de imóveis referem-se principalmente ao m2 do local, fachada frontal do local, disponibilidade de estacionamento. Os dados comerciais incluem principalmente a existência de pontos de interesse, incluindo escolas, bancos, outros operadores de QSR.
- Receita: a coluna de receita indica uma receita (transformada) do restaurante em um determinado ano e é o alvo da análise preditiva. Por favor, note que os valores são transformados para que eles não significam valores reais do dólar.
