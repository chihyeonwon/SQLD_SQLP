# SQLD_SQLP
SQL개발자/SQL전문가  certification

## 24.03.09 춘천 52회 SQLD 

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
#### 24.02.02
2과목 SQL 기본 및 활용
```
테이블명과 칼럼명은 반드시 문자로 시작해야 하며 특수 문자는 _와 $만 가능하다 (-는 불가)
FROM 절에서 테이블에 대한 Alias를 사용하였다면 SELECT 절에서는 반드시 테이블명이 아닌 ALIAS명을 사용해야 한다.
EQUI JOIN은 반드시 기본키, 외래키 관계에서만 성립되는 것은 아니다. 조인 컬럼이 1:1로 맵핑이 가능하면 사용할 수 있다.
테이블의 개수가 N개일 때 필요한 조인 조건의 최소 개수는 N-1이다.
UNION ALL 연산자는 조회 결과에 대해 별도의 정렬 작업을 하지 않고, 중복 데이터에 대해서 삭제하지 않고 여러 번 중복 표현한다.
SELF JOIN을 수행해야할 때는 ? 한 테이블 내에서 두 칼럼이 연관 관계가 있다.
```

#### 1회기출
```
슈퍼타입과 서브타입 변환의 종류 : One To One(개별 테이블로 도출), Plus(분리해서 도출), Single Type(통합)
CONNECT BY는 부모 계층형 쿼리에서 부모 노드와 자식 노드 사이의 특정한 관계를 나타내는데 사용된다.
계층형 쿼리 start with 부모, connect by prior 자식 = 부모 꼴이면 순방향 전개이다.
dense_rank() : 중복된 순위 다음에는 바로 다음 순위를 부여, Rank() 중복된 순위 다음에는 중복된 순위 다음 순위 부여
unbounded preceding은 end point에 사용될 수 없다.
null이 null인지를 비교할 때는 알 수 없음 (오류가된다)
자동형변환 : To_char, To_date,
숫자형->Date는 자동형변환이 안된다.
SQL문을 ANSI 표준 SQL로 바꾸는 문장 -> left,right outer join, cross join이 아닌 inner join 이여야 함
(+)가 붙은 쪽이 null로 추가된다. (+)가 왼쪽에 있다면 outer join on의 왼쪽에 위치하게 한다.
스스로 생성되는 식별자 -> 내부, 다른 엔터티 간의 관계에 의해서 만들어지는 식별자 -> 외부
```
#### 2회기출
```
파티션기법의 종류: List Partition(관리자가 파티셔닝할 항목을 직접 지정), Range(범위 기준), Hash(해시 함수이용)
Compsite(Range와 Hash를 복합적으로 사용한다.)
실행 계획을 읽는 순서 : 안에서 밖으로 읽으면서 같은 레벨에서는 위에서 아래로 읽는다.
declare cursor-> open cursor -> fetch cursor -> close cursor
rownum은 oracle db, sql server에서는 top구에 with ties를 사용한다.
where 절에 같지않음이 들어가면 cross join 을 수행한다.
스칼라 -> 메인쿼리 o 메인쿼리 -> 스칼라 x
인라인 -> 메인쿼리 o 메인쿼리 -> 인라인 o
predicate information에서 행의 수를 9개로 제한 filter(ROWNUM<10)
ntile 함수 -> ntile(n) n만큼 파티션을 균등하게 분할한다. order by 1 오름차순으로 정렬후 균등하게 분할
lead(대상속성, 순서, 디폴트 값) 이후 순서(몇 칸?)에 나올 행을 출력한다. 반대는 Lag 함수 (이전 행)
nullif(a,b) a와 b가 같으면 null을 출력 같지 않으면 a를 출력한다.
Nested Loop join은 Random Access가 발생하여 성능이 떨어진다. 선행과 후행테이블을 선정하고 선행 조회 후
후행 테이블을 Random access로 조인한다.
```
#### 3회기출
```

```
#### 4회기출
```

```
#### 5회기출
```

```
#### 6회기출
```

```
#### 7회기출
```

```
