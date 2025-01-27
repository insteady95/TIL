# 친절한 SQL 튜닝

## 요약 정리

[1. SQL 처리 과정과 I/O](https://github.com/insteady95/TIL/blob/main/Kind_SQL/1.SQL%20%EC%B2%98%EB%A6%AC%20%EA%B3%BC%EC%A0%95%EA%B3%BC%20IO.md)

[1.1 SQL 파싱과 최적화](https://github.com/insteady95/TIL/blob/main/Kind_SQL/1.1.SQL%20%ED%8C%8C%EC%8B%B1%EA%B3%BC%20%EC%B5%9C%EC%A0%81%ED%99%94%20.md)

[1.2 SQL 공유 및 재사용](https://github.com/insteady95/TIL/blob/main/Kind_SQL/1.2.SQL%20%EA%B3%B5%EC%9C%A0%20%EB%B0%8F%20%EC%9E%AC%EC%82%AC%EC%9A%A9%20.md)

[1.3 데이터 저장 구조 및 IO 매커니즘](https://github.com/insteady95/TIL/blob/main/Kind_SQL/1.3.%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%A0%80%EC%9E%A5%20%EA%B5%AC%EC%A1%B0%20%EB%B0%8F%20IO%20%EB%A7%A4%EC%BB%A4%EB%8B%88%EC%A6%98%20.md)

[2.1 인덱스 구조 및 탐색](https://github.com/insteady95/TIL/blob/main/Kind_SQL/2.1.%EC%9D%B8%EB%8D%B1%EC%8A%A4%20%EA%B5%AC%EC%A1%B0%20%EB%B0%8F%20%ED%83%90%EC%83%89.md)

---

## 계획

- SQL 전문가 가이드

---

## 효과적인 SQLP 공부 방법

1. 친절한 SQL 튜닝 가볍게 1독 (이해안되면 PASS)
    
    : SQL 분석 도구 부터 보기
    
2. 친절한 SQL 튜닝 정독 1독
3. SQL 전문가 가이드
4. SQLP 자격걱정 핵심노트 1장 11장

---

1. 시험 보기 (경험)

---

1. 오라클 성능 고도화 1권 4장 6장
    
    : 6장은 친절한 SQL튜닝 1장으로 대체가능
    
2. 오라클 성능 고도화 2권
3. 오라클 성능 고도화 1권 1장 2장 (이해안되면 ‘언젠가는’)
4. 오라클 성능 고도화 1권 3장 (여유되면)
    
    : 실제 업무 그리고 튜닝에 도움
    

---

저자강의

1번전에 SQLP 기본과정 (친절한 SQL 튜닝)

SQLP 고급과정 : 친절한 SQL 튜닝 2~3번 이해수준

---

적당한 시점에 데이터 모델링 공부, ERD를 읽고 해석하는 능력이 필수

---

반드시 직접 SQL 작성 수없이 테스트

---

SQLP 공식 함정

- 시험대비하면 암기는 필요하지만 공식에 의존 X
- 문제풀이식 공부방법은 공식함정에 빠지기 쉽다(출제가 의도)
- 같은 패턴의 문제도 주어진 단서 데이터 분포, 입력값에 따라 답이 다름
- 기출은 출제 경향 참고
- 원리 충실히 공부

---
