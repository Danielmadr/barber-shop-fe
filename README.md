# Barber Shop - Frontend

## 💻 Sobre o Projeto

Este é um projeto Angular para agendamento de atendimentos em uma barbearia. O objetivo é explorar conceitos do framework Angular, como consumo de APIs REST, comunicação com backend e componentização. Além disso, utilizamos a biblioteca Angular Material para estilização e criação de componentes.

## 📚 Pré-requisitos

Antes de iniciar, certifique-se de ter os seguintes conhecimentos:

- **JavaScript**: Intermediário
- **TypeScript**: Intermediário
- **HTML**: Intermediário
- **CSS**: Intermediário
- **Docker**: Básico (opcional)
- **Docker Compose**: Básico (opcional)

## 🛠️ Tecnologias Utilizadas

- **Angular**: Framework principal para desenvolvimento do frontend.
- **Angular Material**: Biblioteca de componentes para estilização.
- **SCSS**: Pré-processador CSS para estilização.
- **Docker**: Para containerização (opcional).

## 🎯 Objetivos e Resultados Esperados

Após a conclusão do projeto, você será capaz de:

- Criar um projeto Angular do zero.
- Consumir APIs REST para comunicação com o backend.
- Componentizar o código para melhorar a organização e reutilização.

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Node.js instalado (versão recomendada: 16 ou superior).
- Angular CLI instalado globalmente.
- Docker (opcional).

### Passos

1. Clone o repositório:

   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd barber-shop-fe
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Execute o projeto em modo de desenvolvimento:

   ```bash
   ng serve
   ```

   O projeto estará disponível em `http://localhost:4200`.

4. (Opcional) Para rodar com Docker:

   ```bash
   docker-compose up
   ```

## 📂 Estrutura do Projeto

```plaintext
barber-shop-fe/
├── src/
│   ├── app/
│   │   ├── clients/        # Módulo para gerenciamento de clientes
│   │   ├── commons/        # Componentes e utilitários comuns
│   │   ├── schedules/      # Módulo para agendamento
│   │   ├── services/       # Serviços para comunicação com APIs
│   │   ├── app.component.* # Componente principal
│   │   ├── app.routes.ts   # Configuração de rotas
│   └── environments/       # Configurações de ambiente
├── public/                 # Arquivos públicos (favicon, etc.)
├── angular.json            # Configuração do Angular CLI
├── package.json            # Dependências do projeto
└── README.md               # Documentação do projeto
```

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.

