# SQL server에서의 계층형 질의문은 CTE(Common Table Expression)를 재귀호출하여 계층구조 전개
# SQL server에서의 계층형 질의문은 앵커 멤버를 실행하여 기본 결과 집합을 만들고 이후 재귀멤버 지속 실행
# 오라클의 계층형 질의문에서 `where`절은 모든 전개를 진행한 이후 필터조건으로서 조건을 만족하는 데이터만을 추출하는데 활용됨
# 오라클의 계층형 질의문에서 `prior` 키워드는 `connect by`뿐 아니라 `select`, `where`절에서도 사용 가능
