# dica-vagrant1

##Pré-requisitos:
Tenha pré-instalados o virtualbox e o Vagrant para o seu sistema operacional:
https://www.virtualbox.org/
https://www.vagrantup.com/


##Crie um diretório onde constarão as configurações da box:
mkdir debian-curso
cd debian-curso

##Em seguida realize a criação do arquivo de configuração da box a ser criada:
vagrant init

###Nesse momento será gerado o arquivo Vagrantfile, abra-o e altere a sessão "config.vm.box" para a imagem do sistema operacional desejado, por exemplo:
config.vm.box = "debian/jessie64"

###Em seguida inicie a vm:
vagrant up

### E realize o acesso ssh à mesma(estando dentro do diretório configurado):
vagrant ssh



##Mais informações sobre boxes a configurar no Vagrant:
https://app.vagrantup.com/boxes/search?_ga=2.122797261.733228015.1502536753-644161865.1493964691
