
# Sistema Biblioteca

Projeto acadêmico de um sistema de gerenciamento de biblioteca, desenvolvido com HTML, JavaScript, Node.js e banco de dados SQL, com foco no aprendizado de operações CRUD (Create, Read, Update, Delete) e na integração entre front-end e back-end.

O objetivo deste projeto é simular o funcionamento básico de uma biblioteca, permitindo o cadastro, edição, listagem e exclusão de clientes/usuários, utilizando um banco de dados relacional para persistência das informações. O sistema foi desenvolvido com fins educacionais, como parte do aprendizado em desenvolvimento web e banco de dados.

Tecnologias utilizadas no front-end incluem HTML5 e JavaScript puro. No back-end é utilizado Node.js com Express para criação do servidor. O banco de dados é relacional, utilizando SQL (MySQL ou MariaDB), com scripts de criação de tabelas incluídos no repositório.

Estrutura do projeto:

Biblioteca/
├── server.js
├── db.js
├── package.json
├── index.html
├── menu.html
├── menu.js
├── clientes_principal.html
├── clientes_incluir.html
├── clientes_editar.html
├── inclui.js
├── altera.js
├── exclui.js
├── arquivos .sql
└── README.md

Funcionalidades do sistema incluem cadastro de clientes, edição de clientes existentes, remoção de clientes, listagem de registros, integração com banco de dados SQL e separação básica entre front-end e back-end.

Para executar o projeto é necessário ter o Node.js instalado, um banco de dados MySQL ou MariaDB configurado e um navegador web. Após clonar o repositório, instale as dependências com o comando npm install. Em seguida, crie o banco de dados, execute os arquivos SQL disponíveis e ajuste as credenciais de conexão no arquivo db.js. Para iniciar o servidor, utilize o comando node server.js e acesse o endereço http://localhost:3000 no navegador.

Este projeto não possui sistema de autenticação de usuários. O foco principal é o aprendizado da integração entre interface web e banco de dados, mantendo o código simples para facilitar a compreensão.

Como melhorias futuras, o projeto pode evoluir com a implementação de autenticação de usuários, controle de empréstimo e devolução de livros, utilização de templates ou frameworks de front-end, aplicação do padrão MVC e validações mais robustas no front-end e no back-end.

Autor: Pedro Henrique Domingos  
Estudante de Engenharia de Software  
GitHub: https://github.com/Domingos001  

Este projeto é destinado exclusivamente para fins acadêmicos e educacionais.
