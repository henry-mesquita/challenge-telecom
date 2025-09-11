# Análise de Churn em Empresa de Telecomunicações

> Projeto de Análise e ETL de dados para identificar os principais fatores que levam ao cancelamento de clientes (churn) e gerar insights estratégicos para a tomada de decisão.

<br>
<img width="983" height="568" alt="image" src="https://github.com/user-attachments/assets/c2593361-93a5-4bf7-82d3-e58d03a53bca" />

---

## Sobre o Projeto

O churn de clientes é um dos desafios mais críticos para empresas de serviço por assinatura. Este projeto foi desenvolvido para atacar esse problema de frente, realizando uma análise exploratória completa em um dataset de uma empresa de telecomunicações fictícia.

O objetivo principal é transformar dados brutos em inteligência de negócio, respondendo à pergunta: **"Quais são os perfis e comportamentos dos clientes que cancelam, e como podemos agir para retê-los?"**

---

## Principais Descobertas e Insights

A análise revelou padrões claros no comportamento dos clientes com churn. Alguns dos principais achados foram:

*   **Contratos Mensais:** Clientes com contratos do tipo "mês a mês" têm uma taxa de churn significativamente maior em comparação com contratos de 1 ou 2 anos.
*   **Serviços de Suporte:** A ausência de serviços adicionais como suporte técnico e backup online está fortemente correlacionada com o cancelamento.
*   **Forma de Pagamento:** Clientes que utilizam boleto eletrônico como forma de pagamento apresentam maior propensão ao churn.
*   *(Opcional: Adicione aqui outro insight interessante que você encontrou!)*

---

## Tecnologias Utilizadas

- **Linguagem:** Python
- **Bibliotecas:** Pandas, Matplotlib, Seaborn
- **Ambiente:** Jupyter Notebook

---

## Como Executar

Para replicar a análise, siga os passos abaixo. O projeto está estruturado da seguinte forma:

- `notebooks/`: Contém o notebook com todo o processo de análise.
- `dados/`: Contém o dataset original.
- `relatorio/`: Contém o relatório final exportado em HTML.

```bash
# 1. Clone o repositório
git clone https://github.com/henry-mesquita/challenge-telecom.git

# 2. Navegue até o diretório
cd challenge-telecom

# 3. (Opcional, mas recomendado) Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate # No Windows: venv\Scripts\activate

# 4. Instale as dependências
pip install -r requirements.txt

# 5. Inicie o Jupyter Notebook
jupyter notebook
```

## Autor
Desenvolvido por **Henry Mesquita**.

*Este projeto foi originalmente criado como parte do Challenge de Ciência de Dados da Oracle em conjunto com a Alura.*
