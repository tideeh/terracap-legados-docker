## Instalação

* Crie uma pasta e entre nela

* Clone este repositório:

      git clone https://github.com/tideeh/terracap-legados-docker.git

* Clone o `adodb`:

      http://sv56/php-projects/adodb

* Clone o `arqweb-interna` e renomeie para `arqweb`:

      http://sv56/php-projects/arqweb-interna
      
* Clone o sistema que deseja trabalhar (por exemplo: `GLP`):

      http://sv56/php-projects/GLP

* Inicie a aplicação através do comando:

      docker-compose up --build
 
* Acesse a aplicação informando no final o nome do sistema: `http://localhost:88/sistemasWeb/NOME-DO-SISTEMA` (exemplo: `GLP`): http://localhost:88/sistemasWeb/GLP/
