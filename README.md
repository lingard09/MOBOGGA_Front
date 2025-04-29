
  ✹ **Git Issue 사용법**

- 작업할 기능에 대한 issue를 작성합니다.
- issue 제목은 **[타입] - 설명**으로 통일합니다. (ex. [Style] - 텍스트 스타일 추가)

✹  Commit 메시지 작성법

```bash
타입 : 짧은 내용(한글로)
feat : 로그인
ex)style : 텍스트 디자인시스템 구축
```

|  |  |  |
| --- | --- | --- |
| type | Description | Example |
| feat | 새로운 기능 추가, 구현 | feat : 로그인 기능 구현 |
| edit | 단순 오타 수정 | edit : 로그인 캐시 처리 방식 수정 |
| style | UI작업, 스타일 관련 파일 추가 및 수정 | style : 폰트 등록 |
| add | asset 파일(이미지, 아이콘 등) 추가 | add : 위젯 이미지 추가 |
| chore | 파일, 경로를 옮기거나 이름 변경 | chore : feet -> feat 이름 변경 |
| delete | 덤프 파일 삭제 | delete : Empty.md 파일 삭제 |
| merge | 브랜치 병합(merge) | merge : pull request #3 from LikeLionHGU/Haeun_Style/#1 |
| fix | 버그 픽스 | fix : Color 버그 수정 |
| docs | 문서 작업 | docs : Readme 작성 |
| refactor | 코드 리팩토링 | refactor : 변수명 수정 |
| model | 데이터베이스(모델) 작업 | model : 데이터 모델 생성 |
| init | 프로젝트 생성 | init : 프로젝트 생성 |
| test | 테스트 케이스 생성 | test: 테스트 케이스 생성 |
| 빌드관련 |  |  |  
| build | 재빌드 | build: 동일버전 재빌드(x.xx) |
| version | 버전 업 | version : 버전(2.0.0) 업데이트 |



✹  Pull Request 제목 작성법

이름_타입/#이슈번호 → 풀 시킬 브랜치 (ex. Hani_Style/#1 -> dev)

