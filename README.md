# 📦 Stock Manager: Sistema de Gestão de Inventário e Alertas

**Stock Manager** é uma aplicação web completa, construída com arquitetura desacoplada (API Backend e Frontend SPA), projetada para gerir o inventário de pequenos negócios ou armazéns. O sistema permite que cada utilizador mantenha o seu próprio inventário, monitorize o stock em tempo real e receba alertas quando os produtos atingem um limite mínimo.

Este projeto demonstra proficiência em **Django REST Framework (DRF)** para a criação de APIs e **React** para a construção de interfaces de utilizador dinâmicas e modernas.

## ✨ Funcionalidades Principais

* **Inventário por Utilizador:** Cada utilizador autenticado gere o seu próprio conjunto de produtos e movimentos.

* **Gestão de Produtos (CRUD via API):** Criação, Leitura, Atualização e Eliminação de produtos.

* **Controlo de Stock (Entrada/Saída):** Registo de movimentos de stock para manter o `stock_atual` preciso.

* **Alertas de Reabastecimento:** Geração automática de alertas quando o stock de um produto cai abaixo do seu `limite_alerta` definido.

* **Dashboard Moderno:** Interface de utilizador construída em React/Tailwind, com visualizações de dados e gráficos (a ser implementado com Recharts).

* **Arquitetura Desacoplada:** Comunicação exclusiva entre Frontend e Backend via endpoints JSON (API REST).

## 🛠️ Tecnologias Utilizadas

### Backend (API REST)

| Ferramenta | Propósito | 
 | ----- | ----- | 
| **Python 3.x** | Linguagem de programação principal. | 
| **Django** | Framework web robusto para a lógica de negócio. | 
| **Django REST Framework (DRF)** | Criação rápida e segura dos endpoints da API (Serializers, Views, Routers). | 
| **SQLite / PostgreSQL** | Base de dados (SQLite para desenvolvimento). | 

### Frontend (Interface de Utilizador)

| Ferramenta | Propósito | 
 | ----- | ----- | 
| **React** | Biblioteca JavaScript para a construção da Single Page Application (SPA). | 
| **Tailwind CSS** | Framework *utility-first* para um design rápido, responsivo e moderno. | 
| **Recharts** | Biblioteca de React para renderização de gráficos de visualização de dados. | 

## ⚙️ Como Configurar e Executar

Este projeto requer que o Backend (Django) e o Frontend (React) sejam executados em separado.

### 1. Pré-requisitos

* Python (3.8+)

* Node.js & npm/yarn

* Git

### 2. Configuração do Backend (Django API)

1. **Clonar o Repositório:**
2. **Criar Ambiente Virtual e Instalar Dependências:**
3. **Configurar a Base de Dados e Migrações:**
4. **Criar um Utilizador Administrador (Opcional):**
5. **Iniciar o Servidor Django (API):**

### 3. Configuração do Frontend (React SPA)

1. **Mudar para a Pasta do Frontend:**
2. **Instalar Dependências:**
3. **Iniciar a Aplicação React:** O frontend será normalmente iniciado em http://localhost:3000/

Developed with ☕ and Python by \[Lucas Dias/Lsdias\].
