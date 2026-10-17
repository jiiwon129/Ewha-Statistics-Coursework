# Ewha Statistics Coursework

이화여자대학교 통계학과 수업에서 수행한 **통계 분석, 데이터 시각화, 머신러닝·딥러닝 실습 및 프로젝트**를 정리한 저장소입니다.

수업별 학습 기록을 보관하는 coursework archive이며, 대표 프로젝트와 주요 실습을 중심으로 구성했습니다.

## Coursework

### 빅데이터를 이용한 통계 그래픽스 — R

#### Olympic Athlete Data Analysis
[프로젝트 보기](./빅데이터를이용한통계그래픽스)

올림픽 선수·경기 데이터를 활용해 R로 탐색적 데이터 분석과 시각화를 수행한 프로젝트입니다.

- 약 27만 건의 athlete-event 데이터 분석
- 결측치 처리 및 기초통계
- 성별·연령·키·몸무게 분포 분석
- 연도별 참가 추세 분석
- 종목별 선수 수·경기 수·메달 분포
- 국가별 하계·동계 올림픽 메달 패턴 비교
- BMI, 연령, 성별 등 선수 특성 시각화

**Files**
- `올림픽_운동선수_데이터_분석.Rmd` — 분석 코드 및 설명
- `올림픽 운동선수 데이터 분석.pdf` — 최종 결과물

**Tech**  
`R` `tidyverse` `dplyr` `ggplot2`

---

### 빅데이터 분석 방법론 — Python

[실습 파일 보기](./빅데이터분석방법론)

Python 기반 데이터 분석과 머신러닝·딥러닝 방법론을 단계적으로 실습했습니다.

- `HW1_Basic_Python.ipynb` — Python 기초
- `HW2_ML_Regression_Classification.ipynb` — 회귀·분류
- `HW3_DL_DNN.ipynb` — Deep Neural Network
- `HW4_DL_CNN.ipynb` — Convolutional Neural Network
- `HW5_DL_RNN.ipynb` — Recurrent Neural Network

**Tech**  
`Python` `pandas` `NumPy` `scikit-learn` `TensorFlow/Keras`

## Repository Structure

```text
.
├── 빅데이터를이용한통계그래픽스/
│   ├── README.md
│   ├── 올림픽_운동선수_데이터_분석.Rmd
│   └── 올림픽 운동선수 데이터 분석.pdf
│
└── 빅데이터분석방법론/
    ├── README.md
    ├── HW1_Basic_Python.ipynb
    ├── HW2_ML_Regression_Classification.ipynb
    ├── HW3_DL_DNN.ipynb
    ├── HW4_DL_CNN.ipynb
    └── HW5_DL_RNN.ipynb
```

## Notes

- 본 저장소는 **수업 및 학습 기록용**으로, 별도의 실무 포트폴리오 프로젝트와 구분해 관리합니다.
- 대표 R 프로젝트는 올림픽 선수 데이터 분석이며, 전체 분석 과정은 R Markdown과 PDF에서 확인할 수 있습니다.
