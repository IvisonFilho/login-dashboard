# 🛰️ Projeto Apollo

Aplicação web com autenticação de usuários e acesso a uma área restrita (*dashboard*), simulando um sistema real utilizado em empresas.

## 🚀 Objetivo
Desenvolver um sistema completo de login e gerenciamento de usuários, com foco em boas práticas de arquitetura e segurança.

## 👥 Atores do Sistema
- **Usuário:** pode se registrar, fazer login e acessar o dashboard.

## 📋 Diagrama de Requisitos
O sistema é definido por **Requisitos Funcionais (FR)** e **Requisitos Não Funcionais (NFR)**, organizados hierarquicamente.

### 🔧 Requisitos Funcionais (FR)
| Código | Descrição |
| --- | --- |
| RF01 | O sistema deve permitir que novos usuários se cadastrem informando nome, e-mail e senha. |
| RF02 | O sistema deve permitir login e acesso à área restrita. |
| RF03 | O usuário autenticado deve visualizar informações personalizadas no dashboard. |
| RF04 | O sistema deve permitir acesso ao dashboard apenas para usuários autenticados. |
| RF05 | O sistema deve impedir acesso a páginas protegidas sem autenticação. |
| RF06 | O sistema deve permitir que o usuário encerre sua sessão (logout). |

### 🛠️ Requisitos Não Funcionais (NFR)
- Segurança de dados e autenticação.
- Interface responsiva e intuitiva.
- Desempenho otimizado para múltiplos acessos simultâneos.

## 🧩 Tecnologias Sugeridas
- **Frontend:** React.js  
- **Backend:** Java (JDA / Spring Boot)  
- **Banco de Dados:** PostgreSQL  
- **Logging:** SLF4J  

## 📁 Estrutura do Projeto
```
/src
 ├── frontend/
 ├── backend/
 ├── docs/
 └── assets/
```