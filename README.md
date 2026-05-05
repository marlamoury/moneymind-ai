# 💰 MoneyMind AI

**Transforme sua planilha financeira em decisões inteligentes com IA.**

---

## 🚀 Sobre o projeto

O **MoneyMind AI** é uma plataforma que analisa dados financeiros pessoais (CSV/Excel) e gera **insights acionáveis** para melhorar sua saúde financeira.

Através de inteligência artificial, o sistema interpreta seus dados e responde perguntas como:

* Para onde meu dinheiro está indo?
* Quais gastos posso reduzir?
* Quais contas devo priorizar?
* Como melhorar minha saúde financeira?

---

## 🎯 Problema que resolve

Muitas pessoas registram seus gastos, mas não sabem **como interpretar esses dados**.

O MoneyMind AI resolve isso transformando informações brutas em:

* Diagnóstico financeiro
* Identificação de desperdícios
* Recomendações práticas
* Priorização de contas

---

## 🧠 Como funciona

1. O usuário envia uma planilha financeira (CSV/Excel)
2. O sistema processa os dados
3. A IA analisa padrões e contexto
4. São gerados insights e recomendações personalizadas

---

## 📊 Exemplo de uso

### 📥 Input (planilha)

| Data       | Descrição | Valor |
| ---------- | --------- | ----- |
| 01/05/2026 | Salário   | 5000  |
| 02/05/2026 | Aluguel   | -1500 |
| 03/05/2026 | Mercado   | -800  |
| 04/05/2026 | Delivery  | -400  |
| 05/05/2026 | Streaming | -120  |

---

### 📤 Output (IA)

> Seus gastos fixos representam aproximadamente 64% da sua renda.
>
> Foi identificado um alto gasto com alimentação fora de casa (delivery), representando cerca de 8% da renda mensal.
>
> Recomenda-se reduzir esse tipo de despesa para melhorar o equilíbrio financeiro.
>
> Priorize o pagamento de despesas essenciais como aluguel antes de gastos variáveis.

---

## 🛠 Tecnologias utilizadas

* C# / .NET 8 (ASP.NET Core Web API)
* OpenAI API (LLM)
* Processamento de dados (CSV/Excel)
* Prompt Engineering
* RESTful API (Swagger / OpenAPI)

---

## ⚙️ Como executar o projeto

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/moneymind-ai.git

# Entrar na pasta
cd moneymind-ai

# Rodar o projeto
dotnet run
```

A API estará disponível em:

```
https://localhost:5001/swagger
```

---

## 🔌 Endpoint principal

### POST `/analyze-financial-health`

Recebe um arquivo CSV/Excel e retorna uma análise financeira com insights gerados por IA.

---

## 🔥 Diferencial

O MoneyMind AI não apenas exibe dados — ele **interpreta, analisa e orienta decisões**.

* Foco em problema real (finanças pessoais)
* Geração de insights acionáveis
* IA aplicada de forma prática
* Simples de usar e fácil de entender

---

## 🚀 Próximos passos

* Interface web (dashboard financeiro)
* Classificação automática de despesas
* Histórico de análises
* Deploy em nuvem (Azure/AWS)

---

## 💡 Frase-chave

> Transformando dados financeiros em decisões inteligentes com IA.

---

## 👩‍💻 Autora

Marla Amoury Silva
Senior Software Engineer | .NET | Arquitetura de Software | IA aplicada

---

## ⭐ Contribuição

Sinta-se à vontade para contribuir ou sugerir melhorias!

