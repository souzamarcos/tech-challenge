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

## Documentação
* [Wiki - Notion](https://www.notion.so/9dfe9780ad5f4d9587adc565f54bb70f?v=f2ef9c679bcf4ad1b857479c1f317c25)
* [Event Storm - MIRO](https://miro.com/app/board/uXjVMK9Fze8=/?share_link_id=624130302810)

### Executando aplicações

Para executar todas as aplicações será necessário baixar o código dos repositórios:

```bash
git submodule init
```

Após isso basta iniciar o docker-compose
```bash
docker-compose up --build
```

#### Endpoints locais
* ms-product: [http://localhost:8080/swagger](http://localhost:8080/swagger)
* ms-order: [http://localhost:8081/swagger](http://localhost:8081/swagger)
* ms-payment: [http://localhost:8082/swagger](http://localhost:8082/swagger)
* ms-customer: [http://localhost:8083/swagger](http://localhost:8083/swagger)
* ms-notification: [http://localhost:8084/swagger](http://localhost:8084/swagger)