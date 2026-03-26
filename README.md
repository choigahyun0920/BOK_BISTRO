# BOK_BISTRO
# 🏦 BOK_BISTRO: Inflation Forecasting Project

이 프로젝트는 BIS(국제결제은행)의 **BISTRO(BIS Time-series Regression Oracle)** 모델을 활용하여 거시경제 시계열 데이터, 특히 물가 상승률(Inflation)을 분석하고 예측하는 연구용 저장소입니다.

상호 연결된 사회경제적 시스템에 대한 연구의 일환으로, 중앙은행 등에서 활용 가능한 계량경제학적 예측 방법론을 실험하고 있습니다.

## 바로 실행하기
아래 버튼을 클릭하면 Google Colab 환경에서 메인 노트북을 즉시 실행할 수 있습니다. 데이터 로드부터 모델 예측까지 모든 과정이 자동으로 세팅됩니다.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/choigahyun0920/BOK_BISTRO/blob/main/forecast_single_timeseries.ipynb)

## 📂 주요 파일 안내
- **`forecast_single_timeseries.ipynb`**: BISTRO 모델을 사용하여 단일 시계열(예: 인플레이션)을 예측하는 메인 노트북입니다.
- **`data/`**: 분석에 사용되는 월간(Monthly) 및 일간(Daily) CSV 데이터들이 저장되어 있습니다.
- **`src/`**: BISTRO 모델 구동을 위한 핵심 소스 코드 폴더입니다.
- **`requirements.txt`**: 분석 환경 구축에 필요한 라이브러리 목록입니다.

## 🛠️ 주요 기능
1. **데이터 자동 통합**: 여러 개의 월간/일간 CSV 파일을 읽어와 일간 단위로 전처리(Forward-fill) 및 병합합니다.
2. **확률적 예측**: BISTRO 모델을 통한 확률적 시계열 예측과 신뢰 구간 산출을 수행합니다.
3. **결과 시각화**: 실제 데이터와 모델의 예측치를 비교하는 고해상도 그래프를 생성합니다.

## ⚙️ 실행 방법
1. 위 **[Open in Colab]** 버튼을 클릭합니다.
2. 노트북 최상단의 환경 설정 셀을 실행하여 깃허브 저장소를 복제합니다.
3. 데이터 전처리 및 BISTRO 모델 예측 과정을 순차적으로 진행합니다.

---
**Author**: Choi Gahyun, Ph.D. (Bank of Korea)
