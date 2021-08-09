# Download the Pretrained models
Download the pretrained models from this [link] (https://drive.google.com/drive/folders/1xqwI764nAw3wIXUN-wnSwlRVodzjn-QM?usp=sharing) 

<br/>

# Pretrained models
The following pretrained models are available in the models directory:
<ol>
<li>MLRoBERTa: This is a RoBERTa model trained on scientific documents. The dataset is composed of NeurIPS (1987-2019), CVPR (2013-2020), ICLR (2016-2020), ACL Anthology data (till 2019) paper title and abstracts, and ICLR paper reviews.</li>
<li>MLEnRoBERTa: This is a variant of the MLRoBERTa model which is trained on a masked dataset. The dataset of MLRoBERTa is modified to replace specific scientific entities in a paper with generic labels. The idea is to make the model focus more on the syntax and semantics of the text without getting confused by specific entity names. Scientific entities which belong to any one of the classes: TDMM (task, dataset, method, metric) are masked with these specific labels. The entity set is manually cleaned and mapped to appropriate labels. Eg: *The authors present results on MNIST.* -> *The authors present results on dataset.*</li>
</ol>