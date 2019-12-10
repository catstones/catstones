# CASTStones

<https://catstones.github.io>

CATStones는 가톨릭대학교 개발 동아리입니다.
가대학사, CUKCAT 등 학우를 위한 앱을 만듭니다.

이 저장소는 팀 블로그 소스코드 저장소입니다.

## 글 작성하기

`_posts` 디렉토리 아래에 `년-월-일-제목.md` 형식으로 문서를 만들고,
글을 작성합니다.

문서 상단에는 FrontMatter로 글 제목이 포함되어야합니다.

예를 들어 2019년 12월 9일에 "안녕 세상아!"라는 글을 쓰려면
`_posts` 디렉토리 아래에 `2019-12-09-hello-world.md` 파일을 만들고
다음처럼 글을 작성합니다.

```markdown
---
title: 안녕 세상아!
---

세상은 **너무** 아름다워
```

## 실행해보기

루비(최소 2.4.0)가 깔려있어야 합니다.

```
$ gem install jekyll
```

위와 같이 jekyll을 깔고 프로젝트 루트에서 다음을 실행합니다.

```
$ jekyll serve --livereload
      Generating...
                    done in 0.017 seconds.
LiveReload address: http://127.0.0.1:35729
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop.
```

웹 브라우저에서 <http://localhost:4000>에 접속하여 확인합니다.

## 발행하기

그대로 커밋하고 푸쉬하면 됩니다.
