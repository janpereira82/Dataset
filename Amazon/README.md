# Dataset de Produtos da Amazon

Este dataset contém informações de mais de 1.000 produtos da Amazon, incluindo avaliações e reviews conforme listados no site oficial da Amazon.

## Estrutura do Dataset

O arquivo `amazon.csv` contém as seguintes colunas:

### Informações do Produto
- `product_id`: Identificador único do produto
- `product_name`: Nome do produto
- `category`: Categoria do produto
- `img_link`: Link da imagem do produto
- `product_link`: Link oficial do produto no site da Amazon

### Informações de Preço
- `discounted_price`: Preço com desconto do produto
- `actual_price`: Preço original do produto
- `discount_percentage`: Porcentagem de desconto aplicada

### Avaliações e Reviews
- `rating`: Avaliação do produto
- `rating_count`: Número de pessoas que avaliaram o produto
- `about_product`: Descrição do produto
- `user_id`: ID do usuário que escreveu a review
- `user_name`: Nome do usuário que escreveu a review
- `review_id`: ID da review
- `review_title`: Título curto da review
- `review_content`: Conteúdo completo da review

## Inspiração

A Amazon é uma empresa multinacional americana de tecnologia com forte presença no e-commerce, onde gerencia todo o processo desde o inventário até o envio, precificação, atendimento ao cliente e devoluções. Este dataset foi criado para permitir que as pessoas possam explorar e trabalhar com dados reais de e-commerce.

## Possíveis Aplicações

Este dataset pode ser utilizado para diversos fins, incluindo:

1. **Análise Exploratória de Dados**
   - Análise de padrões de preços
   - Distribuição de avaliações por categoria
   - Relação entre descontos e avaliações

2. **Pré-processamento de Dados**
   - Limpeza e normalização
   - Tratamento de valores ausentes
   - Codificação de variáveis categóricas

3. **Visualização de Dados**
   - Gráficos de distribuição de preços
   - Mapas de calor de correlações
   - Análise temporal de avaliações

4. **Sistemas de Recomendação**
   - Recomendação baseada em conteúdo
   - Filtragem colaborativa
   - Análise de similaridade entre produtos

5. **Análise de Sentimentos**
   - Processamento de linguagem natural nas reviews
   - Classificação de sentimentos
   - Extração de tópicos

Estas são apenas algumas das possíveis aplicações do dataset. Os usuários são encorajados a explorar outras possibilidades e abordagens criativas para análise e modelagem dos dados.