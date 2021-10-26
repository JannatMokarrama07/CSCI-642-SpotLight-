# CSCI-642-SpotLight-
## What People are Talking about Scholarly Articles in Facebook? ##
### *Introduction:* ###
In recent years, researchers are more actively seen to discuss on research articles in social media, like Facebook, Twitter, LinkedIn, etc. due to their quick and powerful reach and impact to sheer amount of audience. Therefore, social sites are becoming crucial data repository to understand the current trends of research, analyzing the reactions of people to research, getting insights on which types of topics are getting user attention more, etc. [1-3]. This type of analysis is important as it may reveal interesting implicit information about past and current trends of research topics to new researchers and give them an idea how people is going to discuss on their works in future which, at first glance, might not be comprehendible from the voluminous and versatile social data.

### *Objective:* ###
The aim of this spotlight is to investigate the topics that are being discussed frequently in Facebook posts on scholarly articles using one of the most interesting text mining algorithms in natural language processing: Topic Modeling. Two popular topic modeling algorithms, LDA ((Latent Dirichlet Allocation) and GSDMM (Gibbs Sampling Dirichlet Multinomial Mixture) will be used for this purpose and compared on the basis of their performance with respect to better understandability and coherence of the topics. The core assumption of LDA is each document may have multiple topics associated with it, whereas GSDMM considers each document has only one underlying topic. So, it is considered by many researchers that LDA works better when document size is larger (>50), for example, news articles in newspapers, scientific articles in magazines, etc. and GSDMM works better in short-text documents, like posts in Twitter and Facebook, product reviews, etc. [4][6]. The text that will be used in this analysis will be of varying length ranging from 8 to about 72,000 with a mean of 658. Also, they are originally categorized in multiple topics. For this reason, analyzing the dataset with both LDA and GSDMM will help in getting a comparative picture of the sensitivity and performance in this corpus.

### *Dataset:* ###
The dataset that will be used in this spotlight is on scholarly posts in Facebook and was originally collected from altmetric.com and used in [5].

### *Spotlight Steps:* ###
Here I worked in three steps: <br>
* __Task 1__ : Setup <br>
* __Task 2__:* Data Loading, Exploration, and Preprocessing <br>
* __Task 3__:* Topic Modeling and visualization (i) GSDMM, (ii) LDA 

### References ###
1. Zheng, H, et al. (2018) “Social Media Presence of Scholarly Journals”. Journal of the Association for Information Science And Technology, 70(3):256-270.
2. Pulido, CM, et al. (2018): “Social impact in social media: A new method to evaluate the social impact of research”. PLoS ONE, 13(8).
3. “Social media for scientists”. Nature Cell Biology 20, 1329 (2018).
4. Albalawi, R, et al. (2020). “Using Topic Modeling Methods for Short-Text Data: A Comparative Analysis”. Frontiers in Artificial Intelligence, 3(42).
5. Freeman, C, et al. (2019). “Shared Feelings: Understanding Facebook Reactions to Scholarly Articles”. JCDL’19, 301-304.
6. https://towardsdatascience.com/short-text-topic-modelling-lda-vs-gsdmm-20f1db742e14
7. https://www.altmetric.com
8. https://medium.com/analytics-vidhya/topic-modeling-using-lda-and-gibbs-sampling-explained-49d49b3d1045
9. https://techblog.assignar.com/topic_modelling%20-%20assignar_froms_classification/
10. https://www.kaggle.com/ptfrwrd/topic-modeling-guide-gsdm-lda-lsi#LDA-model
11. https://towardsdatascience.com/gsdmm-topic-modeling-for-social-media-posts-and-reviews-8726489dc52f
12. https://www.kaggle.com/ptfrwrd/topic-modeling-guide-gsdm-lda-lsi?scriptVersionId=44304210

