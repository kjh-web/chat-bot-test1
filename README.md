# Galaxy RAG Chatbot

갤럭시 S25 매뉴얼을 위한 RAG(Retrieval Augmented Generation) 기반 챗봇 프로젝트입니다.

## 주요 기능

- 문서 검색 및 관련성 높은 내용 추출
- 이미지 검색 및 문의 내용과 관련된 이미지 제공
- 하이브리드 검색(벡터 유사도 + 키워드)으로 정확한 결과 제공
- 사용자 친화적인 웹 인터페이스

## 설치 및 실행

### 백엔드 설정

```bash
# 필요한 패키지 설치
pip install -r requirements.txt

# 환경 변수 설정 (.env 파일 생성)
# API 키 및 데이터베이스 정보 입력

# 백엔드 서버 실행
python app.py
```

### 프론트엔드 설정

```bash
# galaxy-web-ui 디렉토리로 이동
cd galaxy-web-ui

# 패키지 설치
npm install --force

# 개발 서버 실행
npm run dev
```

## 기술 스택

- 백엔드: FastAPI, LangChain
- 프론트엔드: Next.js, TypeScript
- 데이터베이스: Supabase

## 사용 방법

1. 챗봇에 질문 입력
2. 관련 매뉴얼 내용 및 이미지 확인
3. 다양한 기능 및 설정에 대한 안내 받기