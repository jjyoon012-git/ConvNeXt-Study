# ConvNeXt와 CNN 계열 모델 스터디 🧑‍💻

이 리포지토리는 **ConvNeXt** 및 그 설계에 영향을 끼친 주요 CNN 계열 모델들을 PyTorch로 직접 구현한 코드 모음입니다.

---

##  주요 참고 논문

- **ConvNeXt (2022)** — [A ConvNet for the 2020s](https://arxiv.org/abs/2201.03545) 

---

##  구현 현황 (2025-09-02 기준)

- ⬜ **LeNet-5 (1998)** — 구현 예정
- ⬜ **VGG-16 (2014)** — 구현 예정  
- ⬜ **ResNet-50 (2015)** — 구현 예정  
- ⬜ **ResNeXt (2017)** — 구현 예정  
- ⬜ **EfficientNet (2019)** — 구현 예정  
- ⬜ **Vision Transformer (2020)** — 구현 예정  
- ⬜ **ConvNeXt-Tiny (2022)** — 구현 예정  

---

##  리포지토리 구조
- `models/` : 각 모델 구현 (PyTorch 기반)  
- `experiments/` : 학습, 평가, 모델 비교 실험 코드  
- `notebooks/` : 단계별 학습용 Jupyter/Colab 노트북  
- `results/` : 학습 로그, 그래프, 성능 결과 저장  

---

##  사용 방법

```bash
# 필요한 패키지 설치
pip install -r requirements.txt

# 예: ResNet 모델 학습 (CIFAR-10, 20 epochs)
python experiments/train.py --model resnet --dataset cifar10 --epochs 20
