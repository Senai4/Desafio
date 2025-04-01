Projeto loja de Artesanato
O protótipo do nosso sistema foi desenvolvido com o objetivo de aprimorar e evoluir a loja de artesanato, proporcionando uma experiência mais eficiente e prática para seus clientes. A seguir, apresentaremos, de forma detalhada, as etapas do desenvolvimento do nosso projeto.
Etapas:
	Configuração do Ambiente 
Instalação e configuração das bibliotecas necessárias para o desenvolvimento, como Express, Sequelize, e Body-Parser, garantindo que o ambiente de trabalho esteja adequado para a criação do sistema.
	Modelagem do Banco de Dados 
- Definição da Estrutura da Tabela de Produtos, que inclui atributos como nome, descrição, preço e imagem. 
- Criação de uma database Produto no Mysql.
-  Criação do Arquivo de migração para a criação e conexão do banco de dados e da tabela Produto. 
-  Organização das pastas do projeto, estruturando os diretórios de controllers, models, views e outros arquivos necessários para o funcionamento do sistema.
	Criação das Rotas
- A criação e definição das rotas foi feita pelo index.js, onde foram criadas as rotas para cada função sendo elas, listar produtos, salvar o cadastro do produto e a rota para visualizar os detalhes de um produto específico.
	Implementação dos Controllers
- Os Controllers foram adicionados no começo do código importando e consultando os dados adicionados na tabela Produto e passando os dados de produto para as views index.ejs, produto.ejs e produtos.ejs.
	Criação das Views
- Os arquivos criados dentro da pasta views foram index.ejs, produto.ejs, produtos.ejs.
- O arquivo index.ejs é responsável pelo corpo do site para adicionar um novo produto, produto.ejs é responsável por adicionar as informações na tabela e produtos.ejs é responsável por adicionar e salvar um no cadastro.
	Utilização do Body-Parser
- Utilizamos o Body-Parser para converter os dados nas requisições: 
(app.use (bodyParser.urlencoded({extended: false}));
(app.use (bodyParser.json()));
	Testes
- Para finalizar, testamos o sistema conferindo se estava rodando tudo corretamente. 
	Dificuldades
- Apenas algumas alterações foram necessárias da definição da tabela produto e estilização pelo css.
