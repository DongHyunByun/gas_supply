# gas_supply

1. **기간 : 2021.10.11 ~ 12.10**  

1. **주관 : 한국가스공사**  

1. **팀원**  
    1. 씩씩한오리너구리 (https://github.com/DongHyunByun/)

1. **기술스택**  
    1. 개발환경 : python.   
    2. 전처리 : pandas, numpy, plt, sns, pickle, itertools, sklearn. 
    3. model : LSTM, prophet, LGBMRegressor, DecisionTreeRegressor, RandomForestRegressor, XGBRegressor.   
    
1. **내용 : 가스 공급량 수요예측**  
    1. 가스 사용량 예측 (시계열 예측 대회)
    
1. **파일설명**  
    1. dl_use_date.ipynb
        1. 년, 월, 일 데이터를 x값으로 사용
        2. dnn 모델 사용
    2. dl_use_last_7.ipynb
        1. 직전 7일로 다음 값을 예측
        2. lstm 모델 이용
    3. prophet.ipynb
        1. prophet 모델 이용
        2. y값 만을 이용
    4. ml_use_date.ipynb
        1. 년, 월, 일 데이터를 x값으로 사용
        2. dnn 모델 사용
1. **결과**  
    115위/259명
    ![image](https://user-images.githubusercontent.com/50386280/152793972-8b91b905-c8f4-46a7-9701-996e24ae69ce.png)
