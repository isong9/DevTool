# github 연습 -- 송용호 수정

# 시나리오 A
선 : 레파지토리 생성,README.md 파일에 노트작성  후 커밋 & 푸시
후 : 리모트에서 새 프로젝트 clone 받기
후 : 노트에서 새로운 내용을 추가하여 커밋, 푸시
선 : 풀 받아 오기
선 : 노트에 새로운 내용을 추가하여 커밋 후 푸시
후 : 풀 받아 오기
- 반복 연습

# 시나리오 B : 충돌
- 선 : 첫번째 줄 수정 후 커밋 & 푸시
- 후 : 마지막 줄 수정 후 커밋 & 푸시(!!!) 
--(에러메시지 뜸) -> 풀 받고 푸시
- 선 : 풀 받고, 마지막 줄 수정 후 커밋
- 후 : 마지막 줄 수정 후 커밋 & 푸시
- 선 : 푸시하기(!!!)                    
-- (에러메시지 뜸), -> pull 후 충돌 부분 해결 -> merge commit -> push
```
아래 부분 해결해야됨.
>>>>>
=====
<<<<<
=====
```
- 후 : 풀 받아 오기

## 송용호 1'st README
## 송용호 2'st README


1.송용호 3'st README

- list add

마지막 줄 수정 
정상훈 마지막줄 수정 후 커밋&푸시