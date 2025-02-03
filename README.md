# ContaBanco

## Descrição do Projeto

O projeto **ContaBanco** é um programa simples desenvolvido em Java para praticar conceitos fundamentais de sintaxe, manipulação de entrada e saída via terminal, e uso da classe `Scanner`. Ele permite que o usuário cadastre uma conta bancária informando alguns dados essenciais e, ao final, recebe uma mensagem confirmando a criação da conta.

## Funcionalidades
- Solicita ao usuário os seguintes dados:
  - **Número da conta** (inteiro)
  - **Agência** (texto)
  - **Nome do cliente** (texto)
  - **Saldo** (decimal)
- Exibe uma mensagem final de confirmação com os dados inseridos.

## Tecnologias Utilizadas
- **Linguagem:** Java
- **Ferramentas:** Terminal, Scanner, String concatenation

## Como Executar o Projeto
1. Certifique-se de ter o **Java** instalado em seu sistema.
2. Clone este repositório ou copie o código fonte.
3. Compile o programa:
   ```sh
   javac ContaTerminal.java
   ```
4. Execute o programa:
   ```sh
   java ContaTerminal
   ```
5. Insira as informações conforme solicitado pelo terminal.

## Exemplo de Uso
```
Por favor, digite o número da conta:
1021
Por favor, digite o número da agência:
067-8
Por favor, digite seu nome:
MARIO ANDRADE
Por favor, digite seu saldo:
237.48

Olá MARIO ANDRADE, obrigado por criar uma conta em nosso banco, sua agência é 067-8, conta 1021 e seu saldo 237.48 já está disponível para saque.
```

## Autor
Desenvolvido por **Nicolas Valle** como parte dos estudos em Java.

## Licença
Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

