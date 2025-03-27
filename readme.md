# brAIn_2th_AA_Session_First_Assignment

이 프로젝트는 brAIn 2기 AA 세션의 첫 번째 과제입니다. 이 README 파일은 프로젝트를 설치하고 실행하는 방법을 안내합니다.

## 목차
1. [설치 방법](#1-설치-방법)
2. [실행 방법](#2-실행-방법)
3. [Week 2 - CNN](#3-week-2---cnn)
4. [Exercise Description](#4-exercise-description)

---

## 1. 설치 방법

프로젝트를 설치하려면 다음 단계를 따르세요:

1. VSCODE에서 터미널을 엽니다.
2. 다음 명령어를 사용하여 프로젝트를 복제합니다:
   ```
   git clone https://github.com/rkdrn79/brAIn_2th_AA_Session_First_Assignment.git
   ```
3. 복제된 프로젝트 폴더로 이동합니다:
   ```
   cd brAIn_2th_AA_Session_First_Assignment
   ```
4. 필요한 패키지를 설치합니다:
   ```
   conda create -n brAIn_2th_AA_Session_First_Assignment python=3.10
   conda activate brain_2th_AA_Session_First_Assignment   
   pip install -r requirements.txt
   ```

이제 프로젝트 설치가 완료되었습니다!

---

## 2. 실행 방법

프로젝트를 실행하려면 다음 단계를 따르세요:

1. 터미널이나 명령 프롬프트에서 프로젝트 폴더 내에 있는지 확인합니다.
2. 다음 명령어를 입력하여 프로그램을 실행합니다:
   ```
   python cnn_main.py
   ```
3. 프로그램이 실행되면 콘솔에 출력되는 내용을 확인하세요.

---

## 3. **Week 2 - CNN**

이번 주 학습 주제는 CNN(Convolutional Neural Network)입니다. 아래 내용을 학습하고 실습을 진행합니다.

- **Topic**
  - Convolution Layer (2D)
  - MaxPooling (2D)
  - Flatten Layer
- **Week 2 Exercise**
  - NumPy/Torch 기반의 모델 정확도를 비교
  - Linear 모델과 CNN 모델 성능 비교

---

## 4. **Exercise Description**

이번 과제에서는 MNIST 데이터셋을 활용하여 다양한 모델을 학습시키고 비교합니다.

- `main.py`를 실행하면 4가지 다른 모델이 MNIST 데이터셋을 학습합니다.
- `conv2d`, `pooling2d` 레이어의 빈칸을 채워 완성합니다.
- `models.py` 파일의 `cnn_model_np` 부분을 완성합니다.
- **Linear 모델과 CNN 모델의 정확도를 비교합니다.**
- **NumPy 모델과 Torch 모델의 성능을 비교합니다.**

과제를 완료한 후, 각 모델의 성능 차이를 분석하고 결과를 정리해보세요!

