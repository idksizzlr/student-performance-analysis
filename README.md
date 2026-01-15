# 📊 Análise de Performance Estudantil: Estratégias Multiclasse

Este projeto explora a aplicação de modelos de Machine Learning para prever o desempenho acadêmico de estudantes de matemática em escolas portuguesas, utilizando o dataset "Student Performance" da UCI. O foco principal é a comparação entre duas abordagens de classificação multiclasse: **One-vs-All (OvA)** e **One-vs-One (OvO)**.

## 🚀 Visão Geral do Projeto

O objetivo é classificar os alunos em diferentes níveis de notas com base em atributos demográficos, sociais e acadêmicos. Através da implementação de Regressão Logística, analisamos não apenas a precisão das predições, mas também quais variáveis mais influenciam o sucesso do estudante.

## 🛠️ Stack Tecnológica

O projeto foi desenvolvido utilizando o ecossistema científico do Python, focado em alta performance para análise de dados e machine learning:

* **Manipulação e Análise:**
    * ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white) — Limpeza de dados e engenharia de atributos.
    * ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white) — Processamento matricial e operações matemáticas.
* **Machine Learning (Scikit-Learn):**
    * ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white) — Implementação dos modelos de **Regressão Logística** e estratégias **One-vs-One / One-vs-All**.
* **Visualização de Dados:**
    * ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=flat&logo=Matplotlib&logoColor=black) — Criação de gráficos base para análise de impacto.
    * ![Seaborn](https://img.shields.io/badge/Seaborn-%234479A1.svg?style=flat&logo=python&logoColor=white) — Visualizações estatísticas avançadas e mapas de calor.
* **Ambiente de Desenvolvimento:**
    * ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA4F09.svg?style=flat&logo=jupyter&logoColor=white) — Documentação interativa e experimentação do modelo.

## 📈 Resultados e Performance

Observamos uma evolução significativa na capacidade preditiva ao comparar as estratégias:

* **One-vs-All (OvA):** Alcançou uma acurácia de **74.22%**. Embora eficiente, enfrentou desafios com o desbalanceamento inerente ao comparar uma classe contra todas as outras.
* **One-vs-One (OvO):** Elevou a acurácia para impressionantes **94.23%**. Ao focar em distinguir pares específicos de classes, o modelo capturou nuances fundamentais dos dados.

## 🔍 Insights de Variáveis (Feature Importance)

A análise dos coeficientes revelou os fatores determinantes na educação:

1.  **Histórico Acadêmico (G1 e G2):** São os preditores dominantes. No modelo OvO, a variável **G2** apresentou o maior impacto (**5.27**), seguida por **G1** (**2.81**).
2.  **Esforço e Histórico:** O **tempo de estudo (studytime)** e o histórico de **reprovações (failures)** aparecem como os principais fatores secundários.
3.  **Fatores Periféricos:** Variáveis como consumo de álcool e escolaridade dos pais tiveram impacto reduzido quando comparadas ao desempenho direto em sala de aula.

---

<div align="center">
  
## 👤 Autor

  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/idksizzlr">
          <img src="https://github.com/idksizzlr.png" width="120px;" style="border-radius: 50%;" alt="Vinicius Ferreira Leal"/><br />
          <sub><b>Vinicius Ferreira Leal</b></sub>
        </a>
      </td>
      <td>
        <b>📊 Premium Audit Analyst</b><br>
        Data & Financial analysis. 🚀<br><br>
        <a href="https://linkedin.com/in/viniciusfleal21/">
          <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge">
        </a>
        <a href="mailto:viniciusfleal21@gmail.com">
          <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail Badge">
        </a>
        <a href="https://github.com/idksizzlr">
          <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge">
        </a>
      </td>
    </tr>
  </table>

*Obrigado por acompanhar este estudo! Se este projeto foi útil para você, considere deixar uma ⭐️.*

</div>
