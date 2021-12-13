# Organização CTD E-Commerce (Amar e Cuidar | Cosméticos)

![alt text](https://github.com/CTD-E-Commerce/.github/blob/main/profile/integrantes.png?raw=true)

- Organização criada para a elaboração do Projeto Integrador do 3º Bimestre do curso Certified Tech Developer.

## Integrantes:

- [Dâmares Bortolucci](https://github.com/damaresbortolucci)
- [Felipe Moreira](https://github.com/moreirafelipe)
- [Marcelo Miyoshi](https://github.com/Marcelomsz)
- [Paula Augusto](https://github.com/pcamposaugusto)
- [Pedro Brito](https://github.com/pedroisb)
- [Silvano Araujo](https://github.com/Silvanoeng) 

## Objetivo:

- Desenvolver um protótipo de e-commerce de tema livre.

## Requisitos Back-end:

1. Você deverá fazer o back-end de nosso e-commerce em Java com o Framework Spring no modelo MVC.
2. O banco de dados deverá ser o H2.
3. Modelo de dados: O banco de dados terá duas entidades principais, products e categories, onde cada produto tem apenas uma categoria e cada categoria pode ter vários ou nenhum produto. 

- Modelo para o banco de dados:

![alt text](https://github.com/CTD-E-Commerce/.github/blob/main/profile/BD.png?raw=true)

4. API - O projeto deverá disponibilizar uma API com quatro end-points:

- Método GET - 'https://ctdcommerce.com/products': este end-point deverá disponibilizar os dados de todos os produtos cadastrados em um JSON com o formato que segue:

![alt text](https://github.com/CTD-E-Commerce/.github/blob/main/profile/api2.png?raw=true)

- Método GET - https://ctdcommerce.com/products/1: este end-point deverá disponibilizar os dados de um produto específico em um JSON com o formato que segue:

![alt text](https://github.com/CTD-E-Commerce/.github/blob/main/profile/api3.png?raw=true)

- Método GET - https://ctdcommerce.com/products/categories: este end-point deverá disponibilizar uma lista de categorias cadastradas em um JSON com o formato que segue:

![alt text](https://github.com/CTD-E-Commerce/.github/blob/main/profile/api4.png?raw=true)

- Método GET - https://ctdcommerce.com/products/category/jewelery: este end-point deverá disponibilizar os produtos de uma determinada categoria, em um JSON com o formato a seguir:

![alt text](https://github.com/CTD-E-Commerce/.github/blob/main/profile/api5.png?raw=true)


## Requisitos Front-end:

1. Todo o site deve estar responsivo.
2. O entregável será uma página em HTML5, SASS, React-Bootstrap e React.
3. Utilize a API criada no trabalho de Back-end acima para fornecer os dados necessários pro site.
4. O head deve variar de acordo com a página atual. Ex: Na página do produto leite ficaria: nomeDoProjeto | Leite
5. Header deve conter 4 itens além da logo. Cada item deve linkar com uma parte do site. Exemplo: Home, Produtos, Carrinho, Sobre nós.
6. Na home, faça um carousel de duas páginas com 3 produtos cada, ao clicar no produto, vai para a página do mesmo. Uma seção que exibe as categorias dos produtos que quando clicada, vai para a página de produto, filtrada por categoria.
7. Dentro da página de produtos,haverá uma opção para filtrar os produtos de acordo com a categoria.
8. Seu site tem de ter uma página de detalhes para cada item listado onde haverá uma explicação sobre o mesmo. Ex: A página de uma bolsa teria um título, descrição, categoria, imagem, avaliação, etc.
9. Na tela do produto, deve ser possível adicioná-lo num carrinho, mas esse carrinho ficará em um estado dentro da contextAPI e vai ser compartilhado pela aplicação inteira. Posteriormente, quando o usuário clicar na aba de carrinho, os dados serão buscados da contextAPI e a lista de produtos será listada.
10. Não se esqueça de colocar todos os membros da equipe na página de sobre nós.


## Requisitos Infraestrutura:

1. A API deverá ser implementada e disponibilizada por meio de um ambiente de cloud computing EC2 da Amazon Web Services.
2. O front-end deverá ser hospedado em um ambiente Vercel.

## Resultados:

- Desenvolvimento de um protótipo de e-commerce de cosméticos importados, nomeado de "Amar e Cuidar | Cosméticos"

- Desenvolvimento de uma API para requisições do e-commerce "Amar e Cuidar | Cosméticos"

- Criação de um bucket no AWS S3 para armazenar as imagens dos produtos e imagens utilizadas no site.

- Realização de um deploy no Heroku para implantar a API na nuvem.

- Realização de um deploy na AWS Elastic Beanstalk para implantar a API na Nuvem AWS.

- Criação de uma instância de banco de dados do AWS RDS para implantar um banco de dados relacional MySQL na Nuvem AWS.

## Links:

### Link principal do site:

#### [Amar e Cuidar | Cosméticos - Vercel](https://amar-e-cuidar-two.vercel.app/)

### Links alternativos do site:

#### [Amar e Cuidar | Cosméticos - Heroku](https://ctd-ecommerce-front.herokuapp.com/)

#### [Amar e Cuidar | Cosméticos - CloudFlare](https://ctd-ecommerce-front.pages.dev/)


### Links Back-End:

#### [Link Documentação da API](https://notch-tiglon-21b.notion.site/Amar-e-Cuidar-Cosm-ticos-ba030697b4014482acbc9c077bc6eded)

#### [Link da API no Heroku](https://ctd-ecommerce-api.herokuapp.com)

#### [Link da API no AWS Elastic Beanstalk](http://turmadoisgrupodois-env.eba-e8scz79c.us-east-1.elasticbeanstalk.com)
