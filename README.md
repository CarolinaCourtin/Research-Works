# Research Works
This repository brings together the academic research I conducted as part of my university coursework. It includes literature reviews, state-of-the-art analyses and solution design projects, each documented with its context and main findings.


### From Collaborative Filtering to Hybrid Models : Building and Evaluating Recommender Systems for Video Games

An end-to-end study of recommender systems on the Amazon Reviews 2023 Video Games dataset. Starting from data exploration and a popularity baseline, the project implements and compares collaborative filtering (user- and item-based KNN, SVD), content-based recommendation using text representations of item metadata (TF-IDF, Word2Vec), and three hybrid strategies (weighted sum, round-robin, pipelining). Models are evaluated on rating accuracy (RMSE, MAE) and ranking quality (Precision, Hit Rate, MAP, MRR, coverage), with a focus on the trade-off between accuracy and diversity and on performance for less active users and long-tail items. This work has been completed as part of the course Web Recommender Systems at the University of Copenhagen in the spring semester of 2026. 

📄 [Report](./Web_Recommender_Systems_Submission.pdf)

### Litterature Review : Machine Learning for the Analysis of Quantitative UX Questionnaire Data

A review of research applying machine learning models to analyse and interpret quantitative UX questionnaire results, with the aim of turning user feedback into actionable insights for improving overall user experience. This work has been completed as part of the course Advanced Topics in Human-centered Computing at the University of Copenhagen in the spring semester of 2026. 

📄 [Paper](./HCI_Small_Litterature_Review_Exercise.pdf)

### Artifact Proposal : A Random Forest-based System for Interpreting Attrakdiff Quantitative UX Questionnaires

This project aims at designing an experiment to evaluate an artifact that uses a Random Forest model to interpret quantitative AttrakDiff questionnaire results. The proposal defines the study setup, the evaluation criteria and the procedure for assessing whether the system helps practitioners draw meaningful conclusions to improve user experience. This work has been completed as part of the course Advanced Topics in Human-centered Computing at the University of Copenhagen in the spring semester of 2026.

📄 [Paper](./HCI_Artifact_Proposal.pdf)

### Comparative Review of Three Papers : Knowledge Graphs and AI in the Legal Domain

*Written in French*\
*Original title : L'application des graphes de connaissances et de l'intelligence artificielle dans le secteur juridique*

A critical review of three 2024 research papers on combining knowledge graphs with artificial intelligence to make legal information easier to retrieve. The papers cover the construction of a judicial case knowledge graph using LLMs and graph embedding models with link prediction (TransE, ConvE, RotatE), a retrieval-augmented law article recommendation system combining GPT-4 with a case-enhanced knowledge graph, and a legal case retrieval approach based on a heterogeneous graph that integrates the hierarchy of legal statutes through metapaths. Each paper is summarised and critically assessed, before a comparison highlights their shared techniques and the progression towards increasingly integrated and complex systems.

📄 [Paper (French)](./Legal_Knowledge_Graphs_Papers_Review.pdf)

### 800-words paper : Applying Machine Learning to Interpret Quantitative UX Questionnaire Results

UX questionnaires produce quantitative data that is slow to analyse by hand. This paper presents an artifact that uses classification models to turn AttrakDiff responses into concrete areas for improvement using the 800-words paper method. Six models are compared using two multi-label strategies on detailed and averaged data. The model was integrated into a web application that displays the predicted improvement areas along with design recommendations. This work has been completed as part of the course Design Science Research at the University of Geneva in the fall semester of 2024.

📄 [Paper](./800_Words.pdf)

### Bachelor's Thesis Report : Applying Artificial Intelligence to User Experience : Using Machine Learning to Interpret AttrakDiff Questionnaire Results

*Written in French*\
*Original title : « Application de l'intelligence artificielle au domaine de l'expérience utilisateur : comment utiliser les technologies de machine learning pour interpréter des résultats de questionnaires Attrakdiff ? »*

This bechelor's thesis investigates whether machine learning can automate the interpretation step of quantitative results from UX evaluation questionnaires. After a review of UX evaluation questionnaires and existing ML applications in UX, a dataset of AttrakDiff evaluations was compiled from scientific articles and student projects, with each evaluation labelled with interface problems (clarity, creativity, intuitiveness, lack of information, professionalism, aesthetics). Twenty-four multi-label classification setups were compared using leave-one-out cross-validation, combining six models (Naive Bayes, decision trees, Random Forest, KNN, logistic regression, SVM), two multi-label strategies (One-vs-Rest, Classifier Chains) and two levels of input detail. The selected model, a Random Forest with Classifier Chains on detailed word-pair scores, was integrated into a Flask web application that predicts an interface's weak points from AttrakDiff results and suggests matching design solutions and UX techniques.

📄 [Bachelor's Thesis (French)](./Projet_de_Bachelor.pdf)
