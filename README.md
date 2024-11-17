<h1 align="center"> 가족과 함께 탐승하는 경우 혼자 탑승했을 경우보다 더 높은 등급에 탑승할 확률이 높을 것이라는 가설을 세우고 예측하는 분류 모델을 만들고자 한다  </h1>

### 목차

* 1. 데이터 불러오기
    * 1.1 데이터 확인기기

* 2. 데이터 셋에 대한 궁금증
    * 2.1 등급별 평균 요금 구하기
    * 2.3 등급별 생존자 수 구하기

* 3. 같이 탑승했을 경우에 대한 궁금증
    * 3.1 가족 크기 비교하기
    * 3.2 동반자 수에 따른 생존 확률
- -가설 세우기
    - -각 클래스 별 가족과 함께 탑승한 사람과 혼자 탑승한 사람 비교하기
    - -그렇다면 가족과 함께 탑승할때 더 비싸고 좋은 좌석을 선택했을 것이라고 가설을 세움

<!-- <br>
<div>

</div> -->


## 데이터 탐색
.head()
.show()
.info()
.value_counts()

## 개발 환경
- Windows 11
 
## 설치
 
### Using pip
```bash
python -m venv .titanic
.\.titanic.\Scripts\activate
pip install jupyter
pip install pandas matplotlib seaborn numpy
pip install pykinect-recorder
```
