# Dacon_KLUE_NLI
데이콘 한국어 문장 관계 분류 경진대회(2022.01.28~2022.02.28)

## Contents
* [주제](https://github.com/chohs1221/Dacon_KLUE_NLI/#주제)
* [배경](https://github.com/chohs1221/Dacon_KLUE_NLI/#배경)
* [코드](https://github.com/chohs1221/Dacon_KLUE_NLI/#코드)
* [데이콘 링크](https://github.com/chohs1221/Dacon_KLUE_NLI/#데이콘-링크)
## 주제   
한국어 문장 관계 분류 경진대회 
## 배경   
 Natural Language Inference Dataset을 활용합니다.   

(출처: https://klue-benchmark.com/tasks/68/overview/description)   
## 코드   
[CODE LINK](https://github.com/chohs1221/Dacon_KLUE_NLI/blob/master/nli_RoBERTa_large.ipynb)
1. train_data.csv

├ Index : train data index

├ Premise : 실제 Text

├ Hypothesis : 가설 Text

└ Label : 참(Entailment) 또는 거짓(Contradiction) 또는 중립(Neutral)



*Premise와 Hypothesis의 관계를 추론



2. test_data.csv
├ Index : test data index

├ Premise : 실제 Text

├Hypothesis : 가설 Text

└Label : 추론해야 하는 Label 값



3. sample_submission.csv
├ Index : test data index

└Label : 추론해야 하는 Label 값  
## 데이콘 링크
[DACON PAGE LINK](https://dacon.io/competitions/official/235875/overview/description)
