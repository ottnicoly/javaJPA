## Crie um projeto novo SpringBoot com JPA. <br/> Desenvolva uma API Rest para manipular a tabela Tarefa.

### A tabela tarefa deve conter os seguintes campos:

Identificador único<br/>
Título<br/>
Descrição longa<br/>
Finalizado<br/>
Data Prevista de Finalização<br/>
Data de Finalização<br/>

#### A API Rest deve fornecer os seguintes endpoints:

Inserir<br/>
Consultar todas as tarefas<br/>
Consultar uma tarefa pelo id<br/>
Atualizar uma tarefa<br/>
Consultar todas as tarefas não finalizadas<br/>
Consultar todas as tarefas finalizadas<br/>
Deletar uma tarefa pelo id<br/>
Consultar todas as tarefas atrasadas<br/>
Consultar todas as tarefas não finalizadas entre duas datas (início e fim)<br/>
Finalizar uma tarefa<br/>

#### Algumas regras devem ser obedecidas:<br/>
É obrigatório ter na tarefa o título e a data prevista de finalização<br/>
Uma tarefa finalizada não pode ser modificada ou excluída.<br/>
O título da tarefa deve conter pelo menos 5 caracteres.
