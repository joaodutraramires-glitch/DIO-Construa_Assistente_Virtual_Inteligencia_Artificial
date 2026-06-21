# Avaliação da MIA

## Cenário 1 - Gastos Equilibrados

### Entrada

```text
Renda: R$ 3000

Moradia: R$ 1000
Alimentação: R$ 500
Transporte: R$ 200
Lazer: R$ 150
Streaming: R$ 60
```

### Resultado Esperado

Classificação: Excelente

### Resultado Obtido

Classificação: Excelente

### Observação

A MIA identificou que todos os gastos estavam dentro dos limites recomendados e apresentou sugestões para manter uma boa organização financeira.

---

## Cenário 2 - Lazer Acima do Limite

### Entrada

```text
Renda: R$ 3000

Moradia: R$ 1000
Alimentação: R$ 500
Transporte: R$ 200
Lazer: R$ 500
Streaming: R$ 60
```

### Resultado Esperado

Alerta para gasto excessivo em lazer.

### Resultado Obtido

Alerta para gasto excessivo em lazer.

### Observação

A MIA detectou corretamente que o percentual de lazer ultrapassava o limite recomendado de 10%.

---

## Cenário 3 - Múltiplas Categorias Acima do Limite

### Entrada

```text
Renda: R$ 3000

Moradia: R$ 1000
Alimentação: R$ 1000
Transporte: R$ 200
Lazer: R$ 500
Streaming: R$ 200
```

### Resultado Esperado

Classificação Atenção ou Crítica.

### Resultado Obtido

Classificação Atenção.

### Observação

A MIA identificou múltiplos gastos acima dos limites e apresentou recomendações para reduzir despesas.
