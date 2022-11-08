# TUNiB 과제설명
해당 데이터셋은 TUNiB에서 자체적으로 제작한 데이터인 DKTC(Dataset of Korean Threatening Converstations)으로 classification task 수행합니다.<br>여기서 주어진 훈련데이터의 클래스는 총4가지('협박', '갈취', '직장 내 괴롭힘', '기타 괴롭힘')이고 테스트데이터는 여기에 '일반 대화'클래스가 하나 추가 되어있습니다.
|Class|Traning|Test|
|:--:|:--:|:--:|
| 협박 | 896 | 100 |
| 갈취 | 981 | 100 |
| 직장 내 괴롭힘 | 979 | 100 |
| 기타 괴롭힘 | 1,094 | 100 |
| 일반 | - | 100 |

훈련데이터에서 빠져있는 '일반 대화'는 [AI Hub](https://aihub.or.kr/?utm_source=google&utm_medium=search&utm_campaign=ga&gclid=CjwKCAjw6raYBhB7EiwABge5KnZuqLSaXjiqfgAETqQwG-_7B2r2e26nDY5cOiNSvrwEUrvIsW9GcRoCRCgQAvD_BwE)에서 내려받아 학습에 활용합니다.
# 데이터 설명
### Train data
