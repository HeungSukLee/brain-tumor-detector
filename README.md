# Brain Tumor Detector

## Kaggle Brain Tumor 문제 구현

DataSet: https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri

### 접근 방법

1. CNN 분류기 모델
    - Deep CNN 모델을 활용한 분류기 설계
    - no_tumor, glioma_tumor, pituitary_tumor, meningioma_tumor 4개의 category를 분류하는 모델 제작
    - multi-label 문제를 binary classification으로 치환하여 접근

2. AutoEncoder 모델
    - CNN 기반의 AutoEncoder 모델 설계
    - 정상 뇌 이미지를 학습 후, 복원이 안되는 이미지를 tumor로 판단하는 모델 제작

