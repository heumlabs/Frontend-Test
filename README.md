# Local API 서버 구동방법

프로젝트 경로에 본 저장소에 있는 db.json 파일을 다운로드 받고 다음 단계를 수행한다

## 1. json-server 설치
```
npm install -g json-server
```

## 2. 서버 구동
```
json-server --watch db.json
```

## 3. 확인
json-server는 기본 포트로 3000 번을 사용함

브라우저에서 `localhost:3000`으로 접속, Resources 항목에 bookmarks 가 보이면 정상

# API 문서 경로
https://sh-nam.gitbook.io/test/
