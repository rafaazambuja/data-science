
# Data Science Degree - [Let's Code](https://www.letscode.com.br/degree/ds)

Repositório criado para utilização na formação de data science, onde serão colocados todos os arquivos de aula, exercícios e avaliações.


Para rodar o ambiente de trabalho do Jupyter Lab com os notebooks basta seguir os dois passos abaixo:

## Inicializando Ambiente

1. Instalar [Docker](https://docs.docker.com/get-docker/) e [Docker Compose](https://docs.docker.com/compose/install/).

2. Rodar o arquivo `docker-compose.yml` no seu terminal para acessar o Jupyter Lab:

```bash
   docker-compose up
   ```

3. No terminal aparecerá o link de acesso que começará com `http://127.0.0.1:8888/lab`, basta abrir o link no seu navegador para começar a utilizar.


**Nota:** A pasta `notebooks` estará compartilhada com o container, todos os arquivos que estiverem nesta pasta aparecerão no Jupyter Lab e os novos arquivos criados no Jupyter Lab aparecerão nesta pasta.
