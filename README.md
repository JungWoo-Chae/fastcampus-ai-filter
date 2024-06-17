# Diffusion Model Tutorial

이 레포지토리는 Denoising Diffusion Probabilistic Models (DDPM)을 PyTorch로 구현하고 이해하기 위한 강의 자료를 포함하고 있습니다. 강의에서는 주로 MNIST 데이터셋을 사용하여 모델을 설명합니다.

## 목차
- [소개](#소개)
- [설치](#설치)
- [사용 방법](#사용-방법)
- [코드 구조](#코드-구조)
- [참고 자료](#참고-자료)

## 소개
Denoising Diffusion Probabilistic Models (DDPM)은 데이터에 점진적으로 노이즈를 추가하고 제거하여 새로운 현실적인 데이터 샘플을 생성할 수 있는 생성 모델의 한 종류입니다. 이 튜토리얼은 기본 개념을 설명하고, MNIST 데이터셋을 사용하여 DDPM을 학습하는 코드를 제공합니다.

## 설치
1. 이 레포지토리를 클론합니다:
    ```bash
    git clone https://github.com/yourusername/diffusion-model-tutorial.git
    cd diffusion-model-tutorial
    ```

## 사용 방법
레포지토리에 포함된 Jupyter 노트북을 실행하여 튜토리얼을 진행할 수 있습니다. 각 노트북은 튜토리얼의 특정 부분에 해당합니다.

1. **01_denoising_diffusion_probabilistic_model.ipynb**: DDPM 소개 및 간단한 데이터셋에 대한 구현.
2. **02_ddpm_mnist.ipynb**: MNIST 데이터셋에 대한 DDPM의 상세 구현.

Jupyter 노트북 서버를 시작하려면 다음 명령어를 실행하세요:
```bash
jupyter notebook
