# ⚽️ **Application of Machine Learning for Match Prediction Based on Brazilian Football Championship Data**
👥 Authors: Enzo R. de Oliveira and Renan Souza A. de Leite

The significant increase in the sports betting market in Brazil, especially in football, presentsa pressing need for the creation of more sophisticated prediction systems. This project aims to develop a predictive model for the Brazilian Football Championship, using various specific parameters of each match to generate outcome forecasts - win, lose, or draw.

For the model's implementation, data from past championships from 2015 to 2023 were used, employing various techniques, including a specialized machine learning algorithm and the use of a MLP (Multilayer Perceptron) network as a learning model. The evaluation of the models was based on accuracy, using a confusion matrix.

# 🚀 **Introduction**

Technological advancement has reinvented sports betting, allowing fans to make their predictions through websites and apps, with football being the most betted sport in the country. According to UOL, football accounts for 93% of all bets, followed by basketball (31%) and eSports (29%). Estadão reports that since 2018, the amount invested in sports betting in Brazil revolves around 120-150 billion reais per year.

# 📊 **Database**

The database for this project was obtained from various sources. The main data source was the [Football UK](https://www.football.co.uk/) website, which provided information about matches played and odds. Additional information about team positions was acquired from the Brazilian Football Confederation [CBF](https://www.cbf.com.br/) website. We also used [Transfermarkt](https://www.transfermarkt.com.br/) to obtain data such as market values and team positions per round. In addition, we performed data engineering to add some columns to our data.

# 📈 **Obtained Results**

The performance of the model varied from 2015 to 2023. In 2015, the model had difficulty predicting wins for the visiting team, resulting in an accuracy of 57.14%. There were improvements in 2016 with an accuracy of 61.90%, but still with difficulties in predicting the visiting team.

In 2017, overall performance dropped, with all indices, including accuracy, balanced accuracy, recall, and F1 Score, falling to 47.62%. The model distributed the forecasts similarly among all classes.

Performance improved in 2018 with an accuracy of 66.67% and the model correctly predicted all victories for the visiting team. In 2019 and 2020, accuracy varied little, but challenges persisted in predicting home team wins.

In 2021, the model improved, reaching an accuracy of 66.67%, although it had difficulty predicting draws. In 2022, overall performance dropped again, with all indices decreasing.

However, in 2023, the model achieved perfection with 100% in all indices, but only 9 matches occurred, all resulting in victories for the visiting team. The model has consistently faced challenges in predicting home team wins and draws.

# 💡 **Challenges**

Among the challenges encountered during the development of the model, the unpredictable nature of football, the imbalance of outcome classes, and the manual collection of input data for each match stand out.

# 🎯 **Conclusion**

The model, although not perfect, demonstrated significant results, showing that it is possible to use machine learning techniques to predict football match results. Future improvements may include balancing outcome classes, incorporating new input features, and fine-tuning the learning model.

# 📹 **Access to video presentation**

Youtube video: [Machine Learning Application in the Brazilian Championship in different seasons](https://www.youtube.com/watch?v=fVMqJB_9TiI)

---

# ⚽️ **Aplicação de Machine Learning para Predição de Partidas Baseada em Dados do Campeonato Brasileiro de Futebol**
👥 Autores: Enzo R. de Oliveira e Renan Souza A. de Leite

O aumento expressivo no mercado de apostas esportivas no Brasil, especialmente no futebol, apresenta uma necessidade imperativa para a criação de sistemas de previsão mais sofisticados. Este projeto visa o desenvolvimento de um modelo preditivo para o Campeonato Brasileiro de Futebol, utilizando diversos parâmetros específicos de cada partida para gerar previsões de resultados - vitória, derrota ou empate.

Para a implementação do modelo, foram utilizados dados de campeonatos passados de 2015 a 2023, empregando técnicas variadas, incluindo um algoritmo especializado de aprendizado de máquina e a utilização de uma rede MLP (Multilayer Perceptron) como modelo de aprendizagem. A avaliação dos modelos baseou-se na acurácia, utilizando uma matriz de confusão.

# 🚀 **Introdução**

O avanço tecnológico reinventou as apostas esportivas, permitindo que torcedores realizem suas previsões através de sites e aplicativos, com o futebol sendo a modalidade mais apostada no país. De acordo com a UOL, o futebol responde por 93% do total de apostas, seguido pelo basquete (31%) e eSports (29%). Já o Estadão reporta que, desde 2018, o valor investido em apostas esportivas no Brasil gira em torno de 120-150 bilhões de reais por ano.

# 📊 **Base de Dados**

A base de dados para este projeto foi obtida de diversas fontes. A principal fonte de dados foi o site [Football UK](https://www.football.co.uk/), que forneceu informações sobre partidas disputadas e odds. Informações adicionais sobre as posições das equipes foram adquiridas do site da Confederação Brasileira de Futebol [CBF](https://www.cbf.com.br/). Também recorremos ao [Transfermarkt](https://www.transfermarkt.com.br/) para obter dados como valores de mercado e posições da equipe por rodada. Além disso, realizamos engenharia de dados para adicionar algumas colunas aos nossos dados.

# 📈 **Resultados obtidos**

O desempenho do modelo variou de 2015 a 2023. Em 2015, o modelo teve dificuldade em prever vitórias da equipe visitante, resultando em uma precisão de 57,14%. Houve melhorias em 2016 com uma precisão de 61,90%, mas ainda com dificuldades na previsão da equipe visitante.

Em 2017, o desempenho geral caiu, com todos os índices, incluindo precisão, precisão balanceada, recall e F1 Score, caindo para 47,62%. O modelo distribuiu as previsões de forma semelhante entre todas as classes.

O desempenho melhorou em 2018 com uma precisão de 66,67% e o modelo acertou todas as previsões de vitórias da equipe visitante. Em 2019 e 2020, a precisão variou pouco, mas os desafios persistiram na previsão das vitórias da equipe da casa.

Em 2021, o modelo melhorou, atingindo uma precisão de 66,67%, embora tenha tido dificuldade em prever empates. Em 2022, o desempenho geral caiu novamente, com todos os índices diminuindo.

No entanto, em 2023, o modelo atingiu perfeição com 100% em todos os índices, mas apenas 9 partidas ocorreram, todas resultando em vitórias da equipe visitante. O modelo tem enfrentado desafios consistentes em prever vitórias da equipe da casa e empates.

# 💡 **Desafios**

Entre os desafios encontrados durante o desenvolvimento do modelo, destacam-se a natureza imprevisível do futebol, o desbalanceamento das classes de resultados e a coleta manual de dados de entrada para cada partida.

# 🎯 **Conclusão**

O modelo, embora não seja perfeito, demonstrou resultados significativos, mostrando que é possível utilizar técnicas de aprendizado de máquina para prever resultados de partidas de futebol. Futuras melhorias podem incluir o balanceamento das classes de resultados, incorporação de novos recursos de entrada e ajustes finos no modelo de aprendizagem.

# 📹 **Acesso a apresentação em vídeo**

Vídeo do youtube: [Aplicação Machine Learning no Campeoanto Brasileiro em diferentes temporadas](https://www.youtube.com/watch?v=fVMqJB_9TiI)
