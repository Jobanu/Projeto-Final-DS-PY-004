# Projeto Final — DS-PY-004
## Análise exploratória de dados com Python, NumPy, Pandas e Git

# ✈️ Análise de Segurança Operacional Aeronáutica no Brasil (2012-2024)

## 📌 Sobre o Projeto
Este projeto final foi desenvolvido como parte do critério de avaliação da Turma #1733 - CAIXAVERSO - FC5 | Papel Analista Dados - II do módulo #1 - Técnicas de Programação I PY. O objetivo principal é analisar os fatores que influenciam a gravidade e a frequência de ocorrências aeronáuticas no espaço aéreo brasileiro, traçando um paralelo entrer os registros oficiais de analisados com indicadores de desenvolvimento socioeconômico regional (IDH).

---

## 👥 Integrantes do Grupo
* **Joadson Barbosa Nunes**
* **José Roberto Fabbi Júnior** 
* **João Felipe**

---

## 📊 Fontes de Dados Utilizadas
1. **Base Principal (CENIPA):** Microdados de Ocorrências Aeronáuticas da aviação civil brasileira integrados via ANAC, abrangendo o recorte temporal de 2012 a 2024.
2. **Base Auxiliar (IDH/PNUD):** Série histórica do Índice de Desenvolvimento Humano Municipal (IDHM) adaptado para as Unidades da Federação (UFs), cobrindo a evolução anual de desenvolvimento regional.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Python** (Linguagem base)
* **NumPy** (Cálculos de matrizes, produto escalar e normalização estatística)
* **Pandas** (Tratamento de dados, derretimento de tabelas com `pd.melt` e junções com `pd.merge`)
* **Matplotlib & Seaborn** (Construção de gráficos estatísticos e de dispersão)
* **Git & GitHub** (Controle de versão utilizando fluxo com branch paralela de `desenvolvimento`)

---

## 🚀 Como Executar o Projeto

1. Certifique-se de ter o Python instalado em sua máquina.
2. Clone este repositório localmente:
   ```bash
   git clone https://github.com
   ```
3. Acesse a pasta do projeto:
   ```bash
   cd ProyProjeto-Final-DS-PY-004
   ```
4. Instale as dependências necessárias:
   ```bash
   pip install pandas numpy matplotlib seaborn requests openpyxl
   ```
5. Abra o Jupyter Notebook ou ambiente similar (como o VS Code ou Google Colab) e execute o arquivo dentro da pasta de notebooks:
   ```bash
   notebooks/analise.ipynb
   ```

---

## 📈 Principais Entregas e Resultados
O notebook está estruturado seguindo um plano rigoroso de etapas de negócio:
* **Fase de Diagnóstico:** Mapeamento de valores ausentes, identificação de inconsistências textuais e limpeza da coluna `PSSO`.
* **Transformação de Dados Não-Trivial:** Derretimento simultâneo posicional da tabela de IDH horizontal e cruzamento multidimensional (`merge` por UF e Ano) com a base do CENIPA.
* **Análise Exploratória Visual:** Geração de gráficos complexos, com destaque para a dispersão entre IDH e Volume de Ocorrências por ano, evidenciando o paradoxo do volume de tráfego aéreo em regiões desenvolvidas.
* **Rankings de Negócio:** Possível exportação de planilhas automatizadas no Excel com o índice de severidade e letalidade das ocorrências segmentado por categorias de aeronaves.
