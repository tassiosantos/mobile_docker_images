# mobile_docker_images


Link para o vídeo do youtube com as explicações:

https://youtu.be/Gaq0n6osSpE


** Importante **
Não deve existir nenhuma aplicação rodando nas portas 8080 (backend) e nem 5432 (database)


##Existem duas formas de rodar:

A primeira, baixando os 3 containers na mesma pasta e rodando:

    docker-compose up


A estrutura de arquivos deve ser:
-------containers
-------newsletter_back
--------------database
--------------newsletter_back
-------newsletter_front
--------------newsletter_front

Após os cointainers do back-end e do front-end iniciarem, rodar na aplicação do flutter:

    flutter run



##Outro método:

Rodar o docker-compose do arquivo na pasta "direto"

Após os containers iniciarem, rodar na aplicação do flutter:
    flutter run


