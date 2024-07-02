# Teste Técnico ReactJS

## Descrição do Projeto

Você foi contratado para criar uma aplicação simples de gerenciamento de tarefas ("To-Do List") com ReactJS. A aplicação deve permitir que os usuários adicionem, editem, excluam e marquem tarefas como concluídas. Além disso, a aplicação deve buscar uma lista inicial de tarefas de uma API fictícia.

## Requisitos

### Configuração Inicial
- Use `create-react-app` para configurar o projeto.
- Configure o ESLint e o Prettier para manter a consistência do código.

### Componentes
- Crie os seguintes componentes:
  - `TaskList`: Lista de todas as tarefas.
  - `TaskItem`: Um item individual de tarefa.
  - `TaskForm`: Formulário para adicionar/editar tarefas.
  - `Header`: Cabeçalho da aplicação.

### Funcionalidades
- **Adicionar Tarefa**: Usuários devem ser capazes de adicionar uma nova tarefa.
- **Editar Tarefa**: Usuários devem ser capazes de editar uma tarefa existente.
- **Excluir Tarefa**: Usuários devem ser capazes de excluir uma tarefa.
- **Marcar como Concluída**: Usuários devem ser capazes de marcar uma tarefa como concluída/incompleta.
- **Listar Tarefas**: As tarefas devem ser buscadas de uma API fictícia quando a aplicação for carregada.

### Estado e Hooks
- Use hooks (`useState`, `useEffect`, `useContext`) para gerenciar o estado da aplicação.
- Use Context API para gerenciar o estado global (lista de tarefas).

### Roteamento
- Use `react-router-dom` para gerenciar rotas.
- Crie as seguintes rotas:
  - `/`: Exibe a lista de tarefas.
  - `/task/:id`: Exibe o formulário para editar uma tarefa específica.

### Estilização
- Use CSS Modules ou Styled Components para estilizar a aplicação.

## API Fictícia

Use a seguinte URL para buscar a lista inicial de tarefas: `https://jsonplaceholder.typicode.com/todos`. Filtre para trazer apenas os 10 primeiros itens.

## Critérios de Avaliação

- **Requisitos de negócio**: Se o candidato entendeu corretamentos os requisitos de negócio. 
- **Funcionalidade**: A aplicação atende a todos os requisitos funcionais?
- **Código**: O código é limpo, bem-organizado e segue as melhores práticas de desenvolvimento?
- **Uso de Hooks e Context API**: Os hooks e a Context API são usados de maneira eficaz para gerenciar o estado da aplicação?
- **Roteamento**: O roteamento é implementado corretamente e de forma eficiente?
- **Estilização**: A aplicação é visualmente agradável e responsiva?

## Dicas para o Candidato

- Certifique-se de seguir as melhores práticas do ReactJS.
- Escreva comentários claros e concisos no código, se necessário.
- Garanta que a aplicação esteja responsiva e visualmente agradável.
- Valide os dados do formulário antes de adicioná-los à lista de tarefas.
- Use commits pequenos e frequentes com mensagens claras.

## Envio do Projeto

- Crie um repositório no GitHub e faça commits frequentes com mensagens claras.
- Envie o link do repositório e qualquer instrução adicional necessária para rodar o projeto.
- Envie o link para marcelo@sellers.com.br

Boa sorte!
