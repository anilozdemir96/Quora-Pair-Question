# Quora-Pair-Question
Detecting whether two question is similar or not ?

Recently,with the impressive developments in the field of deep learning, natural language processing has become ahot topic in many different sectors [1]. Also, the methodology of the Natural Language Processing completely shiftedfrom the classical approaches to the neural network based models. [2]. In this project, we will particularly focus on theproblem of paraphrase identification which has addressed the problem of identifying the semantic overlap betweensentences. This problem has been solved by quora by using Random Forests in the past [3]. Within the framework ofthis problem, we will attempt to propose an optimal solution by comparing deep learning, traditional machine learning(ML), and state-of-art models.
In this work, we will provide the followings:
(i)Applying various pre-processing methods such as stemming, lemmatization, stop-word removal,and featureextraction for ML models.
(ii)  Apply and compare various of ML-Deep Learning methods.
(iii)  Hyper-Parameter tuning


Dataset: Quora Question PairsIn this work, we will use Quora Question Pairs Data-set which provided by the Kaggle and sponsored by the Quora.Data consist of 400,000 labeled training sample and 2,300,000 test sample. Each sample of the training has the following features:
•id: The id of a training set question pair
•qid1,qid2: unique ids of each question
•question1, question2: The full text of questions
•isduplicate : The target feature, labeled by 1 if question1 and question2 have originally the same meaning, and 0 otherwise [3]


References
[1]Tom Young, Devamanyu Hazarika, Soujanya Poria, and Erik Cambria. Recent trends in deep learning based naturallanguage processing.ieee Computational intelligenCe magazine, 13(3):55–75, 2018.
[2]Mitchell Marcus. New trends in natural language processing: statistical natural language processing.Proceedingsof the National Academy of Sciences, 92(22):10052–10059, 1995.
[3]  Kaggle. Quora question pairs, 2017-11.
