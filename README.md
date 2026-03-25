# 🤖 Copilot Modes: Framework de Prompts Técnicos

Este repositório contém a documentação e os prompts de sistema para configurar os **Modos do Copiloto**. O objetivo é transformar a IA de um simples "autocompletar" em um ecossistema de especialistas (Ask, Edit, Plan, Agent e Study).

---

## 📌 Os 5 Modos de Operação

Cada modo altera a "postura" da IA para priorizar velocidade, precisão arquitetural ou aprendizado profundo.

### 🔍 1. Modo ASK (O Oráculo)
*   **Foco:** Respostas rápidas e consultas de sintaxe.
*   **Quando usar:** Dúvidas pontuais ("Como centralizar uma div?", "Qual o método de array para X?").
*   **Saída:** Snippets curtos e diretos. Sem explicações longas.

### ✍️ 2. Modo EDIT (O Refatorador)
*   **Foco:** Modificação direta de código existente.
*   **Quando usar:** Refatoração, limpeza de código e aplicação de padrões de linting.
*   **Saída:** Blocos de código prontos para substituição (diffs).

### 📐 3. Modo PLAN (O Arquiteto)
*   **Foco:** Lógica, contratos e fluxos antes da implementação.
*   **Quando usar:** Antes de iniciar uma feature complexa. Define interfaces e estratégia de dados.
*   **Saída:** Checklists de implementação, pseudocódigo e trade-offs de design.

### 🤖 4. Modo AGENT (O Executor)
*   **Foco:** Autonomia e tarefas multiarquivos.
*   **Quando usar:** Migrações em massa, criação de testes para o projeto todo ou busca de padrões no repo.
*   **Saída:** Execução de tarefas encadeadas e relatórios de alteração.

### 🎓 5. Modo STUDY (O Tutor Técnico)
*   **Foco:** Aprendizado real e intuição (Modo atual: **Cortana**).
*   **Quando usar:** Para entender o "porquê" das coisas, dominar novos frameworks ou conceitos de CS.
*   **Saída:** Analogias, exemplos didáticos e checkpoints de compreensão.

---

## 🧠 Analogia de Fluxo
Imagine a construção de um software como uma obra:
*   **PLAN** desenha a planta.
*   **AGENT** gerencia os materiais e equipes.
*   **EDIT** faz o acabamento de uma parede.
*   **ASK** consulta o manual técnico da fiação.
*   **STUDY** ensina você a ser o engenheiro.

---

## 🚀 Como Configurar (Stack: Node.js + TypeScript)

Para ativar um modo, copie o prompt correspondente (disponível na pasta `/prompts` deste repo) e cole nas instruções personalizadas do seu Copiloto.

### Exemplo de Identidade (Modo STUDY/Cortana):
- **Nome:** Cortana
- **Tom:** Calmo, confiante e espirituoso.
- **Regra de Ouro:** Priorizar o aprendizado sobre a entrega rápida.
