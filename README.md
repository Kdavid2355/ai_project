# 각종 프로젝트 목록입니다.

대학교 및 각종 프로젝트 팀에서 진행한 프로젝트 목록입니다! 앞으로도 더 많은 프로젝트와 더욱 심도있는 학습으로 완성도있는 프로젝트를 만들어나가겠습니다!

### 1. 데이콘 도배하자유형분류 인공지능경진대회

벽이나, 공사시공시, 도배하자에 19가지의 유형이 있고, 이를 분류하는 경진대회였습니다. 주어진 데이터의 불균형이 심해, 이를 해결하는 것이 관건인 task 라 생각했습니다. 처음 진행해본 인공지능프로젝트인 만큼 
아쉬운 부분이 많지만, data augmentation 개념, 전이학습 개념을 배울 수 있었고, ResNet, DenseNet, VGG 등 다양한 이미지 분류 모델에 대해 공부할 수 있었습니다. 

##### 배운점
(1) 데이터 개수에 따른 layer 수 적은 모델 선택
데이터의 개수가 많지 않은 상황에서, ResNet 152등 layer 수가 많은 모델을 선택했는데, train 에서는 높은 정확도를 보였으나, test 에서는 좋지 않은 성능을 보여주었고, 주최측의 평가에서는 54%수준의 accuracy 를 보여, ResNet18 과 같이 
layer수가 적은 것을 했어야함을 배울 수 있었습니다. 

(2) test 데이터는 data augmentation 하지 말아야한다.
주어진 전체 data를 augmentation 하고, 이를 7:3 비율로 나누어서 학습/평가를 진행하였으나, test data는 미리 나누어놓고, train dataset만, augmentation 을 해야함을 배울 수 있었습니다.

[paper link] / [code link]