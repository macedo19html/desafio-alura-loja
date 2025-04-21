<p align="center">
  <img src="badge.png" alt="Badge do Projeto" width="300"/>
</p>

# 📊 Análise de Dados - Alura Store

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/status-finalizado-green)]()
[![Repo](https://img.shields.io/badge/GitHub-anthonyhelano%2Fchallenge--alura--store-blue?logo=github)](https://github.com/anthonyhelano/challenge-alura-store)

---

Este projeto foi desenvolvido como parte do desafio proposto no programa **Oracle Next Education**, em parceria com a **Alura**. A proposta consiste em realizar uma **análise exploratória de dados** baseada em um cenário fictício, com o objetivo de apoiar decisões estratégicas dentro de uma empresa.

## 🧩 Contexto

O estudo é centrado na **Alura Store**, negócio fictício do Senhor João, que precisa decidir **qual loja deve ser vendida**. A escolha se baseia em dados quantitativos e qualitativos extraídos de quatro tabelas fornecidas no desafio.

Durante a análise, avaliamos:

- 📈 Faturamento total por loja  
- ⭐ Avaliações de clientes  
- 🚚 Média de frete por pedido  
- 📦 Produtos e categorias mais e menos vendidos  

Com base nesses critérios, busquei identificar qual loja apresenta **o desempenho mais fraco** de forma geral, considerando fatores financeiros, operacionais e de satisfação do cliente.

## 📁 Estrutura do Projeto
```
📂 dados/ → Base de dados utilizada para a análise
📂 graficos/ → Visualizações e gráficos gerados
📄 AluraStoreBr.ipynb → Notebook com todo o processo analítico
📄 README.md → Este arquivo com informações do projeto
```

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Python  
- **Ambientes de desenvolvimento:** PyCharm, Jupyter Notebook  
- **Bibliotecas utilizadas:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `squarify`
 
## 🔍 Sobre o Processo Analítico

Nesta análise, utilizei a biblioteca **pandas** como principal ferramenta para manipulação e exploração dos dados. Como as tabelas disponibilizadas para a atividade já estavam limpas e padronizadas, não foi necessário realizar um processo de limpeza ou tratamento de dados — o que me permitiu focar diretamente na exploração e interpretação dos dados.

### Etapas Realizadas:

1. **Importação dos dados:**  
   As tabelas foram importadas usando `pandas.read_csv()` e organizadas em dataframes para facilitar a análise.

2. **Exploração e análise estatística:**  
   Com o auxílio de `pandas` e `numpy`, foram realizadas análises descritivas, como soma de faturamento por loja, média de frete, e contagem de vendas por produto e por categoria.

3. **Visualização dos dados:**  
   Para facilitar a interpretação e a apresentação dos resultados, foram criados gráficos com `matplotlib` e `squarify` (para representar, por exemplo, a distribuição de vendas entre categorias com diagramas de treemap).

4. **Comparação entre lojas:**  
   Com as informações extraídas, comparei as lojas em relação ao faturamento, avaliações de clientes e desempenho de vendas, buscando evidências que ajudassem a identificar qual loja apresenta menor desempenho geral.

## ✅ Considerações Finais

O resultado completo da análise pode ser conferido no notebook [`AluraStoreBr.ipynb`](https://github.com/anthonyhelano/challenge-alura-store/blob/main/AluraStoreBr.ipynb).

Esse é meu primeiro projeto focado em análise de dados. Ele foi criado com fins educacionais e como uma forma de praticar e demonstrar habilidades em análise exploratória e como parte obrigatória da graduação. Sugestões e melhorias são sempre bem-vindas!

---

🔗 Repositório: [github.com/anthonyhelano/challenge-alura-store](https://github.com/anthonyhelano/challenge-alura-store)


