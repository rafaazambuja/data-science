
# Repositório para utilização do Data Science Degree - [Let's Code](https://www.letscode.com.br/degree/ds)

Para rodar o ambiente de trabalho do Jupyter Lab com os notebooks de aulas, exercícios e avaliações basta seguir os dois passos abaixo:

## Inicializando Ambiente

1. Instalar [Docker](https://docs.docker.com/get-docker/) e [Docker Compose](https://docs.docker.com/compose/install/).

2. Rodar o arquivo `docker-compose.yml`:

```bash
   docker-compose up
   ```

   **Nota:** A pasta `notebooks` estará compartilhada com o container, todos os arquivos que estiverem nesta pasta aparecerão no Jupyter Lab e os novos arquivos criados no Jupyter Lab aparecerão nesta pasta.

3. No terminal aparecerá o link de acesso que começará com `http://127.0.0.1:8888/lab`, basta clicar abrir o link no seu navegador para começar a utilizar.