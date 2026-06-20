# Construa Assistente Virtual Inteligencia Artificial
Desafio da Accenture - Python para Análise e Automação de Dados | DIO

# MIA - Monitor Inteligente de Gastos com IA

## Sobre o Projeto

A MIA é uma assistente virtual criada para ajudar pessoas a entender melhor seus gastos mensais.

A ideia surgiu a partir de um problema comum: muitas vezes gastamos dinheiro sem perceber em quais categorias estamos exagerando. A MIA recebe informações sobre renda e despesas, analisa os dados utilizando o Gemini e gera uma avaliação financeira com sugestões de melhoria.

Este projeto foi desenvolvido como parte do desafio **"Construa Seu Assistente Virtual Com Inteligência Artificial"** da DIO.

---

## O que a MIA faz?

* Analisa gastos mensais informados pelo usuário;
* Calcula o percentual de cada categoria em relação à renda;
* Identifica gastos acima do recomendado;
* Gera alertas e recomendações personalizadas;
* Classifica a situação financeira como Excelente, Boa, Atenção ou Crítica.

---

## Tecnologias Utilizadas

* Python
* Google Colab
* Gemini API
* Engenharia de Prompt
* Inteligência Artificial Generativa

---

## Base de Conhecimento

A MIA utiliza uma base simples de referência para comparar os gastos:

| Categoria   | Limite Recomendado |
| ----------- | ------------------ |
| Moradia     | Até 35%            |
| Alimentação | Até 30%            |
| Transporte  | Até 15%            |
| Lazer       | Até 10%            |
| Streaming   | Até 5%             |

---

## Como Executar

1. Abra o notebook no Google Colab;
2. Instale a biblioteca:

```python
!pip install -q google-genai
```

3. Configure sua API Key do Gemini;
4. Informe sua renda e gastos mensais;
5. Receba a análise gerada pela MIA.

---

## Exemplo

### Entrada

```text
Renda: R$ 3000

Moradia: R$ 1000
Alimentação: R$ 900
Transporte: R$ 300
Lazer: R$ 500
Streaming: R$ 200
```

### Resultado Esperado

* Identificação de gastos acima do recomendado;
* Resumo financeiro;
* Classificação da saúde financeira;
* Sugestões para melhorar a organização dos gastos.

---

## Possíveis Melhorias

* Histórico de análises;
* Geração de gráficos;
* Dashboard interativo;
* Integração com planilhas;
* Memória de conversas.

---

## Autor

João Victor Dutra

Projeto desenvolvido para fins de estudo e aprendizado em Inteligência Artificial, Python e análise de dados.
