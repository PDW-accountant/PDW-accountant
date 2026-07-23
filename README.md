<h2 align="center">박대원 · <sub>PDW-accountant</sub></h2>

<p align="center">회계 업무에서 직접 겪은 문제를 AI로 해결하는 프로젝트를 만들고 있습니다.</p>

<p align="center">
  <a href="https://nimble-birch-e71.notion.site/2679625c9a67800494d8c24b2f0bf596">
    <img src="https://img.shields.io/badge/Portfolio-Notion-000000?style=flat-square&logo=notion&logoColor=white" alt="Portfolio"/>
  </a>
</p>

---

## Projects

### [금융거래조회서 입력 자동화](https://github.com/dongtan-91-dong-welfare-center/audit_inquiry_automation/tree/dev)

스캔된 금융거래조회서를 OCR로 인식하고, 표 데이터를 정제해 엑셀로 변환하는 자동화 프로젝트입니다.

- **직접 구현:** OCR, 결과 후처리, 표 데이터 보정, 템플릿 기반 엑셀 생성, Streamlit 파이프라인 연동 및 통합 테스트
- **결과:** 핵심 항목 594개 중 592개를 일치 또는 검토 필요 상태로 처리
- **사용 도구:** `Python` `PaddleOCR` `Streamlit` `openpyxl`

[PR #11 · OCR 후처리](https://github.com/dongtan-91-dong-welfare-center/audit_inquiry_automation/pull/11) ·
[PR #13 · 엑셀 생성](https://github.com/dongtan-91-dong-welfare-center/audit_inquiry_automation/pull/13) ·
[PR #15 · Streamlit 통합](https://github.com/dongtan-91-dong-welfare-center/audit_inquiry_automation/pull/15)

### [회계기준서 RAG](https://github.com/PDW-accountant/rag_for_accounting)

일반기업회계기준에서 질문과 관련된 조항을 검색하고, 원문 근거와 함께 답변하는 프로젝트입니다.

🔗 **데모:** [http://43.202.147.202:8000/](http://43.202.147.202:8000/)

- **직접 구현:** PDF 헤더 위계 검수, 온톨로지 구조와 관계 추출, 평가용 gold 데이터, 질의 재작성 모듈
- **사용 도구:** `Python` `LangGraph` `Pydantic` `OpenAI API`

[온톨로지 설계 및 구축](https://github.com/dongtan-91-dong-welfare-center/rag_for_accounting/commit/dc8a4168aa73849a617029da301069551dcb4b9d) ·
[질의 재작성 PR #21](https://github.com/dongtan-91-dong-welfare-center/rag_for_accounting/pull/21) ·
[gold 데이터 PR #256](https://github.com/dongtan-91-dong-welfare-center/rag_for_accounting/pull/256)
