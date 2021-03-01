# DockerFiles
Repositório com arquivos de docker-compose pré configurados.

## Utilização
Para utilizar, basta baixar o projeto ou copiar o arquivo que deseja em sua máquina local e rodar o comando 
```bash
docker-compose -f <NOME_DO_ARQUIVO>.yml up
```

## Especificações dos arquivos
- **_start-postgresql.yml_**

  Sobe o Postgresql na porta 5432 e PgAdmin4 na porta 16543 do seu localhost.
  Para utilizar os serviços, estão definidos as seguintes variáveis:

  **Postgresql**
  ```
    username: pgdocker
    password: pgdocker
  ```

  **PgAdmin4**
  ```
    username: pgdocker@pgdocker.com
    password: pgdocker
  ```

- **_start-kafka.yml_**

  Sobe o Zookeeper na porta 2181 e Kafka na porta 9092 do seu localhost

