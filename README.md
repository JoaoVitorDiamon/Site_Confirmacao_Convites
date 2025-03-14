# Sistema de Confirmação de Convites - EventEasy

## Sobre o Projeto

O **Sistema de Confirmação de Convites** é um site integrado ao aplicativo **EventEasy** que permite aos convidados confirmarem sua presença em eventos de maneira fácil e rápida. Através do link gerado pelo app, os convidados acessam a plataforma, preenchem seus dados e dos acompanhantes, garantindo uma organização eficiente para os anfitriões.

## 🚀 Funcionalidades

- 📩 **Confirmação de Presença**: Permite que os convidados confirmem sua presença de forma rápida e intuitiva.
- 👥 **Inclusão de Acompanhantes**: Os convidados podem informar quantas pessoas estarão presentes com eles.
- 🔗 **Acesso via Link do App**: O evento gera um link único que direciona os convidados para a página de confirmação.
- 📋 **Lista de Confirmados**: Os organizadores podem visualizar a lista de confirmações diretamente no EventEasy.
- 📧 **Notificação de Confirmação**: O anfitrião recebe um aviso sempre que um convidado confirma sua presença.

## 🛠️ Tecnologias Utilizadas

- **Vue.js** - Front-end interativo e reativo
- **PostgreSQL** - Banco de dados para armazenar confirmações
- **Node.js (Fastify)** - Back-end para processar as confirmações
- **Docker** - Containerização para facilitação do desenvolvimento e implantação
- **Tailwind CSS** - Estilização moderna e responsiva

## 📌 Como Usar

1. O anfitrião cria um evento no **EventEasy**.
2. O aplicativo gera um link exclusivo para confirmação de presença.
3. Os convidados acessam o link e preenchem seus dados e dos acompanhantes.
4. O anfitrião pode acompanhar todas as confirmações em tempo real pelo app.

## 📥 Como Executar o Projeto Localmente

### Pré-requisitos:
- Node.js instalado
- Docker instalado e configurado
- PostgreSQL configurado (caso não utilize Docker)

### Passos:
1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/confirmacao-eventeasy.git
   ```
2. Acesse a pasta do projeto:
   ```sh
   cd confirmacao-eventeasy
   ```
3. Instale as dependências:
   ```sh
   npm install
   ```
4. Configure o banco de dados com Docker:
   ```sh
   docker-compose up -d
   ```
5. Inicie o servidor:
   ```sh
   npm run dev
   ```
6. Acesse o site no navegador:
   ```
   http://localhost:3000
   ```
