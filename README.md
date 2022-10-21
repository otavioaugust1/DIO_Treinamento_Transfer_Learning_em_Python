<h1>DIO_Treinamento_Transfer_Learning_em_Python</h1>

<h1>DIO_transfer_learning-AI_de_reconhecimento</h1>

<h2>Transfer learning / fine-tuning / Transferência de aprendizado / ajuste fino</h2>

<p>Este tutorial o guiará pelo processo de uso do aprendizado de transferência para aprender um classificador de imagem preciso a partir de um número relativamente pequeno de amostras de treinamento. De um modo geral, a aprendizagem de transferência refere-se ao processo de alavancar o conhecimento aprendido em um modelo para o treinamento de outro modelo.</p>
 <p>Mais especificamente, o processo envolve pegar uma rede neural existente que foi previamente treinada para um bom desempenho em um conjunto de dados maior e usá-la como base para um novo modelo que aproveita a precisão da rede anterior para uma nova tarefa. Este método tornou-se popular nos últimos anos para melhorar o desempenho de uma rede neural treinada em um pequeno conjunto de dados; a intuição é que o novo conjunto de dados pode ser muito pequeno para ser treinado para um bom desempenho por si só, mas sabemos que a maioria das redes neurais treinadas para aprender recursos de imagem geralmente aprendem recursos semelhantes de qualquer maneira, especialmente nas camadas iniciais, onde são mais genéricos (detectores de borda, bolhas, e assim por diante). </p>

<p>A aprendizagem por transferência foi amplamente possibilitada pelo código aberto de modelos de última geração; para os modelos de melhor desempenho em tarefas de classificação de imagens (como do ILSVRC), é prática comum agora não apenas publicar a arquitetura, mas também liberar os pesos treinados do modelo. Isso permite que amadores usem esses classificadores de imagem para aumentar o desempenho de seus próprios modelos específicos de tarefas.
</p>


# 
 

## Projeto de Transfer Learning em Python

O projeto consiste em aplicar o método de Transfer Learning em uma rede de Deep Learning na linguagem Python no ambiente COLAB. 

Para exemplo, utilizaremos o seguinte projeto que realiza Transfer Learning com o Dataset do MNIST:  

https://colab.research.google.com/github/kylemath/ml4a-guides/blob/master/notebooks/transfer-learning.ipynb

O dataset utilizado engloba duas classes: gatos e cachorros. Uma descrição da base de dados pode ser visualizada neste link: https://www.tensorflow.org/datasets/catalog/cats_vs_dogs.  Já o dataset para download pode ser acessado por meio deste outro link: https://www.microsoft.com/en-us/download/details.aspx?id=54765.

Observações: Neste projeto, você pode usar sua própria base de dados (exemplo: fotos suas, dos seus pais, dos seus amigos, dos seus animais domésticos, etc), o exemplo de gatos e cachorros, pode ser substituído por duas outras classes do seu interesse. 

O projeto deve ser enviado para o GitHub da DIO: https://github.com/digitalinnovationone. 




