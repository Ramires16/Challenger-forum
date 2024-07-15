Instalación

Clone o repositório:
git clone <URL_DO_REPOSITORIO>

Navegue até  o diretório do projeto:

cd CHALLENGER3-FORUM

ConfiguraR a base de dados no  MySQL. crie a base de dados e modifique o arquivo application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/SUA-BASE-DE-DADOS
spring.datasource.username=
spring.datasource.password=

Compilar o projeto utilizando Maven:

./mvnw clean install

executar a aplicação:

./mvnw spring-boot:run
