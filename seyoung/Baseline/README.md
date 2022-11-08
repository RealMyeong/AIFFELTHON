## Alpha-Test(Baseline Design)
| |세부내용 및 변동사항|Result|
|:--:|:--:|:--:|
|**1Day**|Model : klue bert base<br>Preprocess : 문장속 '\n' 제거<br>Epoch : 3|Accuracy_val : 0.92<br>Micro_F1score_val : 0.91|
|**2Day**|Model : klue/roberta-base<br>Model : beomi/KcELECTRA-base|Micro_F1score_val : 0.92<br>Micro_F1score_val : 0.90|
|**3Day**|Model : klue/roberta-base<br> 아무런 전처리 없이 수행|Micro_F1score_val : 0.94<br>토크나이저가 자동으로'\n'를 제거함|
|**4Day**|Model : kcT5구현|
|**5Day**|Model : kcT5구현|

