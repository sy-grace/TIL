## pwd: print working directory

```shell
pwd 
```

## ls: list
* -a : 숨긴 파일까지 보기
* -l : long
* -al : hidden & long

## cd: change directory

## mv: move

```shell
mv ../*.py ./
```

상위 디렉토리의 모든 py파일을 현재 디렉토리로 이동

```shell
mv LICENSE ./license.txt
```

파일 이름 변경

## cp: copy

```shell cp main.py ./main_copy.py
```

같은 위치에 똑같은 파일을 복사할 수는 없다. 이름을 바꿔야함

## rm: remove

```shell
rm -rf dest
```

디렉토리 강제 삭제

## vi: vim 사용

```shell
vi hello.md
```

* : set nu : line number on/off
* i : insert mode
* :wq : 저장 후 나오기
* ctrl + u : undo
* ctrl + r : redo

## cat: 파일 내용 확인
