# 🤖 **VoidPython**: Demonstração de um Professor de Programação com a API do Gemini 🧠

👋 Olá, Engenheiro(a)\! Este repositório não é apenas um pacote para ser instalado; é um ***Showcase* de engenharia** que demonstra como a **API do Google Gemini** pode ser estruturada e orquestrada para atuar como um professor de lógica e programação em Python.

Aqui, o foco é em **engenharia de *prompt***, arquitetura e uso avançado do Gemini para criar uma experiência de aprendizado interativa, precisa e segura.

## ✨ **O Cérebro do Professor (Arquitetura)**

O **VoidPython** opera em um loop de conversação onde o Gemini atua como o **instrutor** , avalia o código e fornece *feedback* alinhado à metodologia educacional.

## ⚙️ **Como a Mágica Acontece (A Engenharia por Trás)**

A inteligência do **VoidPython** reside em um *Prompt* dinâmico que orquestra a experiência de aprendizado:

1.  **Metodologia de Ensino:** A IA é instruída a seguir uma ordem estrita em toda explicação: **Contextualizar**, **Definir Conceitos**, **Demonstrar**, **Mostrar Padrões** e **Propor Prática**
2.  **Lógica Explicada:** Para problemas de lógica, o *prompt* exige que o **raciocínio passo a passo** seja mostrado **antes** do código
3.  **Avaliação Detalhada:** A resposta é estruturada rigidamente para análise
      * `🎯 Problema`
      * `💡 Análise e Lógica`
      * `🐍 Solução em Python`
      * `🔍 Explicação do Código` (linha por linha)
      * `⚡ Alternativas e Otimizações`

### **🛡️ Defesa Contra *Prompt Injection***

O projeto inclui um sistema de segurança [cite: 37] [cite\_start]para manter a persona do professor.Ele detecta **red flags** (como `"ignore previous instructions"`) e padrões suspeitos (como `"pretend"`) e, se necessário, retorna uma resposta protocolar e segura.

## 🔑 **Configuração do Projeto (*Setup*)**

Este projeto é feito para ser executado localmente, demonstrando a interação com a API do Gemini.

### Pré-requisitos

  * Python 3.x
  * Uma Chave da API do Google Gemini.
  * Instalação das dependências (ex: `google-genai`).

### ▶️ Como Testar

1.  Clone o repositório: `git clone [seu-link-aqui]`
2.  Defina sua chave de API como variável de ambiente (Obrigatório para segurança):
    ```bash
    export GEMINI_API_KEY='SUA_CHAVE_AQUI'
    ```
3.  Execute o módulo principal para iniciar a demonstração:
    ```bash
    python main.py
    ```

## 📚 **Conteúdo e Conhecimento Demonstrado**

Os arquivos de contexto mostram a profundidade do conhecimento injetado no LLM:

  * **Fundamentos:** Conceitos de Algoritmo, Variável e a Tabela Verdade da Lógica.
  * **Sintaxe Python:** Estruturas de controle (`if/elif/else`, `for`, `while`) e tipos de dados básicos.
  * **Boas Práticas:** Padrões de Nomenclatura, uso de `try-except` e documentação com *docstrings*.
  * **Exemplos Práticos:** Exercícios progressivos (Bubble Sort, Busca Binária e um *case* de aplicação em classes (Sistema de Alunos).

## 🤝 **Colabore\! (Vamos Otimizar o Cérebro\!)**

Este projeto é um campo de testes. Queremos ver a sua engenharia\! Sugestões de melhoria são bem-vindas:

  * **Novas Estratégias de Prompt:** Um jeito mais eficiente de fazer o Gemini avaliar o código (otimização do *zero-shot reasoning*).
  * **Melhoria no Protocolo de Segurança:** Adição de mais *red flags* ou refinamento na análise de intenção.
  * **Novos Módulos:** Adicione novos exercícios e contextos para testar o professor.

-----

*Feito com ☕ e muito *Prompt Engineering* por **Void**
