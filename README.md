# User Behavior ETL & Analysis Project (Project 1)

A practical data engineering and analysis project using AWS Glue, RDS, S3, Tableau, and Python.

---

## 📌 Overview

This project simulates a real-world end-to-end data pipeline for processing and analyzing user behavior data from a SaaS/web/mobile application.

The pipeline covers:
- Data collection from OLTP RDS and JSON logs
- Data Lake construction using AWS S3 and Glue
- Data Warehouse (DW/DM) design and ETL using Glue
- BI analysis using Tableau (AARRR, RFM, Funnel, Cohort)
- Statistical analysis using Python (A/B testing, regression, clustering, time series, etc.)

---

## 🧱 Technologies Used

- **AWS**: Glue (ETL), S3 (Data Lake), RDS (OLTP & DW)
- **Tableau Public**: BI visualization and dashboarding
- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels
- **Git + Notion**: Version control and documentation

---

## 🇰🇷 프로젝트 개요 (Korean)

AWS Glue, RDS, S3, Tableau, Python 라이브러리를 활용해  
**웹/앱 서비스의 사용자 행동 데이터를 수집, 정제, 분석하는 엔드투엔드 데이터 파이프라인을 구현**합니다.

- OLTP RDS 및 JSON 로그 기반 데이터 수집
- AWS Glue를 활용해 AWS S3 데이터 레이크 구성
- Glue를 활용한 DW/DM RDS 적재 및 변환
- Tableau를 활용한 주요 지표 시각화 (AARRR, RFM, Cohort 등)
- Python 기반 통계 분석 수행 (A/B 테스트, 회귀분석, 군집화 등)

---

## 📁 Folder Structure

```
<pre><code>## 📁 Folder Structure <code> user-behavior-etl-analysis-project-1/ ├── README.md # 프로젝트 설명 ├── docs/ # 프로젝트 계획, 아키텍처, 데이터 정의서 ├── glue_jobs/ # AWS Glue PySpark 코드 ├── sql/ # 테이블 스키마 및 쿼리 ├── tableau/ # 대시보드 결과 및 설명 ├── analysis/ # Python 분석 노트북 ├── datasets/ # 샘플 데이터 또는 데이터 생성기 └── etc/ # 보조 문서, 설계도, 흐름도 등 </code> </code></pre>
```