# To-Do List App em Flutter

Este é um aplicativo simples de lista de tarefas (To-Do List) desenvolvido em Flutter. Ele permite que os usuários adicionem, visualizem e excluam tarefas de forma fácil e intuitiva.

## Funcionalidades

- **Adicionar Tarefas**: Os usuários podem adicionar novas tarefas digitando o nome da tarefa e pressionando o botão de adicionar.
- **Listar Tarefas**: As tarefas são exibidas em uma lista, mostrando o título da tarefa e a data de criação.
- **Excluir Tarefas**: As tarefas podem ser excluídas deslizando o item para o lado e pressionando o botão de deletar.
- **Limpar Todas as Tarefas**: Há um botão para limpar todas as tarefas de uma só vez.
- **Contador de Tarefas**: O aplicativo exibe o número de tarefas pendentes.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **`main.dart`**: Ponto de entrada do aplicativo. Configura e inicializa o aplicativo.
- **`todo_list_page.dart`**: Contém a lógica principal da página de lista de tarefas, incluindo a adição e remoção de tarefas.
- **`todo_list_item.dart`**: Define o widget que representa cada item da lista de tarefas, incluindo a funcionalidade de deslizar para excluir.

## Como Executar o Projeto

1. **Pré-requisitos**:
   - Certifique-se de ter o Flutter instalado em sua máquina. Caso não tenha, siga as instruções de instalação no [site oficial do Flutter](https://flutter.dev).

2. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/D0pp13R21/Todo-List-Flutter
   cd Todo-List-Flutter