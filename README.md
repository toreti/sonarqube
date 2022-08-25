# SonarQube

Para iniciar os serviços basta executar:

```bash
docker-compose up -d
```

Depois disso é possível abrir o dashboard através da url [http://localhost:9000](http://localhost:9000).

## Problemas Comuns

Caso tenha problemas ao iniciar o serviço `sonarqube` experimente executar o comando:

```bash
sudo sysctl -w vm.max_map_count=262144
```

Depois tente novamente.
