# KLP KOREA 온라인 발주서 시스템

뉴코 빵 발주서를 자동 생성하는 내부용 웹 앱입니다.

## 기능
- 11개 품목 선택 & 수량 입력
- 발주서 엑셀 자동 생성 & 다운로드 (셀 병합 포함)
- 마진 분석 (엑셀 미포함)
- Supabase DB 연동 (발주 히스토리 저장)
- 기존 고객 데이터 불러오기 (재주문 편의)

## 기술 스택
- HTML / CSS / Vanilla JS (단일 파일)
- Supabase (PostgreSQL DB + REST API)
- Vercel (정적 호스팅)
- SheetJS (엑셀 생성)
