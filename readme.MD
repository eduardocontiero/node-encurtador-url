# README

## Encurtador de URL

Esta é uma API desenvolvida com Typescript, Fastify, Postgres e Redis. O objetivo dela é encurtar URL's e redirecionar para a URL destino, além de obter métricas e fazer um ranking de links mais acessados.

### Como Rodar

Para executar esta API localmente, siga as instruções abaixo:

1. Certifique-se de ter o Docker instalado na máquina.
2. Clone este repositório.
3. Navegue até o diretório raiz do projeto.
4. Instale as dependências utilizando o comando `npm install`.
5. Rode o comando docker-compose up -d
6. Rode o comando `npm run setup` para criar a tabela `short_links` em seu banco de dados 
7. Para executar a API rode em seu terminal o comando `npm run dev`.

### Dependências

Aqui estão as principais dependências utilizadas neste projeto:

- `fastify`: Framework web para Node.js.
- `postgres`: Driver Postgres para Node.js.
- `redis`: Driver Redis para Node.js.
- `zod`: Para validação de dados enviados na request.


### Licença

Este projeto está licenciado sob a [MIT License](LICENSE).