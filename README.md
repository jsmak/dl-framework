# 딥러닝 프레임워크와 딥러닝 학습

PyTorch로 딥러닝 모델을 학습시키는 기본기를 처음부터 차례로 익히는 사내 강좌입니다.
텐서에서 시작해 자동미분, 옵티마이저, 데이터 준비, 학습 루프, 평가까지 다룹니다.

## 목차

| 강 | 주제 | 노트북 |
|---|---|---|
| 3강 | 텐서(Tensor) — 생성, NumPy 변환, 인덱싱·슬라이싱, 연산과 브로드캐스팅, 통계 값 | [01_tensor.ipynb](03_tensor/01_tensor.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jsmak/dl-framework/blob/main/03_tensor/01_tensor.ipynb) |
| 4강 | 순전파·역전파·경사하강법 — 섭씨→화씨 선형 모델로 학습 4단계(순전파, 손실 계산, 역전파, 경사하강법) 확인 | [02_gradientdecent.ipynb](04_gradient_descent/02_gradientdecent.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jsmak/dl-framework/blob/main/04_gradient_descent/02_gradientdecent.ipynb) |
| 5강 | 자동미분과 계산 그래프 — NumPy로 Variable·Function을 직접 만들어 `backward()`를 구현하고 4강 문제를 학습 | [01_autograd_numpy.ipynb](05_autograd/01_autograd_numpy.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jsmak/dl-framework/blob/main/05_autograd/01_autograd_numpy.ipynb) |
| 예정 | 옵티마이저 | |
| 예정 | Dataset과 DataLoader | |
| 예정 | 학습 루프 | |
| 예정 | 평가 | |

## 실행 방법

- **Colab (권장)**: 표의 *Open in Colab* 배지를 누르면 바로 열립니다. PyTorch가 이미 설치되어 있습니다.
- **로컬 (Jupyter Notebook / VS Code)**: PyTorch를 설치한 뒤 노트북을 엽니다.
  ```bash
  pip install torch numpy jupyter
  ```
