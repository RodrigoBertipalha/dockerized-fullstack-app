Este projeto é uma aplicação fullstack Dockerizada, composta por um frontend utilizando NGINX e um backend em Flask, integrados com um banco de dados MySQL. O projeto foi desenvolvido para rodar em containers Docker, facilitando a implantação e execução.

Tecnologias Utilizadas:
Docker: Para conterização do ambiente.
Flask: Framework usado para o backend (API).
NGINX: Servidor utilizado no frontend.
MySQL: Banco de dados relacional utilizado para armazenar os dados.

Como Executar o Projeto:
-Crie uma instancia AWS EC2 e configure para t2.micro, banco de dados até 30gb e portas https liberadas;
-Clone o repositório em sua máquina local e suba na instancia.
-Acessa a instancia baixe o docker.io
-No diretório raiz do projeto, execute o Docker Compose para subir os containers.
-Se tiver problemas com permissões verifique as propriedades do documento ou do arquivo chave criado.
