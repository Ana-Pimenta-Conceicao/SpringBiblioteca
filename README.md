📚 Sistema de Gerenciamento de Biblioteca
Bem-vindo ao Sistema de Gerenciamento de Biblioteca, um projeto desenvolvido em Java Spring para gerenciar livros e gêneros de maneira eficiente. Este sistema permite o cadastro, listagem, edição e exclusão de livros, oferecendo uma interface amigável e moderna.

🚀 Funcionalidades
Cadastro de Livros: Adicione novos livros com informações detalhadas, como nome e gênero.
Gerenciamento de Gêneros: Categorize livros por gêneros literários, como ficção, romance, biografia, entre outros.
Listagem: Visualize todos os livros cadastrados em uma tabela dinâmica.
Edição e Exclusão: Atualize ou remova registros facilmente.
Interface Responsiva: Design moderno e adaptável para diferentes dispositivos.
🛠️ Tecnologias Utilizadas
Back-end:

Java Spring Framework - Para criação do servidor e controle de rotas.
Spring Boot - Para facilitar a configuração e execução do projeto.
Spring Data JPA - Para gerenciamento de persistência de dados.
H2 Database ou MySQL - Banco de dados para armazenar os registros.
Front-end:

Thymeleaf - Motor de templates integrado ao Spring.
HTML5, CSS3 e JavaScript - Para estrutura e estilo da interface.
Design moderno com CSS responsivo.
⚙️ Requisitos para Rodar o Projeto
Antes de começar, certifique-se de ter as seguintes ferramentas instaladas em sua máquina:

Java JDK 17+
Maven
Git
IDE como IntelliJ IDEA ou Eclipse
📝 Instalação e Configuração
Clone o repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/sistema-biblioteca.git
Acesse o diretório do projeto:

bash
Copiar código
cd sistema-biblioteca
Configure o banco de dados:

Atualize o arquivo application.properties para definir as credenciais do banco de dados (ex.: H2 ou MySQL).
Exemplo de configuração para H2 (memória):

properties
Copiar código
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=password
spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
Execute o projeto:

Utilize o Maven para compilar e rodar o projeto:
bash
Copiar código
mvn spring-boot:run
Acesse a aplicação:

Abra o navegador e acesse: http://localhost:8080
📂 Estrutura do Projeto
plaintext
Copiar código
src
├── main
│   ├── java
│   │   └── com.example.sistemabiblioteca
│   │       ├── controllers      # Controladores para gerenciar as rotas
│   │       ├── models           # Entidades JPA (Livro, Gênero, etc.)
│   │       ├── repositories     # Interfaces para acessar o banco de dados
│   │       └── services         # Lógica de negócios
│   ├── resources
│       ├── templates            # Arquivos HTML (Thymeleaf)
│       ├── static               # CSS, JS, imagens
│       └── application.properties
🖼️ Interface
A interface da aplicação foi projetada com foco em simplicidade e modernidade:

Menu de Navegação: Facilita o acesso às funcionalidades principais.
Tabela Interativa: Apresenta os livros cadastrados de forma clara.
Formulários Responsivos: Design adaptado para desktop e dispositivos móveis.
📋 Próximas Melhorias
Implementar autenticação e controle de usuários.
Adicionar funcionalidade de busca por nome ou gênero.
Criar relatórios exportáveis (PDF/Excel).
Integração com APIs para buscar informações de livros.
🤝 Contribuições
Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias e novas funcionalidades.

📝 Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para usá-lo e modificá-lo conforme necessário.
