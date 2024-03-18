# Tech Challenge - FIAP
Repositório central para o tech challenge da pós da FIAP

## Repositórios
* [Serviço de produto](https://github.com/souzamarcos/tech-challenge-ms-product)
* [Serviço de pedidos](https://github.com/souzamarcos/tech-challenge-ms-order)
* [Serviço de pagamento](https://github.com/souzamarcos/tech-challenge-ms-payment)
* [Serviço de cliente](https://github.com/souzamarcos/tech-challenge-ms-customer)
* [Serviço de notificação](https://github.com/souzamarcos/tech-challenge-ms-notification)
* [Infraestrutura Terraform](https://github.com/souzamarcos/tech-challenge-terraform)
* [Configuração do Kubernetes](https://github.com/souzamarcos/tech-challenge-kubernetes)
* [Lambda de Autenticação](https://github.com/souzamarcos/tech-challenge-authentication-lambda)

## Links
* Relatório de Proteção à Impacto de Dados Pessoais - https://drive.google.com/file/d/1Vizxe8AhVau3qtRWpFnpZ7KxoVAuWk4n/view?usp=sharing 
* Relatório OWASP ZAP (baixar e abrir) - https://drive.google.com/file/d/1w5DBp_1NWskAOnnT68nxtARCSP6v_P6V/view?usp=sharing 
* Justificativa Padrão SAGA Coreografado - https://drive.google.com/file/d/1reVAugzzf9TbTvST9ErH3rcBl8mREoR8/view?usp=sharing
* Desenho Padrão SAGA - https://drive.google.com/file/d/1O4zrHemPRQ-XwiMXwbjJFuwU0kaW-QjT/view
* Desenho Arquitetura - https://drive.google.com/file/d/1m9aJ0YxoWZBNBHr3yw_6eYUSIIhARPz-/view?usp=sharing
* Vídeo de entrega da Fase 5 - https://drive.google.com/file/d/1YmER6h7VVz9r5IYOZUHoUR8mc0GqaZXK/view?usp=sharing

## Executando aplicações

Para executar todas as aplicações será necessário que o Docker esteja rodando na máquina. 

1- Baixe esse repositório e dentro da pasta siga as instruções abaixo:

2 - Baixe o código dos repositórios executando o seguinte código:
```bash
git submodule update --init 
```

3 - Execute as aplicações através do Docker-compose executando o seguinte código:
```bash
docker-compose up --build
```

4 - Aguarde alguns minutos para baixar todas as imagens, buildar as aplicações e iniciar os containers. Após isso basta utilizar o endpoints abaixo.

Obs: para criar o token de um cliente localmente siga as instruções em https://drive.google.com/file/d/1elMAUyHxnvPCCEP0zhBC40aX7WcukJST/view?usp=drive_link.

#### Endpoints locais
* ms-product: [http://localhost:8080/swagger](http://localhost:8080/swagger)
* ms-order: [http://localhost:8081/swagger](http://localhost:8081/swagger)
* ms-payment: [http://localhost:8082/swagger](http://localhost:8082/swagger)
* ms-customer: [http://localhost:8083/swagger](http://localhost:8083/swagger)
* ms-notification: [http://localhost:8084/swagger](http://localhost:8084/swagger)
