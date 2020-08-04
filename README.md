# UNSUPERVISED-LEARNING-CLUSTRING-KUMELEME-ALGORITMALARI-KULLANARAK-ANOMALY-DETECTION-PYTHON-APP

Uygulamanın amacı, hali hazırda izleme biriminde çalıştığımızdan bankanını tüm
datası bize gelmektedir. Bu data üzerinden sql ile statik thresholdlar konulmuş ve bu
thresholdlar vasıtasıyla alarm mekanizması oluştutulmuştur. Ancak yaklaşık 1000 kadar
izleme birimi olduğundan dolayı bu yöntem hem zaman hem kod hemde banka personeli
açısından çok pahalı (costly) olmaktadır.
Bu sorunu çözmek için bir makine öğrenme mekanizması uygulanmalıydı. Amacım
varolan data trendini tespit edip datamı bu trend ile train edip yeni gelen datanın outlier olup
olmadığına bakmak olmalıydı. Ancak datamda labellar olmadığından ve geçmişteki her alarm
(statik thresholdu geçme) gerçek alarm olmadığından dolayı (true-false değerler) labellama
işlemi de çok masraflı olucaktı.Bu nedenle yöntem olarak Unsupervised Anomaly Detection
algoritmalarını kullandım. Bu yapılar Clustiring (Kümeleme) tekniğini kullanmaktaydı.

3 adet Kümeleme algoritması kullanılmıştır.

-Kmeans
-Hidden Markov Clustring
-Hierarchical Agglomerative Clustering

Lütfen Raporu Okuyun (pdf)
