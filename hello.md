# hello git
본 문서는 코드스쿼드 강의를 따라가면서 작성되었습니다...
https://www.youtube.com/playlist?list=PLAHa1zfLtLiPrxoBo9a1HVmauvE2Mn3xX

## git 명령어 요약

- clone: 원격 저장소 복사
- add: 스테이지 영역에 작업 파일 추가
- commit: 세이브, 스테이지 영역의 파일들을 가지고 커밋(=세이브)를 만들 수 있다.
- push: 원격 저장소에 커밋을 업로드한다.
- 코드뭉치 버리기: 커밋 전 변경 버림(소스트리에서는 해당 파일을 선택하고 옆 뷰에서 코드뭉치 버리기(아무 줄도 클릭되지 않은 상태에서) 버튼을 누르면 된다.)

## 브랜치 변경하기

- branch: 기존 내용을 유지한 채 새로운 내용을 추가하고 싶을 때 사용한다.
- checkout: 특정 브랜치(혹은 커밋) 으로 돌아가고 싶을 때 사용
- 소스트리에서 체크아웃: 브랜치 이름을 ㄷ블 클릭하는 것만으로 체크아웃 가능

## 머지가 머지?

- 현재 브랜치가 head 브랜치
- 따라서 버전2에서 마스터에 머지하면 머지? 가 아니고 마스터에 반영되는 것..
- fast-forwarding
헤드 브랜치에 변경 사항이 없고 변경 대상 브랜치가 헤드로부터 시작한 경우 아주 쉽게 머지할 수 있다. ![fasterforward](fast_forward_merging.PNG)
- conflict가 일어날 수 있는 상황 ![conflict](can_occur_conflict.PNG)
- 머지하고 필요 없는 브랜치는 지워도 됩니다.
