### Home Hackathon 2018: Recommendation System Competition

<img src="https://www.homedottech.com/wp-content/uploads/2019/08/Hackathon-landscape-20180530-01-2-1-1024x576.jpg" width="600">

This is my work for when I participated in Home Hackathon 2018: recommendation system competition. Given the data of user access logs from January to February 23rd, the goal is to predict the next new pages that each user will visit during the last week of February. Only pages that each user has not visited during the training period are treated as a new page. I got the "Technical Excellence" award from this hackathon.

Competition Detail (in Thai): [[Link1](https://www.homedottech.com/homehackathon-2018/)] [[Link2](https://www.homedottech.com/%E0%B8%9B%E0%B8%A3%E0%B8%B0%E0%B8%81%E0%B8%B2%E0%B8%A8%E0%B8%9C%E0%B8%A5-home-hackathon-2018/)]

---

### Result
- Result Presentation: [[Slide](https://docs.google.com/presentation/d/1i2aegeND4znD5QESJROao_nGRO_cZPvW7DGtp-Lrv8Q/edit?usp=sharing)]

##### Data prepration
- Data Exploration: [[notebook](%5BExplore%5D%201.%20Overview.ipynb)]  
- Data Preparation: [[notebook](%5BClean%5D%201.%20Prepare%20data.ipynb)]  
- Bot data removal: [[notebook](%5BClean%5D%20Remove%20bot.ipynb)]  
- Item2Vec Embeddings from user views: [[notebook](%5B**Train%5D%20Item2Vec.ipynb)]  
- Doc2Vec Embeddings from descriptions: [[notebook](%5BTrain%5D%20Doc2Vec.ipynb)]  

#### Prediction
- Baseline (Most frequent properties): [[notebook](Naive%20most%20frequent.ipynb)]  
- Matrix factorization (SVD): [[notebook](Matrix%20Factorisation%20collaborative%20filtering.ipynb)]  
- Item2Vec embeddings: [[notebook](%5B**Train%5D%20Item2Vec.ipynb)]  
- LSTM: [[notebook](%5B*%20Train%5D%20LSTM%20Multiclass.ipynb)]  
- GRU: [[notebook](%5B**Train%5D%20Last%20GRU.ipynb)]  

---
