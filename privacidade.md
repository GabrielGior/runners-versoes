---
title: Política de privacidade do Runners
---

# Política de privacidade do Runners

Última atualização: 14 de novembro de 2026.

O Runners é um app para Windows e Android que instala e controla runners próprios do GitHub Actions no computador de
quem o usa. Esta página explica o que o app faz com os seus dados.

## O que o app acessa

- **Conta Google:** no Windows, o login com Google serve só para criar e configurar um projeto Firebase **na sua
  própria conta** (Firestore, regras e o app do celular). No Android, o login com Google serve para o app ler os
  dados desse mesmo projeto. O app não lê seus e-mails, arquivos nem contatos.
- **Conta do GitHub:** o login do GitHub dá ao app acesso aos repositórios que você escolher, para cadastrar runners,
  ler e controlar as execuções do Actions e ler os workflows.
- **Dados da máquina:** nome do PC, uso de memória, processador e disco, e o andamento dos trabalhos dos runners.

## Onde os dados ficam

- Os dados da máquina e dos runners vão para o **seu** projeto Firebase (plano gratuito), que só a sua conta Google
  lê e grava.
- Os tokens do GitHub e do Google ficam no Gerenciador de Credenciais do Windows e no armazenamento seguro do Android,
  no seu aparelho.
- O desenvolvedor do Runners **não recebe nem guarda** nenhum dado seu. Não há servidor do desenvolvedor, propaganda
  nem análise de uso.

## Como apagar

Desinstale o app e apague o projeto Firebase criado por ele no console do Firebase. Para tirar o acesso do GitHub,
desinstale o App do Runners em github.com/settings/installations; para tirar o do Google, use
myaccount.google.com/permissions.

## Contato

Dúvidas: abra uma issue em github.com/GabrielGior/runners-versoes.
