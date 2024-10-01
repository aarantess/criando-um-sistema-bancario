# Sistema Bancário Orientado a Objetos

Este projeto é uma implementação de um sistema bancário orientado a objetos, seguindo os conceitos de Programação Orientada a Objetos (POO). O sistema permite criar contas, realizar saques, depósitos e gerar extratos. Além disso, mantém um histórico de transações para cada conta.

## Funcionalidades

- **Criação de Usuários**: Os usuários podem ser cadastrados no sistema com informações como nome, CPF, endereço, e data de nascimento.
- **Criação de Contas Bancárias**: Cada usuário pode ter uma ou mais contas correntes associadas.
- **Saque e Depósito**: Realização de operações de saque e depósito com limite de saques diários.
- **Histórico de Transações**: Todas as transações realizadas são registradas e exibidas no extrato.
- **Conta Corrente**: As contas correntes possuem um limite de saldo e limite de saques diários.

## Estrutura do Projeto

O sistema foi desenvolvido utilizando a linguagem Python e é composto pelas seguintes classes principais:

- `Conta`: Representa uma conta bancária genérica.
- `ContaCorrente`: Herda de `Conta` e adiciona funcionalidades como limite de saldo e limite de saques.
- `Cliente`: Armazena os dados do cliente e suas contas associadas.
- `PessoaFisica`: Especialização da classe `Cliente` que inclui CPF e data de nascimento.
- `Historico`: Registra todas as transações de uma conta.
- `Transacao`: Interface para transações bancárias.
  - `Deposito`: Implementa a operação de depósito.
  - `Saque`: Implementa a operação de saque.

## Diagrama UML

Aqui está um diagrama UML que representa a estrutura do sistema:

![Diagrama UML](link-para-o-diagrama.png) 

## Requisitos

- Python 3.8+
- Nenhuma biblioteca externa é necessária.

## Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
    ```

2. Navegue até a pasta do projeto:

    ```bash
    cd nome-do-projeto
    ```

## Execução

Para executar o sistema, basta rodar o arquivo principal no terminal:

```bash
python src/resolucao_desafio_parte_1.py
