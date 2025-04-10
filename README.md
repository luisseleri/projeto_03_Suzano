💰 Sistema Bancário V2 - Bootcamp Suzano
Este projeto é a versão 2 do desafio proposto no Bootcamp da Suzano. Nessa versão, o sistema bancário foi refatorado e aprimorado com integração de funções e uso de listas para o gerenciamento de usuários e contas.

🔄 Funcionalidades
O sistema oferece um menu interativo com as seguintes opções:

[d] Depositar — Permite realizar depósitos em conta.

[s] Sacar — Permite realizar saques com controle de limite e quantidade.

[e] Extrato — Mostra todas as movimentações financeiras da conta.

[nu] Novo usuário — Cadastra um novo usuário no sistema.

[nc] Nova conta — Cria uma conta para um usuário já cadastrado.

[lc] Listar contas — Exibe a lista de contas cadastradas.

[q] Sair — Encerra a aplicação.

👤 Cadastro de Usuários
Cada usuário é identificado unicamente pelo CPF.

São armazenadas informações como: nome completo, data de nascimento e endereço.

🏦 Contas Bancárias
Cada conta é vinculada a um usuário já existente.

As contas possuem um número sequencial e são associadas à agência 0001.

⚙️ Regras do Sistema
Saques possuem um limite de R$ 500,00 por operação.

O usuário pode realizar até 3 saques por dia.

Depósitos e saques válidos atualizam o extrato automaticamente.

Operações inválidas são notificadas ao usuário com mensagens apropriadas.

🛠️ Tecnologias Utilizadas
Python 3

Biblioteca padrão textwrap para melhor formatação visual dos menus e saídas.

▶️ Como executar
Certifique-se de ter o Python 3 instalado.

Salve o código em um arquivo, por exemplo: sistema_bancario_v2.py

Execute no terminal com:

bash
Copiar
Editar
python sistema_bancario_v2.py
📁 Estrutura do Código
O sistema é baseado em funções puras com passagem clara de argumentos.

Utiliza parâmetros nomeados e posicionais para maior legibilidade.

As listas usuarios e contas armazenam os dados em memória durante a execução.

📌 Melhorias em relação à Versão 1
Separação total entre funções e lógica principal (main).

Criação de funções específicas para criação e listagem de usuários e contas.

Uso de listas para simular persistência em memória dos dados.

Código modular, mais fácil de testar e manter.
