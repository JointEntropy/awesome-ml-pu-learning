# Awesome ML Positive Unlabeled learning

### Papers
<!-- MarkdownTOC depth=4 -->
- [Papers \\w code](#papers)
  - [Overview](#overview)
    - [Theoretical Comparisons of Positive-Unlabeled Learning against Positive-Negative Learning(2016)](https://proceedings.neurips.cc/paper/2016/file/be3159ad04564bfb90db9e32851ebf9c-Paper.pdf)
    - [Learning from positive and unlabeled data: a survey(2018)](https://arxiv.org/abs/1811.04820)
    - [Positive and unlabeled learning algorithms and applications: A survey(2019)](https://www.researchgate.net/profile/Kristen-Jaskie/publication/337503578_Positive_And_Unlabeled_Learning_Algorithms_And_Applications_A_Survey/links/609b0124458515d31513c2e9/Positive-And-Unlabeled-Learning-Algorithms-And-Applications-A-Survey.pdf)
    - [Exploring Positive Unlabeled Machine Learning(2021)](https://digital.wpi.edu/downloads/vq27zr55f)
  - [Cost-sensitive methods](#cost-sensitive)
    - [Learning Classifiers from Only Positive and Unlabeled Data(2008)](https://cseweb.ucsd.edu/~elkan/posonly.pdf)\[[pulearn](https://github.com/pulearn/pulearn#31elkanoto)\]
    - [Analysis of Learning from Positive and Unlabeled Data(2014)](https://papers.nips.cc/paper/2014/file/35051070e572e47d2c26c241ab88307f-Paper.pdf)
    - [A Modified Logistic Regression for Positive and Unlabeled Learning(2019)](https://www.researchgate.net/profile/Kristen-Jaskie/publication/340306999_A_Modified_Logistic_Regression_for_Positive_and_Unlabeled_Learning/links/609b0152a6fdccaebd2525d1/A-Modified-Logistic-Regression-for-Positive-and-Unlabeled-Learning.pdf) \[[video](https://www.youtube.com/watch?v=uk6SlTzfbUY)\]
  - [Sample-selection/Two-step methods](#sample-selection)
    - [A bagging SVM to learn from positive and unlabeled examples(2013)](https://members.cbio.mines-paristech.fr/~jvert/svn/bibli/local/Mordelet2013bagging.pdf) \[[pulearn](https://github.com/pulearn/pulearn#32bagging-based-pu-learning)\]
    - [Improving Positive Unlabeled Learning: Practical AUL Estimation and New Training Method for Extremely Imbalanced Data Sets(2020)](https://arxiv.org/pdf/2004.09820.pdf)
    - [PULNS: Positive-Unlabeled Learning with Effective Negative Sample Selector(2021)](https://ojs.aaai.org/index.php/AAAI/article/view/17064/16871)\[[slides](https://slideslive.com/38948747/pulns-positiveunlabeled-learning-with-effective-negative-sample-selector)\]
    - [Revisiting Sample Selection Approach to Positive-Unlabeled Learning: Turning Unlabeled Data into Positive rather than Negative(2019)](https://arxiv.org/pdf/1901.10155.pdf)

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
- [Class prior and label frequency](https://youtu.be/mSoeaYt6Oi8?t=1282)
- Cost-sensitive and sample-selection methods
- Inductive vs Transductive PU learning. a.k.a(?) [(Single-training set vs case-control scenario)](https://youtu.be/mSoeaYt6Oi8?t=823)
- [Labelling mechanism](https://youtu.be/mSoeaYt6Oi8?t=419)
- Assumptions
  - [Partial Seperability](https://youtu.be/uk6SlTzfbUY?t=1129)
  - [SCAR(Selected Completely At Random)](https://youtu.be/uk6SlTzfbUY?t=1243)

### Cases/Applications 
- [Positive Unlabeled Learing, MegaFon, ODS.ai(2020)\[RU\]](https://youtu.be/7nKswav3Zrw) 
