<h1 align="center">
  <img src="https://i.ibb.co/WvQrpXDy/Knowledge-Logo.png" alt="Knowledge Logo" width="100" style="border-radius:50%;"/><br/>
  Knowledge
</h1>

<p align="center">
  <strong>Gerador de questões via IA que transforma textos em simulados personalizados para identificar lacunas de aprendizado.</strong><br/>
  <sub>Desenvolvido por <strong>Eriky Lima</strong></sub>
</p>

---

## Sobre o Projeto

O **Knowledge** é um sistema educacional que utiliza **inteligência artificial (Google Gemini)** para transformar conteúdos em **quizzes personalizados**, permitindo identificar lacunas de aprendizado e reforçar o conhecimento de forma prática.

O objetivo é oferecer uma **experiência de aprendizado interativa e eficiente**, integrando front-end e back-end de forma clara e objetiva.

> “Aprender de forma inteligente é conhecer onde você precisa melhorar.”

---

## Funcionalidades Principais

- ✔️ **Geração de quizzes** a partir de temas ou textos  
- ✔️ **Busca de temas** por palavra-chave com paginação e ordenação  
- ✔️ **Interface intuitiva** para responder e revisar questões  
- ✔️ **Visualização de resultados** com gráficos e destaques de acertos/incorretas  
- ✔️ **Integração com IA** para criação de perguntas inteligentes  

---

## Repositórios do Projeto

O repositório **genérico** centraliza links e informações do projeto:

- **[Front-End](https://github.com/devErikyLS/Knowledge-Front)** – Interface em React 18+ com Vite  
- **[Back-End](https://github.com/devErikyLS/Knowledge-Back)** – API em Java 21 + Spring Boot, responsável por quizzes e temas  

---

## Tecnologias Utilizadas

- **Front-End:** React 18+, Vite, Axios, CSS Modules, Framer Motion, Recharts  
- **Back-End:** Java 21, Spring Boot 3, Spring Data JPA, PostgreSQL/H2, RestClient, ModelMapper  
- **IA:** Google Gemini API  

---

## Como Executar o Sistema Completo

### Pré-requisitos

- **Node.js 18+**  
- **Java 21 + Maven**  
- Variável de ambiente `GEMINI_API_KEY` configurada:

```bash
# Linux / macOS
export GEMINI_API_KEY=sua_chave
```

## Passos

Clonar repositórios

git clone https://github.com/devErikyLS/Knowledge-Front.git

git clone https://github.com/devErikyLS/Knowledge-Back.git

---

Executar o Back-End

```bash
cd Knowledge-Back
./mvnw spring-boot:run
```

---

Executar o Front-End

```bash
cd Knowledge-Front
npm install
npm run dev
```

- Aplicação disponível em: http://localhost:5173

---

## Impacto Esperado

- Identificar lacunas de aprendizado de forma personalizada

- Estimular estudo ativo e focado

- Fornecer métricas e dados para alunos e professores

- Criar um ambiente educacional inteligente e interativo

---

## Autor

Eriky Lima
