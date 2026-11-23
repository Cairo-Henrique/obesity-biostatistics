<div align="center">

# **Análise Bioestatística de Obesidade: Testes de Associação e Regressão Logística**

Investigação estatística de fatores associados à classificação do estado nutricional de indivíduos

<br>

<img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white">
<img src="https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white">

<br><br>

</div>

---

<div align="center">

## Autores

**Grupo G02**  
Disciplina 7600133 — Introdução à Bioestatística

<table>
  <tr>
    <td align="center">
      <strong>Cairo Henrique Vaz Cotrim</strong>
    </td>
    <td align="center">
      <strong>Uebton Oliveira da Silva</strong>
    </td>
  </tr>
</table>

Universidade de São Paulo — USP

</div>

---

## Resumo

Neste projeto, desenvolvemos uma análise bioestatística do [Obesity Dataset](https://www.kaggle.com/datasets/suleymansulak/obesity-dataset), composto por 1.610 observações e 15 variáveis, integrando análise exploratória, visualização de dados, testes de hipóteses e modelagem estatística em Python. Investigamos associações entre características demográficas, hábitos comportamentais e classificação do estado nutricional por meio de testes qui-quadrado, V de Cramér com correção de viés, correlação de Kendall, correlações de Pearson e Spearman e testes de Kruskal–Wallis com comparações post-hoc de Dunn. Todas as 12 variáveis categóricas apresentaram associação significativa com a classificação nutricional, enquanto cinco das seis variáveis ordinais exibiram tendências monotônicas significativas. A idade destacou-se pela associação mais intensa com a classificação (Spearman $\rho = 0{,}6134$; $\varepsilon^2 = 0{,}4255$), em comparação com a altura ($\rho = 0{,}1589$; $\varepsilon^2 = 0{,}0335$). Diante da violação da hipótese de chances proporcionais na regressão ordinal, desenvolvemos um modelo de regressão logística multinomial com idade (termos linear e quadrático), sexo, histórico familiar e consumo de fast food. O modelo convergiu, apresentou significância global ($p < 0{,}001$) e pseudo-$R^2$ de McFadden igual a 0,2987. Os resultados identificam padrões de associação na amostra, sem estabelecer relações causais.

---

## Fonte dos dados

| Campo | Informação |
|:---|:---|
| **Conjunto de dados** | Obesity Dataset |
| **Autor** | Suleyman Sulak |
| **Plataforma** | Kaggle |
| **Observações** | 1.610 indivíduos |
| **Variável de interesse** | Classificação do estado nutricional |
| **Acesso** | [Obesity Dataset — Kaggle](https://www.kaggle.com/datasets/suleymansulak/obesity-dataset/data) |

---
