### 🏠 Cadastro de Imóveis

Este é um sistema simples de cadastro de imóveis desenvolvido em JavaScript. Ele permite que o usuário registre imóveis com informações detalhadas, visualize a lista de imóveis cadastrados e saia do programa quando desejar.

### 🚀 Funcionalidades

✅ Adicionar um novo imóvelO usuário pode inserir informações como:

Nome do proprietário

Quantidade de quartos

Quantidade de banheiros

Se possui garagem (Sim/Não)

✅ Listar imóveis cadastradosExibe uma lista de todos os imóveis cadastrados com suas respectivas informações.

✅ Sair do programaEncerra a execução do sistema.

### 🔍 Como o Código Funciona

📌 O programa utiliza um array imoveis para armazenar os dados dos imóveis cadastrados.
📌 Um loop do...while mantém a execução ativa até que o usuário escolha a opção de sair.
📌 O usuário interage por meio do prompt() e escolhe entre as opções disponíveis:

Opção 1: Inserir um novo imóvel, preenchendo os detalhes solicitados.

Opção 2: Exibir todos os imóveis cadastrados.

Opção 3: Sair do sistema.

📌 A opção escolhida é processada dentro de um switch, e as ações correspondentes são executadas.
📌 Antes de salvar um imóvel, é exibida uma confirmação via confirm(). Se o usuário confirmar, os dados são adicionados ao array imoveis.
