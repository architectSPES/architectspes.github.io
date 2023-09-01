## 1차로 할 것

### 기본적인 홈페이지 만들기
0. https://www.free-css.com/free-css-templates/page230/stimulus
   또는, Google 등에서 free css template for personal website 등으로 검색
1. 템플릿 가져와서, Visual Studio Code 같은 도구를 사용해서 편집
   + Google Chrome 등의 브라우저의 개발자 도구(F12)를 사용해서 눈으로 보면서 편집
   + HTML / CSS 위주로 수정 (MDN, 생활코딩, ... 참고)
2. 이미지 교체, 내용 교체, ...

### GitHub 사용법 익히기
1. GitHub에 있는 저장소(repository)를 가져와서 (= git clone)
2. Visual Studio Code에서 편집한 내용을 반영하고 (= git commit)
3. GitHub에 올리기 (= git push)


### GitHub Pages 사용법 익히기
1. 저장소의 Settings에서 기본 설정은 되어 있음
   (Deploy from branch: main branch + / 폴더를 참조)
2. <사용자 아이디>.github.io 가 기본 도메인
3. 도메인을 구입 => CNAME 파일을 만들어서 도메인을 설정
   (CNAME 파일은 루트 폴더에 있어야 함)

---

## 이후에 더 할 것

* [ ] 정적 사이트 제작 도구 (Static Site Generator)를 선택 & 학습
  * ; Jekyll, Hugo, Gatsby, Hexo, ... + Pelican(Python), ...
* [ ] 정적 사이트 제작 도구에 맞춰서 템플릿을 가져와서 편집
* [ ] Markdown format을 배우시면 됨 (HTML의 subset: 태그를 간소화해서 표현)
  ```
    <h1>제목</h1>
    # 제목
    <h2>제목</h2>
    ## 제목

    <b>굵게</b>
    **굵게**
  ```
  **참고** 참고로, 이 문서는 Markdown으로 작성되었습니다.
