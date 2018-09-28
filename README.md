# Awesome H2O [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Powered by H2O.ai](https://img.shields.io/badge/powered%20by-h2oai-yellow.svg)](https://github.com/h2oai/)

[<img src="https://rawgit.com/h2oai/awesome-h2o/master/h2o_logo.png" align="right" width="100">](https://github.com/h2oai/h2o-3)

Below is a curated list of all the awesome projects, applications, research, tutorials, courses and books that use [H2O](https://github.com/h2oai/h2o-3), an open source, distributed machine learning platform.  H2O offers parallelized implementations of many supervised and unsupervised machine learning algorithms such as Generalized Linear Models, Gradient Boosting Machines (including XGBoost), Random Forests, Deep Neural Networks (Deep Learning), Stacked Ensembles, Naive Bayes, Cox Proportional Hazards, K-means, PCA, Word2Vec, as well as a fully automatic machine learning algorithm (AutoML).

[H2O.ai](http://www.h2o.ai/about/) produces many [tutorials](https://github.com/h2oai/h2o-tutorials), [blog posts](http://blog.h2o.ai/), [presentations](https://github.com/h2oai/h2o-meetups) and [videos](https://www.youtube.com/user/0xdata) about H2O, but the list below is comprised of awesome content produced by the greater H2O user community.

We are just getting started with this list, so pull requests are very much appreciated!  🙏  Please review the [contribution guidelines](contributing.md) before making a pull request.  If you're not a GitHub user and want to make a contribution, please send an email to community@h2o.ai.

If you think H2O is awesome too, please ⭐ the [H2O GitHub repository](https://github.com/h2oai/h2o-3/).

## Contents
- [Blog Posts & Tutorials](#blog-posts--tutorials)
- [Books](#books)
- [Research Papers](#research-papers)
- [Benchmarks](#benchmarks)
- [Presentations](#presentations)
- [Courses](#courses)
- [Utilities](#utilities)
- [License](#license)

## Blog Posts & Tutorials

- [Using machine learning with LIME to understand employee churn](http://www.business-science.io/business/2018/06/25/lime-local-feature-interpretation.html) June 25, 2018
- [Analytics at Scale: h2o, Apache Spark and R on AWS EMR](https://redoakstrategic.com/h2oaws/) June 21, 2018
- [Automated and unmysterious machine learning in cancer detection](https://kkulma.github.io/2017-11-07-automated_machine_learning_in_cancer_detection/) Nov 7, 2017
- [Time series machine learning with h2o+timetk](http://www.business-science.io/code-tools/2017/10/28/demo_week_h2o.html) Oct 28, 2017
- [Sales Analytics: How to use machine learning to predict and optimize product backorders](http://www.business-science.io/business/2017/10/16/sales_backorder_prediction.html) Oct 16, 2017
- [HR Analytics: Using machine learning to predict employee turnover](http://www.business-science.io/business/2017/09/18/hr_employee_attrition.html) Sep 18, 2017
- [Autoencoders and anomaly detection with machine learning in fraud analytics ](https://shiring.github.io/machine_learning/2017/05/01/fraud) May 1, 2017
- [Building deep neural nets with h2o and rsparkling that predict arrhythmia of the heart](https://shiring.github.io/machine_learning/2017/02/27/h2o) Feb 27, 2017
- [Predicting food preferences with sparklyr (machine learning)](https://shiring.github.io/machine_learning/2017/02/19/food_spark) Feb 19, 2017
- [Moving largish data from R to H2O - spam detection with Enron emails](https://ellisp.github.io/blog/2017/02/18/svmlite) Feb 18, 2016
- [Deep learning & parameter tuning with mxnet, h2o package in R](http://blog.hackerearth.com/understanding-deep-learning-parameter-tuning-with-mxnet-h2o-package-in-r) Jan 30, 2017
- [Are categorical variables getting lost in your random forests?](http://roamanalytics.com/2016/10/28/are-categorical-variables-getting-lost-in-your-random-forests/) Oct 28, 2016

## Books

- [Machine Learning Using R](https://www.amazon.com/Machine-Learning-Using-Karthik-Ramasubramanian/dp/1484223330) Karthik Ramasubramanian, Abhishek Singh. (2016)
- [Practical Machine Learning with H2O: Powerful, Scalable Techniques for Deep Learning and AI](https://www.amazon.com/Practical-Machine-Learning-H2O-Techniques/dp/149196460X) Darren Cook. (2016)
- [Disruptive Analytics](http://link.springer.com/book/10.1007/978-1-4842-1311-7) Thomas Dinsmore. (2016)
- [Computer Age Statistical Inference: Algorithms, Evidence, and Data Science](https://web.stanford.edu/~hastie/CASI/) Bradley Efron, Trevor Hastie. (2016)
- [R Deep Learning Essentials](https://www.packtpub.com/big-data-and-business-intelligence/r-deep-learning-essentials) Joshua F. Wiley. (2016)
- [Spark in Action](https://www.manning.com/books/spark-in-action) Petar Zečević, Marko Bonaći. (2016)
- [Handbook of Big Data](https://www.crcpress.com/Handbook-of-Big-Data/Buhlmann-Drineas-Kane-van-der-Laan/p/book/9781482249071) Peter Bühlmann, Petros Drineas, Michael Kane, Mark J. van der Laan (2015)

## Research Papers

- [Machine Learning Methods to Perform Pricing Optimization.  A Comparison with Standard GLMs.](http://www.variancejournal.org/articlespress/articles/Machine-Spedicato.pdf) (2018)
- [Algorithmic trading using deep neural networks on high frequency data](https://link.springer.com/chapter/10.1007/978-3-319-66963-2_14) Andrés Arévalo, Jaime Niño, German Hernandez, Javier Sandoval, Diego León, Arbey Aragón. (2017)
- [Generic online animal activity recognition on collar tags](https://dl.acm.org/citation.cfm?id=3124407) Jacob W. Kamminga, Helena C. Bisby, Duc V. Le, Nirvana Meratnia, Paul J. M. Havinga. (2017)
- [Robust and flexible estimation of data-dependent stochastic mediation effects: a proposed method and example in a randomized trial setting](https://arxiv.org/pdf/1707.09021.pdf) Kara E. Rudolph, Oleg Sofrygin, Wenjing Zheng, and Mark J. van der Laan. (2017)
- [Automated versus do-it-yourself methods for causal inference: Lessons learned from a data analysis competition](https://arxiv.org/abs/1707.02641) Vincent Dorie, Jennifer Hill, Uri Shalit, Marc Scott, Dan Cervone. (2017)
- [Using deep learning to predict the mortality of leukemia patients](https://qspace.library.queensu.ca/bitstream/handle/1974/15929/Muthalaly_Reena%20S_201707_MSC.pdf) Reena Shaw Muthalaly. (2017)
- [Use of a machine learning framework to predict substance use disorder treatment success](http://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0175383&type=printable) Laura Acion, Diana Kelmansky, Mark van der Laan, Ethan Sahker, DeShauna Jones, Stephan Arnd. (2017)
- [Ultra-wideband antenna-induced error prediction using deep learning on channel response data](https://www.kn.e-technik.tu-dortmund.de/.cni-bibliography/publications/cni-publications/Tiemann2017a.pdf) Janis Tiemann, Johannes Pillmann, Christian Wietfeld. (2017)
- [Inferring passenger types from commuter eigentravel matrices](http://www.tandfonline.com/doi/abs/10.1080/21680566.2017.1291377?journalCode=ttrb20) Erika Fille T. Legara, Christopher P. Monterola. (2017)
- [Deep neural networks, gradient-boosted trees, random forests: Statistical arbitrage on the S&P 500](http://www.sciencedirect.com/science/article/pii/S0377221716308657) Christopher Krauss, Xuan Anh Doa, Nicolas Huckb. (2016)
- [Identifying IT purchases anomalies in the Brazilian government procurement system using deep learning](http://ieeexplore.ieee.org/document/7838233/?reload=true) Silvio L. Domingos, Rommel N. Carvalho, Ricardo S. Carvalho, Guilherme N. Ramos. (2016)
- [Predicting recovery of credit operations on a Brazilian bank](http://ieeexplore.ieee.org/abstract/document/7838243/) Rogério G. Lopes, Rommel N. Carvalho, Marcelo Ladeira, Ricardo S. Carvalho. (2016)
- [Deep learning anomaly detection as support fraud investigation in Brazilian exports and anti-money laundering](http://ieeexplore.ieee.org/abstract/document/7838276/) Ebberth L. Paula, Marcelo Ladeira, Rommel N. Carvalho, Thiago Marzagão. (2016)
- [Deep learning and association rule mining for predicting drug response in cancer](http://dx.doi.org/10.1101/070490) Konstantinos N. Vougas, Thomas Jackson, Alexander Polyzos, Michael Liontos, Elizabeth O. Johnson, Vassilis Georgoulias, Paul Townsend, Jiri Bartek, Vassilis G. Gorgoulis. (2016)
- [The value of points of interest information in predicting cost-effective charging infrastructure locations](http://www.rsm.nl/fileadmin/Images_NEW/ECFEB/The_value_of_points_of_interest_information.pdf) Stéphanie Florence Visser. (2016)
- [Adaptive modelling of spatial diversification of soil classification units. Journal of Water and Land Development](https://www.degruyter.com/downloadpdf/j/jwld.2016.30.issue-1/jwld-2016-0029/jwld-2016-0029.xml) Krzysztof Urbański, Stanisław Gruszczyńsk. (2016)
- [Scalable ensemble learning and computationally efficient variance estimation](http://www.stat.berkeley.edu/~ledell/papers/ledell-phd-thesis.pdf) Erin LeDell. (2015)
- [Superchords: decoding EEG signals in the millisecond range](https://dx.doi.org/10.7287/peerj.preprints.1265v1) Rogerio Normand, Hugo Alexandre Ferreira. (2015)
- [Understanding random forests: from theory to practice](https://github.com/glouppe/phd-thesis) Gilles Louppe. (2014)

## Benchmarks

- [Are categorical variables getting lost in your random forests?](http://roamanalytics.com/2016/10/28/are-categorical-variables-getting-lost-in-your-random-forests/) - Benchmark of categorical encoding schemes and the effect on tree based models (Scikit-learn vs H2O). Oct 28, 2016
- [Deep learning in R](http://www.rblog.uni-freiburg.de/2017/02/07/deep-learning-in-r/) - Benchmark of open source deep learning packages in R. Mar 7, 2016
- [Szilard's machine learning benchmark](https://github.com/szilard/benchm-ml) - Benchmarks of Random Forest, GBM, Deep Learning and GLM implementations in common open source ML frameworks. Jul 3, 2015

## Presentations

- [Pipelines for model deployment](https://www.slideshare.net/rocalabern/digital-origin-pipelines-for-model-deployment) Apr 25, 2017
- [Machine learning with H2O.ai](https://speakerdeck.com/szilard/machine-learning-with-h2o-dot-ai-la-h2o-meetup-at-at-and-t-jan-2017) Jan 23, 2017

## Courses

- [UCLA: Tools in Data Science (STATS 418)](https://github.com/szilard/teach-data-science-UCLA-master-appl-stats) - Masters of Applied Statistics Program
- [GWU: Data Mining (Decision Sciences 6279)](https://github.com/jphall663/GWU_data_mining) - Masters of Science in Business Analytics
- [University of Cape Town: Analytics Module](http://www.stats.uct.ac.za/stats/study/postgrad/honours) - Postgraduate Honors Program in Statistical Sciences
- [Coursera: How to Win a Data Science Competition: Learn from Top Kagglers](https://www.coursera.org/learn/competitive-data-science) - Advanced Machine Learning Specialization

## Utilities

- [Spin up PySpark and PySparkling on AWS](https://github.com/kcrandall/EMR_Spark_Automation)

## License

[![CC0](https://upload.wikimedia.org/wikipedia/commons/6/69/CC0_button.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [H2O.ai](http://h2o.ai) has waived all copyright and related or neighboring rights to this work.
