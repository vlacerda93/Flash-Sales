Objetivo do Projeto: Aplicação Flash Sales com ambiente containerizado e monitoramento configurado para a disciplina de Engenharia DevOps.

Pilares da Arquitetura:

Docker & Docker Compose: Garantem paridade entre ambientes e orquestração simplificada.

Prometheus: Coleta de métricas em tempo real (/metrics) para monitorar saúde e desempenho.

Jest: Execução de testes automatizados de integração e rotas.

Segurança: Separação de credenciais através do arquivo .env.example.

Como Executar:

Clonar o repositório e criar o .env a partir do .env.example.

Subir os serviços com o comando docker compose up -d --build.

Endpoints e Portas:

API: http://localhost:3000

Métricas: http://localhost:3000/metrics

Prometheus: http://localhost:9090

Integração com Contratos: Link direcionando para o repositório dedicado com as especificações OpenAPI e coleções do Postman ([github.com/vlacerda93/contratos](https://github.com/vlacerda93/contratos)).