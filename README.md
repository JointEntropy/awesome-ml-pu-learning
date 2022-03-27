# Awesome ML Positive Unlabeled learning

### Papers
<!-- MarkdownTOC depth=4 -->
- [Papers \\w code](#papers)
  - [Overview](#overview)
    - [Learning from positive and unlabeled data: a survey(2018)](https://arxiv.org/abs/1811.04820)
    - [Positive and unlabeled learning algorithms and applications: A survey(2019)](https://www.researchgate.net/profile/Kristen-Jaskie/publication/337503578_Positive_And_Unlabeled_Learning_Algorithms_And_Applications_A_Survey/links/609b0124458515d31513c2e9/Positive-And-Unlabeled-Learning-Algorithms-And-Applications-A-Survey.pdf)
  - [Cost-sensitive methods](#cost-sensitive)
    - [Learning Classifiers from Only Positive and Unlabeled Data(2008)](https://cseweb.ucsd.edu/~elkan/posonly.pdf)\[[pulearn](https://github.com/pulearn/pulearn#31elkanoto)\]
    - [Analysis of Learning from Positive and Unlabeled Data(2014)](https://papers.nips.cc/paper/2014/file/35051070e572e47d2c26c241ab88307f-Paper.pdf)
  - [Sample-selection/Two-step methods](#sample-selection)
    - [A bagging SVM to learn from positive and unlabeled examples(2013)](https://members.cbio.mines-paristech.fr/~jvert/svn/bibli/local/Mordelet2013bagging.pdf) \[[pulearn](https://github.com/pulearn/pulearn#32bagging-based-pu-learning)\]
    - [Improving Positive Unlabeled Learning: Practical AUL Estimation and New Training Method for Extremely Imbalanced Data Sets(2020)](https://arxiv.org/pdf/2004.09820.pdf)
    - [PULNS: Positive-Unlabeled Learning with Effective Negative Sample Selector(2021)](https://ojs.aaai.org/index.php/AAAI/article/view/17064/16871)\[[slides](https://slideslive.com/38948747/pulns-positiveunlabeled-learning-with-effective-negative-sample-selector)\]

### Implementations
- [Frameworks](#frameworks)
  - [Python](#frameworks-python)
    - [`nnPUlearning`](https://github.com/kiryor/nnPUlearning)
    - [`pulearn`](https://github.com/pulearn/pulearn)
  - [Spark](#frameworks-spark)
    - [`pu4spark`](https://github.com/ispras/pu4spark)

### Tutorials

- [An introductory tutorial to the "Learning from Positive and Unlabeled Data" field.](https://dtai.cs.kuleuven.be/tutorials/pulearning/)
- [tinyML Talks Phoenix: Positive Unlabeled Learning for Tiny ML](https://www.youtube.com/watch?v=uk6SlTzfbUY)
- [Semi-Supervised Classification of Unlabeled Data (PU Learning)](https://towardsdatascience.com/semi-supervised-classification-of-unlabeled-data-pu-learning-81f96e96f7cb)

### Concepts

- Cost-sensitive and sample-selection methods
- Inductive vs Transductive PU learning. a.k.a(?) (Single-training set vs case-control scenario)
- Assumptions
  - [Partial Seperability](https://youtu.be/uk6SlTzfbUY?t=1129)
  - [SCAR(Selected Completely At Random)](https://youtu.be/uk6SlTzfbUY?t=1243)
