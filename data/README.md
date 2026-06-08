# 데이터셋 안내

## 출처

본 프로젝트에서 사용한 데이터는 데이콘(Dacon)의 공개 대회 데이터셋을 기반으로 한다.

- **대회명**: 칼로리 소모량 예측 AI 해커톤
- **주최**: 데이콘 (https://dacon.io)
- **대회 링크**: https://dacon.io/competitions/official/236097/overview/
- **참가 맥락**: 부트캠프 내부 해커톤으로 진행 (동일 데이터셋 사용)

## 데이터 구성

| 파일명 | 설명 | 샘플 수 |
|--------|------|---------|
| `train.csv` | 학습 데이터 | 7,500건 |
| `test.csv` | 예측 대상 데이터 | 7,500건 |
| `sample_submission.csv` | 제출 양식 | - |

## 주요 변수

| 변수명 | 설명 | 단위 |
|--------|------|------|
| `Exercise_Duration` | 운동 시간 | 분 |
| `BPM` | 운동 중 평균 심박수 | bpm |
| `Body_Temperature(F)` | 운동 중 체온 | °F |
| `Weight(lb)` | 체중 | 파운드 |
| `Height(Feet)` | 키 (피트) | feet |
| `Height(Remainder_Inches)` | 키 (나머지 인치) | inches |
| `Age` | 나이 | 세 |
| `Gender` | 성별 | M / F |
| `Weight_Status` | 체중 상태 | Normal Weight / Overweight / Obese |
| `Calories_Burned` | 칼로리 소모량 **(타겟 변수)** | kcal |

## 원본 데이터 미포함 안내

데이콘 대회 데이터 규정에 따라 원본 데이터 파일은 이 레포지토리에 포함안함.
원본 데이터 위 대회 링크에서 확인가능.
