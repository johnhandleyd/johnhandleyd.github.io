---
title: "📃 Does Noise matter when training Neural Machine Translation engines?"
#excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
excerpt: "Analysis of the impact that noise has in the data used to train Neural Machine Translation engines."
collection: portfolio
paperurl: ./files/thesis.pdf
---

Researchers have reached tremendous advances in the field of Neural Machine Translation (NMT) since it was first introduced. Up to the date of writing this thesis, searching for Neural Machine Translation in Google Scholar triggers hundreds of thousands of papers. However, not a lot of researchers seem to attribute much importance to the quality of the data they are using to carry out these studies. In this paper, we bring more awareness to this topic and provide tangible results that prove the following statement: quality is just as important as quantity in terms of training data when referring to NMT engines. To this end, we explore different cleaning methods for our chosen corpus and compare the results of these methods, both manually and automatically. The results prove that limiting segment length and the character difference between source and target segments, and removing untranslated and foreign language segments enhance the translations of the trained engines. Nonetheless, automatic evaluation metrics and a manual assessment agree that when all cleaning methods are applied, the outcome is confusing and, at times, lacks information from the source segment.