# Objetivo
API Hello Swagger.

## Iniciando

- `git clone https://github.com/sergio-aliceral/hello-swagger.git`
- `cd hello-swagger`

## Pré-requisitos
- `mvn --version`<br>

Você deverá ver a indicação da versão do Maven instalada e a versão do JDK. Observe que o JDK é obrigatório, assim como a definição das variáveis de ambiente **JAVA_HOME** e **M2_HOME**.

## Limpar, compilar e empacotar
- `mvn clean install`<br>

Gera arquivo _hello-swagger-1.0.0.jar_ no diretório _target_.

## Executando a aplicação
- `java -jar target/hello-swagger-1.0.0.jar`<br>

Executa o aplicativo por meio do arquivo jar criado pelo comando `mvn clean install`, conforme comentado anteriormente.

### Documentação com Swagger

- http://localhost:9999/swagger-ui.html
 
