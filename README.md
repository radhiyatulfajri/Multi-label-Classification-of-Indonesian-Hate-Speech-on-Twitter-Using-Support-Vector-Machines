# Multi-label Classification of Indonesian Hate Speech on Twitter Using Support Vector Machines

If you want to know more about this program you can read this paper : https://ieeexplore.ieee.org/document/9212992

Don't forget to cite my paper if you use my code or data for your research or business.

The dataset consists of 18396 tweets with 12 labels.

Languages in dataset :

- 12334 (67,05%) Indonesian
- 3780 (20,55%) English
- 1991 (10,82%) Mixture of Indonesian and English
- 251 (1,58%) Others

Labels :

- HS (hate speech)
- Abusive (contain abusive word)
- HS_Individual (Hate speech aimed to individual target)
- HS_Group (Hate speech aimed to group target)
- HS_Religion (Hate speech with religion category)
- HS_Race (Hate speech with racial category)
- HS_Physical (Hate speech with physical category)
- HS_Gender (Hate speech with gender category)
- HS_Other (Hate speech that not belong to any category)
- HS_Weak (Weak level hate speech)
- HS_Moderate (Moderate level hate speech)
- HS_Strong (Strong level hate speech)

Classifier :

- Support Vector Machines
- Convolutional Neural Network
- Convolutional Neural Network + DistilBERT

Data Transformation :

- Classifier chains
- Label powerset

Preprocessing :

- Full preprocess
- Without stopword removal
- Without stemming and removal

Overcome multilingual problem :

- With translate
- Without translate
