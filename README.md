# JobPlatform-Filter-A/B-Test-project

## 1. 프로젝트 개요


- 이 프로젝트는 채용 플랫폼에서 구직자의 이탈을 탐지하고, 검색 필터 UI를 개선하여 전환율을 높이기 위한 A/B 테스트 설계서를 작성하는것을 목표로 함
- 검색 필터 사용 빈도와 전환율에 대한 분석을 통해 개선이 필요한 퍼널 단계를 파악하고, 구직자가 플랫폼 내에서 채용 공고를 검색하고 지원하는 여정을 최적화하기 위한 전략적 A/B 테스트 설계를 제안함

### 목표

	1.	사용자 여정 분석: 플랫폼 방문부터 지원 완료까지의 사용자 여정을 분석하여 주요 이탈 지점을 파악함
	2.	필터 사용 분석: 다양한 검색 필터가 구직자의 전환에 미치는 영향을 평가함
	3.	A/B 테스트 제안: 검색 필터 UI 개선을 통해 전환율이 상승할 것이라는 가설을 검증하기 위한 A/B 테스트 설계를 제공함


### 정의된 퍼널 단계

사용자 여정은 세 가지 주요 단계로 구성됨:
- 방문: 플랫폼에 방문한 사용자
- 채용 공고 조회: 채용 공고를 조회한 사용자
- 지원서 제출: 채용 공고를 조회 후 실제로 지원서를 제출한 사용자


### 데이터셋

- 본 프로젝트에서는 로그 데이터만을 사용하여 분석을 진행함. 로그 데이터에는 사용자 활동 기록이 포함되어 있으며, 페이지 방문, 필터 사용, 이벤트 타임 등의 정보가 담겨 있음


## 2. 주요 분석 내용

1. 사용자 여정 분석

- 퍼널 분석을 통해 각 단계의 전환율을 측정하였으며, 채용 공고 조회 단계에서 지원서 제출 단계로 이어지는 구간에서 큰 이탈이 발생하는 것을 발견함. 이는 구직자가 원하는 공고를 쉽게 찾지 못하거나, 필터 사용에서 어려움을 겪고 있음을 시사함

2. 필터 사용 효과 분석

- 분석 결과, 직무 분야와 지역 필터는 사용 빈도가 높았지만 상대적으로 낮은 전환율을 보임. 반면, 언어 필터는 높은 전환율을 보였지만 사용 빈도가 낮아, 필터 기능 개선의 여지가 있음을 확인함

3. 클릭-to-전환 시간 분석

- 사용자가 채용 공고 조회에서 지원서 제출로 이어지는 시간도 분석함. 필터 사용이 클릭-to-전환 시간을 증가시키는 경향을 보이며, 이는 필터 선택 과정에서 사용자의 마찰을 의미할 수 있음


## 3. A/B 테스트 제안

### 목표

- 검색 필터 UI를 개선하여 채용 공고 조회에서 지원서 제출로 이어지는 전환율을 높이는 것

### 테스트 설계

	•	가설: UI 변경 시 “채용 공고 조회 → 지원서 제출” 전환율 증가
	•	실험 설계:
		- 대조군(A안): 기존 드롭다운 형식
		- 실험군(B안): 중앙 스프레드 형식
		- 2024년 1월 1일부터 2월 5일까지 36일간 테스트 진행
	•	성과 판단 기준:
		- 주요 지표: 지원서 제출 전환율
		- 보조 지표: 필터 사용률

## 4. 주요 결과

	•	분석 결과를 통해 사용자 경험 및 전환율 개선 가능성 확인
	•	추가 실험 아이디어로 필터 순서 변경, 세부 분류 재조정, 항목 정렬 등을 제안

![image.jpg1](https://github.com/user-attachments/assets/fb50ca2d-964b-40bf-8607-ff801da7f5df) |![image.jpg2]([https://steemitimages.com/0x0/https://static.tasteem.io/uploads/image/image/7293/content_994dbe3f-631b-4f76-9ee1-751c87c668dd.jpeg](https://github.com/user-attachments/assets/fb2bdcd1-8a19-4b7d-99f1-e0fd1c38bd05))
--- | --- | 
