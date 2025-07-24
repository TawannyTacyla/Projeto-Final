🧠 MindStack – Organizador Cognitivo com Gestão de Memória

O MindStack é um sistema interativo em Python que simula o funcionamento da memória humana para organizar tarefas pessoais, acadêmicas e profissionais. Ele usa múltiplas estruturas de dados clássicas (listas, pilhas, filas, árvores, hash tables e heaps) para modelar diferentes componentes do processo de organização mental. Ideal para estudos de estrutura de dados com aplicação prática.

📌 Objetivo do Projeto

Muitas pessoas enfrentam dificuldades para organizar tarefas, priorizar atividades e manter o foco no que é realmente importante. O MindStack foi criado com o objetivo de auxiliar nesse processo, simulando a lógica da mente humana na organização do dia a dia.

⚙️ Funcionalidades

1. Registrar Tarefa

- O usuário descreve a tarefa, seleciona uma categoria (Estudo, Trabalho ou Pessoal), tempo estimado e prioridade.
- A tarefa é armazenada em várias estruturas para análise e planejamento posterior.

2. Mostrar Tarefas Registradas

- Lista todas as tarefas já registradas com seus metadados (tempo, prioridade, categoria).

3. Planejar Execução

- Utiliza um algoritmo de classificação com heapq para organizar as tarefas mais urgentes na fila de execução.

4. Executar Próxima Tarefa

- Retira a próxima tarefa da fila (estrutura de fila deque) e a exibe como sendo executada.

5. Desfazer Última Tarefa

- Utiliza uma pilha para permitir o "desfazer" da última ação registrada.

6. Ver Categorias (Árvore Simulada)

- Apresenta uma estrutura de árvore (simulada com dicionários) com categorias e exemplos.

7. Encerrar Sistema

- Opção para sair do sistema com uma mensagem final.


🧪 Testes Sugeridos

- Registre tarefas com diferentes prioridades e tempos para testar a ordem automática de execução.
- Use a opção "Desfazer" e observe a remoção da última tarefa.
- Planeje a execução e execute algumas tarefas, verificando a ordem de retirada da fila.
