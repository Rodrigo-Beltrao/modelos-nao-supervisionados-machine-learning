# modelos-nao-supervisionados-machine-learning

Este projeto tem como objetivo realizar uma análise de dados exploratória e demonstrar a aplicação de algoritmos de agrupamento em um conjunto de dados relacionados a sensores. Os passos abordados no projeto incluem:

    Criação e Manipulação de Matrizes:
        Geração de duas matrizes 3x3 a partir de números aleatórios entre 0 e 1.
        Multiplicação das duas matrizes para demonstrar operações matriciais.

    Carregamento de Dados:
        Carregamento de dados do arquivo "dataset.csv" para um DataFrame utilizando a biblioteca Pandas.

    Visualização de Dados:
        Criação de histogramas para as variáveis "Humidity" e "Temperature" para compreender a distribuição dos dados.

    Evolução Temporal da Pressão:
        Apresentação da evolução média por minuto da variável "Pressure".

    Filtro de Dados Outliers:
        Criação de uma função de filtro para remover as 5% maiores e menores leituras de temperatura e umidade.

    Histogramas Pós-Filtro:
        Geração de novos histogramas das colunas de temperatura e umidade após a operação de limpeza.

    Comparação de Histogramas:
        Comparação das frequências em ambos os histogramas, destacando as semelhanças e diferenças.

    Impacto da Eliminação de Dados Extremos:
        Explicação sobre como a eliminação de dados extremos afetou a distribuição dos histogramas.

    Métricas de Avaliação de Associações:
        Apresentação das métricas Suporte, Confiança e Lift utilizadas para avaliar associações.

    Poda de Algoritmo de Associações:
        Discussão sobre como a métrica de suporte mínimo é utilizada para "poda" do algoritmo.

    Formato Obrigatório para o Algoritmo Apriori:
        Explicação sobre o formato necessário para a base de dados que será processada pelo algoritmo Apriori.

    Aplicabilidade do Apriori em Classificação:
        Explicação de que o algoritmo de associações Apriori não é adequado para problemas de classificação.

    Diferença entre Agrupamentos e Classificação:
        Diferenciação entre os algoritmos de agrupamento e classificação, destacando seus propósitos.

    Limitações do Algoritmo K-Means:
        Discussão sobre as limitações do algoritmo K-Means, como sensibilidade a outliers e determinação de clusters.

    Estabelecimento do Número Ideal de Grupos:
        Utilização da base de dados "Wine" para determinar o número ideal de grupos utilizando o Método de Elbow.

    Aplicação do Algoritmo K-Means:
        Utilização do algoritmo K-Means com o número de grupos ideal na base de dados "Wine".

Este projeto visa fornecer insights sobre a análise exploratória de dados e a aplicação de algoritmos de agrupamento. Ele demonstra como realizar operações matriciais, carregar dados, visualizar distribuições, aplicar filtros, avaliar métricas e explorar algoritmos de agrupamento como o K-Means. As etapas descritas permitem entender melhor os dados e suas características, bem como identificar padrões relevantes para tomadas de decisão futuras.
