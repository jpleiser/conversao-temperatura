# Criando a imagem no docker.
docker image build -t conversao-temperatura .

# Executando o container no docker
docker container run -d -p 8080:8080 conversao-temperatura