# BlockChain

Um código que simula uma blockchain, juntamente com um `Banco.py` que cria contas e realiza transações entre as contas. Todas as transações e adições de dinheiro são incluídas na blockchain.

## Estrutura do Projeto
Aqui está um diagrama que ilustra a estrutura do projeto:
<p align="center">
  <img src="https://github.com/CarlosMikaelCardoso/BlockChain/blob/main/blockchain.jpeg?raw=true" alt="Diagrama da Estrutura do Projeto" width="400">
</p>

- **blockchain.txt**: Armazena os dados da blockchain.
- **contas.txt**: Armazena as informações das contas criadas.

## Como Usar

1. **Criar Contas**: Execute o script `Banco.py` para criar novas contas.
2. **Realizar Transações**: Use o `Banco.py` para realizar transações entre as contas.
3. **Verificar Blockchain**: Todas as transações e adições de dinheiro são registradas na blockchain, que pode ser visualizada no arquivo `blockchain.txt`.

## Requisitos

- Python 3.x

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/CarlosMikaelCardoso/BlockChain.git
   cd BlockChain
   python Banco.py
