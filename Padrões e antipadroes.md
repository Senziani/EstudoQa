# Padrões e antipadroes

- antipadrão da piramide de teste
- cupcacke
- Icescream


## Variação da piramide de teste 

- Temos testes manuais em E2E


![Imagem Ilustrativa](https://miro.medium.com/v2/resize:fit:1304/format:webp/0*gG7K_Qm7gD5EuJAm)


* Cupcacke 

- Anti Padrão
- menos pior de se trabalhar e reverter

![Imagem Ilustrativa](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fdea931b6-8ebb-4db0-875a-5bd65cd75507_640x640.png)

- muita refaroração de codigo
    - Muita automação
    - TDD - Testing Drive Development (Desenvolvimento orientado por teste)
     - TDD = ele foca em desenvolver o teste primero e depois escrever o codigo em cima , na    situação em que o codigo passe no teste, ajuda a identificar bugs mais rapidamente

        - tem 3 fases:
            - Red - Teste falha
            - grem - Escrever o codigo para que passe no teste
            - Refatorara - melhorar estrutura do codigo

- Para arrumar:
   - Implementar teste de contrato e serviço
   - automatizar apenas os cenarios mais criticos
   - finalizar com testes manuais

# ice Cream

- Pior anti Padrão

![Imagem Ilustrativa](https://miro.medium.com/v2/resize:fit:1000/1*INoAm_g7PBqRn-qSwhv8vw.png)


* Para acerta somente modificando.


* obs: o quadrante de teste Agil é o melhor para converter anti Padrões.