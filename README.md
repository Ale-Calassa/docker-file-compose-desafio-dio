# 📜  O que o desafio propunha:
### Este projeto foi desenvolvido como parte de um desafio da DIO (Digital Innovation One), com o objetivo de aplicar conhecimentos básicos em Docker, Docker Compose, Apache e HTML. O desafio solicitava:
    • Criar um arquivo docker-compose.yml com as definições de um servidor Apache (httpd)
    • Especificar no arquivo .yml o local onde os arquivos da aplicação estariam
    • Criar uma aplicação web simples (ex: Hello World)
    • Subir o projeto completo para um repositório no GitHub
    • Demonstrar protagonismo e autonomia na implementação
    
## 🤔 Como eu decidi implementar
Além de atender aos requisitos mínimos, optei por explorar duas abordagens distintas para enriquecer o projeto e consolidar meu aprendizado:
### 🔹 Abordagem 1: Dockerfile 
    • Criei um Dockerfile personalizado que utiliza a imagem oficial do Apache
    • Copiei os arquivos HTML e imagem diretamente para o diretório público do Apache
    • Construi e executei a imagem manualmente com docker build e docker run
**Estrutura: docker-projeto-DIO-Dockerfile**

    • Dockerfile
    • index.html
    • minha-foto.PNG

### 🔹 Abordagem 2: Docker Compose
    • Criei um docker-compose.yml que orquestra o container Apache
    • Usei volumes para montar os arquivos HTML e imagem diretamente no container
    • Executei a aplicação com docker-compose up, facilitando a manutenção
**Estrutura: docker-projeto-DIO-Compose**

    • docker-compose.yml
    • index.html
    • minha-foto.PNG

## 🧐 Por que eu escolhi fazer as duas versões?
### Ao implementar ambas as abordagens, pude:
    • Comparar a flexibilidade do Dockerfile com a praticidade do docker-compose.yml
    • Demonstrar domínio sobre diferentes formas de configurar e servir aplicações web com Docker
    • Criar um projeto mais completo e didático para meu portfólio
**`Essa escolha reforça meu compromisso com o aprendizado contínuo e com a entrega de soluções bem estruturadas.`**
