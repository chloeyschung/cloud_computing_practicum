# 클라우드컴퓨팅실습 개인과제

## 프로젝트 소개
개인 소개 페이지와, 프론트엔드(React)·백엔드(FastAPI)를 연동한 메모장 API 연습 프로젝트입니다.

## 주요 구성
| 구분 | 내용 | 배포 |
|---|---|---|
| 개인 소개 페이지 | `memo-frontend/public/intro.html` | Vercel |
| 프론트엔드 | `memo-frontend` (React + Vite, 메모장 화면에서 백엔드 API 호출) | Vercel |
| 백엔드 | `memo-backend` (FastAPI + SQLite) | Render |

개인 소개 페이지와 메모장 화면은 서로 링크로 연결되어 있습니다.

## 배포 주소
- GitHub 저장소: https://github.com/chloeyschung/cloud_computing_practicum
- Vercel (프론트엔드 + 개인 소개): TODO
- Render (백엔드 Swagger UI, `/docs`): TODO

## 로컬 실행
### 백엔드
```
cd memo-backend
source .venv/bin/activate
pip install -r requirements.txt
fastapi dev main.py
```

### 프론트엔드
```
cd memo-frontend
npm install
npm run dev
```

## 실습 기록
TODO
