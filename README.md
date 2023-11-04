# EatHealth

## Visão Geral

Este documento descreve as funcionalidades e o processo de implementação do sistema para nutricionistas. O sistema foi desenvolvido utilizando as seguintes linguagens e tecnologias:

- PHP: linguagem de programação principal para o desenvolvimento do sistema
- JavaScript: utilizado para aprimorar a interatividade e a experiência do usuário
- HTML: responsável pela estrutura e marcação do sistema
- CSS: utilizado para estilizar e personalizar a aparência do sistema
- MySQL: banco de dados utilizado para armazenar e gerenciar as informações dos clientes e planos alimentares.

## Instalação

A seguir, estão os passos necessários para instalar e configurar o sistema:

1. Certifique-se de ter um servidor web configurado com suporte para PHP e MySQL.
2. Faça o download dos arquivos do sistema para o diretório raiz do seu servidor web.
3. Crie um banco de dados MySQL para o sistema e execute o arquivo de script SQL fornecido para criar as tabelas necessárias.
4. Abra o arquivo `geral.php` e defina o local do aplicativo.
5. Abra o arquivo `conn.php` e insira as informações de conexão com o banco de dados.

Após seguir esses passos, o sistema estará pronto para ser utilizado.

## Funcionalidades do Sistema para Nutricionistas

### Implementar autenticação para nutricionistas no painel

- Criação de um sistema de login seguro para nutricionistas com autenticação por nome de usuário e senha.
- Criar a interface do painel do nutricionista.

### Desenvolver a interface do painel de controle para os nutricionistas

- Proporcionar acesso às funcionalidades do sistema.
- Listar clientes cadastrados no painel.

### Exibir a lista de clientes cadastrados para o nutricionista

- Implementar a opção para cadastrar um novo cliente.
- Criar um formulário para que o nutricionista possa cadastrar informações de novos clientes.

### Adicionar funcionalidade para editar e excluir clientes

- Permitir que o nutricionista edite e exclua informações de clientes conforme necessário.
- Criar um formulário para cadastrar informações de clientes.

### Armazenar informações de clientes de forma segura no banco de dados

- Garantir que as informações dos clientes sejam armazenadas de forma segura no banco de dados, seguindo as melhores práticas de segurança.
- Associar clientes aos nutricionistas.

### Estabelecer uma associação entre os clientes e os nutricionistas

- De modo que cada nutricionista tenha acesso apenas às informações de seus próprios clientes.
- Implementar um formulário para criar planos alimentares para clientes.

### Criar um formulário que permita ao nutricionista criar planos alimentares personalizados

- Para seus clientes.
- Armazenar os planos alimentares no banco de dados, associados aos clientes correspondentes.

### Armazenar os planos alimentares no banco de dados

- E associá-los aos clientes correspondentes.
- Adicionar funcionalidades para editar e excluir planos alimentares.

### Permitir que o nutricionista edite e exclua planos alimentares existentes

- Gerar relatórios a partir dos planos alimentares

### Desenvolver uma função para gerar relatórios detalhados

- A partir dos planos alimentares, incluindo informações sobre os alimentos e as calorias.
- Criar uma interface para gerar relatórios com todos os planos alimentares dos clientes.

### Criar uma interface que permita ao nutricionista gerar relatórios

- Com todos os planos alimentares de seus clientes.
- Implementar a geração de relatórios em formato legível para exportação ou visualização.

### Desenvolver a funcionalidade de geração de relatórios

- Em formatos legíveis, como PDF ou Excel, para exportação ou visualização.
- Calcular as calorias consumidas com base nos planos alimentares dos clientes.

### Implementar um cálculo de calorias consumidas

- Com base nos planos alimentares dos clientes.
- Classificar os alimentos mais consumidos por calorias e apresentar o ranking ao nutricionista.