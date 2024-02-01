# SQLD_SQLP
SQL개발자/SQL전문가  certification

## 자격요건 및 합격기준
![image](https://github.com/wonttan/SQLD_SQLP/assets/58906858/cc8e8790-50c4-4efc-926a-7d4272b00a98)
```
60점 이 즉, 2점짜리 50문제 중 30문제 맞추면 합격
과락40%  1과목 데이터모델링 4/10 4문제이상
2과목 SQL 기본 및 활용 16/40 16문제이상
```

## 시험일정
![image](https://github.com/wonttan/SQLD_SQLP/assets/58906858/82367731-d736-46fc-a5ad-af98475bc1b7)

## 출제문항
![image](https://github.com/wonttan/SQLD_SQLP/assets/58906858/fbf5f40e-8648-4fe1-a0c3-b38cb424f510)

## 시험준비
[이기적 CBT SQL 개발자](https://cbt.youngjin.com/exam/index.php?no=73)
[이기적 SQL 개발자 기출문제 500제](https://license.youngjin.com/free_edu/free_edu_mp4.asp?elc_cd=2536&cate_cd=2393)
```
데이터베이스 응용 과목 들으면서 이기적 기출문제 500제 풀고 쉴 때 CBT
```
![image](https://github.com/wonchihyeon/SQLD_SQLP/assets/58906858/d0e5f82d-3df7-44aa-8c6b-29e4dc7ec7b8)
![image](https://github.com/wonchihyeon/SQLD_SQLP/assets/58906858/239539e7-daba-4887-b6aa-abb2b195f450)
![image](https://github.com/wonchihyeon/SQLD_SQLP/assets/58906858/2a753950-e317-4194-b3be-9db85738624a)

## SQL 개발자 핵심 150제 틀린 문제 개념 정리
#### 24. 02.01
![image](https://github.com/wonchihyeon/SQLD_SQLP/assets/58906858/96efc438-7ad1-4d5e-9658-7bf7d41f1c8f)
```
모델링을 할 때 세 가지 관점 : 데이터, 프로세스, 데이터와 프로세스의 상관 관점

데이터 모델링의 세 가지 개념 : 업무가 관여하는 어떤 것 Things, 업무가 관여하는 어떤 것의 성격 Attributes, 업무가 관여하는
어떤 것의 관계 : Relationships

발생 시점에 따라 구분할 수 있는 엔터티의 유형 : 행위, 중심, 기본

관계를 정의할 때 주요하게 체크해야 하는 사항 : 업무기술서, 관계연결을 가능하게 하는 동사가 있는가?

식별자의 대체 여부에 따라 분류하는 방식은? : 본질-인조 식별자

비식별자 관계란 부모 엔터티로부터 속성을 받았지만 자식 엔터티의 주식별자로 사용하지 않고 일반적인 속성으로만 사용하는 것

데이터 모델링에 대한 설명 : 논리 모델링의 외래키는 물리 모델에서 반드시 구현되지는 않는다.

분산 데이터베이스의 특징 : 처리 비용의 증가, 오류 잠재성 증대, 빠른 응답 속도와 통신 비용 절감

해시 조인 기법 : 조인 작업을 할 때 결과 행의 수가 적은 것을 선행 테이블로 사용, '='로 수행하는 동등조인만 가능
적재할 수 있는 영역 크기보다 커지면 임시 영역(디스크)에 적재, 조인 칼럼의 인덱스가 존재하지 않아도 사용 가능

어떤 엔티티의 모든 속성을 참조하기를 원할 때 성능 향상과 SQL 문장을 단순화하는 가장 적절한 반정규화 방법은 ?
- 관계를 중복하는 관계의 반정규화 (1:M관계 등을 추가하는 관계 반정규화)

데이터 모델의 성능을 고려하기 위해 정규화를 적용한 데이터모델을 만든다.

분산 데이터베이스의 투명성 : 분할, 위치, 지역, 중복, 병행, 장애

논리적인 데이터 모델 슈퍼/서브 타입의 데이터 모델 성능을 고려한 물리적인 모델에서 변환하는 방법 세 가지
1:1 타입, 슈퍼+서브 타입, All in One 타입

데이터무결성을 깨뜨리지 않는 기법 : 중복관계의 반정규화
데이터무결성을 깨뜨리는 기법 : 칼럼, 테이블의 반정규화
```
