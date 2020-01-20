## 페이지 추가

이 장에서는 웹 사이트에 페이지를 추가하는 방법을 보여줍니다.

- 코드 패널 상단에서 ** + ** 기호를 누르고, 새 파일의 이름을 입력하십시오. 파일 명은 `.html` (도트 포함!) 로 끝나야 브라우저가 웹 페이지임을 알 수 있습니다.

![Trinket에 새 파일 추가하기](images/tktNewFileArrows.png)

## \--- collapse \---

## title: 파일 이름 바꾸기 또는 삭제

만약에 파일 이름을 변경하고 싶다면, 파일 이름 우측에 있는 **톱니바퀴** 아이콘을 클릭하고 **연필** 아이콘을 클릭하세요. 새로운 이름을 입력하고 **Enter**를 누릅니다. **연필** 아이콘 대신 **쓰레기통** 아이콘을 눌러 파일을 삭제할 수 있습니다.

![](images/EditFilename.png)

You might be wondering why you can't change the name of the `index.html` file. `index.html` is a special name used for the **homepage** of a website. That's the first page you land on when you visit a website. Whenever you go to a website's homepage, the browser looks for the file called `index.html` and displays it on your screen.

\--- /collapse \---

- `blank_page.html` 파일을 찾고, 모든 내용을 복사해 새로운 파일에 붙여 넣으세요. 전체 내용을 복사하고자 하는 경우 코드의 아무 곳이나 클릭하고 키보드의 단축키 <kbd>Ctrl</kbd> (Mac에서는 <kbd>cmd</kbd>) 및 <kbd>A</kbd>를 눌러 모든 내용을 선택하세요.

- `<title></title>` 태그를 사용하여 새 페이지의 적합한 제목을 지정하세요. Trinket은 제목을 표시하지 않지만 프로젝트를 다운로드하면 브라우저 창 상단에 표시됩니다.

![The page title showing in the browser tab](images/egLocalFileWindowTitle.png)

- 새 파일의 `<main></main>` 태그 사이에 단락, 헤더, 이미지 및 목록과 같은 태그를 사용해 보세요!

- 추가하려는 각 새 페이지에 대해 위의 단계를 반복하십시오.

When there are too many tabs for Trinket to show at once, you can use the **<** and **>** icons in the top left-hand corner of the tabs to scroll between them.

![The buttons for scrolling the tabs](images/tktScrollTabIcons.png)

Now you need to make links so that you can get to each of your new pages! Let's put all the links in a list.

- `index.html` 파일에 다음 코드를 웹 페이지 body에 추가하십시오.

```html
    <ul>
        <li><a href="index.html">홈</a></li>
        <li><a href="attractions.html">관광 명소</a></li>
        <li><a href="music.html">음악</a></li>
        <li><a href="food.html">음식</a></li>
    </ul>
```

- 각 링크의 `href` 값을 변경하세요. (따옴표 안에 텍스트가 들어가야 한다는 것을 꼭 기억하세요) 각 HTML 파일의 이름과 정확히 일치해야 합니다.

- `<a> </a>` 태그를 페이지의 적절한 곳에 추가하십시오.

Now you can navigate to your new pages!

![Example list of links on a web page](images/egListOfPageLinks.png)