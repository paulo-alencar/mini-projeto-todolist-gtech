# 📝 To-Do List Javascript - Mini Projeto Fullstack

Este é um projeto de uma lista de tarefas (To-Do List) funcional, desenvolvida para exercitar a integração entre uma interface Front-end moderna e uma API simulada (Backend).

## 🚀 Funcionalidades

- **Listagem de Tarefas:** Exibição dinâmica das tarefas armazenadas.
- **Criação de Tarefas:** Modal interativo para adicionar título e descrição.
- **Busca em Tempo Real:** Filtro inteligente por título conforme a digitação.
- **Persistência de Dados:** Integração com banco de dados via JSON Server (CRUD básico).
- **Interface Responsiva:** Design limpo com uso de Boxicons e feedback visual ao passar o mouse.

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3** (Layout e estilização customizada)
- **Javascript (ES6+)** (Manipulação de DOM e Fetch API)
- **[JSON Server](https://www.npmjs.com/package/json-server)** (Para simular uma API REST)
- **[Boxicons](https://boxicons.com/)** (Para iconografia)

## 📦 Como rodar o projeto

### Pré-requisitos
Antes de começar, você precisará ter o [Node.js](https://nodejs.org/) instalado em sua máquina.

### Passo a passo

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git)

2. **Instale as dependências: No terminal, dentro da pasta do projeto, execute:**

Bash
npm install

3. **Inicie a API (Backend): Execute o comando abaixo para rodar o JSON Server na porta 3000:**

Bash
npm run api

4. **Inicie o Frontend:**

Para garantir que as requisições à API e o carregamento dos ícones funcionem corretamente devido às políticas de segurança do navegador (CORS), abra o arquivo index.html utilizando a extensão Live Server do VS Code.

### ⚠️ Observações Técnicas
Por que usar o Live Server? O projeto utiliza o protocolo http:// para se comunicar com o banco de dados local e carregar bibliotecas externas. Abrir o arquivo diretamente via file:/// pode causar bloqueios de segurança e impedir a exibição dos ícones.

API: O arquivo api.json atua como seu banco de dados. Caso deseje resetar as tarefas, basta editar esse arquivo manualmente.

### ✒️ Autor
Desenvolvido por Paulo Alencar durante o curso de Desenvolvedor Fullstack do Geração Tech 3.0
