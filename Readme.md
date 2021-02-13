## DACON : 3학년 2학기 오픈소스설계 <br>
This is a project for Data Science and AI competetion, using Machine-Learning and Neural Network, by Inho Song, Dankook UNIV.<br>

> 데이터 과학 대회에 나가보자! 
>	> 1. DACON 데이콘 <br>
> > > 단국대 천체모형 : ML, NN, 정형 데이터 분류기 대회 (Multi-Classifier) - 최종성적 (13/400)<br>
간단한 데이터 가공 및 Augmentation 이후 Xgboost, Random Forest, LightGBM, Linear Regression 등을 ensemble 한 Model을 최종 제출함. <br>

> > > 소설저자AI : NN, 자연어 처리 소설저자 예측 대회 (NLP) - 최종성적 (92/287)<br>
500단어 이내로 문장을 가공, Text Augmentation 등을 통해 데이터를 약 2~3배 정도 불리는(약 18만개) 텍스트 가공.<br>
RNN, CNN, DNN 등 NN기반 Model과 Xgboost, LightGBM 등 분류기 모델을 Ensemble.<br>
But, ensemble하는 과정에서 데이터의 크기들이 서로 통일되지 않는 초기단계의 오류 때문에 마감시간내에 최종 설계 모델을 제출하지 못함.<br>
최종 제출 모델은 CNN모델의 성능임.<br>
