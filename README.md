# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

> Ferramenta em Excel para simular aportes mensais, evolução de patrimônio e estimativa de dividendos em Fundos Imobiliários — com projeções de longo prazo e segmentação por perfil de investidor.

---

## 🎯 Problema que resolve

Muitas pessoas têm dificuldade em visualizar o impacto real dos investimentos ao longo do tempo. Esta planilha responde perguntas como:

- *"Se eu investir R$ 500/mês por 10 anos, quanto terei acumulado?"*
- *"Qual será minha renda passiva mensal com esse patrimônio?"*
- *"Qual perfil de carteira faz mais sentido para o meu objetivo?"*

---

## ✨ Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| 💰 Cálculo de aportes | Define salário e percentual de investimento sugerido |
| 📈 Evolução de patrimônio | Calcula crescimento mês a mês com juros compostos |
| 💵 Estimativa de dividendos | Projeta renda passiva mensal com base no patrimônio acumulado |
| 🗓️ Múltiplos cenários | Simulações para 2, 5, 10, 20 e 30 anos |
| 🎯 Perfis de investidor | Carteiras para perfil Conservador, Moderado e Agressivo |

---

## 🖥️ Como usar

1. **Baixe** o arquivo `Simulador_Investimento$.xlsx`
2. **Abra** no Microsoft Excel (recomendado), Google Sheets ou LibreOffice Calc
3. **Preencha** os campos de entrada:
   - Salário mensal
   - Valor a investir por mês
   - Taxa de rendimento mensal estimada
   - Perfil de investidor desejado
4. **Visualize** os resultados automáticos nas abas de projeção

---

## 🛠️ Tecnologias e Conceitos Aplicados

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

- **Fórmulas financeiras**: juros compostos, valor futuro (`VF`), cálculo de dividendos
- **Validação de dados**: entradas controladas para evitar erros do usuário
- **Lógica condicional**: `SE`, `PROCV`, `ÍNDICE/CORRESP` para cenários dinâmicos
- **Tabelas estruturadas**: organização de dados para facilitar manutenção e escalabilidade

---

## 📐 Lógica do Cálculo

```
Patrimônio Acumulado = Aporte × [(1 + taxa)^meses - 1] / taxa
Dividendos Mensais   = Patrimônio Acumulado × Yield Médio do Perfil
```

---

## 💡 Aprendizados

- Modelagem de problemas financeiros reais em planilhas
- Criação de interfaces intuitivas sem código (UX de planilha)
- Aplicação de fórmulas financeiras para simulação de longo prazo
- Segmentação de soluções por perfil de usuário

---

## 👤 Autor

**Moises Lima Jr**
- GitHub: [@MoisesLimaJr](https://github.com/MoisesLimaJr)
- LinkedIn: [linkedin.com/in/moises-lima-jr](https://linkedin.com/in/moises-lima-jr)
- Estudante de Análise e Desenvolvimento de Sistemas — Universidade Cruzeiro do Sul
