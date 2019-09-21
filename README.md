##### Meeting Log & Timeline
---

### 1st : 프로젝트 아웃라인 소개, 플젝장 정하기
#### Overview
- 일시: 9/19
- 작성자: 최보경  
- 참석자: 전원

#### Pre-shared (해온 것을 공유)
<details>
  <summary> Click to expand! </summary>
  1. 데이터셋 소개자료
  2. 지난 프로젝트에서의 방황 이야기
</details>

#### Contents and Decisions (결정 사항)
- 앞으로 기대하는 프로세스: 데이터 분석 A to Z 를 경험해보는 것이 우선순위 목표

#### Forward Plans (앞으로 할 것을 이야기)
1. 변수설명 한글 파일 + pdf 파일 
   => 각 6가지 파일을 pd.read_csv()
   주피터를 통해서 읽어보고, 변수에 대해 이해
2. EDA, 전처리, 모델링 다 무엇인지에 대한 구글링

---
### 2nd : 데이터 구조와 변수 파악

#### Overview
* 일시: 9/21 17:00 ~ 18:00
* 작성자: 최보경
* 참석자:

#### Pre-shared (해온 것을 공유)
<details>
  <summary> Click to expand! </summary>

- 데이터셋에 대한 생각, 모르는 것
 동민: session 데이터셋에서 sess_seq sess_id 가 헷갈린다. session이 어렵다.
 동진: 결과적으로 상품 구매를 유도하는데, hit을 어떻게 유도할 수 있을까? 선후관계를 어떻게 파악할 수 있을까? hit 상품 구매 최소 단위
 원지: 
 한 명의 방문자여도 여러개의 adid. 세션 단위를 한 사람으로 카운트해도 괜찮을까?
 검색어 관련 데이터셋은 EDA가 어렵지 않을까?
 
- EDA, 전처리 프로세스에 대한 구글링
 리서치 자료는 공유
 http://www.dodomira.com/2016/10/20/how_to_eda/
 https://towardsdatascience.com/a-gentle-introduction-to-exploratory-data-analysis-f11d843b8184
 https://eda-ai-lab.tistory.com/13
 https://wanzargen.tistory.com/1
  
</details>

#### Contents and Decisions (결정 사항)

1. 데이터셋 분담
동민 - Product
동진 - Search1
원지 - Search2
민섭 - Custom
상품 분류 left

2. 전처리는 차후로 미루고, 이번에는
> 1) EDA(통계량 분석, 눈으로 훑어 변수 이해, 변수들간 상관관계 파악)
> 2) 아웃라이어 제거
> 3) 각 데이터셋을 더 파고들어 보자. 더 깊은 고민을 해보자


#### Forward Plans (앞으로 할 것을 이야기)




