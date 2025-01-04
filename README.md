# <KTX 승차수요 단기예측 분석>

분석내용 : KTX 노선별 수요 예측
* 데이터기간 : 2015년1월~2024년3월
  * Train : 2015년1월~2023년3월
  * Val : 2023년4월~2024년3월
  * Test : 2024년4월~2025년12월
* 종속변수 : 승차인원수
* 독립변수 : 날짜 변수, 좌석 및 운행 변수, 한국 CPI, 승차인원수 lag 변수(과거승차인원)
---
예측대상 :
* KTX 5개 노선 : 경부선, 경전선, 동해선, 전라선, 호남선
* 주중 및 주말 기준 : (주중) 월화수목, (주말) 금토일
* 케이스 5종 : 월별 KTX 전체 수요
---
* 활용 알고리즘 : 머신러닝 5종(Random Forest, XGBosst, LightGBM, Catboost), 딥러닝 3종(LSTM, GPU, CNN-LSTM)
* 각 노선별 Best Model : 
![ktx](https://github.com/user-attachments/assets/eebe8416-2d1b-4804-857f-64c0587d87bc)
---
* 시각화
![경부선](https://github.com/user-attachments/assets/d9f6f180-d98b-43db-84fe-4491445bfe3e)
![경전선](https://github.com/user-attachments/assets/a158af5f-60ec-4843-ae59-3f2f42272cf6)
![전라선](https://github.com/user-attachments/assets/1a55456d-98ae-4a50-a466-91b2ab241918)
![호남선](https://github.com/user-attachments/assets/c49b80ce-a77c-49d5-9d57-7ce053c5d0f5)
![동해](https://github.com/user-attachments/assets/e3c02f9a-67bc-45ec-971a-9c62b92da109)

