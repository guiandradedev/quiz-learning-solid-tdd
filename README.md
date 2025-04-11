
# Quiz Learning - SOLID & TDD

Este projeto é um sistema backend de questionários desenvolvido com Node.js e TypeScript, com o objetivo de aplicar os princípios de SOLID, TDD e arquitetura de software limpa. Utiliza Prisma como ORM e MySQL como banco de dados.

## 💡 Objetivo

Este projeto nasceu com o propósito de consolidar meus aprendizados em backend em 2023 após 3 anos de estudos. Durante o período de férias da faculdade, aproveitei para aprofundar meus conhecimentos práticos em:

- Organização de código com foco em manutenibilidade e escalabilidade;
- Princípios de arquitetura limpa (Clean Architecture);
- Aplicação dos princípios do SOLID;
- Desenvolvimento guiado por testes (TDD);
- Boas práticas com Git e escrita de código em inglês.

Mais do que um simples CRUD, essa aplicação representa minha dedicação à melhoria contínua e minha paixão por desenvolvimento backend.

## 🎥 Vídeo de Apresentação

<div align="center">
  <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:7092625403541897217?compact=1" height="399" width="504" frameborder="0" allowfullscreen="" title="Publicação incorporada"></iframe>
</div>

## 🧠 Funcionalidades

- Criação de quizzes de múltipla escolha por usuários;
- Participação de outros usuários nos quizzes, com cálculo de pontuação baseado nas respostas corretas;
- Estrutura modular seguindo princípios de DDD e SOLID;
- Testes automatizados utilizando TDD.

## 🛠️ Tecnologias Utilizadas

- Node.js
- TypeScript
- Prisma ORM
- MySQL
- Docker & Docker Compose
- Insomnia (para testes de requisições)

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/guiandradedev/quiz-learning-solid-tdd.git
   cd quiz-learning-solid-tdd
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Configure o arquivo `.env` com base no `.env.example`.

4. Execute as migrações do banco de dados:
   ```bash
   npx prisma migrate dev
   ```

5. Inicie a aplicação:
   ```bash
   npm run dev
   ```

## 🔍 Testes

Para executar os testes automatizados:
```bash
npm run test
```

## 📌 Próximas Implementações

- Visualização das respostas submetidas em um formulário;
- Prevenção de múltiplas respostas ao mesmo formulário por um único usuário.

## 📄 Licença

Este projeto está sob a licença MIT.

---

Para mais detalhes sobre o projeto e minha jornada de aprendizado, confira minha publicação no LinkedIn:  
[Publicação de Guilherme Andrade](https://www.linkedin.com/posts/guiandradedev_carreira-ti-backend-activity-7092626182227079168-CbXW)
<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:7092625403541897217?collapsed=1" height="399" width="504" frameborder="0" allowfullscreen="" title="Publicação incorporada"></iframe>

Caso tenha interesse em contribuir ou fornecer feedback, sinta-se à vontade para abrir uma issue ou pull request.
