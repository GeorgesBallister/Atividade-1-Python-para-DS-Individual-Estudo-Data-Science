# 🏫 Atividade I - Python para DS (Individual) Estudo Data Science

## Informações do Projeto

Este projeto tem como objetivo aplicar os conhecimentos em Python e Data Science para a execução de um processo de **ETL (Extração, Transformação e Exportação)** utilizando o dataset **MovieLens Latest Datasets SMALL**. O estudo foca na análise das avaliações de filmes, permitindo a identificação de padrões e insights a partir dos dados.

- **Dataset Utilizado:** MovieLens Latest Datasets SMALL  
- **Link do Dataset:** [ml-latest-small.zip](https://files.grouplens.org/datasets/movielens/ml-latest-small.zip)  
- **Tamanho Compactado:** 1MB  
- **Tamanho Descompactado:** 5.45MB  

> ⚠️ O exemplo de amostragem dos dados pode variar conforme o momento do download, pois o site da MovieLens atualiza os dados periodicamente. Caso deseje, utilize os dados presentes neste repositório.

---

## Objetivos do Projeto

- **Extração (E):** Carregar os dados dos arquivos CSV (ratings e movies).  
- **Transformação (T):** Realizar a limpeza, renomeação e tratamento dos dados, além de calcular estatísticas descritivas e gerar visualizações para análise exploratória.  
- **Integração:** Cruzar os dados dos filmes com as médias das avaliações para enriquecer a análise.  
- **Exportação (L):** Salvar os resultados consolidados em um novo arquivo CSV para uso futuro.

---

## Ambiente e Ferramentas Utilizadas

![VS Code](./Imagens/Print%201.png)

- **Ambiente de Desenvolvimento:** Jupyter Notebook configurado no VS Code.  
- **Linguagem:** Python  
- **Principais Bibliotecas:**
  - **Pandas:** Manipulação e tratamento dos dados.
  - **Seaborn:** Geração de visualizações e gráficos.
  - **Matplotlib (Pyplot):** Configuração e exibição dos plots.



---

# Rodando o projeto localmente

> Caso o codigo não rode localmente na sua maquina voce pode subistituir o seguinte codigo  pelo caminho dos arquivos

```python
notasDS = pd.read_csv("CAMINHO CORRETO DO ARQUIVO/ratings.csv")
```

---

## Análise Exploratória e Storytelling

- **Distribuição das Notas:**  
  A análise dos gráficos revela a dispersão dos valores, nos fazendo encontrar uma normalização nos valores dos dados.


- **Insights e Considerações:**  
  - A média geral das notas se aproxima de 3.5, indicando uma distribuição equilibrada.  
  - Alguns filmes apresentam avaliações fora do padrão, sugerindo possíveis polarizações de opinião.  

---

## Conclusões e Próximos Passos

- **Principais Descobertas:**  
  - O processo de ETL permitiu a consolidação dos dados de avaliações e informações dos filmes.  
  - A visualização dos dados ajudou a evidenciar a distribuição das notas.

---

## Considerações Finais

Este projeto me ajudou a entender melhor como funciona a estruturação do python com relação a analize dos dados e os processos que estruturam os deveres de um cientista de dados, ao decorrer do codigo você pode perceber que eu fiz dezenas e inumeros comentarios apra explicar oque estava acontecendo, assim consolidando o meu conhecimento da linguagem para essa finalidade

> OBS:
> Sim, esta foi a primeira vez que eu fiz um join dentro desta linguagem, e a praticidade disto expandiu a minha mente para dezenas de novas possibilidades.

---

*Projeto desenvolvido por: **Georges Ballister de Oliveira***