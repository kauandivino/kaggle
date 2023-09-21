# Predição da Doença Arterial Coronariana (DAC) Usando Aprendizado de Máquina

## Introdução
A DAC é uma das principais causas de morte em todo o mundo. A capacidade de prever essa condição pode ter implicações significativas no tratamento precoce e na prevenção. Este projeto explora a aplicação de modelos de aprendizado de máquina para essa tarefa, utilizando um conjunto de dados detalhado que inclui uma variedade de características demográficas, sintomas, resultados de eletrocardiograma e métricas laboratoriais.

## Requisitos
* Python 3.x
* Bibliotecas: pandas, numpy, scikit-learn, tensorflow, keras, matplotlib, seaborn
* Jupyter Notebook

## Como Usar
1. Acesse o Google Colab.
2. No menu superior esquerdo, clique em "File" e depois em "Open notebook" (ou "Arquivo" e "Abrir notebook", dependendo do idioma).
3. Na janela que abrir, vá até a aba "GitHub". Cole o link do repositório na barra de pesquisa e pressione Enter. Os notebooks disponíveis no repositório serão listados abaixo.
4. Abra o notebook Analise_Exploratoria.ipynb para visualizar a análise exploratória dos dados.
5. No início do notebook, importe o conjunto de dados (arquivo CSV) executando a célula com o código que utiliza a função files.upload() do Google Colab. Isto permitirá que você faça o upload do arquivo CSV diretamente do seu computador. Ou então faça o upload do dataset diretamente no ambiente do google colab
6. Execute as células do notebook para ver as análises e gráficos.
7. Repita os passos 4 a 6 para o notebook Modelos_Treinados.ipynb, onde você poderá ver os modelos treinados e os resultados obtidos.
8. Para uma visão detalhada do projeto, metodologia e discussões, você pode baixar e consultar o arquivo documentacao.pdf do repositório GitHub.

## Metodologia
O projeto segue as etapas:

1. Análise Exploratória de Dados (EDA)
2. Pré-processamento e limpeza de dados
3 . Modelagem e treinamento de modelos
4. Avaliação e otimização de modelos
5. Conclusões e insights

## Resultados
Neste projeto, várias técnicas de análise exploratória de dados foram aplicadas para entender as nuances do conjunto de dados relacionado a detecção automática de doenças cardíacas. Isso permitiu a identificação de padrões, tendências e possíveis correlações entre as características dos pacientes e a presença da doença.

Após essa etapa inicial, diversos modelos de machine learning foram treinados e avaliados. Entre eles, Random Forest, Gradient Boosting, Support Vector Machines e Redes Neurais. Cada modelo teve seus hiperparâmetros otimizados para garantir a melhor performance possível.

Os modelos apresentaram performances variadas, com acurácias oscilando entre 85% e 90%. O modelo Gradient Boosting, em particular, destacou-se com uma acurácia de 90.16%, tornando-se uma opção robusta para essa tarefa específica.

Além disso, foi realizada uma análise de importância das características, revelando quais atributos têm mais influência na detecção da doença. Isso pode oferecer insights valiosos para profissionais da saúde ao avaliar pacientes em situações reais..

## Conclusão
Este projeto demonstrou o potencial das técnicas modernas de machine learning na área médica, especificamente na detecção de doenças cardíacas. Através de uma abordagem metódica, desde a análise exploratória até a avaliação dos modelos, conseguimos obter insights valiosos sobre o conjunto de dados e desenvolver modelos com desempenho consideravelmente alto.

A importância das características revelou quais fatores são mais indicativos da presença da doença, o que pode guiar profissionais de saúde em seus diagnósticos. A combinação de conhecimento médico com ferramentas de análise de dados pode revolucionar a maneira como diagnósticos são feitos, tornando-os mais precisos e eficazes.

É importante ressaltar que, apesar dos bons resultados obtidos, o modelo é apenas tão bom quanto os dados em que foi treinado. Portanto, sempre é crucial ter cuidado ao aplicar tais modelos em ambientes clínicos reais, garantindo que sejam usados como uma ferramenta auxiliar, e não como um substituto para o julgamento clínico humano.

No geral, este projeto serviu como uma prova de conceito da aplicação de técnicas de machine learning na área de cardiologia e destacou a importância da colaboração entre as áreas de tecnologia e medicina.



