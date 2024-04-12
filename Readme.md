# Projeto: Sistema de Gerenciamento de Tarefas

### Descrição:
Desenvolva um sistema de gerenciamento de tarefas simples, onde os usuários possam criar, visualizar, atualizar e excluir suas tarefas. O sistema deve ser construído utilizando Node.js para o backend e qualquer framework de sua escolha para o frontend (como React.js, Vue.js ou Angular).
### Recursos do Sistema:

- Autenticação de Usuário: Permita que os usuários se cadastrem, façam login e logout. As tarefas devem estar associadas aos usuários logados.
- CRUD de Tarefas: Os usuários devem ser capazes de criar, visualizar, atualizar e excluir suas próprias tarefas.
Categorias de Tarefas: Permita que os usuários classifiquem suas tarefas em diferentes categorias, como "Trabalho", "Estudos", "Pessoal", etc.
- Prioridades: Os usuários devem poder definir a prioridade de suas tarefas (baixa, média, alta).
- Data de Vencimento: Permita que os usuários adicionem uma data de vencimento às suas tarefas.
- Notificações: Implemente um sistema de notificação para lembrar os usuários sobre tarefas pendentes ou datas de vencimento próximas.
- Interface Amigável: Desenvolva uma interface de usuário intuitiva e responsiva para facilitar a interação dos usuários com o sistema.

### Requisitos Técnicos:
Use Node.js para criar o backend do aplicativo, utilizando um framework como Express.js para gerenciar rotas e requisições HTTP.
Utilize um banco de dados para armazenar informações de usuários e tarefas. Você pode escolher entre bancos de dados relacionais (como MySQL, PostgreSQL) ou não relacionais (como MongoDB).
Implemente autenticação de usuário utilizando tokens JWT (JSON Web Tokens) para proteger as rotas que exigem autenticação.
Desenvolva APIs RESTful para manipular operações CRUD (Create, Read, Update, Delete) de tarefas.
Utilize validação de entrada para garantir a integridade dos dados enviados pelos usuários.
Desafios Extras (Opcional):

- Testes Unitários e de Integração: Escreva testes para garantir que seu aplicativo funcione corretamente e que novas alterações não quebrem funcionalidades existentes.
- WebSocket para Notificações em Tempo Real: Implemente WebSocket para enviar notificações em tempo real aos usuários sobre tarefas pendentes ou próximas datas de vencimento.
Implementação de Paginação e Filtros: Permita que os usuários paginem e filtrem suas tarefas com base em diferentes critérios, como categoria, prioridade ou data de vencimento.
- Internacionalização (i18n): Torne seu aplicativo multilíngue, permitindo que os usuários escolham seu idioma preferido.
