# TCC 2026 — Lixeira Inteligente
LTP3 + QP3 · CEMIC 2026 · Prof. Rafael Martins Alves

---

## 👥 Integrantes

| Nome completo | GitHub | Turma |
|--------------|--------|-------|
| Rafael Martins Alves | @rafaelalvesmartins | 3A |
| Rodrigo Martins Alves | @rodrigoalves | 3B |
| (nome 3) | @username | 3A |

Tema: Sistema web para monitorização em tempo real e gestão de capacidade de lixeiras inteligentes.
Tecnologia: Python + Flask + SQLite

---

## 🎯 O que o sistema faz

O sistema resolve o problema da acumulação excessiva de resíduos através da monitorização em tempo real da capacidade de lixeiras inteligentes. O programa processa os dados de sensores de nível, guarda o histórico no banco de dados e apresenta um painel web intuitivo. Isto permite que os utilizadores saibam o momento exato para realizar a recolha, otimizando o tempo e evitando o transbordo de lixo.

---

## 🔄 Como o grupo trabalha toda semana

1. Segunda — cada integrante abre Issues da semana (use o template "Tarefa Semanal")
2. Durante a semana — trabalham e fazem commits
3. Sexta — o grupo abre 1 Pull Request linkando as Issues concluídas
4. Push — métricas de participação aparecem automaticamente no Actions

---

## 📁 Estrutura do projeto


├── README.md        ← este arquivo
├── BACKLOG.md          ← resumo fixo do MVP e links
├── docs/
│   ├── arquitetura.md  ← diagrama de arquitetura
│   └── decisoes/       ← registros de decisão técnica (ADR)
├── diagramas/          ← imagens e diagramas
├── evidencias/         ← screenshots das demos
├── src/                ← código do sistema
└── tests/              ← testes automáticos


---

## ⚡ Comandos rápidos

```bash
# Clonar o repositório
git clone <URL>

# Rodar o projeto
pip install -r requirements.txt
python src/app.py

# Rodar os testes
pytest tests/ -v
