## 2. 이론적 배경
### 2.1 언어학적 설명 
### 2.1.1 참조표현의 유형
* 부정명사(Indefinite Noun Phrases)
* 한정명사(Definite Noun Phrases)
* 대명사(Pronouns)
* 지시대명사(Demonstrative Pronouns)
* 영형 조응 현상(Zero Anaphora)
* 명칭(Names)

### 2.1.2 담화구조와 참조표현
#### 2.1.2.1 정보 위상(Inforamtion Satus) (Prince, 1981, Prince, 1992)
* 청자 구정보(hearer-old)와 청자 신정보(hearer-new) 
* 담화 구정보(discourse-old)와 담화 신정보(discourse-new) 
* 추론 가능 표현(inferrables)과 가교 지시(Bridging reference)
#### 2.1.2.2 중심화 이론(Centering Theory) (Joshi & Prince, 1998a, Joshi & Prince, 1998b)
* 전향중심(forward-looking centers, Cf), 후향중심(backward-looking centers, Cb), 선호중심(preferred center, Cp)
* 제약 및 규칙
#### 2.1.2.3 접근성 이론(Accessibility Theory) (Ariel, 2001, Ariel, 2013)
* 중심화 이론의 한계점
* 접근성 표지로서의 참조표현

### 2.1.3 상호참조관계와 언어적 제약조건
* 수(數)일치
* 인칭(人稱)일치
* 성(性)일치
* 결속이론(Binding Theory)의 제약
* 문장성분(Grammatical Roles) 관련 제약
* 동사 관련 제약
* 선택적 제약

### 2.2 자연어처리에서의 상호참조해결 문제
### 2.2.1 상호참조해결 태스크의 정의
* 정의: 감지된 멘션 간의 상호참조 관계에 있는 멘션들을 쌍 혹은 클러스터로 분류하는 네트워크의 
* 멘션 감지와 상호참조해결

### 2.2.2 데이터셋과 평가 매트릭스
#### 2.2.2.1 주요 데이터셋
* MUC
* ACE
* OntoNotes
#### 2.2.2.2 CoNLL 상호참조해결 경진대회와 평가 매트릭스
* MUC F-measure
* B<sup>3<sup>
* CEAF

### 2.2.3 상호참조해결 알고리즘 구현 아키텍처들
* 멘션쌍 아키텍처
* 멘션 순위 아키텍처
* 엔티티 기반 모델

### 2.2.4 규칙 기반 모델과 머신 러닝 기반 모델
* 규칙 기반 모델
* 머신 러닝 기반 모델
* 자질(features)을 활용한 분류기(classifiers)의 역할

### 2.2.5 한국어 상호참조해결 관련 기존 연구
* 규칙 기반 연구
* 머신 러닝 기반 연구
* 한국어 상호참조해결을 위한 자질

### 2.2.6 기타 이슈들
* 2.2.5.1 엔티티 연결(Entity Linking)
* 2.2.5.2 위노그라드 스키마
* 2.2.5.3 상호참조해결와 젠더

### 2.3 요약
