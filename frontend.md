# Desafio de Frontend

### O que você deve desenvolver?
Bem simples, um simulador de vendas!

O usuário precisa inserir o valor a quantidade de parcelas e escolher os cartões(que nós chamaremos de bandeiras) e ser redirecionado 
para a página de detalhes das taxas de cada bandeira selecionada. 

O seu trabalho como frontend é desenvolver 2 telas simples consumindo e enviando dados para nossa API.

### Estilo e Visual
Pode ficar livre para desenvolver do jeito que você quiser, não temos _wireframes_ para essa tarefa, o mais importante é você desenvolver as duas telas:
  - Página Principal
    - Deve ter um campo para o valor, parcela e a seleção de múltiplas bandeiras, as bandeiras disponíveis estão na rota _GET BRANDS_, e um botão para **SIMULAR VENDA**.
  - Página Simulação
    - Separar por bandeiras e exibir os valores de taxa, porcentagem da taxa cobrada, valor original da venda e o valor + taxa.

### Sobre a API
O link da API que você irá utilizar: https://documenter.getpostman.com/view/17299486/UVe9QUWc
Essa documentação possui a collection do POSTMAN. Na documentação também possui exemplos de Request e Response.

> A API necessita de autenticação. Que é uma chave de api (API KEY) Que deve ir na HEADER __*x-functions-key*__. 
> 
> A api key será enviada no e-mail do teste.

- GET BRANDS - HTTP GET
  - Rota para exibir as bandeiras disponíveis.

- SIMULATION - HTTP POST
  - Rota para fazer a simulação de acordo com as bandeiras, valor e parcela enviada.

### Requerimentos técnicos:
- Você precisa criar um repositório no GitHub para hospedar seu código.
- Tudo bem usar scaffolds, nós queremos ver como você cria o problema proposto.
- Mantenha simples, não há necessidade de coisas extravagantes.
- Não ligamos se for feito em JS ou TS, pode escolher o que for melhor, pois nós iremos avaliar a estrutura.
- TESTES, realmente amamos testar nosso código e suas características aqui!
- Queremos ser capaz de apenas executar o projeto localmente `npm start`


## Método de Avaliação

Seu código estará sob análise do time de Tecnologia. O que vamos procurar:
- **Boas práticas e padrões**
- **Código e estrutura de pastas**
- **Componentização e fluxo de dados**
- **Código fácil de entender (novamente, não precisa de coisas extravagantes)**
- **TESTES**

Sinta-se à vontade para implementar da maneira que você se sentir mais confortável :)

