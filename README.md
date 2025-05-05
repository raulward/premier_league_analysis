# Premier League Data Analysis

Este repositório contém uma análise exploratória de dados (EDA) de partidas da Premier League inglesa. A análise foi realizada em um Jupyter Notebook (`premier_league_analysys.ipynb`) e gera diversos gráficos que ilustram padrões de gols, finalizações, disciplina e desempenho de equipes ao longo das temporadas.

## 📝 Requisitos

- Python 3.8 ou superior  
- Jupyter Notebook  
- Dependências (listar em `requirements.txt`):
  ```
  pandas
  numpy
  matplotlib
  seaborn
  ```
  
Para instalar todas de uma vez:
```bash
pip install -r requirements.txt
```

## 🚀 Como executar

1. Clone este repositório.  
2. Coloque o arquivo de dados (`England CSV.csv`) no mesmo diretório do notebook.  
3. Abra o notebook:
   ```bash
   jupyter notebook premier_league_analysys.ipynb
   ```
4. Execute todas as células em ordem.  
5. Os gráficos serão salvos automaticamente no diretório de trabalho com os seguintes nomes:
   - `boxplots_gols.svg`  
   - `histogram_gols.svg`  
   - `boxplots_cartoes.svg`  
   - `off_def_ration.svg`  
   - `champs_epl.svg`  
   - `wins_and_losses.svg`  

## 📊 Principais Insights

### 1. Distribuição de Gols por Mandante e Visitante  
O boxplot abaixo mostra a distribuição de gols marcados pelo mandante versus visitante. Observa-se uma vantagem clara para o mandante, cuja mediana de gols é consistentemente mais alta.  
![Distribuição de Gols](./assets/boxplots_gols.svg)

---

### 2. Finalizações ao Gol  
O histograma a seguir ilustra a frequência de finalizações no alvo (`shots on target`) para mandantes e visitantes. O time da casa mantém média superior, reforçando o fator mando de campo como vantagem ofensiva.  
![Histograma de Finalizações ao Gol](./assets/histogram_gols.svg)

---

### 3. Distribuição de Cartões  
Analisando cartões amarelos e vermelhos, percebe-se que os visitantes recebem ligeiramente mais cartões, possivelmente devido à postura mais defensiva ou falta de familiaridade com o estádio adversário.  
![Distribuição de Cartões](./assets/boxplots_cartoes.svg)

---

### 4. Evolução de Gols Marcados vs Sofridos  
Neste gráfico de razão ofensiva/defensiva, observamos como cada equipe evoluiu ao longo das temporadas em termos de gols marcados e sofridos. Alguns clubes exibem tendência de crescimento constante no ataque, enquanto outros apresentam oscilações defensivas.  
![Evolução Gols Marcados e Sofridos](./assets/off_def_ration.svg)

---

### 5. Distribuição de Títulos da Premier League  
Entre as temporadas 2000/01 e 2024/25, Manchester City lidera no número de troféus, seguido por Manchester United, Chelsea, Arsenal, Liverpool e Leicester.  
![Campeões da Premier League](./assets/champs_epl.svg)

---

### 6. Vitórias e Derrotas Acumuladas  
O gráfico abaixo mostra o total de vitórias versus derrotas por clube. Manchester City e Manchester United aparecem no topo das vitórias, enquanto equipes como West Ham, Everton e Newcastle concentram mais derrotas.  
![Vitórias vs Derrotas](./assets/wins_and_losses.svg)

---

## 🎯 Conclusão

Esta análise explora características fundamentais das partidas da Premier League: vantagem de campo, padrões de finalização, disciplina e performance histórica de títulos e resultados. Sinta-se à vontade para estender o estudo, adicionar novas métricas ou comparar com outras ligas.
