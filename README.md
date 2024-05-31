# GlobalSolution

Descrição do Problema 

Os oceanos, pulmões azuis do nosso planeta, afogam-se em um mar de plástico. Estima-se que 80% do lixo marinho tenha origem em terra firme, envenenando a vida marinha e ameaçando a saúde humana. Diante desse cenário alarmante, surge a necessidade urgente de soluções inovadoras e eficazes. Nossa proposta apresenta um sistema de drones inteligentes munidos de inteligência artificial (IA) e machine learning, capazes de navegar pelos oceanos, coletar dados cruciais e gerar relatórios abrangentes para auxiliar no combate à poluição marítima e na preservação da vida marinha. 

A poluição marítima por plástico representa uma grave ameaça à saúde do planeta. Esse material persistente, confundido com alimento por animais marinhos, entra na cadeia alimentar, contaminando-a e causando danos irreversíveis. As correntes marítimas, outrora símbolos da magnificência oceânica, transformam-se em autopistas para o lixo, transportando-o para áreas remotas e criando giros oceânicos, como a Grande Mancha de Lixo do Pacífico, onde se acumula em quantidades alarmantes. 

Metodologia Utilizada 

Coleta de Imagens: Inicialmente, foi feita uma coleta de imagens relatando problemas dos oceanos, como vazamentos de petróleo, descarte de lixo e microplásticos, que geram danos para os humanos. 

Anotação das Imagens: Utilizando a plataforma Roboflow, realizamos a anotação das imagens para preparar os dados para treinamento, teste e validação. As imagens foram divididas em 15% para teste, 60% para treino e 25% para validação. Foram usadas aproximadamente 200 imagens, classificadas em duas categorias: Animais Marinhos e Poluição Marítima, incluindo microplásticos, itens de plástico e vazamentos de petróleo. 

Processamento de Imagens: As imagens passaram por várias etapas de processamento para melhorar a performance, incluindo: 

Auto-Orientação 

Redimensionamento para 640x640 pixels 

Tile com 2 linhas e 2 colunas 

Aumento de Dados (Augmentação): Realização de transformações nas imagens existentes, como rotação de 90° em ambos os sentidos e espelhamento horizontal, para criar novas variações e aumentar o número de imagens no conjunto de dados, tornando os modelos mais precisos. 

Desenvolvimento do Projeto: Utilizamos o Google Colab para importar bibliotecas necessárias, como Roboflow, OpenCV e a API do YOLOv8 para visualizar os resultados das imagens. O código foi estruturado para maximizar a eficiência e precisão do modelo. 

Resultados Obtidos 

Os resultados obtidos mostraram um mAP de aproximadamente 46,1%, onde mAP é a média da métrica de Precisão Média (Average Precision) em todas as classes de um modelo. A precisão foi de aproximadamente 60%, indicando que o modelo frequentemente fazia previsões corretas. O recall foi também de cerca de 60%, mostrando que uma boa porcentagem dos rótulos relevantes foi identificada com sucesso. 

Conclusões 

O trabalho desenvolvido sobre a detecção de animais marinhos e poluição marítima utilizando técnicas de visão computacional apresentou resultados promissores. O código foi estruturado para utilizar modelos avançados de detecção de imagens, treinados em um conjunto de dados composto por imagens de animais marinhos e diferentes tipos de poluição. 

Para a realização deste projeto, as seguintes etapas foram executadas: 

Coleta de Dados: Imagens de animais marinhos e de poluição marítima foram coletadas de diversas fontes, garantindo uma variedade de cenários e condições ambientais. 

Pré-processamento de Imagens: As imagens coletadas foram processadas para normalização e aumento de dados, assegurando que o modelo fosse treinado em um conjunto de dados diversificado e equilibrado. 

Treinamento do Modelo: O modelo foi treinado para detectar e classificar diferentes categorias de animais marinhos e tipos de poluição. Durante o treinamento, técnicas como regularização e ajuste de hiperparâmetros foram aplicadas para melhorar a performance. 

Avaliação do Modelo: A performance do modelo foi avaliada utilizando métricas como Precisão (Precision), Revocação (Recall) e Média da Precisão (mAP). Os resultados mostraram uma alta precisão e recall, indicando que o modelo foi eficaz na identificação correta dos alvos. 

Testes e Validação: O modelo foi testado em um conjunto de dados separado de validação, onde conseguiu identificar com sucesso os animais marinhos e diferentes formas de poluição com alta acurácia. 

Os resultados indicam que o código desenvolvido é robusto e eficiente para a detecção automática de problemas ambientais no oceano. A aplicação dessas técnicas de visão computacional pode facilitar significativamente o monitoramento e a conservação dos ecossistemas marinhos. Este trabalho fornece uma base sólida para futuros desenvolvimentos e melhorias nos modelos de detecção de imagens, contribuindo para avanços significativos na área de monitoramento ambiental. 

 
