# DeeplearningProject_2020-2
deeplearning trajectory prediction in 2020-2

## 구성원 :
인하대학교 산업경영공학과<br>
: 12140471 김성진 <br>
: 12160539 김성민 <br>
: 12180604 김민규 <br>

## 개요 :

한 사람의 데이터를 바탕으로 과거의 데이터를 바탕으로 미래의 방문할 장소 혹은 좌표를 예측하는 프로젝트
데이터 출처 : https://www.microsoft.com/en-us/download/details.aspx?id=52367&from=http%3A%2F%2Fresearch.microsoft.com%2Fen-us%2Fdownloads%2Fb16d359d-d164-469e-9fd4-daa38f2b2e13%2F

## 사용될 모델
1. lstm 완료 - 파라미터 튜닝 중
2. gru
3. transformer

## 디렉토리 구조
Map_info : 
1) 구글 map api를 활용해 좌표 데이터를 바탕으로 주소를 받아온 후 papago api를 활용해 그 데이터를 해석하여 한글로 만들어 냄 
2) td-idf를 활용해 문자열 처리하여 필요한 단어 추출 + 관련된 장소로 매핑

DataPreprocessing : trajectory 기본 데이터 전처리

Model : 3가지 모델 구현
