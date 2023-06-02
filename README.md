# mobile_docker_images


Link para o vídeo do youtube com as explicações:

https://youtu.be/5sX3pwmiFJ0


** Importante **
Não deve existir nenhuma aplicação rodando nas portas 8080 (backend) e nem 5432 (database)


##Existem duas formas de rodar:

A primeira, baixando os 3 containers na mesma pasta e rodando:

    docker-compose up


A estrutura de arquivos deve ser:
 - containers
 - newsletter_back
   - database
   - newsletter_back
 - newsletter_front
  - newsletter_front

Após os cointainers do back-end e do banco de dados iniciarem, rodar na aplicação do flutter:

    flutter run



##Outro método:

Rodar o docker-compose do arquivo na pasta "direto"

Após os containers iniciarem, rodar na aplicação do flutter:
    flutter run


