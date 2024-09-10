# 💰 Sistema Bancário - Bootcamp NTT DATA - Engenharia de Dados com Python 

Este projeto faz parte do desafio do **Bootcamp NTT DATA - Engenharia de Dados com Python**, em parceria com a Digital Innovation One (DIO). O objetivo deste desafio é implementar um sistema bancário simples com três operações: depósito, saque e visualização de extrato.

## 🛠 Funcionalidades
### 1. Depósito
- Permite depositar valores positivos.
- Todos os depósitos são armazenados e exibidos na operação de extrato.
### 2. Saque
- Permite realizar até 3 saques diários.
- O valor máximo por saque é de R$ 500,00.
- Se o saldo disponível na conta for insuficiente, o sistema exibirá uma mensagem informando a impossibilidade do saque.
- Todos os saques são armazenados e exibidos na operação de extrato.
### 3. Extrato
- Exibe uma lista detalhada de todos os depósitos e saques realizados.
- Ao final da listagem, o saldo atual da conta é exibido.
- Todos os valores são apresentados no formato `R$ xxx.xx`.

### Regras de Negócio
- Depósitos só podem ser realizados com valores positivos.
- Saques estão limitados a 3 por dia, com um valor máximo de R$ 500,00 por saque.
- O sistema verifica o saldo antes de autorizar o saque.
- O saldo e todas as transações (depósitos e saques) são exibidos no extrato.

### Tecnologias Utilizadas
- **Python:** Linguagem de programação utilizada para desenvolver o sistema.

## ⚙ Como Executar o Projeto
1. Clone o repositório para sua máquina local
   ```bash
    git clone https://github.com/feer-rodriguess90/Sistema-Bancario.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
     cd Sistema-Bancario
   ```
3. Execute o arquivo principal:
   ```bash
     python sistema_bancario.py
   ```

## 🎯 Próximos Passos
Para versões futuras, o sistema poderá ser expandido com funcionalidades adicionais, como transferências, limites personalizados de saque e integração com APIs externas.
  
## ✍🏼 Sugestões
Se tiver sugestões de melhoria, sinta-se à vontade para abrir uma issue ou entrar em contato diretamente. Todo feedback é bem-vindo!

Happy coding! 👩🏽‍💻
