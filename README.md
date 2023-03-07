## Instalação
<br/>

1. Clone este repositório:
   ```git
   git clone https://github.com/tideeh/terracap-legados-docker.git
   ```

1. Entre na pasta `terracap-legados-docker`.
<br/><br/>

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
![image](https://user-images.githubusercontent.com/33804453/223494169-9b0b6574-cbc2-4693-b8c6-8df9101e9fa2.png)
