# Base de Conhecimento

## Dados Utilizados

| Arquivo | Formato | Utilização no Agente |
|---------|---------|---------------------|
| `historico_atendimento.csv` | CSV | Contextualizar interações anteriores |
| `perfil_investidor.json` | JSON | Personalizar recomendações |
| `produtos_financeiros.json` | JSON | Sugerir produtos adequados ao perfil |
| `transacoes.csv` | CSV | Analisar padrão de gastos do cliente |

---

## Adaptações nos Dados

Os arquivos foram utilizados sem modificações, para intenções de aprendizado.

---

## Estratégia de Integração

### Como os dados são carregados?

Todos os arquivos são utilizados logo no início do atendimento do agente.

### Como os dados são usados no prompt?

Os dados serão consultados dinamicamente durante o uso do agente.

---

## Exemplo de Contexto Montado

```
Dados do Cliente:
- Nome: João Silva
- Perfil: Moderado
- Saldo disponível: R$ 5.000

Últimas transações:
- 01/11: Supermercado - R$ 450
- 03/11: Streaming - R$ 55
...
```
