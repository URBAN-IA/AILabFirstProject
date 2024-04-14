# Upstage AI Lab 첫번째 과제.
---



## 프로젝트 소개
---
특정 코인 정보 사이트에서 크롤링한 코인 정보를 웹API 로 제공.



## Web API 목록

### * http://localhost:8000/docs
### * http://localhost:8000/api/v1/coin/TopCoinsByExchangeVolume



## 필요한 패키지 설치

pip install beautifulsoup4

pip install selenium

pip install webdriver-manager

pip install fastapi

pip install uvicorn[standard]

pip install tensorflow

pip install pillow

pip install numpy

pip install python-multipart

pip install python-telegram-bot

pip install streamlit

pip install snowflake-connector-python


## 약간의 수정

Crawling/TopCoinsByExchangeVolume.py -> crawlingTopCoinsByExchangeVolume() 함수에서

원하는 url 로 수정할것.

https://docs.snowflake.com/ko/developer-guide/python-connector/python-connector-connect 를 참고해서 

%USERPROFILE%\AppData\Local\snowflake\connections.toml 파일 생성할것.


## 실행 방법

### WebAPI, 웹 스크래핑
python main.py

### Streamlit 웹페이지
Streamlit 폴더에서,

streamlit run app.py
