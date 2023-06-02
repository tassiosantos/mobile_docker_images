# mobile_docker_images


Link para o vídeo do youtube com as explicações:

https://youtu.be/5sX3pwmiFJ0


** Importante **
Não deve existir nenhuma aplicação rodando nas portas 8080 (backend) e nem 5432 (database)


## Existem duas formas de rodar:


## Primeiro método:


 - #### Baixar os 2 containers na mesma pasta:

    - ##### Os containers são:

        - ###### Controle de imagens:
          https://github.com/tassiosantos/mobile_docker_images

        - ###### Front-end:
          https://github.com/tassiosantos/newsletter_front

 - #### Na pasta "direto" do respositório Controle de imagens rodar:
  
       docker-compose up

 - #### Após os containers iniciarem, rodar na aplicação do flutter:

       flutter run




## Segundo Método: 

- #### Baixar os 3 containers na mesma pasta:

    - ##### Os containers são:

        - ###### Controle de imagens:
          https://github.com/tassiosantos/mobile_docker_images

        - ###### Front-end:
          https://github.com/tassiosantos/newsletter_front
          
        - ###### Back-end:
          https://github.com/tassiosantos/newsletter_back

 - #### A estrutura de arquivos deve ser:
   - containers
   - newsletter_back
     - database
     - newsletter_back
   - newsletter_front
     - newsletter_front


 - #### Após baixar os três repositórios, na pasta 'containers', rodar:

       docker-compose up

 - #### Após os cointainers do back-end e do banco de dados iniciarem, rodar na aplicação do flutter:

       flutter run

