# Data-Analysis-Practice
## kaggle-survey-2017

**[부스트코스] 캐글 실습으로 배우는 데이터 사이언스**

**⊙ 캐글러 대상 설문조사 데이터 분석과 시각화**

https://www.edwith.org/boostcourse-ds-kaggle/joinLectures/28019

[목차]
1. 데이터 사이언스 어떤 사람들이 할까요?
2. 데이터 사이언스 공부 어떻게 시작해야 될까요?
3. 데이터 사이언스 직무에서 가장 중요하다고 생각되는 스킬은?
4. 어떻게 하면 데이터 사이언티스트가 될 수 있을까요?


## Quiz 정리

1. Pandas

- 파이썬에서 사용하는 엑셀과도 유사한 데이터 분석 라이브러리이다. 이 라이브러리는 증권사에서 퀀트를 하던 Wes Mckinney에 의해 개발되었으며 R과 유사한 도구가 파이썬에도 있었으면 좋겠다는 아이디어에서 만들어지게 되었다. 따라서 R과 유사한 기능을 제공하고 있으며 엑셀로 다룰 수 없는 대용량 데이터를 다루기에 적합하다.
- describe로 요약 수치 보기, head, tail로 데이터 미리 보기, shape로 행렬 데이터의 크기를 보기, groupby로 데이터 집계하기, fillna로 결측치를 다른 값으로 채우기 등의 기능이 있다.
> df[].astype('str').apply(lambda x: x.split(',')) \
º 문자열을 , 로 분리해서 리스트로 만드는 역할을 한다.

2. describe

데이터의 요약된 수치를 볼 수 있는 기능이다. count, max, min, median 등의 값을 볼 수 있다.

3. value_counts(normalize=True)

value_counts는 범주형 데이터의 값을 그룹화해서 count 할 때 주로 사용한다. normalize=True 옵션을 사용하면 비율을 통해 그룹화한 수를 표현할 수 있다.

4. countplot

seaborn 으로 시각화를 할 때 x, y축 둘 중 하나의 값만 지정을 하면 나머지 축에 그룹화 된 갯수를 세어 표시해 주는 plot이다.
