# docker
Projeto em Node utilizado para criação de imagem e execução de contêiner docker



API com Docker

- Testando Instalacao docker: 
docker --version

- Baixando uma imagem docker:
docker run hello-world

- Listando imagem:
docker image ls

- Removendo Imagem
docker image rmi ID_DA_IMAGEM

- Listando contêiner:
docker container ls --all

- Iniciando e parando contêiner
docker container start ID_DO_CONTAINER
docker container stop ID_DO_CONTAINER

- Removendo um Contêiner
docker container rm ID_DO_CONTAINER

- Criando imagem docker:
docker image build -t name:version .

- Rodando o Contêiner:
docker container run --publish 8080:3000 --detach --name api dockerapi:1.0






