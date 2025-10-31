# Sistema de Vendas de Celulares

Bem-vindo ao repositório do **Sistema de Vendas de Celulares**, um projeto desenvolvido para simular e melhorar o processo de vendas em uma loja de celulares.  
O sistema foi pensado para ser **simples, funcional e eficiente**, oferecendo recursos que ajudam tanto o vendedor quanto o cliente durante todo o processo de compra.

---

##  Descrição e definição do Projeto

O **Sistema de Vendas de Celulares** é um programa que permite realizar o processo completo de uma venda — desde a seleção do produto até o registro e pagamento do pedido.  
Ele foi desenvolvido com foco na **organização, segurança e praticidade**, simulando o funcionamento real de um e-commerce voltado para a comercialização de celulares.

A aplicação gerencia as principais entidades do processo de vendas:
- **Cliente**
- **Vendedor**
- **Pedido**
- **Pagamento**
- **Celular**

Essas entidades interagem entre si para garantir que cada venda seja registrada corretamente, com atualização automática e controle de pedidos.

---

##  Objetivo

Este projeto tem como objetivo desenvolver um programa voltado para a venda de smartphones, oferecendo suporte aos usuários na escolha e compra de novos aparelhos. A funcionalidade do sistema busca atender a todos os públicos, no intuito de fornecer melhor acessibilidade, melhor custo-benefício e informações detalhadas sobre os produtos, para que o cliente possa realizar uma compra mais consciente e sem arrependimentos.

---

## Funcionalidades Principais

### 1. Efetuar a Venda de Celulares
O sistema permite que o cliente (ou o vendedor em nome dele) navegue pelos modelos disponíveis, visualize detalhes como **marca, armazenamento, preço e promoções**, e adicione os produtos ao carrinho virtual.  
Durante a compra, o sistema calcula automaticamente o **subtotal e o valor total**, considerando quantidade e descontos.  
Essa é a base da aplicação, onde todo o processo de venda tem início.

### 2. Processar o Pagamento
Após a confirmação dos produtos, o sistema oferece **métodos de pagamento digitais**, como cartão, Pix ou carteiras online.  
A transação é validada automaticamente, o **status do pedido é atualizado para “Pago”**, e o sistema garante que todo o processo ocorra de forma **segura e confiável**.

### 3. Gerar e Registrar o Pedido
Após o pagamento, o sistema cria um **registro completo do pedido**, com todas as informações do cliente, vendedor, produtos e valores.  
Cada pedido possui um **status** (Ex: Aguardando pagamento, Pago, Enviado, Concluído), permitindo rastrear e gerenciar cada venda de maneira organizada.

---

##  Problema que o Sistema Resolve

Imagine uma loja com dezenas de clientes comprando ao mesmo tempo.  
Sem um sistema digital, facilmente podem ocorrer erros:  
vender um celular que já acabou, esquecer de registrar um pagamento, ou perder o controle dos pedidos.  

O **Sistema de Vendas de Celulares** resolve esse problema ao:
- Registrar todas as transações;
- Atualizar o status dos pedidos em tempo real;
- Garantir segurança e rastreabilidade em cada venda.

---

## Tecnologias Utilizadas

O projeto pode ser desenvolvido com diferentes tecnologias, mas a estrutura base sugerida é:

**Banco de Dados:**
- MySQL Workbench

**Ferramentas adicionais:**
- Git e GitHub para controle de versão  
- VS Code para desenvolvimento  
- App.Diagrams.net para o DER

---

## Modelagem do Sistema

**Entidades Principais:**

- Cliente: armazena informações como nome e contato.
- Vendedor: identifica o responsável pela venda.
- Celular: contém dados sobre marca, modelo, preço e estoque.
- Pedido: registra as compras e seus respectivos status.
- Pagamento: guarda informações sobre o método e a confirmação.

Mais informações no MER anexado ao repositório.

---

## Créditos

Este projeto foi desenvolvido como parte de um trabalho escolar/técnico na disciplina de Desenvolvimento de Sistemas.
Todos os direitos autorais das marcas de celulares (Samsung, Apple, Motorola, etc.) pertencem aos seus respectivos donos e são usados apenas para fins educacionais e ilustrativos.

**Integrantes:**

- Adrielly Trindade Martins Paixão 
- Maria Luiza Nunes dos Santos Silva 
- Nicoli Isabel Huallpa Coarite 

## Lincença

## Licença

Este projeto é de uso educacional e está sob a **[Licença MIT](./LICENSE)** — © 2025 ETEC Parque da Juventude.

**Ano de desenvolvimento: 2025**
**Instituição: ETEC Parque da Juventude**




