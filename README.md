# react-native-challenge
Desafio de reactNative pra mobile da +TODOS

How-to-solve
------------
- Use Git;
- Procure fazer micro commits que são muitos commits com menos código isso nos ajuda a compreender a sua lógica;
- Nos pergunte sobre qualquer dúvida que venha a surgir durante o desenvolvimento;
- Documente detalhadamente quaisquer referencias/ferramentas que vc pesquisar;
- Crie um repositório público e nos passe o link para acompanharmos o desenvolvimento;


Problema
--------

A MAISTodos precisa mostrar para os seus clientes o saldo disponível em suas contas
Para isso vamos fazer um APP mobile bem simples, que mostra apenas as movitações da conta do cliente e o seu saldo
Para isso vamos consultar a nossa API de CC

Seguindo a **sugestão** de layout:
![Saldo escondido](balance.png)
![Saldo visível](hidden_balance.png)

Deve seguir os conceitos
========================
- Saldo carregado via api, mais não ficaria viível num primeiro momento
- Click para mostrar o saldo
- Fica a seu critério limpar o layout: tem v;arios link, botões, etc...que não serão usados neste exercício
- Importante ter as abas (Entrada e Saída)

Documentação da API
===================

API de saldo
=============
- balance (float com o saldo
- https://5efb30ac80d8170016f7613d.mockapi.io/api/mock/balance

```json
{
  "balance": 12
}
```

API de transações
=================

- tipoLancamento C para Crédito e D para Débito
- https://5efb30ac80d8170016f7613d.mockapi.io/api/mock/transactions


Resposta:
```json
[
    {
      "id": 1102,
      "descricao": "CREDENCIADO TESTE",
      "dataTransacao": "2020-01-28",
      "tipoTransacao": "Recarga Pré-pago ",
      "valorTransacao": 20,
      "tipoLancamento": "C",
      "cartaoMascarado": "600000******1234",
      "finalCartao": "1234",
      "nomePortador": "RITA DE CASSIA ALVES MACEDO "
    },
   ...
 ]
 ```
 
 Documentação
 ------------
 
 Detalhe bem os requisitos do projeto e como rodar, ex:
 
Requisitos e tecnologias usadas na aplicação
============================================
```json
React-Native
Redux
Redux-Saga
Styled-Components
Jest
Enzyme
Lint
````


 
