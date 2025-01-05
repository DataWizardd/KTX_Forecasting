# <KTX 승차수요 예측 프로젝트>

분석내용 : KTX 노선별 월별 수요 예측
* 데이터기간 : 2015년1월~2024년3월
* 종속변수 : 승차인원수
* 독립변수 : 날짜 변수, 좌석 및 운행 변수, 한국 CPI, KSVKOSPI, 승차인원수 lag 변수(과거승차인원)
---
예측대상 :
* KTX 5개 노선 : 경부선, 경전선, 동해선, 전라선, 호남선
* 노선별 월별 수요(승차인원수)
---
모델링 :
* 활용 알고리즘 : 머신러닝 4종(Random Forest, XGBoost, LightGBM, Catboost), 딥러닝 2종(LSTM, GPU)
* 각 노선별 Best Model :
  
![result_ktx](https://github.com/user-attachments/assets/fe1bc97e-409b-4fd1-91c3-d641595535c3)
* 시각화(경부선)
  
![경부](https://github.com/user-attachments/assets/053b21cd-a71e-4845-9947-2f239206b0ac)
---
결과 :
* 예측기간 : 2024년4월~2025년12월
* 활용 알고리즘 : 경부선, 전라선 - Random Forest / 경전선, 전라선 - XGBosst / 동해선 - LSTM
* 시각화(경부선)
  
![경부2](https://github.com/user-attachments/assets/2d225cdb-9c7a-4349-89f5-ed01e82fc4f4)

