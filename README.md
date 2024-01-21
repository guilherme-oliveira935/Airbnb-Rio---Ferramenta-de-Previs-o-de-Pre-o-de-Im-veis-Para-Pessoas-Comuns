# Airbnb Rio Ferramenta de Previsão De Preço De Imóveis Para Pessoas Comuns

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/guilherme-oliveira935/Airbnb-Rio--Ferramenta-de-Previsao-de-Precos-de-Imoveis-Para-Pessoas-Comuns/blob/main/LICENSE)

## Descrição:

No Airbnb, qualquer pessoa que tenha um quarto ou um imóvel de qualquer tipo (apartamento, casa, chalé, pousada, etc.) pode ofertar o seu imóvel para ser alugado por diária.
Você cria o seu perfil de host (pessoa que disponibiliza um imóvel para aluguel por diária) e cria o anúncio do seu imóvel.
Nesse anúncio, o host deve descrever as características do imóvel da forma mais completa possível, de forma a ajudar os locadores/viajantes a escolherem o melhor imóvel para eles (e de forma a tornar o seu anúncio mais atrativo)
Existem dezenas de personalizações possíveis no seu anúncio, desde quantidade mínima de diária, preço, quantidade de quartos, até regras de cancelamento, taxa extra para hóspedes extras, exigência de verificação de identidade do locador, etc.

## Objetivo:

Construir um modelo de previsão de preço que permita uma pessoa comum que possui um imóvel possa saber quanto deve cobrar pela diária do seu imóvel. E ainda, por consequência do objetivo principal, para o locador comum, dado o imóvel que ele está buscando, ajudar a saber se aquele imóvel está com preço atrativo (abaixo da média para imóveis com as mesmas características) ou não. Mas isso ficará em segundo plano.

### Material, Comentários e créditos:

- As bases de dados foram retiradas do site kaggle: https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro - Dependendo da data, ela pode estar diferente da usada nesse projeto;
- Caso queira uma outra solução, você pode olhar como referência a solução do usuário Allan Bruno do kaggle no Notebook: https://www.kaggle.com/allanbruno/helping-regular-people-price-listings-on-airbnb ao qual serviu de referência para a construção desse projeto;
- As bases de dados são os preços dos imóveis obtidos e suas respectivas características em cada mês;
- Os preços são dados em reais (R$);
- Temos bases de abril de 2018 a maio de 2020, com exceção de junho de 2018 que não possui base de dados;
- O Story Telling do projeto pode ser visualizado nas células do script principal;

## Tecnologias e Bibliotecas utilizadas:

- Python 3
  - Bilbliotecas
    - Pandas: Cria/gerencia dataframes
    - Pathlib: Usado para gerenciar diretórios
    - Numpy: Ideal para trabalhar com números e arrays
    - Matplotlib: Visualização de gráficos
    - Seaborn: Deixar o matplotlib visualmente mais agradável
    - Sklearn: Possiu recursos de aprendizado de máquina

## Como Executar o Projeto:

- Instalar as bibliotecas mencionadas;
- Clonar esse repositório;
- Mudar o caminho dos diretórios indicados no arquivo principal;
- Caso opte por baixar a base de dados direto do kaggle, certifique-se que todas as colunas trabalhadas ao longo do projeto estão presentes nele.

## Autor:

Guilherme Oliveira



