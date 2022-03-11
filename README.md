# Reading List

## Text books
### Machine Learning
- [Lectures on Machine Learning](http://www.math.snu.ac.kr/~hichoi/machinelearning/index.html) by Hyeong In Choi, Seoul National University, Department of Mathematics

### Deep Learning
- [Dive into Deep Learning](https://d2l.ai/) by Zhang, Aston, et al.
- [Deep learning](https://www.deeplearningbook.org/front_matter.pdf) by Goodfellow, Ian, Yoshua Bengio, and Aaron Courville

### Recommender System
- [Recommender-Systems: The Textbook](https://d1wqtxts1xzle7.cloudfront.net/63186644/2016_Book_RecommenderSystems20200503-102501-wsddcn-with-cover-page-v2.pdf?Expires=1646156544&Signature=CcG3hMtXlo5DVbWh6byEceCXyi0E0cuUlp2XI5q4q1BoVW8DmUY75NnNvf1WVfQAO7wS8YhiGeF2VW5hRiXLPNd2oUFv8ygBTdU9IOxcGjvwgvLzGolGNtMjzadXeYtdWnQI9eEZvMFpcv3tTq4aMuMhEzMJtBLwe3GUCf-JP1yIreto2l3bO5KniB0EKkHi4CAgOgTRw7Rdh1YF3sWiD~ymU5-rKx42wH1HvLq7vg9jtL73s9sClk-L1aFXb5ktMmZmFUX3awRgaMMT7XEK6L2mbpUMnEDcbpWPGq7dYBvuj0xldRp-BGIfthjengR1ENfFPDbgXxckIDmIznitEg__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA) by Charu C. Aggarwal
### Outlier Detection
- [Outlier Analysis](https://d1wqtxts1xzle7.cloudfront.net/57870486/Outlier-Analysis-with-cover-page-v2.pdf?Expires=1646156648&Signature=DeivOYXXH3LY5cY-v782O4GBHUKYglvAFxQScRRCylaxOAikFQU5pkiNubLvhzCSzsDTZn-o6H5EHdwl51jiHrTzaiKxXNbgh-JrGzzVRfxxeGIOsoJYM-Y46WVwfcAjzpB5RWy6udkbJSxBVeUXcXvvTzq4mkxcdQ5y5wOJedcDah5sBslff7tWQrI7wBJXHntpJ48VaNOG25kjQ0mwpjd9lfme0hJpaexIwMvPfBUskjkilUu~GZinCj-mmgL~pgySG4Rq-6Rl95K-pWgkkUW7YNnQtvgQaGj6~il4hXeZ~bxCBxfpYbFyyy6XaHS9MDp7uGc2-9SoFonSkqEgiA__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA) by Charu C. Aggarwal


## Papers

### Recommender System
- Survey
  - Bobadilla, J., Ortega, F., Hernando, A., & Gutiérrez, A. (2013). [Recommender systems survey](https://reader.elsevier.com/reader/sd/pii/S0950705113001044?token=553447D6D7B8A4E3226134561D3B99E932D26D1157D2978A108E8A3DAD9C9827EE90A04018A39894E7D04D8B0B777252&originRegion=us-east-1&originCreation=20220311004943)). Knowledge-based systems, 46, 109-132.
- Collaborative Filtering
  - Matrix Factorization
    - Survey
      - Koren, Y., Bell, R., & Volinsky, C. (2009). [Matrix factorization techniques for recommender systems](https://www.inf.unibz.it/~ricci/ISR/papers/ieeecomputer.pdf). Computer, 42(8), 30-37.
    - Lecture Note
      - CS168: The Modern Algorithmic Toolbox Lecture #9: [The Singular Value Decomposition (SVD) and Low-Rank Matrix Approximations](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=9FDFC0123B6694B3FF30191E1304C55F?doi=10.1.1.725.8741&rep=rep1&type=pdf)
      - CME 323: Distributed Algorithms and Optimization, Spring 2015 [Matrix Completion via Alternating Least Square(ALS)](http://stanford.edu/~rezab/classes/cme323/S15/notes/lec14.pdf)
    - Methods  
      - Alternative Least Square (ALS)
        - Bell, R. M., & Koren, Y. (2007, October). [Scalable collaborative filtering with jointly derived neighborhood interpolation weights](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4470228&casa_token=if_rND5ujU8AAAAA:nHRXPYaN2YMBj4hOheqYfGekrJLpU6wMuvwQP9xDCV9zUQqDhcro31RR9IMQrEcB1D_FH13Ll5Q&tag=1). In Seventh IEEE international conference on data mining (ICDM 2007) (pp. 43-52). IEEE.
      - Non-negative Matrix Factorization
        - Gillis, N. (2017). [Introduction to nonnegative matrix factorization](https://arxiv.org/pdf/1703.00663.pdf). arXiv preprint arXiv:1703.00663.
      - Probabilistic Matrix Factorization
        - Mnih, A., & Salakhutdinov, R. R. (2007). [Probabilistic matrix factorization](https://proceedings.neurips.cc/paper/2007/file/d7322ed717dedf1eb4e6e52a37ea7bcd-Paper.pdf). Advances in neural information processing systems, 20.
      - Temporal Dynamics
        - Koren, Y. (2009, June). [Collaborative filtering with temporal dynamics](https://dl.acm.org/doi/pdf/10.1145/1557019.1557072?casa_token=Q3pNHhM5MQQAAAAA:p2_4w6ancNgFR6IORMlmm-KTZK7mQBCB8jrOlHT9-DKshGO0CXylibF5d9gZX3XLTToUKoZ2ibWP). In Proceedings of the 15th ACM SIGKDD international conference on Knowledge discovery and data mining (pp. 447-456).
      - Neural Collaborative Filtering
        - He, X., Liao, L., Zhang, H., Nie, L., Hu, X., & Chua, T. S. (2017, April). [Neural collaborative filtering](https://dl.acm.org/doi/pdf/10.1145/3038912.3052569?casa_token=kcPSEjY_YJkAAAAA:7hlKuZGwuuoMYwQUDsU0owoB_qbPYwJ7nRCo5I7NJXk0Vgfvr5j-4udGQELZYsNYiaWxFu_owwmy). In Proceedings of the 26th international conference on world wide web (pp. 173-182).
      - Factorization Machines (FM)
        - Rendle, S. (2010, December). [Factorization machines](https://analyticsconsultores.com.mx/wp-content/uploads/2019/03/Factorization-Machines-Steffen-Rendle-Osaka-University-2010.pdf). In 2010 IEEE International conference on data mining (pp. 995-1000). IEEE. 
      - Deep Factorization Machines (DeepFM)
        - Guo, H., Tang, R., Ye, Y., Li, Z., & He, X. (2017). [DeepFM: a factorization-machine based neural network for CTR prediction](https://arxiv.org/pdf/1703.04247.pdf，这个是华为用在应用商店做排序的%E3%80%82这两个算法既可以在广告中做ctr预估，也可以在推荐系统中做排序%E3%80%82). arXiv preprint arXiv:1703.04247.
- Evaluation
  - Ge, M., Delgado-Battenfeld, C., & Jannach, D. (2010, September). [Beyond accuracy: evaluating recommender systems by coverage and serendipity](https://dl.acm.org/doi/pdf/10.1145/1864708.1864761?casa_token=gDQ4yOFm52AAAAAA:sXTcHzaf-xaz6zyVQM96wcWVHL2YT-MmlJ3vQlI9UCBExi_XHDb-7EObeGRx8gd0RY8SM5mYZ6nQ). In Proceedings of the fourth ACM conference on Recommender systems (pp. 257-260).
  - Kotkov, D., Wang, S., & Veijalainen, J. (2016). [A survey of serendipity in recommender systems](https://www.sciencedirect.com/science/article/pii/S0950705116302763?casa_token=wDQDFQVGSWoAAAAA:nMVB8o_-kbwDS1IVUjnA9312bmsMYogibSf8eFoyjVkn6kzDRKqgeSihRxAUZNZxYeRvL3Ee). Knowledge-Based Systems, 111, 180-192.



### Educational Data Mining
- Survey
  - Baker, R. S., & Inventado, P. S. (2014). [Educational data mining and learning analytics](https://edtechbooks.org/lidtfoundations/educational_data_mining_and_learning_analytics/simple). In Learning analytics (pp. 61-75). Springer, New York, NY.
- Knowledge Tracing (answer correctness prediction)
  - Survey
    - Pelánek, R. (2017). [Bayesian knowledge tracing, logistic models, and beyond: an overview of learner modeling techniques](https://www.fi.muni.cz/~xpelanek/publications/umuai-overview.pdf). User Modeling and User-Adapted Interaction, 27(3), 313-350.
    - Gervet, T., Koedinger, K., Schneider, J., & Mitchell, T. (2020). [When is deep learning the best approach to knowledge tracing?](https://jedm.educationaldatamining.org/index.php/JEDM/article/download/451/123). Journal of Educational Data Mining, 12(3), 31-54.
  - Bayesian Knowledge Tracing (BKT)
    - Lecture Notes
      - CS229: [Hiden Markov Models Fundamentals](https://www.google.co.kr/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjzlICo9bz2AhUJZ94KHXlXDjIQFnoECAgQAQ&url=https%3A%2F%2Fcs229.stanford.edu%2Fsection%2Fcs229-hmm.pdf&usg=AOvVaw3EuZ3G7Dcr707GKPatmxG_) by Daniel Ramage
      - [Hiden Markov Models](http://www.stats.ox.ac.uk/~caron/teaching/sb1b/lecturehmm.pdf) by Fran ̧cois Caron
    - Methods
      - Yudelson, M. V., Koedinger, K. R., & Gordon, G. J. (2013, July). [Individualized bayesian knowledge tracing models](http://www.cs.cmu.edu/~./ggordon/yudelson-koedinger-gordon-individualized-bayesian-knowledge-tracing.pdf). In International conference on artificial intelligence in education (pp. 171-180). Springer, Berlin, Heidelberg.
    - Review
      - van De Sande, B. (2013). [Properties of the Bayesian Knowledge Tracing Model](https://files.eric.ed.gov/fulltext/EJ1115329.pdf). Journal of Educational Data Mining, 5(2), 1-10.
    - Implementation
      - [pyBKT](https://github.com/CAHLR/pyBKT)
        - Badrinath, A., Wang, F., & Pardos, Z. (2021). [pyBKT: an accessible python library of Bayesian knowledge tracing models](https://arxiv.org/pdf/2105.00385.pdf). arXiv preprint arXiv:2105.00385.
  - Deep Knowledge Tracing (DKT)
    - Methods
      - DKT
        - Piech, C., Bassen, J., Huang, J., Ganguli, S., Sahami, M., Guibas, L. J., & Sohl-Dickstein, J. (2015). [Deep knowledge tracing](https://proceedings.neurips.cc/paper/2015/file/bac9162b47c56fc8a4d2a519803d51b3-Paper.pdf). Advances in neural information processing systems, 28.
      - DKT+
        - Yeung, C. K., & Yeung, D. Y. (2018, June). [Addressing two problems in deep knowledge tracing via prediction-consistent regularization](https://dl.acm.org/doi/pdf/10.1145/3231644.3231647?casa_token=ZWcK0jwxnI4AAAAA:8N11uHSCa_QZ5KUuTuZP0vcc8k1hKF818roWwQ5doJIQLz1hXrVTZCedmuQnHRQtKgFCcet-Zy38). In Proceedings of the Fifth Annual ACM Conference on Learning at Scale (pp. 1-10).
      - PEBG
        - Liu, Y., Yang, Y., Chen, X., Shen, J., Zhang, H., & Yu, Y. (2020). [Improving knowledge tracing via pre-training question embeddings](https://arxiv.org/pdf/2012.05031.pdf). arXiv preprint arXiv:2012.05031.
      - DKVMN
        - Zhang, J., Shi, X., King, I., & Yeung, D. Y. (2017, April). [Dynamic key-value memory networks for knowledge tracing](https://dl.acm.org/doi/pdf/10.1145/3038912.3052580?casa_token=50ADFLMwmF0AAAAA:NpLsUcDAg9rIshSzuv4y8bc7EeVIMxre_0xg90BIubCYpgfbde2METq9LkETSBnTDnSI6K2mrYrx). In Proceedings of the 26th international conference on World Wide Web (pp. 765-774).
      - Deep-IRT
        - Yeung, C. K. (2019). [Deep-IRT: Make deep learning based knowledge tracing explainable using item response theory](https://arxiv.org/pdf/1904.11738). arXiv preprint arXiv:1904.11738.
          Chicago
      - SAKT
        - Pandey, S., & Karypis, G. (2019). [A self-attentive model for knowledge tracing](https://arxiv.org/pdf/1907.06837). arXiv preprint arXiv:1907.06837.
    - Review
      - Khajah, M., Lindsey, R. V., & Mozer, M. C. (2016). [How deep is knowledge tracing?](https://arxiv.org/pdf/1604.02416.pdf). arXiv preprint arXiv:1604.02416.
      - Xiong, X., Zhao, S., Van Inwegen, E. G., & Beck, J. E. (2016). [Going deeper with deep knowledge tracing](https://files.eric.ed.gov/fulltext/ED592679.pdf). International Educational Data Mining Society.
  - Logistic Knowledge Tracing (LKT)
    - Methods
      - LFA (Learning Factor Analysis)
        - Cen, H., Koedinger, K., & Junker, B. (2006, June). [Learning factors analysis–a general method for cognitive model evaluation and improvement](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.297.2141&rep=rep1&type=pdf). In International conference on intelligent tutoring systems (pp. 164-175). Springer, Berlin, Heidelberg.
      - PFA (Performance Factor Analysis)
        - Pavlik Jr, P. I., Cen, H., & Koedinger, K. R. (2009). [Performance Factors Analysis--A New Alternative to Knowledge Tracing](https://files.eric.ed.gov/fulltext/ED506305.pdf). Online Submission.
      - R-PFA
        - Galyardt, A., & Goldin, I. (2015). [Move Your Lamp Post: Recent Data Reflects Learner Knowledge Better than Older Data](https://files.eric.ed.gov/fulltext/EJ1115280.pdf). Journal of Educational Data Mining, 7(2), 83-108.
      - LKT (Logistic Knowledge Tracing)
        - Pavlik, P. I., Eglington, L. G., & Harrell-Williams, L. M. (2021). [Logistic Knowledge Tracing: A Constrained Framework for Learner Modeling](https://ieeexplore.ieee.org/iel7/4620076/4620077/09616435.pdf?casa_token=AlBw4sHxzGEAAAAA:tpH4z1jSQAHKueU7_4_Ux5PefjX7OgyUygRODNWKBDP4VceHs8wnAoxOzsvKM0imcOaN66ij). IEEE Transactions on Learning Technologies, 14(5), 624-639.
      - KTM (Knowledge Tracing Machine)
        - Vie, J. J., & Kashima, H. (2019, July). [Knowledge tracing machines: Factorization machines for knowledge tracing](https://ojs.aaai.org/index.php/AAAI/article/download/3853/3731). In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 33, No. 01, pp. 750-757).
      - DAS3H
        - Choffin, B., Popineau, F., Bourda, Y., & Vie, J. J. (2019). [DAS3H: modeling student learning and forgetting for optimally scheduling distributed practice of skills](https://arxiv.org/pdf/1905.06873.pdf?ref=https://githubhelp.com). arXiv preprint arXiv:1905.06873.
    - Review
      - Gong, Y., Beck, J. E., & Heffernan, N. T. (2011). [How to construct more accurate student models: Comparing and optimizing knowledge tracing and performance factor analysis](http://web.cs.wpi.edu/~nth/pubs_and_grants/papers/2010/Journals/Gong%20How%20to%20Construct%20More.pdf). International Journal of Artificial Intelligence in Education, 21(1-2), 27-46.
      - Rosé, C. P., McLaughlin, E. A., Liu, R., & Koedinger, K. R. (2019). [Explanatory learner models: Why machine learning (alone) is not the answer](https://bera-journals.onlinelibrary.wiley.com/doi/pdf/10.1111/bjet.12858). British Journal of Educational Technology, 50(6), 2943-2958.
      - Wu, M., Davis, R. L., Domingue, B. W., Piech, C., & Goodman, N. (2020). [Variational item response theory: Fast, accurate, and expressive](https://arxiv.org/pdf/2002.00276). arXiv preprint arXiv:2002.00276.
- Exercise Recommendation
  - Survey
    - Nabizadeh, A. H., Leal, J. P., Rafsanjani, H. N., & Shah, R. R. (2020). [Learning path personalization and recommendation methods: A survey of the state-of-the-art](https://www.sciencedirect.com/science/article/pii/S0957417420304206?casa_token=MHxZ55SJbP8AAAAA:OqJrfK5Yv5l_JduGW0t7pT1P5-7TQJ0imZDp2V6li7t4Acct9_ZfitWau5DR4f4-T32M9FBl). Expert Systems with Applications, 159, 113596.
  - Methods
    - Wu, Z., Li, M., Tang, Y., & Liang, Q. (2020). [Exercise recommendation based on knowledge concept prediction](https://www.sciencedirect.com/science/article/pii/S0950705120306109?casa_token=_YiStacQMU8AAAAA:FLXhwRo-mtQSXJoKUbrf1od9YjRtDCNRyNFxKRjXqWnm5W1_zGyJFvQCfuKk6kfbZsXmEYUH). Knowledge-Based Systems, 210, 106481.
    - Ai, F., Chen, Y., Guo, Y., Zhao, Y., Wang, Z., Fu, G., & Wang, G. (2019). [Concept-Aware Deep Knowledge Tracing and Exercise Recommendation in an Online Learning System](https://files.eric.ed.gov/fulltext/ED599194.pdf). International Educational Data Mining Society.
    - Cai, D., Zhang, Y., & Dai, B. (2019, December). [Learning path recommendation based on knowledge tracing model and reinforcement learning](https://ieeexplore.ieee.org/iel7/9048180/9064028/09064104.pdf?casa_token=Qf-IVVE9MS0AAAAA:gHTKNucQ1w7BVHp2Py-tVdZwl5gW2iij1JegLMT0AdC5ydfkZRFxVqTOraPM4iemGAusIFvs). In 2019 IEEE 5th International Conference on Computer and Communications (ICCC) (pp. 1881-1885). IEEE.
  - Lecture Notes
    - Combinatorial Optimization
      - [Simulated Annealing Overview](https://www.google.co.kr/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjfqffE_7z2AhVSxYsBHb9RA3wQFnoECAYQAQ&url=https%3A%2F%2Fwww.lancaster.ac.uk%2Fpg%2Fvarty%2FRTOne.pdf&usg=AOvVaw3SXjelVkiTloyuj4INH5xb) by Zak Varty
      
### Outlier Detection
- Survey 
  - Chandola, V., Banerjee, A., & Kumar, V. (2009). [Anomaly detection: A survey](https://conservancy.umn.edu/bitstream/handle/11299/215731/07-017.pdf?sequence=1). ACM computing surveys (CSUR), 41(3), 1-58.
- Unsupervised Learning Methods
  - Methods
    - LOF
      - Breunig, M. M., Kriegel, H. P., Ng, R. T., & Sander, J. (2000, May). [LOF: identifying density-based local outliers](https://dl.acm.org/doi/pdf/10.1145/342009.335388?casa_token=qB9shs2wYrEAAAAA:SAupZ3128dEneCw2U_na34GRnCalsVfx4PdiqlaQBtj4Aw59VYVuY55v1-e3P8b4gFssW29kg4ik). In Proceedings of the 2000 ACM SIGMOD international conference on Management of data (pp. 93-104).
    - Isolation Forest
      - Liu, F. T., Ting, K. M., & Zhou, Z. H. (2008, December). [Isolation forest](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4781136&casa_token=q6603pKvIdcAAAAA:I3-JTq4vuu1-wWMo-k6aFUgoDjQZUvdBstpjpBF-ODjulIXNXuaxh0nDs9CAPM4rq0B08u72). In 2008 eighth ieee international conference on data mining (pp. 413-422). IEEE.
  - Use of Outlier Scores
    - Gao, J., & Tan, P. N. (2006, December). [Converting output scores from outlier detection algorithms into probability estimates](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4053049&casa_token=i__CmdPhRCUAAAAA:cd-_kQlL138goSE0FHtDE0N_Bs-K6zKsMbhX2qGchgu6Ci4pTtRy_m_ZEs2iqKMRM4elg8Cu&tag=1). In Sixth International Conference on Data Mining (ICDM'06) (pp. 212-221). IEEE.
    - Schubert, E., Wojdanowski, R., Zimek, A., & Kriegel, H. P. (2012, April). [On evaluation of outlier rankings and outlier scores](https://epubs.siam.org/doi/pdf/10.1137/1.9781611972825.90). In Proceedings of the 2012 SIAM International Conference on Data Mining (pp. 1047-1058). Society for Industrial and Applied Mathematics.
    - Kriegel, H. P., Kroger, P., Schubert, E., & Zimek, A. (2011, April). [Interpreting and unifying outlier scores](https://epubs.siam.org/doi/pdf/10.1137/1.9781611972818.2). In Proceedings of the 2011 SIAM International Conference on Data Mining (pp. 13-24). Society for Industrial and Applied Mathematics.
  - For High-Dimensional Data
    - Survey
      - Zimek, A., Schubert, E., & Kriegel, H. P. (2012). [A survey on unsupervised outlier detection in high‐dimensional numerical data](https://onlinelibrary.wiley.com/doi/pdf/10.1002/sam.11161?casa_token=icDu1psN5dkAAAAA:9mJA1-D1kjaQYLiG_ClD9V10Ls6TzOC_Szz8jsjV1pvDQeoLnHtcc6IYrHijmUhJBHsMwFPaqdnEMoY). Statistical Analysis and Data Mining: The ASA Data Science Journal, 5(5), 363-387.
      - Campos, G. O., Zimek, A., Sander, J., Campello, R. J., Micenková, B., Schubert, E., ... & Houle, M. E. (2016). [On the evaluation of unsupervised outlier detection: measures, datasets, and an empirical study](https://www.proquest.com/openview/680cbe1465cde1fe5386f3aeba4d8cb0/1.pdf?pq-origsite=gscholar&cbl=43030&casa_token=GyAgPM0lhSsAAAAA:2L-tdQtGk9Nt17JhOOQXNUw01m9LtQEJu727pXcKLvS2iHa1Uh18pm9oovwHgjJNFJr1Fa-mIw). Data mining and knowledge discovery, 30(4), 891-927.
        Chicago
      - Xu, X., Liu, H., Li, L., & Yao, M. (2018). [A comparison of outlier detection techniques for high-dimensional data](https://www.atlantis-press.com/article/25892518.pdf). International Journal of Computational Intelligence Systems, 11(1), 652.
    - Concentration Effect (Motivation for HD Outlier detection)
      - Beyer, K., Goldstein, J., Ramakrishnan, R., & Shaft, U. (1999, January). [When is “nearest neighbor” meaningful?](https://minds.wisconsin.edu/bitstream/handle/1793/60174/TR1377.pdf?sequence=1). In International conference on database theory (pp. 217-235). Springer, Berlin, Heidelberg.
      - Durrant, R. J., & Kabán, A. (2009). [When is ‘nearest neighbour’meaningful: A converse theorem and implications](https://www.sciencedirect.com/science/article/pii/S0885064X09000260). Journal of Complexity, 25(4), 385-397.

### etc
#### Hyper-parameter Tuning
- Survey
  - Yu, T., & Zhu, H. (2020). [Hyper-parameter optimization: A review of algorithms and applications](https://ieeexplore.ieee.org/iel7/9048180/9064028/09064104.pdf?casa_token=Qf-IVVE9MS0AAAAA:gHTKNucQ1w7BVHp2Py-tVdZwl5gW2iij1JegLMT0AdC5ydfkZRFxVqTOraPM4iemGAusIFvs). arXiv preprint arXiv:2003.05689.
#### Model Combination
- Motivation
  - [Can multi-model combination really enhance the prediction skill of probabilistic ensemble forecasts?](https://rmets.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/qj.210?casa_token=ABUs37ApamoAAAAA:5x4sB2xjMmAx3xg85NuikkvyodCnRIX4ZLd3P253rin_JVgE8t52p_Sox0RZMKC4kLrZCKGiIt4r0kI)
- Review
  - [Model Combination in multiclass classification](https://www.proquest.com/openview/eeb8f8b64391d56327c6eac829c3cb20/1?pq-origsite=gscholar&cbl=18750)
- Methods
  - Stacked Generalization
    - [Issues in Stacked Generalization](https://www.jair.org/index.php/jair/article/view/10228)
#### Ordinal Classification
- Methods
  - Frank, E., & Hall, M. (2001, September). [A simple approach to ordinal classification](https://link.springer.com/content/pdf/10.1007/3-540-44795-4_13.pdf). In European conference on machine learning (pp. 145-156). Springer, Berlin, Heidelberg.


## Websites
- [Distill](https://distill.pub/)

## Soft Readings (in Korean)
- [Kakao AI Report](http://aitimes.org/archives/1339)
- [세상에서 가장 쉬운 베이즈 통계학](http://www.kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&ejkGb=KOR&barcode=9788965022718)
- [세상에서 가장 쉬운 통계학 입문](http://www.kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&ejkGb=KOR&barcode=9788990994004)
- [헬로 데이터 과학](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788968482656)

