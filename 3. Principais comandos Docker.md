# Principais comandos Docker

### Criação
| Função | README |
| ------ | ------ |
| cria um container sem executar | docker container create / docker create|
| cria um container baseado em uma imagem sem executar | docker container create IMAGE_NAME / docker create IMAGE_NAME |
| cria e roda um container baseado em uma imagem | docker run IMAGE_NAME / docker container run IMAGE_NAME |
|cria e roda um container em modo terminal interativo | docker run -it IMAGE_NAME [bash ou sh] |
|cria e roda um container em segundo plano| docker run -d IMAGE_NAME |
| cria e roda um container definindo uma porta virtual | docker run - p 1234:80 docker/image / (nesse caso porta 1234 acessa porta 80 do container)] |

### Execução
| Função | README |
| ------ | ------ |
| inicia a execução de um container já criado | docker start CONTAINER_ID|
| para/interrompe a execução de um container já criado | docker stop CONTAINER_ID |
| pausa a execução dos processos do container | docker pause CONTAINER_ID |
|reinicia o container parado | docker restart CONTAINER_ID |

#### Documentação oficial:
https://docs.docker.com/
