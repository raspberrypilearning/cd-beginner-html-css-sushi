## 사진 추가하기

사진을 추가해 봅시다!

- ` index.html` 탭으로 이동하세요. ` </main> ` 태그를 찾아 **그 위에** 입력하십시오: 

```html
    <img src="tito.png" alt="Tito the dog" width="100px" />
```

아래와 같이 보일 것입니다:

![티토의 이미지 코드 및 그림](images/egImgCodeTito.png)

이 태그에는 추가 정보가 들어 있습니다. 그것들은 **속성**이라고 부릅니다.

- `width="100px"`가 포함된 코드를 찾으세요. 이 속성이 어떤 역할을 하는지 파악할 수 있도록 하기 위해 다른 숫자로 실험해 보세요. 절대 `px` 문자를 지우지 마세요!

\--- collapse \---

* * *

## title: How the `img` tag works

`<img>` 태그는 지금까지 사용해 왔던 다른 태그와 다릅니다 - 닫는 태그 `</img>` 가 없습니다. 대신에, 이 태그는 **자체 마감** 태그입니다: `/>` 가 없습니다. 텍스트에는 시작과 끝을 지정해 주어야 하지만 이미지 요소에서는 시작과 끝이 없기 때문입니다.

이러한 태그는 추가 **속성**을 가지고 있습니다:

- `src`는 이미지의 경로를 나타냅니다. 
- `alt` 는 이미지의 대안을 뜻하며, 그림을 표시할 수 없는 경우에 브라우저에 표시되는 간단한 설명입니다. 'alt' 는 'Alternate(대체하다)' 의 줄임말입니다. 이 텍스트는 시각장애인과 같은 사람들에게 스크린 리더를 활용하여 이미지의 속성을 알 수 있도록 합니다.
- `width` 속성은 이미지의 너비를 지정합니다. `100px` 은 100 **pixels** 을 나타냅니다. 이는 화면에 보이는 것을 구성하는 작은 점들입니다. 만약에 이 속성을 지정하지 않으면 그림이 원래 크기로 표시됩니다.

\--- /collapse \---

이제 웹 사이트에 그림을 올리는 방법을 알았으므로 그림을 변경하고 싶을 것입니다.

- 물론 가장 먼저 필요한 것은 그림입니다! 찍은 사진과 같이 이미 컴퓨터에 있는 사진을 사용하거나 인터넷에서 사진을 가져올 수 있습니다.

[[[generic-get-picture-from-web]]]

** 참고: ** 인터넷에서 찾을 수있는 모든 이미지가 누구나 자유롭게 사용할 수있는 것은 아닙니다. 사진을 다운로드하는 경우 사진이 허용 된 사진인지 확인해야합니다. 이에 대한 자세한 내용은 다음을 참조하십시오:

[[[images-permissions-to-use]]]

사진이 있으면 Trinket에 파일을 **업로드** 할 수 있습니다:

- Trinket에서는, **이미지 아이콘 옆의** **+** 을 클릭합니다. 

![이미지 아이콘](images/tktImageIconArrow.png)

여기에서 웹 사이트에서 사용할 수있는 사진을 볼 수 있습니다. CoderDojo 강아지인 Tito 의 그림을 볼 수 있습니다.

- **Add Image**을 클릭하고 **Upload**을 클릭하십시오.

- ** 클릭하여 파일 선택하기 ** 버튼을 클릭하십시오. 창에서 이미지 파일을 찾아 더블 클릭하십시오.

- **Done**을 클릭하세요.

![이미지 업로드](images/tktUploadImages.png)

사진이 업로드되어 사용할 준비가 될 것입니다.

- ` index.html` 파일로 이동하여 `<img>` 태그를 찾습니다. 텍스트를 `tito.png`로 변경하면 당신이 선택한 이미지 파일의 이름과 정확히 일치합니다. 파일 확장자는 `.png` 가 아닌 `.jpg`로 끝나야 할 것입니다!

방금 변경 한 텍스트는 `src`라는 속성으로, 어떤 파일을 표시할지 브라우저에 알립니다.

**참고:** 속성은 무조건 따옴표(`""`)로 둘러싸여 있어야 합니다!

\--- challenge \---

## 과제: 그림의 alt 텍스트 변경

- `alt` 속성을 변경하여 그 안에있는 텍스트를 그림의 간단한 설명으로 변경하십시오. 

\--- /challenge \---