Atividade Avaliativa 2 — Web + Mobile (CRUD de Alunos)

Aplicação completa dividida em Web (React + Vite) e Mobile (Expo + React Native), consumindo a API pública de alunos:
https://proweb.leoproti.com.br/alunos

A solução implementa todo o CRUD: listar, visualizar detalhes, adicionar, editar e excluir alunos.

| Método | Endpoint      | Descrição             |
| ------ | ------------- | --------------------- |
| GET    | `/alunos`     | Lista todos os alunos |
| GET    | `/alunos/:id` | Detalhes de um aluno  |
| POST   | `/alunos`     | Cria um aluno         |
| PUT    | `/alunos/:id` | Atualiza um aluno     |
| DELETE | `/alunos/:id` | Remove um aluno       |

Projeto Web (React + Vite)
Tecnologias
React
Vite
React Router DOM
Axios
React Bootstrap
Vitest + React Testing Library


Como executar
Abra um terminal na pasta web.
Instale dependências:
npm install
Rodar em desenvolvimento:
npm run dev

Build:
npm run build

Preview:
npm run previe

Testes
Para rodar testes:
npm run test
Os testes usam Vitest e mockam a camada api (axios). Exemplos já inclusos em src/tests/.

Web 
/ — Tela inicial (lista de alunos)
/alunos/novo — Formulário para adicionar
/alunos/:id — Tela de detalhes
/alunos/:id/editar — Formulário para editar

Mobile (Expo + React Native)
Tecnologias
Expo
React Native
React Navigation
Axios

Como executar
Abra um terminal na pasta mobile.
Instale dependências:
npm install
ou
expo install

Inicie o Metro:
npm run start
Em seguida use expo go no celular (scan QR) ou rode em emulador pelo npm run android / npm run ios.

Navegação (mobile)
Tela Home — lista e botão para novo
Tela Details — detalhes do aluno, editar/excluir/voltar
Tela Form — adicionar / editar

Projeto criado como atividade avaliativa — base: programação web
API pública fornecida por: [proweb.leoproti.com.br](https://proweb.leoproti.com.br/swagger-ui/index.html)
