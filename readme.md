# n8n - Instruções de Uso

Este projeto utiliza Docker Compose para facilitar a execução do n8n com PostgreSQL.

## Passos para iniciar

1. **Renomeie o arquivo de variáveis de ambiente**

   Copie ou renomeie o arquivo `.env.example` para `.env`:

   ```bash
   mv .env.example .env
   ```

   Se necessário, edite o arquivo `.env` para ajustar as configurações.

2. **Suba os containers com Docker Compose**

   Execute o comando abaixo para iniciar o ambiente:

   ```bash
   docker-compose up -d
   ```

   Isso irá baixar as imagens necessárias e iniciar os serviços do n8n e do PostgreSQL.

3. **Acesse o n8n**

   Após subir os containers, acesse o n8n pelo navegador em:  
   [http://localhost:5678](http://localhost:5678)

---

Pronto! O ambiente estará rodando localmente.
