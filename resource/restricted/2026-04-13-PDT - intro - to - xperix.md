---
date: Mon Apr 13 09:53:52 PDT 2026
last_modified_at: Mon Apr 13 10:44:06 PDT 2026
layout: single
title: "에루디오바이오 회사 소개"
permalink: /xperix/erudio-bio-intro/
toc: true
toc_label: "&nbsp;Table of Contents"
toc_icon: "fa-solid fa-music"
toc_sticky: true
author_profile: true
---

posted: {{ page.date| date: "%d-%b-%Y" }}
&
updated: {{ page.last_modified_at| date: "%d-%b-%Y" }}
{: .notice--primary}

<style>
table, tr, td, th {
    font-size: inherit !important;
    font-family: inherit !important;
}
</style>

**Erudio Bio, Inc. & Erudio Bio Korea, Inc.**

# 1. 회사 개요

## Erudio Bio, Inc.
- **설립:** 2023년
- **본사:** 미국 캘리포니아주 실리콘밸리
- **대표:** Kee-Hyun Paik, Ph.D. (Co-Founder & CEO)
- **주요 인력:**
  - Sunghee Yun, Ph.D. (Co-Founder & CTO): AI 및 소프트웨어 개발 총괄
  - Leon Chen, MBA, CFA (COO): 사업 개발 및 운영
  - Susanne Baumhueter, Ph.D. (Biology Lead): 생물학 및 면역학
- **자문단:** Stanford University, Harvard Medical School 교수진

## Erudio Bio Korea, Inc.
- **설립:** 2025년 7월
- **본사:** 대한민국 서울
- **대표:** 윤성희 대표 (CEO)
- **CLO:** 허진영 이사 (법무 및 규제 담당)
- **사업 영역:** 한국, 일본, 동남아시아, 중국

# 2. 핵심 기술: VSA (Versatile Smart Assay) 플랫폼

## 기술 개요
VSA는 **동적 힘 분광법(Dynamic Force Spectroscopy)** 기반의 분자 결합 측정 플랫폼으로, 기존 multiplex assay의 한계를 극복한 차세대 진단 기술입니다.

## 핵심 차별성
- **1,000배 데이터 생성 효율:** 단 10µL 시료로 50-100개 분자 상호작용 동시 측정
- **정량적 결합 분석:** 결합 강도(unbinding force), 결합/해리 속도(on/off kinetics), 특이성(specificity) 측정
- **교차반응 제거:** 비특이적 결합 및 cross-reactivity 필터링으로 위양성 최소화
- **AI 학습용 데이터 생성:** Kinetics-resolved "ground-truth" binding labels 제공

## 지식재산권
- **특허:** 21건 출원/등록 (동적 힘 분광법 핵심 기술)
- **독자 기술:** 하드웨어(벤치탑 리더 + 마이크로플루이딕 칩) + 소프트웨어 통합 스택

# 3. 한국 사업: 암 바이오마커 검진 서비스

## 사업 개요
건강검진센터 및 종합병원을 대상으로 **다중 암 표지자(Multi-Cancer Biomarker) 정밀 검진 서비스** 제공

## 타겟 시장
- **1차 타겟:** 대형 종합병원 건강검진센터
- **2차 타겟:** 독립형 건강검진센터, 지역 거점병원
- **잠재 시장:** 한국 연간 건강검진 1,500만 명 이상

## 현재 진행 중인 협력
**✅ 분당서울대병원 (Seoul National University Bundang Hospital)**
- IRB 승인 진행 중
- 암 바이오마커 공동 연구개발 협의
- 15M+ 환자 데이터 접근 가능 (IRB 승인 후)

**✅ 계명대학교 동산병원 (Keimyung University Dongsan Hospital)**
- 다기관 임상 검증 참여

<!--
- 공동 연구개발 협약 체결
-->

**✅ 기타 협력 기관**
- KRIBB (한국생명공학연구원)
- KAIST NanoFab Center

## 검진 패널 (현재 개발 완료)
**6종 암 바이오마커 동시 검진:**
- AFP (간암)
- CA19-9 (췌장암, 담도암)
- CA125 (난소암)
- CEA (대장암, 폐암)
- FT4 (갑상선암)
- TSH (갑상선암)

## 경쟁 우위
- **비용:** 기존 6개 개별 검사 대비 **1/3 가격**
- **정확도:** 교차반응 제거로 위양성률 감소
- **편의성:** 단일 검사로 다중 암 스크리닝

## 규제 전략
- **목표:** 2027년 MFDS (식품의약품안전처) 허가
- **전략:** 측정기기(1등급 신고) + 카트리지(별도 허가) 분리 접근
- **협력:** C&R Research (CRO) 규제 컨설팅

# 4. 미국 사업: bioTCAD 신약개발 AI 플랫폼

## Gates Foundation 프로젝트 ($1M Grant)

**✅ 수령일:** 2025년 8월  
**✅ 금액:** $1,000,000 (경쟁 선발)  
**✅ 프로젝트명:** bioTCAD (Biology Technology Computer-Aided Design) 플랫폼 개발

