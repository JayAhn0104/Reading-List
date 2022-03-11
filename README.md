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
  - Bobadilla, J., Ortega, F., Hernando, A., & Gutiérrez, A. (2013). [Recommender systems survey]((https://reader.elsevier.com/reader/sd/pii/S0950705113001044?token=553447D6D7B8A4E3226134561D3B99E932D26D1157D2978A108E8A3DAD9C9827EE90A04018A39894E7D04D8B0B777252&originRegion=us-east-1&originCreation=20220311004943)). Knowledge-based systems, 46, 109-132.
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
      - Neural Collaborative Filtering
        - He, X., Liao, L., Zhang, H., Nie, L., Hu, X., & Chua, T. S. (2017, April). [Neural collaborative filtering](https://dl.acm.org/doi/pdf/10.1145/3038912.3052569?casa_token=kcPSEjY_YJkAAAAA:7hlKuZGwuuoMYwQUDsU0owoB_qbPYwJ7nRCo5I7NJXk0Vgfvr5j-4udGQELZYsNYiaWxFu_owwmy). In Proceedings of the 26th international conference on world wide web (pp. 173-182).
      - Factorization Machines (FM)
        - Rendle, S. (2010, December). [Factorization machines](https://analyticsconsultores.com.mx/wp-content/uploads/2019/03/Factorization-Machines-Steffen-Rendle-Osaka-University-2010.pdf). In 2010 IEEE International conference on data mining (pp. 995-1000). IEEE. 
      - Deep Factorization Machines (DeepFM)
        - Guo, H., Tang, R., Ye, Y., Li, Z., & He, X. (2017). [DeepFM: a factorization-machine based neural network for CTR prediction](https://arxiv.org/pdf/1703.04247.pdf，这个是华为用在应用商店做排序的%E3%80%82这两个算法既可以在广告中做ctr预估，也可以在推荐系统中做排序%E3%80%82). arXiv preprint arXiv:1703.04247.


### Educational Data Mining
- Knowledge Tracing (answer correctness prediction)


### Outlier Detection
- Survey 
  - Chandola, V., Banerjee, A., & Kumar, V. (2009). [Anomaly detection: A survey](https://conservancy.umn.edu/bitstream/handle/11299/215731/07-017.pdf?sequence=1). ACM computing surveys (CSUR), 41(3), 1-58.
- Unsupervised Learning Methods
  - LOF
    - Breunig, M. M., Kriegel, H. P., Ng, R. T., & Sander, J. (2000, May). [LOF: identifying density-based local outliers](https://dl.acm.org/doi/pdf/10.1145/342009.335388?casa_token=qB9shs2wYrEAAAAA:SAupZ3128dEneCw2U_na34GRnCalsVfx4PdiqlaQBtj4Aw59VYVuY55v1-e3P8b4gFssW29kg4ik). In Proceedings of the 2000 ACM SIGMOD international conference on Management of data (pp. 93-104).
  - For High-Dimensional Data
    - Survey
      - Zimek, A., Schubert, E., & Kriegel, H. P. (2012). [A survey on unsupervised outlier detection in high‐dimensional numerical data](https://onlinelibrary.wiley.com/doi/pdf/10.1002/sam.11161?casa_token=icDu1psN5dkAAAAA:9mJA1-D1kjaQYLiG_ClD9V10Ls6TzOC_Szz8jsjV1pvDQeoLnHtcc6IYrHijmUhJBHsMwFPaqdnEMoY). Statistical Analysis and Data Mining: The ASA Data Science Journal, 5(5), 363-387.
      - Campos, G. O., Zimek, A., Sander, J., Campello, R. J., Micenková, B., Schubert, E., ... & Houle, M. E. (2016). [On the evaluation of unsupervised outlier detection: measures, datasets, and an empirical study](https://www.proquest.com/openview/680cbe1465cde1fe5386f3aeba4d8cb0/1.pdf?pq-origsite=gscholar&cbl=43030&casa_token=GyAgPM0lhSsAAAAA:2L-tdQtGk9Nt17JhOOQXNUw01m9LtQEJu727pXcKLvS2iHa1Uh18pm9oovwHgjJNFJr1Fa-mIw). Data mining and knowledge discovery, 30(4), 891-927.
        Chicago
      - Xu, X., Liu, H., Li, L., & Yao, M. (2018). [A comparison of outlier detection techniques for high-dimensional data](https://www.atlantis-press.com/article/25892518.pdf). International Journal of Computational Intelligence Systems, 11(1), 652.
    - Concentration Effect (Motivation for HD Outlier detection)
      - Beyer, K., Goldstein, J., Ramakrishnan, R., & Shaft, U. (1999, January). [When is “nearest neighbor” meaningful?](https://minds.wisconsin.edu/bitstream/handle/1793/60174/TR1377.pdf?sequence=1). In International conference on database theory (pp. 217-235). Springer, Berlin, Heidelberg.
      - Durrant, R. J., & Kabán, A. (2009). [When is ‘nearest neighbour’meaningful: A converse theorem and implications](https://www.sciencedirect.com/science/article/pii/S0885064X09000260). Journal of Complexity, 25(4), 385-397.
    - Methods

### etc
- Model Combination
  - [Can multi-model combination really enhance the prediction
    skill of probabilistic ensemble forecasts?](https://rmets.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/qj.210?casa_token=ABUs37ApamoAAAAA:5x4sB2xjMmAx3xg85NuikkvyodCnRIX4ZLd3P253rin_JVgE8t52p_Sox0RZMKC4kLrZCKGiIt4r0kI)
  - [Model Combination in multiclass classification](https://www.proquest.com/openview/eeb8f8b64391d56327c6eac829c3cb20/1?pq-origsite=gscholar&cbl=18750)
  - Stacked Generalization
    - [Issues in Stacked Generalization](https://www.jair.org/index.php/jair/article/view/10228)
- Hyper-parameter Tuning

## Websites
- [Distill](https://distill.pub/)

## Soft Readings (in Korean)
- [Kakao AI Report](http://aitimes.org/archives/1339)
- [세상에서 가장 쉬운 베이즈 통계학](http://www.kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&ejkGb=KOR&barcode=9788965022718)
- [세상에서 가장 쉬운 통계학 입문](http://www.kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&ejkGb=KOR&barcode=9788990994004)
- [헬로 데이터 과학](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788968482656)

