# 🤖 Sistema de Chatbot de Atendimento

Projeto acadêmico de um sistema de **chatbot de atendimento para um negócio local**, desenvolvido para representar o funcionamento de um atendimento automatizado utilizando Inteligência Artificial e banco de dados.

## 📌 Sobre o projeto

O sistema consiste em um chatbot integrado a um site de um negócio local, como uma **pizzaria, barbearia ou clínica**.

O cliente pode enviar mensagens pelo chat e receber respostas contextualizadas. Para isso, o sistema utiliza uma **API de Inteligência Artificial** e, quando necessário, consulta informações armazenadas em um **banco de dados MySQL**.

Entre os dados que podem ser consultados estão:

- 🍕 Cardápio
- 🕐 Horários de funcionamento
- 💰 Preços
- 📋 Outras informações relacionadas ao negócio

## 🎯 Objetivo

O objetivo do projeto é representar, por meio de um **Diagrama de Caso de Uso UML**, a interação entre o cliente, o chatbot, a API de IA e o banco de dados.

O fluxo principal do sistema é:

```text
Cliente
   ↓
Enviar mensagem no chat
   ↓
Processar mensagem via IA
   ↓
Gerar resposta contextualizada
   ↓
Receber resposta no chat
