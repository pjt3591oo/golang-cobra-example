# cobra 기반 cli 구축

## (시작하기 전에...) cobra 기본 사용법

* 프로젝트 생성

```bash
$ $GOPATH/bin/cobra init github.com/경로
```

* 옵션추가

```bash
$ cd github.com/경로

$ $GOPATH/bin/cobra add [옵션이름]
```

---

## 샘플코드 실행해보기

* 소스내려받기

```bash
$ git clone https://github.com/pjt3591oo/golang-cobra-example.git
$ cd golang-cobra-example
```

* 실행

```bash
$ go run main.go --help
```

```bash
$ go run main.go A --boo 123
```

```bash
$ go run main.go B --foo 234
```

```bash
$ go run main.go version
```

> 참고: [설명보러가기](https://blog.naver.com/pjt3591oo/221452097691)