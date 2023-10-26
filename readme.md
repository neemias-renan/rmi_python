# Sistema de Votação Remota

Este é um exemplo de um sistema de votação remota utilizando Pyro4 em Python. O sistema consiste em um servidor de votação e um cliente que permite aos eleitores adicionar candidatos, votar e visualizar os resultados da votação.

## Pré-requisitos

- Python 3
- Biblioteca Pyro4

## Como Executar

### Passo 1: Verificando se o servidor de nomes está em execução

1. Abra um terminal e navegue até o diretório do projeto.

2. Você pode iniciá-lo com o seguinte comando:

```bash
python -m Pyro4.naming

```

### Passo 2: Iniciando o Servidor de Votação

1. Execute o servidor de votação com o seguinte comando:

```bash
python server.py
```

### Passo 3: Iniciando o Cliente de Votação

1. Abra outro terminal e navegue até o diretório onde o arquivo `client.py` está localizado.

2. Execute o cliente de votação com o seguinte comando:

```bash
python client.py
```

### Passo 4: Interagindo com o Sistema

O cliente irá exibir um menu com opções para interagir com o sistema. Você pode:

- Adicionar Candidato
- Votar
- Ver Resultados
- Sair

Siga as instruções no terminal para realizar as operações desejadas.
