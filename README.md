# <KTX 승차수요 예측 프로젝트>

분석내용 : KTX 노선별 월별 수요 예측
* 데이터기간 : 2015년1월~2024년3월
* 종속변수 : 승차인원수
* 독립변수 : 날짜 변수, 좌석 및 운행 변수, 한국 CPI, 승차인원수 lag 변수(과거승차인원)
---
예측대상 :
* KTX 5개 노선 : 경부선, 경전선, 동해선, 전라선, 호남선
* 노선별 월별 수요(승차인원수)
---
결과 :
* 활용 알고리즘 : 머신러닝 4종(Random Forest, XGBoost, LightGBM, Catboost), 딥러닝 2종(LSTM, GPU)
* 각 노선별 Best Model : 
![result_ktx](https://github.com/user-attachments/assets/fe1bc97e-409b-4fd1-91c3-d641595535c3)


* 시각화
![경부선](https://github.com/user-attachments/assets/d9f6f180-d98b-43db-84fe-4491445bfe3e)
![경전선](https://github.com/user-attachments/assets/a158af5f-60ec-4843-ae59-3f2f42272cf6)
![전라선](https://github.com/user-attachments/assets/1a55456d-98ae-4a50-a466-91b2ab241918)
![호남선](https://github.com/user-attachments/assets/c49b80ce-a77c-49d5-9d57-7ce053c5d0f5)
![동해](https://github.com/user-attachments/assets/e3c02f9a-67bc-45ec-971a-9c62b92da109)

