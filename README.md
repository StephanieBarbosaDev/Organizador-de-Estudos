# Organizador de Estudos

Aplicação web desenvolvida para auxiliar estudantes na organização de tarefas acadêmicas e no gerenciamento de sessões de estudo, oferecendo ferramentas para acompanhar atividades, controlar prazos e administrar o tempo de dedicação aos estudos.

##  Objetivo

O projeto tem como objetivo facilitar a rotina acadêmica, proporcionando uma maneira simples e prática de organizar compromissos, acompanhar tarefas e manter uma rotina de estudos mais estruturada.

##  Funcionalidades

- **Cadastro de usuário:** identificação do estudante.
- **Gerenciamento de tarefas:** cadastro, edição, exclusão e pesquisa de tarefas.
- **Controle de atividades:** acompanhamento do status das tarefas (Pendente, Em Andamento e Concluída).
- **Sessões de estudo:** cadastro e gerenciamento de sessões, com descrição, data, duração e observações.
- **Cronômetro:** controle do tempo de estudo com opções para iniciar, pausar e continuar.
- **Armazenamento local:** utilização do LocalStorage para salvar informações no navegador.

##  Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- LocalStorage
- Jest (testes automatizados)

##  Estrutura do projeto

```text
OrganizadorDeEstudos/
│
├── css/
│   ├── estilo.css
│   └── inicio.css
│
├── imagem/
│   ├── imgestudos.png
│   └── imgtarefas.png
│
├── js/
│   ├── cadastro.js
│   ├── cronometro.js
│   ├── estudos.js
│   └── tarefas.js
│
├── src/
│   ├── estudoLogica.js
│   ├── tarefaLogica.js
│   ├── tempo.js
│   └── validacoes.js
│
├── test/
│
├── cadastro.html
├── estudos.html
├── estudocronometro.html
├── inicio.html
├── index.html
└── tarefas.html
```

##  Como executar

1. Faça o download ou clone este repositório.
2. Abra a pasta do projeto.
3. Execute o arquivo `index.html` no navegador.
4. Clique em começar e explore as funcionalidades.

##  Testes

O projeto utiliza Jest para realizar testes automatizados de algumas funcionalidades, como gerenciamento de tarefas, sessões de estudo, formatação de tempo e validações.

Para executar os testes:

```bash
npm install
npm test
```

##  Armazenamento

As informações são armazenadas localmente por meio do LocalStorage do navegador. Portanto, os dados ficam disponíveis no navegador utilizado, sem necessidade de conexão com um banco de dados.

##  Desenvolvimento

Projeto desenvolvido com o objetivo de praticar e aprimorar conhecimentos em desenvolvimento web, lógica de programação, manipulação de dados e testes automatizados.

---
