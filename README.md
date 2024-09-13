# 신용 등급 분류
[딥러닝] 개인의 신용 관련 정보를 바탕으로 신용 점수를 분류할 수 있는 모델 구축\
https://www.kaggle.com/datasets/parisrohan/credit-score-classification


## 문제 설명
당신은 글로벌 금융회사에서 데이터 과학자로 일하고 있습니다. 수년에 걸쳐 회사는 기본 은행 정보를 수집하고 많은 신용 관련 정보를 수집했습니다. 경영진은 수동 작업을 줄이기 위해 직원을 신용 점수 등급으로 분리하는 지능형 시스템을 구축하려고 합니다.


## 데이터 설명
| 컬럼명                    | 의미           | 간단한 설명                                                  |
|---------------------------|--------------|---------------------------------------------------------------|
| ID                        | 항목 고유 식별자    | 각 항목에 대한 고유 식별자                                     |
| Customer_ID               | 고객 고유 식별자    | 개인을 식별하는 고유 식별자                                    |
| Month                     | 월            | 해당 연도의 월                                                |
| Name                      | 이름           | 개인의 이름                                                   |
| Age                       | 나이           | 개인의 나이                                                   |
| SSN                       | 사회 보장 번호     | 개인의 사회 보장 번호 (Social Security Number)                  |
| Occupation                | 직업           | 개인의 직업                                                   |
| Annual_Income             | 연간 소득        | 개인의 연간 소득                                              |
| Monthly_Inhand_Salary      | 월급           | 개인의 월별 기본 급여                                          |
| Num_Bank_Accounts          | 은행 계좌 수      | 개인이 보유한 은행 계좌의 수                                   |
| Num_Credit_Card            | 신용카드 수       | 개인이 보유한 신용카드의 수                                    |
| Interest_Rate              | 이자율          | 신용카드의 이자율                                              |
| Num_of_Loan                | 대출 수         | 은행에서 받은 대출의 수                                        |
| Type_of_Loan               | 대출 종류        | 개인이 받은 대출의 종류                                        |
| Delay_from_due_date        | 연체 일수        | 평균적으로 납부 기한을 초과한 일수                              |
| Num_of_Delayed_Payment     | 지연 납부 횟수     | 개인이 지연한 평균 납부 횟수                                    |
| Changed_Credit_Limit       | 신용한도 변경 비율   | 신용카드 한도 변경 비율                                        |
| Num_Credit_Inquiries       | 신용 조회 횟수     | 신용카드 조회 횟수                                             |
| Credit_Mix                 | 신용 혼합 유형     | 신용 혼합 유형의 분류                                           |
| Outstanding_Debt           | 미지급 잔액       | 미지급 잔액 (USD 기준)                                         |
| Credit_Utilization_Ratio   | 신용카드 이용 비율   | 신용카드 이용 비율                                             |
| Credit_History_Age         | 신용 이력 기간     | 개인의 신용 이력 연수                                           |
| Payment_of_Min_Amount      | 최소 납부 여부     | 최소 금액만 지불했는지 여부                                     |
| Total_EMI_per_month        | 월별 EMI 납부 금액 | 월별 EMI(할부금) 납부 금액 (USD 기준)                           |
| Amount_invested_monthly    | 월별 투자 금액     | 고객이 월별로 투자한 금액 (USD 기준)                            |
| Payment_Behaviour          | 납부 행태        | 고객의 납부 행태                                                |
| Monthly_Balance            | 월별 잔액        | 고객의 월별 잔액 (USD 기준)                                     |



---
### 프로젝트
- [발표자료](https://www.canva.com/design/DAGQgKHmSps/tlUMXsoOWgc6dqOrinJ2_w/view?utm_content=DAGQgKHmSps&utm_campaign=designshare&utm_medium=link&utm_source=editor)