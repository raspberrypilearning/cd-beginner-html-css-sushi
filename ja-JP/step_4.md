## 見た目の制御

Webサイトの見た目を記述するコードは**CSS**と呼ばれています。

- コードパネルの上にあるタブを見て、`styles.css`というファイル名のタブをクリックして移動します。 ファイルには次のテキストが書かれています。

```css
  body {   
    background-color: white;
   }
```

- `white`の色を`LightSkyBlue`に変えて、何が起きるか見てください。 ウェブサイトが青い背景になっているはずです！ 

![Example with blue background](images/egFirstCSSbluebg.png)

## \--- collapse \---

## title: どうなっているのでしょうか。

上にある`index.html`ファイルを見ると、次の行があることが分かります。

```html
  <link type="text/css" rel="stylesheet" href="styles.css"/>
```

上の行は`styles.css`という特別なのファイルを探すようブラウザにに指示しています。 その特別なファイルは**スタイルシート**と呼ばれています。 スタイルシートはファイル名に`.css`があることから分かります。

スタイルシートにはWebページにある各要素の見た目の**ルール**が記述されています。

中かっこ`{ }`とその間にあるコードは**CSSルール**のセットです。 `body`はWebサイトのすべての`<body>`要素のルールであることを表しています。 中かっこの前に短く書かれているその箇所は**セレクタ**と呼ばれています。 今回の場合は、body要素のセレクタです。

Each rule inside the curly braces is made up of:

- A **property** on the left, followed by a colon symbol `:`
- A **value** for the property on the right-hand side after the colon
- A semi-colon symbol `;` at the end

\--- /collapse \---

- Lets add rules to change how the text looks. Add two new lines inside the curly braces:

```css
  body {
    background-color: LightSkyBlue;
    font-family: "Helvetica", sans-serif;
    color: purple;
  }
```

Look at how this has changed the webpage.

The `color` property is always for text. Here, you are setting the colour of all text in the `body` of your webpage.

- You can also write separate rules for the headings and the paragraphs. For `<h1>` headings, you use the `h1` selector. Below the closing curly brace containing the CSS rule for the body, add the following code.

```css
  h1 {
    color: orange;
    font-family: "Times New Roman", serif;
  }
```

Your heading text should be orange now, with the paragraph in purple as before.

![Result of new CSS code](images/egCssColorsFonts.png)

Notice how the letters also look different as well as being a different colour? This is because you changed their **font family**. You can find some more fonts [here](http://dojo.soy/web-font-families).

- Try adding a set of rules for the `<h2>` headings, using the `h2` selector.

- Why not experiment with different colour combinations for the text and background? There are lots of colours available to use. Find a full list of them [here](http://dojo.soy/web-color-names).