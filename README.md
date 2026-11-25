🎥 **Vídeo de demonstração do experimento de 1 tanque (MATLAB + Factory I/O):** [Assistir ao vídeo](https://youtu.be/Z7RZSBbpD1g)

# COS360 — Otimização e Controle de Nível de Tanques

Este material reúne a apresentação, o relatório e os notebooks desenvolvidos para o projeto de otimização e controle de nível de tanques.

## Arquivos

### `Apresentacao_COS360_Tanques_Graficos.pdf`
PDF com os slides utilizados na apresentação do projeto. Resume o problema de otimização, a modelagem dos tanques, a formulação das funções objetivo e restrições, os experimentos e a generalização para múltiplos tanques.

### `Codigos_Utilizados_No_Matlab_FactoryIO.ipynb`
Notebook de caráter **informativo**, que reúne e apresenta os códigos implementados em MATLAB para os experimentos com o Factory I/O. **Não é um notebook executável no ambiente Python.** Para executar os códigos, é necessário utilizar o MATLAB e configurar adequadamente os parâmetros de comunicação e a cena do Factory I/O.

### `Relatorio_Otimizacao_Atualizado.pdf`
Relatório técnico do projeto. Apresenta a formulação matemática, desde o modelo dinâmico dos tanques até o problema de otimização, incluindo as funções objetivo, as restrições e o método SQP. Também reúne as análises dos gráficos e resultados obtidos nos experimentos em MATLAB/Factory I/O e nas simulações em Python.

### `SLSQP_Umtanque_DoisTanques.ipynb`
Notebook com as simulações em Python utilizando o método SLSQP. As simulações foram desenvolvidas como uma tentativa de reproduzir, no ambiente Python, o comportamento dos experimentos realizados com MATLAB e Factory I/O. O notebook permite acompanhar essa implementação e comparar seus resultados com os ensaios na plataforma original.

## Observações

- O vídeo demonstra o experimento de **um tanque** executado com MATLAB e Factory I/O.
- O notebook `Codigos_Utilizados_No_Matlab_FactoryIO.ipynb` documenta os códigos MATLAB; ele não substitui a execução no MATLAB.
- O notebook `SLSQP_Umtanque_DoisTanques.ipynb` contém as simulações desenvolvidas em Python, separadas da implementação conectada ao Factory I/O.
