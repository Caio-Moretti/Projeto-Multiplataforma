![Banner](img/Banner.png)


# Projeto Multiplataforma Etapa 2

**Link da Aplicação**: [http://54.189.185.141:5000/library](http://54.189.185.141:5000/library)

Este projeto é uma aplicação multiplataforma desenvolvida com a finalidade de demonstrar a integração entre front-end e back-end utilizando a arquitetura de microserviços. A aplicação é composta por um front-end responsivo, desenvolvido utilizando um framework web, e um back-end construído com microserviços implementados através de APIs RESTful.

O objetivo principal do projeto é fornecer uma solução prática que aborda os conhecimentos de implementação de back-end como serviço, práticas de segurança específicas para APIs (como autenticação e autorização baseadas em tokens), e desenvolvimento de front-end para web. Além disso, o projeto está preparado para deploy automatizado na AWS, utilizando CI/CD pipelines e containerização.

A aplicação funciona como um espaço onde você pode adicionar livros lidos e dar uma nota a eles.

## Tecnologias Utilizadas

- **Front-End:** Desenvolvido utilizando Bootstrap.
- **Back-End:** Microserviços construídos com Flask.
- **Nuvem:** AWS
- **Segurança:** Implementação de security groups na AWS.
- **CI/CD:** Github Pipelines configurado para deploy contínuo na AWS.
- **Containerização:** Utilização de containers para garantir a portabilidade e escalabilidade da aplicação.
- **Monitoramento:** Cloudwatch

## Próximos Passos
- Melhorar o front-end do website.
- Adicionar um sistema de Log In.
- Adicionar um serviço de banco de dados, como RDS ou DynamoDB.

## Como funciona

- Criar um PR de modificação da pasta "terraform/" acionará o workflow de terraform plan e aprovar o PR criará um workflow de terraform apply, isso vai fazer com que a aplicação seja deployada na AWS

- Criar um PR de modificação da pasta "app/" acionará o workflow de redeploy da aplicação que vai modificar o container no Docker Hub e depois vai fazer o redeploy da instância EC2.


![Banner](img/Ending.png)