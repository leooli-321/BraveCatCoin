# BCC - Brave Cat Coin 🐾💎

O **BCC** é o Brave Cat Coin, uma criptomoeda baseada na rede Ethereum. 💎

Nosso gatinho de olhos verdes e amarelos nasceu e foi criado na Ethereum. 💙

Por que um gato? 🐈 Porque neste projeto, nos opomos às criptomoedas caninas associadas a Elon Musk (Doge, Shiba…) 🙅‍♂️

O **BCC** marca o início de um ambicioso projeto com o objetivo principal de reduzir taxas e aumentar lucros para todos os participantes. 💰

Aproveitando a **BLOCKCHAIN** e a **DESCENTRALIZAÇÃO**, buscamos justiça para nossa liberdade financeira. 🚀

**JUNTE-SE A ESTE MOVIMENTO!** 🌟

---

## Smart Contract - BCC Token

### SafeMath Contract

Este contrato fornece funções aritméticas seguras, prevenindo estouros e subfluxos durante operações matemáticas para evitar vulnerabilidades.

### ERC20Interface Contract

Define a interface padrão ERC-20, estabelecendo métodos como totalSupply, balanceOf, transfer, approve, transferFrom, e eventos como Transfer e Approval.

### ApproveAndCallFallBack Contract

Declara uma função receiveApproval, chamada quando uma entidade aprova o gasto de tokens e, simultaneamente, executa uma função específica.

### BCCToken Contract

Implementa o contrato ERC-20, utilizando a biblioteca SafeMath.

Define propriedades do token, como símbolo ("BCC"), nome ("Brave Cat Coin"), casas decimais (2) e fornecimento total (150.000 tokens).

Distribui o fornecimento para o endereço 0x8BD1Eca9b97E2EA6634A690F93ef0aD08C81F19d no início do contrato.

Fornece funções para verificar saldo, transferir tokens, aprovar transferências por terceiros e executar chamadas de aprovação com dados adicionais.

A função fallback (function() public payable) é implementada para rejeitar transferências de Ether, prevenindo envios acidentais ao contrato.

Este contrato cria a criptomoeda "Brave Cat Coin (BCC)" seguindo o padrão ERC-20 na blockchain Ethereum. Os tokens podem ser transferidos entre detentores, com autorização para terceiros realizar transferências em nome dos detentores. A utilização da biblioteca SafeMath visa evitar vulnerabilidades relacionadas a operações matemáticas não seguras.
