# Desafio: shakers-semana-3-dados-avancados


**Metafields e Metaobjetos:** São ferramentas de dados avançadas da Shopify. Enquanto Metafields guardam informações extras de um objeto (como um produto), Metaobjetos funcionam como "mini tabelas" personalizadas que permitem criar estruturas de dados complexas e reutilizáveis.

##  O que foi implementado
Um slider dinâmico de recomendações que consome uma lista de metaobjetos associada ao produto principal. O slider utiliza a biblioteca Swiper.js para navegação responsiva.

## Passo a Passo de Configuração

### 1. Como criar o Metaobjeto
* Primeiro, precisa ir em **Conteúdo > Metaobjetos**.
* Criar uma definição chamada `Products with banner`.
* Adicionar os campos: `produto_banner` (tipo Produto) e `banner` (tipo Arquivo/Imagem).

### 2. Como criar o Metafield
* Ir em **Configurações > Dados personalizados > Produtos**.
* Criar um metacampo chamado `related_products_with_banner`.
* Selecionar o tipo **Metaobjeto** e apontar ele para a definição criada no passo anterior.

### 3. Como associar ao produto
* No Admin, acesse o produto desejado.
* No final da página, é necessario localizar o metacampo e selecionar as entradas de metaobjetos criadas.

### 4. Como testar localmente
* Precisa ter o **Shopify CLI** instalado.
* Executar o comando `shopify theme dev` no terminal para visualizar as alterações.

##
* **Pull Request:** [Cole o link do seu PR aqui]
* **Vídeo Demonstrativo:** [Cole o link do seu vídeo aqui]