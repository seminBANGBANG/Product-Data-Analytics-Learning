# Product Metrics Notes

## Metric 정의

Metric은 의사결정을 돕는 정량 신호다. 분자, 분모, 기간, 단위·grain, 세그먼트, 제외·중복 처리를 고정해야 한다.

- Vanity metric은 보기에는 좋지만 다음 행동을 알려주지 않는다. Actionable metric은 팀이 바꿀 수 있는 원인과 연결된다.
- Leading metric은 결과를 먼저 신호하고, lagging metric은 이미 나타난 결과를 확인한다.
- Outcome은 최종 결과, Driver는 주요 요인, Diagnostic은 원인 탐색, Guardrail은 부작용 방지 지표다.

OMTM은 현재 단계의 하나의 집중 metric, NSM은 장기 고객 가치를 대표하는 북극성, KPI는 목표 달성도를 평가하는 핵심 지표다. Metric Tree는 outcome을 driver와 diagnostic으로 분해한다.

## AARRR

- Acquisition: 어떤 채널로 유입되는가
- Activation: 첫 가치를 경험했는가
- Retention: 핵심 행동을 반복하는가
- Revenue: 지불과 수익이 발생하는가
- Referral: 다른 사용자를 불러오는가

Funnel은 단계별 전환과 이탈을, Cohort는 공통 시작점 이후의 행동을 본다. Retention은 Classic(특정 N일), Range(특정 구간), Rolling(N일 이후 한 번 이상) 정의를 구분한다. Churn은 정의한 기간의 고객·수익 이탈이다.

## 핵심 제품·수익 지표

- DAU / WAU / MAU: 일·주·월 활성 사용자. 활성 이벤트를 먼저 정의한다.
- Stickiness: 일반적으로 DAU/MAU 또는 DAU/WAU. 제품의 사용 주기와 함께 해석한다.
- ARPU / ARPPU: 전체 사용자·결제 사용자당 평균 매출.
- ROI / ROAS: 투자 전체·광고비 대비 성과.
- LTV / LTR / CAC: 고객 생애가치·생애수익·획득비용. 수익과 매출을 구분한다.
- MRR / ARR: 월·연 반복 매출. 일회성 매출을 제외한다.
- Viral Coefficient: 기존 사용자 한 명이 만드는 평균 신규 사용자 수.
- NPS: 추천자 비율에서 비추천자 비율을 뺈 추천의향 지표. 행동 지표와 함께 본다.

## 분석 방법과 해석 주의사항

Trend는 시간 변화, Segment는 집단 차이, Funnel은 단계별 이탈, Cohort는 시작점 이후의 행동, Decomposition은 지표의 구성, A/B Test는 무작 배정을 통한 인과 효과를 다룬다.

- 평균의 함정: 분포, 중앙값, 극단값, 샘플 크기를 함께 본다.
- 비율 vs 절대값: 비율 개선이 모수 축소나 전체 가치 하락을 숨기는지 확인한다.
- 상관관계 vs 인과관계: 동반 변화만으로 원인을 단정하지 않는다.
- 데이터 품질: 신선도, 완전성, 중복, ID 연결, timestamp·timezone, 정의 변경을 검증한다.

## 실무 프로세스

문제 정의 → 지표 정의 → 분해 → 비교 → 세분화 → 가설 → 검증 → 액션 → 재측정