## bioTCAD 플랫폼 개요
**AI 기반 신약개발의 핵심 문제 해결:**
- 기존 AI 모델의 한계: noisy한 실험 데이터, 동역학 정보 부족
- Erudio 솔루션: VSA로 생성한 고품질 결합 데이터를 AI 학습에 활용
- 결과: True binder vs. look-alike 분자 구분, hit ranking 정확도 향상

## 기술적 접근
1. **데이터 생성:** VSA로 분자 결합 동역학 측정
2. **AI 변환:** Force-of-binding curve를 machine-ready feature로 전환
3. **모델 학습:** Binding-aware AI 모델 구축
4. **검증:** 신약 후보물질 우선순위 결정, go/no-go decision 지원

## Gates Foundation 후속 투자
- **후속 펀딩:** 약 $5M 규모 지원 예정
- **조건:** 리드 투자자(lead investor) 확보 시

## 타겟 시장
- AI 신약개발 기업 (Tempus, Owkin, Recursion 등)
- 글로벌 제약사 (Pfizer, Merck, AstraZeneca 등)
- 바이오텍 스타트업 (전임상 단계 후보물질 검증)

# 5. 글로벌 네트워크 및 파트너십

## 제조 파트너십
**✅ Analog Devices (ADI)**
- 반도체 센서 칩 대량 생산 협력
- 글로벌 제조 인프라 활용

## 임상 협력 (아시아)
- **한국:** 분당서울대병원, 계명대 동산병원
- **중국:** Shanghai General Hospital (JDA 체결, $1M 상당 in-kind 기여)

## 과학 자문단
- **Stanford University:** 유전체학, 분자생물학 교수진
- **Harvard Medical School:** 임상 및 진단 전문가

<!--
## 정부 협력
- **미국 상무부(DOW):** Assistant Secretary급 논의 진행 중
- **한국:** KOTRA Silicon Valley, K-BioX, K-ASIC 파트너십
-->

# 6. 사업 모델 및 수익 구조

## 한국 사업 (Erudio Bio Korea)
**1. 장비 판매 (Hardware)**
- VSA 벤치탑 리더 시스템
- 고마진 모델 (70%+ gross margin)

**2. 소모품 판매 (Consumables)**
- 마이크로플루이딕 칩 (반복 구매)
- 시약 키트

**3. 검사 서비스 (Per-Sample Fee)**
- 검체당 검사 수수료 (₩150,000-300,000 예상)
- 병원 파트너십 기반 B2B2C 모델

## 미국 사업 (Erudio Bio)
**1. 데이터 라이선싱 (Data Licensing)**
- AI 학습용 고품질 결합 데이터셋 제공
- 프로젝트당 $200K-500K

**2. SaaS 플랫폼 (Subscription)**
- bioTCAD 클라우드 분석 플랫폼
- 연간 구독료 $50K-200K

**3. 전략적 파트너십**
- 제약사 공동 연구개발
- 마일스톤 기반 성공 보수

# 7. 시장 규모 및 성장 가능성

## 한국 암 검진 시장
- **TAM:** 글로벌 암 진단 시장 $25B (2024)
- **SAM:** 한국 + 중국 암 스크리닝 시장 $2.5B
- **SOM (3-5년):** $15M-60M (연간 100K-200K 검사 기준)

## 글로벌 AI 신약개발 시장
- **TAM:** AI drug discovery $5B (2024), 연평균 25-35% 성장
- **SAM:** AI 모델 학습 데이터 시장 $2B
- **SOM (3-5년):** $8M-25M (데이터 라이선싱 + SaaS)

## 기타 확장 시장
- 면역치료 동반진단
- 항체 개발 서비스
- 감염병 진단
- **추가 TAM:** $60B+

# 8. 핵심 성과 및 마일스톤

## 기술 검증
✅ 21건 특허 포함 독자 기술 확보\
✅ Gates Foundation 경쟁 선발 ($1M grant)\
✅ VSA 플랫폼 기술 완성 (50-100 interactions/run)  

<!--
✅ 6종 암 바이오마커 패널 개발 완료
-->

## 임상 협력
✅ 분당서울대병원 IRB 승인 진행 중\
✅ 계명대 동산병원 연구 협력 진행 중\
✅ Shanghai General Hospital JDA 체결

## 사업 진행
✅ 미국 법인 설립 (2023)\
✅ 한국 법인 설립 (2025.07)\
✅ C&R Research CRO 규제 컨설팅 진행 중

## 향후 계획
- **2026:** 한국 MFDS 품목 허가 신청
- **2027:** 한국 건강검진센터 상용화
- **2027-2028:** Gates Foundation 후속 투자 ($5M)
- **2028+:** 글로벌 확장 (일본, 동남아)

# 9. 연락처

## Erudio Bio Korea, Inc.
**대표:** 윤성희 박사  
**이메일:** sunghee.yun@gmail.com  

---

**본 자료는 국가 연구개발 과제 지원을 위한 회사 소개 자료입니다.**  
**작성일:** 2026년 4월 5일
