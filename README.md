# 📋 Backlog do Produto — Lixeira Inteligente

Este documento apresenta o escopo do MVP (Mínimo Produto Viável) e a lista de funcionalidades planejadas para o sistema de monitoramento de lixeiras inteligentes.

---

## 🚀 Escopo do MVP

O objetivo principal do MVP é permitir o monitoramento remoto do nível de preenchimento de uma ou mais lixeiras através de uma interface web, alertando os responsáveis quando a lixeira atingir a capacidade crítica (80% ou mais).

---

## 📌 Requisitos Funcionais (Product Backlog)

### 🔴 Alta Prioridade (Essencial para o MVP)
- [ ] **RF01 - Cadastro e Login de Usuários:** Sistema de autenticação para administradores/equipe de limpeza.
- [ ] **RF02 - Monitoramento em Tempo Real:** Painel (Dashboard) que exibe o percentual de preenchimento atual da lixeira.
- [ ] **RF03 - Simulação/Recebimento de Dados:** Rota da API (Flask) para receber o nível do sensor e salvar no banco de dados SQLite.
- [ ] **RF04 - Alerta de Transbordo:** Indicação visual (cor vermelha/alerta) na tela quando a lixeira passar de 80% da capacidade.

### 🟡 Média Prioridade (Desejável)
- [ ] **RF05 - Histórico de Coletas:** Relatório ou gráfico mostrando os dias e horários em que a lixeira foi esvaziada.
- [ ] **RF06 - Cadastro de Múltiplas Lixeiras:** Possibilidade de monitorar mais de uma lixeira em pontos diferentes da instituição.

### 🟢 Baixa Prioridade (Futuro/Diferencial)
- [ ] **RF07 - Previsão de Tempo de Preenchimento:** Algoritmo simples para estimar em quantas horas a lixeira ficará cheia com base no uso recente.

---

## 🔗 Links Úteis
* **Repositório do Projeto:** [Insira o link do seu GitHub aqui]
* **Documentação da API:** `docs/arquitetura.md`
