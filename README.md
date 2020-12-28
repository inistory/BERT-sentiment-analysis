# BERT

## BERT를 이용하여 movie review data에 Fear score 매기기


### Reference

##### Building a Multi-label Text Classifier using BERT and TensorFlow

* Training Dataset : Kaggle의 toxic comment classification Dataset
![image](https://user-images.githubusercontent.com/53829167/103154624-00661780-47dc-11eb-997d-0f580c5545f4.png)

* Algorithm : BERT
https://towardsdatascience.com/building-a-multi-label-text-classifier-using-bert-and-tensorflow-f188e0ecdc5d


### Ours

* Training Dataset : SemEval-2018 Task 1 – El-oc
![image](https://user-images.githubusercontent.com/53829167/103154715-aa45a400-47dc-11eb-9c19-e1091b95b13c.png)

* Fear, anger, joy, sadness 의 감정 강도를 0,1,2,3으로 표현

  |          |     fear    |     joy    |     anger    |     sadness    |
  |:--------:|:-----------:|:----------:|:------------:|:--------------:|
  |     0    |     1490    |     548    |      445     |       594      |
  |     1    |      320    |     363    |      322     |       260      |
  |     2    |      249    |     346    |      507     |       364      |
  |     3    |      193    |     359    |      427     |       315      |


