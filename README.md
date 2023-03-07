## Instalação
<br/>

1. Crie uma pasta e entre nela.
<br/><br/>

2. Clone este repositório:
   ```git
   git clone https://github.com/tideeh/terracap-legados-docker.git
   ```

3. Clone o `adodb`:
   ```git
   http://sv56/php-projects/adodb
   ```

4. Crie uma pasta chamada `sistemasWeb` e entre nela.
<br/><br/>

5. Clone o `arqweb-interna` e renomeie para `arqweb`:
   ```git
   http://sv56/php-projects/arqweb-interna
   ```

6. Clone o sistema que deseja trabalhar (por exemplo: `GLP`):
   ```git
   http://sv56/php-projects/GLP
   ```

7. Volte a pasta raíz e inicie a aplicação através do comando:
   ```docker
   docker-compose up --build
   ```

8. Acesse a aplicação informando no final o nome do sistema:`http://localhost:88/sistemasWeb/NOME-DO-SISTEMA` (exemplo: `GLP`):
   - [`http://localhost:88/sistemasWeb/GLP/`](http://localhost:88/sistemasWeb/GLP/)
<br/><br/><br/>

* A estrutura deve ter o seguinte padrão:  
![image](https://user-images.githubusercontent.com/33804453/223464964-79e95564-beb0-4c67-a1ab-ef762b98adff.png)
