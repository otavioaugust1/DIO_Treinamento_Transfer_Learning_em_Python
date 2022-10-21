<h1>DIO_transfer_learning-AI_de_reconhecimento</h1>

<h2>Transfer learning / fine-tuning / Transferência de aprendizado / ajuste fino</h2>

<p>Este tutorial o guiará pelo processo de uso do aprendizado de transferência para aprender um classificador de imagem preciso a partir de um número relativamente pequeno de amostras de treinamento. De um modo geral, a aprendizagem de transferência refere-se ao processo de alavancar o conhecimento aprendido em um modelo para o treinamento de outro modelo.</p>
 <p>Mais especificamente, o processo envolve pegar uma rede neural existente que foi previamente treinada para um bom desempenho em um conjunto de dados maior e usá-la como base para um novo modelo que aproveita a precisão da rede anterior para uma nova tarefa. Este método tornou-se popular nos últimos anos para melhorar o desempenho de uma rede neural treinada em um pequeno conjunto de dados; a intuição é que o novo conjunto de dados pode ser muito pequeno para ser treinado para um bom desempenho por si só, mas sabemos que a maioria das redes neurais treinadas para aprender recursos de imagem geralmente aprendem recursos semelhantes de qualquer maneira, especialmente nas camadas iniciais, onde são mais genéricos (detectores de borda, bolhas, e assim por diante). </p>

<p>A aprendizagem por transferência foi amplamente possibilitada pelo código aberto de modelos de última geração; para os modelos de melhor desempenho em tarefas de classificação de imagens (como do ILSVRC), é prática comum agora não apenas publicar a arquitetura, mas também liberar os pesos treinados do modelo. Isso permite que amadores usem esses classificadores de imagem para aumentar o desempenho de seus próprios modelos específicos de tarefas.
</p>





