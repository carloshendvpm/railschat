# TurboChat Rails

Aplicação desenvolvida no desafio passaporte Real Seguro Viagem. A aplicação utiliza o Turbo Rails para melhorar a experiência do usuário, o Devise para autenticação de usuários e o Tailwind CSS juntamente com o DaisyUI para estilização.

## Funcionalidades

A aplicação possui as seguintes funcionalidades:

- Autenticação de usuários com Devise: os usuários podem se registrar, fazer login e fazer logout na aplicação.
- Criação e gerenciamento de grupos de chat: os usuários podem criar grupos de chat, adicionar membros aos grupos existentes e gerenciar as configurações dos grupos.
- Chat em tempo real: os membros dos grupos podem enviar mensagens em tempo real e ver as mensagens dos outros membros atualizadas automaticamente.
- Estilização com Tailwind CSS e DaisyUI: a interface da aplicação é estilizada usando o Tailwind CSS, um framework de CSS utilitário, com o auxílio do DaisyUI para adicionar componentes pré-estilizados.

## Requisitos do sistema

Certifique-se de ter as seguintes dependências instaladas em seu sistema:

- Ruby 3.1.3 ou superior
- Rails 7.0.5 ou superior
- Banco de dados (como o sqlite)

## Configuração do ambiente

Siga estas etapas para configurar o ambiente da aplicação:

1. Clone este repositório para sua máquina local.
2. Navegue até o diretório da aplicação.

```bash
cd railschat
```

3. Instale as dependências do Ruby executando o comando:

```bash
bundle install
```

4. Crie e migre o banco de dados:

```bash
rails db:create
rails db:migrate
```

6. Inicie o servidor local:

```bash
rails s
```

A aplicação estará disponível em `http://localhost:3000`.

## Uso

1. Acesse a página inicial em seu navegador.
2. Crie uma conta ou faça login, se já tiver uma conta existente.
3. Crie um novo grupo de chat ou junte-se a um grupo existente.
4. No grupo de chat, você pode enviar mensagens e ver as mensagens dos outros membros do grupo.
