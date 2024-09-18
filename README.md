# Sistema Bancário Simples

## Descrição
Este projeto Python implementa um sistema bancário básico que permite ao usuário realizar depósitos, saques e verificar o extrato. O sistema possui um limite de saques diários e verifica se o valor do saque não excede o saldo disponível ou o limite estabelecido.

## Funcionalidades
* **Depósito:** Permite adicionar valores ao saldo da conta.
* **Saque:** Permite retirar valores do saldo da conta, respeitando o limite diário e o saldo disponível.
* **Extrato:** Exibe o histórico de transações e o saldo atual.

## Como Usar
1. **Executar o código:** Execute o script Python em seu ambiente de desenvolvimento preferido.
2. **Interagir com o menu:** Siga as instruções do menu para realizar as operações desejadas.

## Tecnologias Utilizadas
* **Python:** Linguagem de programação utilizada para desenvolver o projeto.

## Estrutura do Código
* **Variáveis:**
    * `saldo`: Armazena o saldo atual da conta.
    * `limite`: Define o limite máximo por saque.
    * `extrato`: Armazena o histórico das transações.
    * `numero_saques`: Contabiliza o número de saques realizados.
    * `LIMITE_SAQUES`: Define o limite máximo de saques por dia.
* **Funções:**
    * **Não possui funções definidas explicitamente:** O código utiliza estruturas de controle para implementar as funcionalidades.

## Considerações e Melhorias
* **Persistência de dados:** Para um sistema bancário mais robusto, seria necessário implementar um mecanismo para persistir os dados do usuário, como um banco de dados.
* **Tratamento de erros:** Poderia ser adicionado um tratamento de erros mais robusto para lidar com entradas inválidas do usuário.
* **Interface gráfica:** Uma interface gráfica poderia tornar a aplicação mais amigável.
* **Múltiplas contas:** Poderia ser implementada a funcionalidade de criar e gerenciar múltiplas contas.
* **Taxas e juros:** Poderiam ser adicionadas taxas e juros para simular um sistema bancário mais real.

## Contribuições
Contribuições são bem-vindas! Para contribuir, siga estes passos:
1. Fork este repositório.
2. Crie um novo branch para sua feature.
3. Faça as suas alterações e commit.
4. Envie um pull request.

## Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
