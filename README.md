## Topic Modelling UK Political Speech on COVID-19.

This project was my final assignment for Distributed Computing for Big Data, a postgraduate course in the LSE statistics department.

The goal of the project was to demonstrate the use of the Spark MLlib library and unsupervised learning techniques like LDA Topic Modelling to explore a dataset of UK House of Commons speeches from 2020/2021. Throughout the past year UK MPs have spent a great deal of time talking about COVID-19, but their views on how best to address the pandemic have differed. Topic modelling can uncover the topics that MPs discussed in the House of Commons during the COVID-19 pandemic and this may give insight into prominence and nature of the debate. I will use Spark MLlib Topic Model algorithms to run Latent Dirichlet Allocation on House of Commons speeches made during the COVID-19 pandemic and examine the clusters that form. 

This project uses UK Parliamentary Hansard data accessed from "theyworkforyou.com" which provides up to date XML files of parliamentary speech. My hope is that these clusters will be informative about the underlying structure of the political discourse on COVID-19 and the imposed restrictions. I have downloaded and cleaned ~70,000 speeches from over the course of the year. 


## References:

 
[1] Apache Spark: Machine Learning Library (MLlib) Guide. https://spark.apache.org/docs/latest/ml-guide.html.

[2] Apache Spark: Latent Dirichlet Allocaiton (LDA). https://spark.apache.org/docs/latest/ml-clustering.html#latent-dirichlet-allocation-lda.

[3] Blei, D.M., A.Y. Ng and M.I. Jordan. 2003. “Latent dirichlet allocation.” The Journal of Machine Learning Research 3:993–1022.

[4] Blei, David M. 2012. “Probabilistic topic models.” Communications of the ACM 55(4):77. doi: 10.1145/2133806.2133826.

[5] Blei, David, and John Lafferty. "Correlated topic models." Advances in neural information processing systems 18 (2006): 147.

[6] MySociety. Hansard Reports. https://parser.theyworkforyou.com/hansard.html.

[7] Odell, Evan. 2020. "Hansard Speeches Version 3." https://github.com/evanodell/hansard-data3.

[8] Roberts, Margaret E., et al. "The structural topic model and applied social science." Advances in neural information processing systems workshop on topic models: computation, application, and evaluation. Vol. 4. 2013.

[9] Zaharia, M., Chowdhury, M., Das, T., Dave, A., Ma, J., McCauley, M., ... & Stoica, I. (2012, April). Resilient distributed datasets: A fault-tolerant abstraction for in-memory cluster computing. In Proceedings of the 9th USENIX conference on Networked Systems Design and Implementation (pp. 2-2). USENIX Association.
