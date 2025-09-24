# 📱 DailyGoals - Aplicativo Mobile

O **DailyGoals** é um aplicativo desenvolvido para ajudar usuários a **definir, organizar, acompanhar e concluir metas diárias**, fornecendo maior controle e produtividade em suas atividades pessoais e profissionais.

Este repositório contém o **código-fonte do aplicativo mobile**, integrado com serviços da **AWS** para autenticação, armazenamento de dados e sincronização.

---

## 🚀 Funcionalidades principais

- 🔐 **Autenticação e Autorização** com **AWS Cognito** (login seguro com e-mail/senha).
- ✅ Criação, edição e conclusão de metas diárias.
- ☁️ **Sincronização entre dispositivos** utilizando **API Gateway + Lambda + DynamoDB**.
- 📊 Histórico detalhado de metas concluídas, permitindo análise de desempenho.
- 🔔 Notificações e lembretes para metas próximas do prazo.

---

## 🛠️ Tecnologias utilizadas

- **React Native (Expo)** → desenvolvimento mobile multiplataforma
- **AWS Amplify** (integração com serviços backend)
- **AWS Cognito** → autenticação
- **AWS API Gateway + Lambda** → camada backend serverless
- **AWS DynamoDB** → banco de dados NoSQL escalável
- **AWS Route 53** → configuração de DNS
