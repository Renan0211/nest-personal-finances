# 💰 Personal Finance Dashboard API 🇧🇷 🇺🇸

<div align="center">
  <a href="#portuguese-version"><img src="https://img.shields.io/badge/Português-BR-%23FFD700?style=for-the-badge&logo=brazil" alt="Portuguese Version"></a>
  <a href="#english-version"><img src="https://img.shields.io/badge/English-US-%23007ACC?style=for-the-badge&logo=united-states" alt="English Version"></a>
</div>

---

<div id="portuguese-version"></div>

## 🇧🇷 Versão em Português

### 🛠️ Tecnologias Utilizadas
**Backend:**
- NestJS (Framework Node.js)
- TypeORM (ORM para banco de dados)
- PostgreSQL (Banco de dados relacional)
- JWT (Autenticação)


### 📌 Sobre o Projeto
API backend para um dashboard de finanças pessoais com:
- Autenticação segura de usuários
- Processamento de transações bancárias via CSV
- Análise inteligente de gastos usando IA
- Geração automática de dashboards

### 🚀 Funcionalidades Principais
- [ ] Upload de arquivos CSV/extratos bancários
- [ ] Categorização automática de transações
- [ ] Identificação de padrões de gastos
- [ ] Alertas de orçamento excedido
- [ ] Dashboard interativo

### 🔮 Roadmap
1. MVP básico (CRUD de transações)
2. Integração com bancos brasileiros
3. Implementação de modelos de ML
4. Sistema de alertas personalizados

---

<div id="english-version"></div>

## 🇺🇸 English Version


## 🔧 Tech Stack
**Backend:**
- NestJS (Node.js framework)
- TypeORM (Database ORM)
- PostgreSQL (Relational database)
- JWT (Authentication)

**AI/ML Components:**
- CSV transaction analysis (Planned)
- Financial pattern recognition (Planned)
- Dashboard generation (Planned)

**Future Considerations:**
- TensorFlow.js/PyTorch for AI models
- Python microservice for heavy ML tasks
- RabbitMQ for async processing

### 📌 About The Project
Backend API for a personal finance dashboard featuring:
- Secure user authentication
- Bank statement CSV processing
- AI-powered spending analysis
- Automated dashboard generation

### 🚀 Key Features
- [ ] CSV/bank statement uploads
- [ ] Automatic transaction categorization
- [ ] Spending pattern recognition
- [ ] Budget threshold alerts
- [ ] Interactive dashboard

### 🔮 Roadmap
1. Basic MVP (Transaction CRUD)
2. Brazilian bank integrations
3. ML model implementation
4. Custom alert system

---

## 🛠️ Development Setup

```bash
# Clone repository
git clone https://github.com/Renan0211/nest-personal-finances.git

# Install dependencies
npm install

# Configure environment
cp .env.example .env

# Run in development mode
npm run start:dev