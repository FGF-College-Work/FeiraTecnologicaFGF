# Detalhamento do assunto a ser pesquisado - Base de Conhecimento 

- **Conteudo**
  - [Reconhecimento de padrões](#reconhecimento-de-padrões)
  - [Aplicações](#aplicações)
  - [Algoritmos](#algoritmos)
  - [Ver também](#ver-também)
  - [Referências](#referências)
  - [Ligações externas](#ligações-externas)


O reconhecimento de padrões é um campo maduro, mas excitante e de desenvolvimento rápido, que sustenta desenvolvimentos em campos conhecidos, como visão computacional, processamento de imagem, análise de texto e documentos e redes neurais. É semelhante ao aprendizado de máquinas, e também encontra aplicações em áreas emergentes rápidas, como biometria, bioinformática, análise de dados multimídia e, mais recentemente, ciência dos dados. O jornal Pattern Recognition foi estabelecido há cerca de 50 anos, já que o campo emergiu nos primeiros anos da ciência da computação. Durante os anos intermediários, expandiu-se consideravelmente.

### Reconhecimento de Padrões

Reconhecimento de padrões é uma área da ciência cujo objetivo é a classificação de objetos dentro de um número de categorias ou classes. Esses objetos de estudo variam de acordo com cada aplicação, podem ser imagens, sinais em forma de ondas (como voz, luz, rádio) ou qualquer tipo de medida que necessite ser classificada. Tendo aplicação em vários campos, tais como psicologia, etologia e ciência da computação.

O reconhecimento de padrões tem uma longa história, mas antes de 1960 era formada principalmente por estatística teórica. O surgimento de computadores aumentou a demanda por aplicação práticas capazes de reconhecer padrões, que criaram novas demandas por desenvolvimentos teóricos. Como nossa sociedade evolui de uma fase industrial para uma fase pós-industrial, automação da produção industrial e a necessidade de modelos capazes de lidar com e recuperar informação se tornar cada vez mais importantes. Essa tendência estimula o reconhecimento de padrões para além dos limites de conhecimento e aplicação de hoje. Reconhecer padrões é hoje uma parte fundamental da maior parte dos sistemas de tomada de decisão.

Um sistema completo de reconhecimento de padrões consiste de um sensor que obtém observações a serem classificadas ou descritas; um mecanismo de extração de características que computa informações numéricas ou simbólicas das observações; e um esquema de classificação das observações, que depende das características extraídas.

O esquema de classificação é geralmente baseado na disponibilidade de um conjunto de padrões que foram anteriormente classificados, o "conjunto de treinamento"; o resultado do aprendizado é caracterizado como um aprendizado supervisionado. O aprendizado pode também ser não supervisionado, de forma que o sistema não recebe informações a priori dos padrões, estabelecendo então as classes dos padrões através de análise de padrões estatísticos.

### Aplicações

Aplicações típicas do reconhecimento de padrões incluem reconhecimento de fala, classificação de documentos em categorias (por exemplo, mensagens de correio eletrônico que são spam ou não), reconhecimento de escrita, reconhecimento de faces. Os últimos dois temas são tópicos do campo de processamento de imagens.

Dentro da ciência médica, o reconhecimento de padrões é a base para sistemas de diagnóstico por computador (CAD). O CAD descreve um procedimento que apóia as interpretações e descobertas do médico. Outras aplicações típicas de técnicas de reconhecimento de padrões são o reconhecimento automático de fala, classificação de texto em várias categorias (por exemplo, mensagens de e-mail sem spam / não-spam), reconhecimento automático de códigos postais manuscritos em envelopes postais, reconhecimento automático de imagens de rostos humanos ou extração de imagem manuscrita de formas médicas. [7] Os dois últimos exemplos formam a análise de imagens subtópicas do reconhecimento de padrões que trata de imagens digitais como entrada para sistemas de reconhecimento de padrões.

O reconhecimento óptico de caracteres é um exemplo clássico da aplicação de um classificador de padrões, veja o exemplo OCR. O método de assinatura do nome foi capturado com caneta e sobreposição a partir de 1990. [precisão] Os cursos, a velocidade, o min relativo, o maximo relativo, a aceleração e a pressão são usados para identificar e confirmar identidade. Os bancos foram oferecidos pela primeira vez nesta tecnologia, mas se contentaram em cobrar da FDIC por qualquer fraude bancária e não quer prejudicar os clientes. 

As redes neurais artificiais (classificadores de redes neurais) e o aprendizado profundo têm muitas aplicações do mundo real no processamento de imagens, alguns exemplos: identificação e autenticação: por exemplo, reconhecimento de placa de licença, análise de impressão digital e detecção / verificação de rosto; diagnóstico médico: por exemplo, triagem para câncer cervical (Papnet) ou tumores mamários; defesa: vários sistemas de navegação e orientação, sistemas de reconhecimento de alvo, tecnologia de reconhecimento de formas, etc.

Para uma discussão sobre as aplicações acima mencionadas de redes neurais no processamento de imagens, veja o trabalho de Egmont-Petersen et al, "Image processing with neural networks - a review". Pattern Recognition.

Na psicologia, o reconhecimento de padrões (fazer sentido e identificar objetos) está intimamente relacionado com a percepção, o que explica como os insumos sensoriais que os seres humanos recebem são tornados significativos. O reconhecimento de padrões pode ser pensado de duas maneiras diferentes: o primeiro sendo o modelo de correspondência e o segundo sendo a detecção de recursos. Um modelo é um padrão usado para produzir itens das mesmas proporções. A hipótese de correspondência de modelos sugere que os estímulos recebidos sejam comparados com modelos na memória de longo prazo. Se houver uma correspondência, o estímulo é identificado. Os modelos de detecção de recursos, como o sistema Pandemonium para classificação de letras (Selfridge, 1959), sugerem que os estímulos são divididos em componentes para identificação. Por exemplo, uma E principal tem três linhas horizontais e uma linha vertical.

### Algoritmos

Algoritmos para o reconhecimento de padrões dependem do tipo de saída do rótulo, se o aprendizado é supervisionado ou não supervisionado, e se o algoritmo é de natureza estatística ou não estatística. Os algoritmos estatísticos podem ainda ser categorizados como generativos ou discriminativos.

- Classification algorithms (supervised algorithms predicting categorical labels)
- Main article: Statistical classification

  - Parametric:
    - Linear discriminant analysis
    - Quadratic discriminant analysis
    - Maximum entropy classifier (aka logistic regression, multinomial logistic regression): Note that logistic regression is an algorithm for classification, despite its name. (The name comes from the fact that logistic regression uses an extension of a linear regression model to model the probability of an input being in a particular class.)

  - Nonparametric:
    - Decision trees, decision lists
    - Kernel estimation and K-nearest-neighbor algorithms
    - Naive Bayes classifier
    - Neural networks (multi-layer perceptrons)
    - Perceptrons
    - Support vector machines
    - Gene expression programming

- Clustering algorithms (unsupervised algorithms predicting categorical labels)
- Main article: Cluster analysis

  - Categorical mixture models
  - Deep learning methods[citation needed]
  - Hierarchical clustering (agglomerative or divisive)
  - K-means clustering
  - Correlation clustering
  - Kernel principal component analysis (Kernel PCA)

- Ensemble learning algorithms (supervised meta-algorithms for combining multiple learning algorithms together)
- Main article: Ensemble learning

  - Boosting (meta-algorithm)
  - Bootstrap aggregating ("bagging")
  - Ensemble averaging
  - Mixture of experts, hierarchical mixture of experts

- General algorithms for predicting arbitrarily-structured (sets of) labels

  - Bayesian networks
  - Markov random fields

- Multilinear subspace learning algorithms (predicting labels of multidimensional data using tensor representations)

  - Unsupervised:

    - Multilinear principal component analysis (MPCA)

- Real-valued sequence labeling algorithms (predicting sequences of real-valued labels)
- Main article: sequence labeling

  - Supervised:

    - Kalman filters
    - Particle filters

- Regression algorithms (predicting real-valued labels)
- Main article: Regression analysis

  - Supervised:

    - Gaussian process regression (kriging)
    - Linear regression and extensions
    - Neural networks and Deep learning methods

  - Unsupervised:

    - Independent component analysis (ICA)
    - Principal components analysis (PCA)

- Sequence labeling algorithms (predicting sequences of categorical labels)

  - Supervised:

    - Conditional random fields (CRFs)
    - Hidden Markov models (HMMs)
    - Maximum entropy Markov models (MEMMs)
    - Recurrent neural networks

  - Unsupervised:

    - Hidden Markov models (HMMs)




### Ver também

- Aprendizagem de máquina
- FAN (rede neural)
- Teoria dos Padrões

### Referências

- Sergios Theodoridis, Konstantinos Koutroumbas (2006). Pattern Recognition 3 ed. [S.l.]: Elsevier. [ISBN 0-12-369531-7](https://pt.wikipedia.org/wiki/Especial:Fontes_de_livros/0-12-369531-7)
- C.M. van der Walt e E. Barnard (2006). [Data characteristics that determine classifier performance](http://www.patternrecognition.co.za/). Proceedings of the Sixteenth Annual Symposium of the Pattern Recognition Association of South Africa: [s.n.] pp. 160–165. ISBN 34523432 Verifique |isbn= (ajuda)
- Phiroz Bhagat (2005). Pattern Recognition in Industry. [S.l.]: Elsevier. ISBN 0-08-044538-1
- Richard O. Duda, Peter E. Hart, David G. Stork. Pattern classification 2 ed. Nova Iorque: Wiley. ISBN 0-471-05669-3
- Dietrich Paulus e Joachim Hornegger (1998). Applied Pattern Recognition 2 ed. [S.l.]: Vieweg. ISBN 3-528-15558-2
- J. Schuermann (1996). Pattern Classification: A Unified View of Statistical and Neural Approaches. [S.l.]: Wiley&Sons. ISBN 0-471-13534-8
- Sholom Weiss e Casimir Kulikowski (1991). Computer Systems That Learn. [S.l.]: Morgan Kaufmann. ISBN 1-55860-065-5
- 13 Egmont-Petersen, M., de Ridder, D., Handels, H. (2002). "Image processing with neural networks - a review". Pattern Recognition. 35 (10): 2279–2301. doi:10.1016/S0031-3203(01)00178-9

### Ligações externas

- [Sítio da Associação Internacional de Reconhecimento de Padrões - IAPR](http://www.iapr.org/)
