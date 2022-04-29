# Trabalho 3

Esse trabalho foi desenvolvido utilizando o google colab, pep8 e pylint. A instalação dos componentnes do colab estão diretamente no notebook.

Nele utilizamos um dataset proposto pelo Dataquest com informações técnicas de veículos, limpamos e tratamos os dados. Depois disso fomos utilizar modelos de
Machine Learning, modelos k-nearest neighbors univariados e multivariados e no final houve um ajuste de hiperparâmetros para melhorar seu desempenho.
## Pep8

Essa ferramenta funcinou perfeitamente, contudo como o notebook é dividido em células foi necessário rodar o comando em cada célula, além disso tive problemas na execução
autopet no google colab.

## Pylint

Durante a execução do Pylint no colab algums problemas foram percebidos, pelo que compreendi a ferramenta não suporta ler um arquivo .ipynb e portanto
ocorreram diversas mensagens de erro difíceis de compreender e inconclusivas, no final a fiquei com nota 0/10. Aqui irei mostrar algumasm mensagens de
erro que é possível verificar no final do notebook:

```
drive/MyDrive/mlops/basics.ipynb:1:0: C0304: Final newline missing (missing-final-newline)
drive/MyDrive/mlops/basics.ipynb:1:0: C0301: Line too long (88567/100) (line-too-long)
drive/MyDrive/mlops/basics.ipynb:1:561: E0602: Undefined variable 'null' (undefined-variable)
drive/MyDrive/mlops/basics.ipynb:1:70971: E0602: Undefined variable 'null' (undefined-variable)
-----------------------------------
Your code has been rated at 0.00/10>
```
