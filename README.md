# 🚀 Shadow Tracker: Demo de Infraestrutura

Este repositório é uma demonstração da arquitetura e da estrutura de engenharia do **Shadow Tracker**, uma solução de otimização de roteamento para ambientes multichain.

## 🛠️ O que esta demo demonstra?
Esta versão pública foca na qualidade da estrutura do projeto:
*   **Clean Architecture:** Organização modular para escalabilidade.
*   **Testes Automatizados:** Implementação de testes unitários para garantir a integridade do engine.
*   **Log Estruturado:** Sistema de telemetria para auditoria financeira.

## 🏛️ Estrutura do Projeto
```text
/src
  ├── /decision_engine  # (Exemplo de interface - Lógica proprietária oculta)
  ├── /logger           # Módulo de auditoria
  └── main.py           # Orchestrator
/tests
  └── test_engine.py    # Testes unitários
