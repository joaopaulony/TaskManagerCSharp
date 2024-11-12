# Gerenciador de Tarefas

Este é um aplicativo de console simples em C# para gerenciar tarefas diárias. Ele permite que os usuários cadastrem, listem, excluam e alterem o status de suas tarefas (concluídas ou não concluídas).

## Funcionalidades
- **Cadastro de Tarefas**: Adiciona novas tarefas com um nome e define o status inicial como "não concluída".
- **Listagem de Tarefas**: Exibe todas as tarefas cadastradas com o status atual (concluída ou não concluída).
- **Exclusão de Tarefas**: Permite remover uma tarefa específica da lista.
- **Alteração de Status**: Alterna o status de uma tarefa entre "concluída" e "não concluída".

## Tecnologias Utilizadas
- **C#**
- **.NET Core Console Application**

## Como Executar o Projeto

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
2. Abra o projeto em sua IDE preferida (como Visual Studio ou Visual Studio Code).

3.Compile e execute o projeto:

No Visual Studio, pressione F5.
No Visual Studio Code, execute o comando dotnet run.

## Estrutura do Código
Classe Tarefa
A classe Tarefa representa uma tarefa e contém:

Nome: o nome da tarefa.
Concluida: um bool que indica se a tarefa está concluída.

## Menu Principal
O menu principal oferece ao usuário as seguintes opções:

Cadastrar uma nova tarefa
Listar todas as tarefas
Excluir uma tarefa
Alterar o status de uma tarefa (marcar como concluída ou não concluída)
Sair do programa

## === Gerenciador de Tarefas ===
1 - Cadastrar tarefa
2 - Listar tarefas
3 - Excluir tarefa
4 - Marcar/Desmarcar conclusão
5 - Sair
Escolha uma opção: 1

Digite o nome da tarefa: Estudar para o exame
Tarefa cadastrada com sucesso!

Escolha uma opção: 2

## === Lista de Tarefas ===
1. Tarefa: Estudar para o exame, Status: Não Concluída

Escolha uma opção: 4
Digite o número da tarefa para alterar o status: 1
Status da tarefa 'Estudar para o exame' alterado com sucesso!

## Objetivo do Projeto
Este projeto foi desenvolvido para praticar conceitos básicos de:

Programação orientada a objetos em C#
Manipulação de listas e controle de fluxo
Desenvolvimento de um CRUD simples em uma interface de console

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma Issue ou enviar um Pull Request.

## Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para obter mais detalhes.
