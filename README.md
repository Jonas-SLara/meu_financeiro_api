# meu_financeiro_api
api para meu financeiro contendo autenticacao do usuario para ver suas entradas e saidas

```bash
cp .env.example .env
```

modificar suas variaveis de ambiente se nescessario para produção!


gerar a chave para o secret
```bash
openssl rand -base64 64
```

```bash
docker compose up -d
```

caso nao tenha o wrapper do mvn, executar comando, com o mvn instalado (opcional)

```bash
mvn -N wrapper:wrapper
```

executando no modo dev (precisa das variaveis de ambiente e wrapper acima)
```bash
./mvnw spring-boot:run
```