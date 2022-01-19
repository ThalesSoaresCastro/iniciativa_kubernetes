# INICIATIVA KUBERNETES

"APRENDA DOCKER E KUBERNETES DE FORMA PRÁTICA E DESCUBRA COMO FAZER PARTE DA ELITE DA TI CAPAZ DE ENTREGAR AS MELHORES SOLUÇÕES EM CONTAINERS"

[LINK PARA INSCRIÇÂO AQUI...](https://iniciativakubernetes.com.br/)

## PARTE 1 - CONTAINERS
DESAFIO 01

"Containerização" da aplicação de conversão de temperatura feita em nodejs.
    
    - Criação do Dockerfile
    - Criação do docker-compose

### Execução utilizando docker-compose:

- Scripts para a execução estão do diretório scripts

Ambiente de desenvolvimento:

    iniciar containers: docker-compose -f docker-compose-dev.yaml up -d    
    matar containers: docker-compose -f docker-compose-dev.yaml down

Ambiente de produção:

    iniciar containers: docker-compose -f docker-compose-prod.yaml up -d    
    matar containers: docker-compose -f docker-compose-prod.yaml down

