## 첫 번째 웹페이지!

- 왼쪽 **코드 패널**에서, `index.html` 탭을 클릭하세요.

- ` Welcome to Ireland! `로 줄을 찾아 메시지에서 변경하십시오. 줄의 시작 부분에 `<p>` 태그를 붙이지 **말고** ` </p> `을 입력하십시오. 오른쪽 패널에 웹 페이지가 업데이트 되어 표시되어야 합니다.

![HTML 단락 예시](images/egFirstHtmlCode.png)

- 이제 `<h1>`과 ` </h1> `을 사용하여 동일한 줄에서 `<p>`과 ` </p> `을 변경하십시오. 오른쪽 결과가 업데이트되어 표시되었나요?

```html
  <h1>아일랜드에 오신 것을 환영합니다!</h1>
```

## \--- collapse \---

## title: HTML과 태그

**HTML**은 웹 페이지를 만드는 코드입니다.

파일 이름에있는 `.html`은 브라우저에 파일이 웹 페이지임을 알려주고 브라우저는 표시 할 내용을 알려주는 ** 태그 ** (레이블)를 찾습니다. (브라우저는 웹 사이트를 볼 때 사용하는 프로그램입니다. Chrome, Internet Explorer, Firefox 등의 브라우저가 있습니다.)

`<p>` 및 ` </p> `과 같은 HTML 태그는 단락, 제목 또는 내용과 같이 페이지의 다른 부분을 정의합니다. 이러한 부분을 ** 요소 ** 라고 합니다. 그들을 빌딩 블록이라고 생각하세요.

### 왜 두 개의 태그가 필요합니까?

태그의 **시작** 과 **끝**을 브라우저에게 알려주어, 태그가 **시작**되는 영역과 **끝**나는 영역을 제대로 알 수 있도록 하기 위함입니다. 따라서, 어떠한 문장을 표시할 때에는 `<p>` 태그를 사용하여 "여기에 문장으로 표시하기를 원하는 텍스트가 있습니다." 와 같은 문장을 입력합니다. 이후 `</p>` 태그를 사용하여 문장이 끝나는 위치를 알려줍니다.

모든 홈페이지의 영역은 `<body>`에서 시작하여 `</body>` 에서 끝납니다.

- 모든 태그의 끝에는 **항상 '<' 다음에** `/` 가 추가되어야 합니다.

\--- /collapse \---

- **heading** 숫자를 바꾸어 다양한 크기의 글자를 만들어 보세요. `<h1>` 부터 `<h6>` 까지 입력이 가능합니다. 꼭 시작 태그와 닫기 태그가 일치하도록 변경해야합니다.

- `이 웹사이트는 아일랜드에 대해 다룹니다.` 문단이 들어 있는 코드를 찾아보세요. 그리고 아래와 같이 바꿔 보세요.

```html
  <p>
    <em>이 웹사이트는</em> <strong>아일랜드</strong>에 대해 다룹니다. 
    아일랜드의 특색은 다음과 같습니다: 관광명소, 음악, 음식
  </p>
```

`<em> </em>` 과 `<strong> </strong>` 태그는 어떤 역할을 하는지 알아낼 수 있나요?

![HTML 태그 예시](images/egFirstTags.png)

\--- challenge \---

## 도전: 더 많은 텍스트 추가하기

- 배운 태그 중 일부를 사용하여 페이지에 새로운 문장이나 제목을 추가해보십시오.

\--- hints \---

\--- hint \---

When you want to put text on a page, you need to put it in between two tags that tell your browser how to display your text. For example, the `<p> </p>` tags tell the browser that whatever is in between them is a new paragraph of text, and the `<h1> </h1>` tags tell it that the text in between is a heading.

\--- /hint \---

\--- hint \---

The code for paragraphs looks like this:

```html
  <p> 이것은 텍스트의 단락입니다. </p>

  <p> 이것은 또 다른 단락입니다.
  p 태그 안에 있는 문장입니다. 
  웹 페이지에 하나의 긴 줄에 함께 표시됩니다. </p>
```

\--- /hint \---

\--- hint \---

The code for headings looks like this:

```html
  <h1>이것은 헤딩입니다.</h1>
```

Headings will normally be displayed bigger or bolder than the paragraphs.

\--- /hint \---

\--- /hints \---

\--- /challenge \---

Congratulations, you've built your first webpage! On the next card, you'll find out how to control how it looks.