## 🧠 Organizador Cognitivo com Gestão de Memória

### 📍 Problema para Resolver (Inovação)

Em um mundo cada vez mais acelerado, é comum que pessoas enfrentem **sobrecarga mental**, **procrastinação** e **desorganização de tarefas**. Inspirado no funcionamento da mente humana que possui diferentes níveis de memória e sistemas de priorização. O **projeto** propõe uma solução inovadora: um **organizador cognitivo digital**, que simula elementos da cognição humana por meio de estruturas de dados da ciência da computação.

Esse projeto visa ajudar usuários a **registrar, classificar, priorizar, planejar e executar tarefas** de forma intuitiva, didática e funcional, promovendo uma experiência que imita a memória de curto prazo, o processo decisório e a categorização mental.

A ideia surgiu da junção entre:

- A observação de como esquecemos tarefas importantes com frequência;
- A necessidade de sistemas que ajudem na produtividade sem complexidade;
- A vontade de aplicar conceitos de estruturas de dados em um contexto real.

🔍 **Por que ele é relevante?**

- Permite visualizar como diferentes estruturas de dados trabalham juntas;
- É um modelo inicial para aplicativos de organização pessoal mais robustos;
- Estimula o uso da inteligência computacional na solução de problemas cognitivos;
- Pode evoluir para versões com inteligência artificial, persistência de dados e interface gráfica.

---

### 🧪 Roteiro para Resolver (Criação)

Para transformar esse desafio em solução, foi seguido o seguinte plano:

1. **Modelar a cognição humana com estruturas de dados**:
   - Memória de curto prazo (últimos pensamentos): pilha;
   - Organização hierárquica de assuntos: árvore;
   - Execução de tarefas: fila;
   - Registro geral: lista;
   - Acesso rápido a detalhes: hash table;
   - Prioridades e urgências: heap.

2. **Criar funções interativas** que permitam:
   - Registrar tarefas;
   - Visualizar e desfazer registros;
   - Planejar automaticamente uma fila de execução;
   - Executar tarefas com base na prioridade.

3. **Oferecer uma interface de linha de comando simples**, com menu e opções acessíveis.

---

### 🧱 Estruturas Utilizadas

| Estrutura de Dados | Função no Projeto |
|--------------------|-------------------|
| **Lista** (`caixa_entrada`) | Armazena todas as tarefas registradas |
| **Pilha** (`memoria_curta`) | Simula memória de curto prazo (últimas tarefas) |
| **Fila** (`fila_execucao`) | Define a ordem de execução das tarefas |
| **Árvore simulada** (`categorias`) | Organiza as tarefas por área temática |
| **Hash Table** (`metadados`) | Guarda dados específicos de cada tarefa |
| **Heap (fila de prioridade)** (`heap_prioridade`) | Garante execução ordenada por urgência |

---

### 💻 Script – Implementação

O sistema é implementado em **Python** e conta com as seguintes funções principais:

- `registrar_tarefa()`: recebe os dados da tarefa, armazena em múltiplas estruturas e calcula a urgência com base em tempo e prioridade.
- `planejar_execucao()`: utiliza o heap para ordenar as tarefas e armazená-las na fila.
- `executar_tarefa()`: simula a realização da tarefa.
- `desfazer_ultima()`: remove a tarefa mais recente registrada.
- `mostrar_tarefas()`: exibe todas as tarefas registradas e seus metadados.
- `exibir_categorias()`: mostra a árvore simulada com categorias e subtarefas.

A interface principal (`main()`) apresenta um menu para interação em tempo real com o sistema.
