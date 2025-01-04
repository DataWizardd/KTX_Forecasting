# <KTX 승차수요 단기예측 분석>

분석내용 : KTX 노선별 수요 예측
* 데이터기간 : 2015년1월~2024년3월
  * Train : 2015년1월~2023년3월
  * Val : 2023년4월~2024년3월
  * Test : 2024년4월~2025년12월
* 파생변수 : 시간정보/경제환경 등 활용
---
예측대상 :
* KTX 5개 노선 : 경부선, 경전선, 동해선, 전라선, 호남선
* 주중 및 주말 기준 : (주중) 월화수목, (주말) 금토일
* 케이스 5종 : 월별 KTX 전체 수요
---
* 활용 알고리즘 : 머신러닝 5종(Random Forest, XGBosst, LightGBM, Catboost), 딥러닝 3종(LSTM, GPU, CNN-LSTM)
* 각 노선별 Best Model : 
![ktx](https://github.com/user-attachments/assets/eebe8416-2d1b-4804-857f-64c0587d87bc)
