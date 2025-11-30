# 📊 Progresso - Analisador de Sequências S/F

Uma aplicação web interativa para registrar e analisar padrões de sucessos (S) e falhas (F) com sistema inteligente de previsão baseado em sequências repetidas.

![Preview](https://img.shields.io/badge/Status-Funcionando-green)
![Tecnologias](https://img.shields.io/badge/Tecnologias-HTML%2C%20CSS%2C%20JavaScript-blue)

## 🚀 Funcionalidades

- **Registro Intuitivo**: Botões dedicados para Sucesso (S) e Falha (F)
- **Previsão Inteligente**: Algoritmo que detecta padrões repetidos e prevê o próximo valor
- **Visualização Clara**: Exibe a sequência base utilizada para cada previsão
- **Estatísticas em Tempo Real**: Contadores de sucessos, falhas e total
- **Histórico de Ações**: Funcionalidades de desfazer e limpar
- **Design Responsivo**: Interface adaptável a diferentes dispositivos

## 🎯 Como Funciona

O sistema analisa a sequência atual em busca de padrões de 3 caracteres que se repetem. Quando encontra uma sequência repetida, ele usa o valor que veio após a primeira ocorrência para prever o próximo valor.

**Exemplo:**

Sequência: FFFSFFSSFFF
Últimos 3: FFF
Encontrado anteriormente: FFF → S
Previsão: S


## 🛠️ Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Design**: CSS Flexbox, Gradients, Responsive Design
- **Funcionalidades**: Local Storage, Pattern Matching Algorithm


