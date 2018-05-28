# html

## meta tag

### 기본적인 meta tag

`<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />`
해당 문서의 언어 설정

`<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes"> `
모바일에서 접속시 모바일크기에 맞춘 화면을 렌더링설정

`<meta name="title" content="이 문서의 제목은 000 입니다. "/> `

`<meta name="keyword" content="키워드1,키워드2,키워드3, .... "/> `

`<meta name="author" content="000"/>`

`<meta name="description" content="이 문서는 html 소개를 위한 문서입니다. ~~~~ "/> `

### SEO(Search Engine Optimization)

`<meta name="keywords" content="html, CSS, JS" />`
`<meta name="description" content="HTML,CSS,JS 를 활용한 웹페이지 만들기" />`

* keyword는 10~20개를 쓰는 것이 좋다는 말도 있고, 10개 미만으로 작성하고 description을 잘 적어야 한다는 말도 있음.(조금 더 확인해야겠음)
* google은 keyword로 검색엔진 최적화를 하지 않음.

### 오픈 그래프

링크를 공유했을 때 미리보기 화면을 구성. 페이스북에서 제작했으며 많은 웹에서 사용.

[트위터의 오픈그래프 태그](https://developer.twitter.com/en/docs/tweets/optimize-with-cards/guides/getting-started)도 존재. 더 풍부한 메타태그를 지원한다고 함.

Tip

* [Sharing debugger](https://developers.facebook.com/tools/debug/sharing/)에서 적용 됐는지 여부 확인




### Ref

* [Meta 태그란 무엇인가?!](http://conol.tistory.com/23)
* [메타태그(META TAG) 속성정리 및 사용 방법](http://blog.munilive.com/%ED%8E%8C-%EB%A9%94%ED%83%80%ED%83%9C%EA%B7%B8meta-tag-%EC%86%8D%EC%84%B1%EC%A0%95%EB%A6%AC-%EB%B0%8F-%EC%82%AC%EC%9A%A9-%EB%B0%A9%EB%B2%95/)
* [Google에서 이해할 수 있는 메타태그](https://support.google.com/webmasters/answer/79812?hl=ko)
* [링크의 미리보기 제목, 설명, 이미지를 결정하는 open graph 태그](http://blog.ab180.co/open-graph-as-a-website-preview/)
* [Open graph protocol](http://ogp.me/)
