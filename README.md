![shutterstock_1888907947](https://github.com/user-attachments/assets/dcf3de70-0fd5-4b98-b027-8523a46fa902)
# Bitbuy, sistema de compra e venda de criptomoedas

## Objetivo:
### O sistema **Bitbuy** permite:
- **Usuários**: Comprar, vender e consultar cotações das criptomoedas: Bitcoin, Ethereum e Ripple. Além de cadastrar, logar, adicionar e sacar fundos à carteira, acessar o saldo e o extrato de sua conta.
- **Administradores**: Gerenciar o sistema, incluindo a adição e exclusão de usuários, cadastro e exclusão de novas criptomoedas, consulta de saldo e extrato de qualquer investidor e atualização das cotações de criptomoedas.

## Formas de compilação
### Para compilar e executar o código como usuario, deve-se:
1. Acessar o terminal de sua máquina
2. Digitar gcc main_usuario.c funcoes_usuario.c -o usuario para compilar o programa
3. Executar .\usuario.exe

### Para compilar e executar o código como administrador, deve-se:
1. Acessar o terminal de sua máquina
2. Digitar gcc main_admin.c funcoes_admin.c funcoes_usuario.c -o admin para compilar o programa
3. Executar .\admin.exe
   
### Além de, se preferir, abrir o código no site [Replit](https://replit.com), onde o programa é compilado e executado sem necessidade de baixar o gcc, apenas usando os comando escritos acima.

## Uso do programa
### **Para o Usuário:**
1. Ao abrir o programa do usuário:
   - Escolha entre as opções: **Cadastrar**, **Logar** ou **Sair**.
2. Após logar, o menu de opções será exibido. As funcionalidades disponíveis são:
   - **Depósito**: Adicionar fundos à carteira.
   - **Saque**: Retirar fundos da carteira.
   - **Compra de Criptomoedas**: Comprar Bitcoin, Ethereum ou Ripple utilizando os fundos disponíveis.
   - **Venda de Criptomoedas**: Converter Bitcoin, Ethereum ou Ripple para fundos reais.
   - **Consultar Saldo**: Ver o saldo em reais e criptomoedas.
   - **Consultar Extrato**: Exibir o histórico de transações.
   - **Atualizar Cotações**: Atualizar os valores de mercado das criptomoedas.
3. Para salvar as alterações, escolha a opção **Sair** no menu.


### **Para o Administrador:**
1. Ao abrir o programa do administrador:
   - Faça login utilizando a senha de administrador.
   - Login: admin.
   - Senha: 123456.
2. O menu administrativo será exibido. As funcionalidades disponíveis são:
   - **Adicionar Usuário**: Cadastrar um novo usuário no sistema.
   - **Excluir Usuário**: Remover um usuário do sistema.
   - **Consultar Saldo de um Usuário**: Informar o CPF de um investidor e visualizar o saldo da conta.
   - **Consultar Extrato de um Usuário**: Informar o CPF de um investidor e visualizar o extrato completo de transações.
   - **Cadastrar Nova Criptomoeda**: Adicionar uma nova criptomoeda ao sistema, informando nome, cotação inicial, taxa de compra e taxa de venda.
   - **Excluir Criptomoeda**: Remover uma criptomoeda existente. O sistema exibirá os detalhes da moeda e pedirá confirmação para exclusão.
   - **Atualizar Cotações de Criptomoedas**: Atualizar os valores de mercado das criptomoedas.
3. Ao finalizar, escolha a opção **Sair** para encerrar o programa.

## Autores
### José Reginaldo de Lima Junior
### R.A: 24.124.017-5
### Gabriel Oliveira Alves de Sá
### R.A: 24.124.026-6
