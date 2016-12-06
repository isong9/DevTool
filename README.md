# github 연습 -- 송용호 수정

# 시나리오 A
- 선 : 레파지토리 생성,README.md 파일에 노트작성  후 커밋 & 푸시
- 후 : 리모트에서 새 프로젝트 clone 받기
- 후 : 노트에서 새로운 내용을 추가하여 커밋, 푸시
- 선 : 풀 받아 오기
- 선 : 노트에 새로운 내용을 추가하여 커밋 후 푸시
- 후 : 풀 받아 오기
- 반복 연습

# 시나리오 B : 충돌
- 선 : 첫번째 줄 수정 후 커밋 & 푸시
- 후 : 마지막 줄 수정 후 커밋 & 푸시(!!!) 
 - (에러메시지 뜸) -> 풀 받고 푸시
- 선 : 풀 받고, 마지막 줄 수정 후 커밋
- 후 : 마지막 줄 수정 후 커밋 & 푸시
- 선 : 푸시하기(!!!)                    
 - (에러메시지 뜸), -> pull 후 충돌 부분 해결 -> merge commit -> push
```
아래 부분 해결해야됨.
>>>>>
=====
<<<<<
=====
```
- 후 : 풀 받아 오기

# 시나리오 C : 커밋 쪼개기
- 선 : README.md 의 첫줄, 마지막 줄 수정
- 선 : 각 line별로 커밋 하고 (커밋 2개) 푸시하기
- 후 : head-1.md / body-1.md 파일 만들고 내용 작성
- 후 : 각 파일별로 커밋하고(커밋 2개) 푸시하기(!!! rebase) 하여 풀(git pull --rebase) 받기 : histroy oneline 유지)
- 순서를 바꿔서 다시 해보기(head-2.md/ body-2.md)

# 시나리오 D : stash
- 선 : README.md의 아무 내용이나 수정중
- 후 : README.md 수정 후 커밋 & 푸시
- 선 : 풀 받기(!!!), stash 한 후 풀 받기
- 선 : stash pop 하여 마저 수정하고 커밋 & 푸시
- 후 : 풀 받기
- 순서를 바꿔 다시 해보기

## 송용호 1'st README
## 송용호 2'st README


1.송용호 3'st README

- list add


마지막 줄 수정 -- 송용호 수정


정상훈 마지막줄 수정 후 커밋&푸시


#  송용호 추가