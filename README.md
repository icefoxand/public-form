# 1. 주기능

**1. 폼 생성**

- 기능 설명: 사용자는 새로운 폼을 생성할 수 있어야 한다.
- 요구사항:
  - 사용자가 폼의 제목을 입력할 수 있어야 한다.
  - 사용자가 폼의 설명을 선택적으로 입력할 수 있어야 한다.
  - 폼 생성 후 고유한 URL이 생성되어야 한다.
  - 폼은 다수의 질문을 포함할 수 있어야 한다.

**2. 질문 추가**

- 기능 설명: 사용자는 폼에 다양한 형태의 질문을 추가할 수 있어야 한다.
- 요구사항:
  - 지원하는 질문 유형: 단답형, 서술형, 선택형 (다중 선택 포함), 체크박스, 드롭다운 등.
  - 각 질문에 대해 필수 여부를 설정할 수 있어야 한다.
  - 사용자는 질문의 순서를 변경할 수 있어야 한다.
  - 질문 별로 설명을 추가할 수 있어야 한다.

**3. 응답 수집**

- 기능 설명: 생성된 폼을 통해 사용자 응답을 수집하고 저장할 수 있어야 한다.
- 요구사항:
  - 모든 입력된 응답은 데이터베이스에 저장되어야 한다.
  - 사용자가 폼을 제출할 때 응답 완료 페이지를 볼 수 있어야 한다.
  - 폼 제출 전 사용자는 자신의 입력을 검토하고 수정할 수 있어야 한다.

**4. 응답 분석**

- 기능 설명: 수집된 응답을 분석하고 결과를 표시할 수 있어야 한다.
- 요구사항:
  - 수집된 응답의 요약을 통계적으로 표시해야 한다 (예: 응답률, 평균 선택 등).
  - 각 질문별로 응답을 그래프 형태로 시각화할 수 있어야 한다 (예: 바 차트, 파이 차트).
  - 사용자는 특정 시간 범위 내의 응답을 필터링 할 수 있어야 한다.
  - 응답 데이터는 CSV 또는 Excel 형식으로 내보낼 수 있어야 한다.

# 2. 부가기능

**1. 사용자**

1. 공공기관 측 (공공인)
   1. 회원가입
      - 자기 기관을 지도에서 검색해서 집어넣기(카카오맵 - 지도api 사용)
   2. 로그인
2. 일반인 (비 공공인)
   1. 회원가입
   2. 로그인
3. 질문 만들 때 응답으로 지도에서 특정한 곳들을 **마커 형태**로 선택해서 응답으로 제출할 수 있음
