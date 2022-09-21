# TIL

## 2022-09-21
## 리눅스 용어와  의미
|용어|의미  |
|--|--|
|ls|list  |
|pwd|print working directory|
|cd|change directory  |
|cd ..|상위 디렉토리로 가기 |


## vim 용어와  의미
|용어|의미  |
|--|--|
|vim 파일명.확장자|편집하고 싶은 파일 열기  |
|i|insert(입력 모드 전환)|
|:w|저장  |
|:q|나가기  |
|:wq|저장 후 나가기|


### vim 사용법
> window에서 git bash를 설치할 때, default editor로 vim을 선택했기 때문에 git을 사용하려면 반드시 vim을 사용할 줄 알아야 함

#### 명령모드 vs. 입력모드

1. vim 에디터를 처음 킬때는 명령모드로 진입. 이때는 입력이 불가능함
2. 입력 하려면 입력 모드로 바꿔야함
  - 입력 모드로 바꾸려면 키보드에서 `i`키(insert)등을 누름
3. 입력이 다 끝나고 저장 등의 명령을 컴퓨터에게 내리려면 명령모드로 다시 돌아가야 함
  - 명령모드로 바꾸려면 키보드에서 `esc`키를 누름
  - 명령모드에서 `:w`를 입력하고 `enter`키를 누르면 저장만 됨(write)
  - `:wq`를 입력하면 저장하고 에디터에서 빠져나올 수 있음(write and quit)
  - `:q`를 입력하면 에디터에서 빠져나올 수 있음(quit)