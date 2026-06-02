# diochallenge1
Repository created for the DIO bootcamp on AWS Cloud Foundations

## 🎯 Objetivo do Repositório
Este repositório foi criado para armazenar os desafios de código, projetos e anotações do bootcamp da DIO.

## 📚 Conteúdo Estudado
- [ ] Conceitos básicos da AWS Cloud Computing
- [ ] Principais serviços da AWS (EC2, S3, IAM)
- [ ] Arquitetura de serviços de Nuvem usando ferramentas de visualização gráfica, como Draw.io.

## Entendendo o IAM
Após entender os conceitos gerais de AWS, fizemos uma imersão no gerenciamento de acessos IAM. Nessa etapa, criamos usuários, grupos para esses usuários e definimos algumas políticas de acesso, como por exemplo, redefinição de senhas, acesso total (para grupo administrador), etc. 
No arquivo IAM na pasta images mostro a tela inicial do IAM com a criação de um usuário adicionado a um grupo. Esse usuário possui os mesmos privilégios de um usuário root, só que com nome diferente. Algo que farei em breve é a otimização na criação de usuários e atribuição de grupos através de um shell script utilizando CLI. 

## Primeiro projeto
Após estudarmos os conceitos de EC2, EBS, S3, foi dado um desafio para desenhar uma arquitetura utilizando um dos recursos. Utilizei a ferramenta draw.io para desenhar pois nela contém todos os detalhes gráficos importantes que facilitam a visualização. Utilizei uma arquitetura de acesso a nuvem com recusros de lambda, S3 e DynamoDB.
