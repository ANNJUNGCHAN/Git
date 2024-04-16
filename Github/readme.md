## Github 사용하기

- 코드 저장공간으로 이동 후, git 시작

```
cd [폴더 경로]
git init
```

- github는 main 브렌치 이용 강제. 브렌치 이름 바꾸기

```
git branch -M main
```

- github에 올리기
. 원격 저장소 주소는 저장소 처음 만들면 알려줌
. 상단 파란색 박스 안에 주소 있음
. http부터 시작하는 주소
  (ex.https://github.com/ANNJUNGCHAN/Git.git)
. 한번 '-u'를 쓰면, 원격 저장소 주소를 자동으로 기억

```
git push -u [github 원격 저장소 주소] main
git push
```

- github 원격 저장소 주소 변수 문법으로 간단하게 하기

```
git remote add [변수명] [주소]
```

- 원격 저장소 복사하기
. 주의 : 원격 저장소에 다른 팀원이 push하면 내가 push 못함
         git pull을 사용하자!

```
git clone [원격저장소 주소]
```

- 원격 저장소와 동기화

```
git pull
```


