Instalação

Clone o repositório:
git clone <URL_DO_REPOSITORIO>

Navegue até  o diretório do projeto:

cd CHALLENGER3-FORUM

Configurar a base de dados no  MySQL. crie a base de dados e modifique o arquivo application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/SUA-BASE-DE-DADOS
spring.datasource.username=
spring.datasource.password=

Compile o projeto utilizando Maven:

./mvnw clean install

execute a aplicação:

./mvnw spring-boot:run
