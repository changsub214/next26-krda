# Google Next 26 DA 영역 신기능 톺아보기

## 개요

| 항목 | 내용 |
|---|---|
| **대상 및 목적** | 본 노트북은 한국 리전의 GCP 유저들이 DA 영역에 대한 신기능을 빠르고 쉽게 이해할 수 있도록 제작되었습니다. |
| **다루는 범위** | Infra 측면의 기능은 별도로 참고하십시오. 해당 노트북은 BigQuery에서 User가 실제로 작업하는 과정만 다룹니다. |
| **관련 링크** | Lakehouse(구. BigLake) 및 Lightning Engine for Apache Spark 관련은 [여기](https://github.com/changsub214/icebergingcp)를 참고하세요. |

---

## 주의 사항

| 항목 | 내용 |
|---|---|
| **실행 안내** | 최대한의 과정은 Run만 누르면 동작하도록 제작되었으나, 일부 과정은 직접 생성 및 수정이 필요할 수 있습니다. |

---

## 목차 (Table of Contents)

| 연번 | 서비스 | 출시 상태 | 기능명 | 비고 및 상세 내용 |
|---|---|---|---|---|
| 1 | BigQuery | GA | **AI Functions** | TimesFM ➔ AI Functions의 `AI.FORECAST` 함수로 적용됨 |
| 2 | BigQuery | Preview | **Zero-Shot Tabular FM** | - |
| 3 | BigQuery | GA | **ObjectRef** | - |
| 4 | BigQuery | GA | **Python UDFs** | - |
| 5 | BigQuery | Preview | **Knowledge Graph** | - |
| 6 | BigQuery | Preview | **Hybrid Search** | 지원예정 |
| 7 | BigQuery | GA | **Conversational Analytics in BigQuery** | - |
