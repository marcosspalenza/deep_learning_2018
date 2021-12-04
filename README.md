# Deep Learning - PPGEE/UFES 2018

- Disciplina: Tópicos Especiais em Engenharia Biomédica e Processamento de Sinais: Redes de Aprendizado Profundo.

- Ministrado por: Prof. Dr. Jorge Leonid Aching Samatelo. 

Trabalhos de Deep Learning (2018) disciplina do Programa de Pós-Graduação em Engenharia Elétrica da Universidade Federal do Espírito Santo (UFES).

Trabalho final foi realizado com [EMNIST dataset](https://www.nist.gov/itl/products-and-services/emnist-dataset) com 814.255 amostras e 62 classes. A tarefa é de reconhecimento de caracteres por imagem, com amostras de diferentes caligrafias para todas as letras do alfabeto. É um problema clássico da Computação, o objetivo é analisar a escrita humana via métodos computacionais. O experimento realizado foi simplificado para 36 classes (sem *case sensitive*) com 10 dígitos e 26 letras do alfabeto escritas à mão. Em aspectos gerais, o desafio é equivalente ao tradicional [MNIST dataset](https://www.tensorflow.org/datasets/catalog/mnist), porém apresenta complexidade bem maior do que a classificação dos caracteres numéricos (Cohen; 2017).

Todos os testes foram realizados via [Google Colab](https://colab.research.google.com/).


# Referências

Cohen, G. Afshar, S. Tapson, J. Van Schaik, A. [EMNIST: Extending MNIST to Handwritten Letters](https://arxiv.org/abs/1702.05373v1). Proceedings of the International Joint Conference on Neural Networks (IJCNN' 2017). pp. 2921-2926. 2017.

Goodfellow, I. Bengio, Y. Courville, A. [Deep Learning](https://www.deeplearningbook.org/). MIT press. 2016.