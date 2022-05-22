## POI-Recommendation
POI-Recommendation is a repository of codes and experiment results for next Position-Of-Interest recommendation.

### Publications
See the following publications for examples of this code in use:
 * **An LSTM-based Point-Of-Interest Recommendation System Considering Stay Time**, S. Yu, C. Kim, K. Y. Lee  
[Korea Computer Congress 2022](https://www.kiise.or.kr/conference/kcc/2022/), Jun. 2022, Jeju, Republic of Korea. (Ack: NRF-2021)

### Datasets  
Used the data given below by attaching the stay time (formula for calculating stay time is presented in the paper)
 * [Gowalla](https://snap.stanford.edu/data/loc-gowalla.html): location-based social networking website where users share their locations by checking-in  
 * [Foursquare](https://sites.google.com/site/yangdingqi/home/foursquare-dataset): check-ins, tips and tags data of restaurant venues in NYC collected from Foursquare  

### Codes
 * [poi_lstm.py](poi_lstm.py) is the Python code of next POI recommendation using LSTM.  
 * [poi_attention.py](poi_attention.py) is the Python code of next POI recommendation using Attention Machanism.  
