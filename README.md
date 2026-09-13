# Sistema de Desconto Progressivo Automatizado — Agenda 06 (DSI I)

### 📌 Sobre o Projeto
Programa em Python que simula um ponto de venda, aplicando regras automáticas de descontos de forma progressiva. O software opera em regime de fluxo contínuo.

### ⚙️ Lógica de Fluxo Contínuo (Loops)
- **Laço de Repetição:** O sistema utiliza uma estrutura `while True` para manter o caixa aberto para infinitas operações sucessivas.
- **Interrupção Controlada:** O programa monitora a entrada de dados. Caso o operador digite a string literal `'sair'`, o laço é quebrado via comando `break` e a memória é liberada.
- **Tratamento de Exceções:** Erros de digitação (letras ou símbolos) acionam a instrução `continue`, impedindo que o programa sofra um encerramento forçado (*crash*).

### 🛠️ Tecnologias e Conceitos Utilizados
- **Linguagem:** Python 3
- **Estruturas Condicionais:** `if`, `elif`, `else`
- **Controle de Fluxo:** `while`, `break`, `continue`
- **Validação de Tipos:** `try/except` com captura de `ValueError`
- **Uso de IA:** Inteligência Artificial para validação técnica do algoritmo e automação de relatórios.
