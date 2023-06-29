## ಲಿಂಕ್‌ಗಳನ್ನು ರಚಿಸುವುದು

ಈ ಕಾರ್ಡ್‌ನಲ್ಲಿ ಲಿಂಕ್ ಅನ್ನು ಕ್ಲಿಕ್ ಮಾಡಿದಾಗ ಅದನ್ನು ಇನ್ನೊಂದು ಪುಟಕ್ಕೆ ಕರೆದೊಯ್ಯುವುದು ಹೇಗೆ ಎಂದು ನೀವು ಕಲಿಯುವಿರಿ.

- `index.html` ನ ದೇಹದ ವಿಭಾಗಕ್ಕೆ ಈ ಕೆಳಗಿನ ಕೋಡ್ ಸೇರಿಸಿ:

```html
  <a href="">Click here</a>
```

`<a> </a>` ಟ್ಯಾಗ್‌ಗಳು ಅವುಗಳ ನಡುವೆ ಇರುವ ಯಾವುದನ್ನಾದರೂ ಲಿಂಕ್ ಆಗಿ ಪರಿವರ್ತಿಸುತ್ತವೆ.

- ಏನಾಗುತ್ತದೆ ಎಂದು ನೋಡಲು ನಿಮ್ಮ ಲಿಂಕ್ಅನ್ನು ಕ್ಲಿಕ್ ಮಾಡಿ. ಅದು ಏನೂ ಮಾಡುವುದಿಲ್ಲ, ಸರಿನಾ?

ಏಕೆಂದರೆ ಈ ಸಮಯದಲ್ಲಿ `href` ಗುಣಲಕ್ಷಣ ಖಾಲಿಯಾಗಿದೆ. ನೀವು ಲಿಂಕ್ ಮಾಡಲು ಬಯಸುವ ಪುಟದ **URL** (ಜಾಲತಾಣದ ವಿಳಾಸ) ಅನ್ನು ಇದು ಒಳಗೊಂಡಿರಬೇಕು.

- ವಿಕಿಪೀಡಿಯಾಕ್ಕೆ ಹೋಗಿ ಮತ್ತು ನಿಮ್ಮ ವೆಬ್‌ಸೈಟ್‌ನಲ್ಲಿ ಯಾವುದಾದರೂ ಒಂದು ಪುಟವನ್ನು ಹುಡುಕಿ. ನಾನು ಐರ್ಲೆಂಡ್ ಬಗ್ಗೆ ಪುಟವನ್ನು ಬಳಸಲಿದ್ದೇನೆ.

- ವಿಳಾಸ ಪಟ್ಟಿಯಲ್ಲಿ ಕ್ಲಿಕ್ ಮಾಡಿ ಮತ್ತು ಅದರಲ್ಲಿರುವ ಎಲ್ಲಾ ಪಠ್ಯವನ್ನು ಆಯ್ಕೆಮಾಡಿ. ಅದು ನೀವು ಇರುವ ಪುಟದ ಸಂಪೂರ್ಣ URL ಆಗಿದೆ. ಅದನ್ನು ನಕಲಿಸಲು <kdb>ಒಂದೇ</kdb> (or <kdb>cmd</kdb>) and <kdb>C</kdb> ಕೀಗಳನ್ನು ನಕಲಿಸಲು ಅದೇ ಸಮಯದಲ್ಲಿ.
    
    ![ವಿಳಾಸ ಪಟ್ಟಿಯಲ್ಲಿರುವ URL](images/AddressBarURL.png)

- ನಿಮ್ಮ ಟ್ರಿಂಕೆಟ್‌ನಲ್ಲಿ, `href=` ನಂತರ ಉದ್ಧರಣ ಚಿಹ್ನೆಗಳ ನಡುವೆ ಕ್ಲಿಕ್ ಮಾಡಿ <kdb>Ctrl</kdb> (or <kdb>cmd</kdb>) and <kdb>V</kdb> ನೀವು ಇದೀಗ ನಕಲಿಸಿದ URL ನಲ್ಲಿ ಅಂಟಿಸಲು ಕೀಲಿಗಳು. ನಿಮ್ಮ ಕೋಡ್ ಈಗ ಈ ರೀತಿ ಕಾಣಬೇಕು:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">Click here</a>
```

ನಿಮ್ಮ ಮೊದಲ ಲಿಂಕ್ ಅನ್ನು ನೀವು ಇದೀಗ ರಚಿಸಿದ್ದೀರಿ! ಅದು ಈಗ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತದೆಯೇ ಎಂದು ನೋಡಲು ಅದರ ಮೇಲೆ ಕ್ಲಿಕ್ ಮಾಡಿ.

![Link tag](images/egLinkTagWithURL.png)

## \--- collapse \---

## title: ಇತರ ವೆಬ್‌ಸೈಟ್‌ಗಳಿಗೆ ಲಿಂಕ್‌ಗಳು

Trinket ‌ಗೆ ಕೆಲವು ಜಾಲತಾಣದ ವಿಳಾಸಗಳೊಂದಿಗೆ ತೊಂದರೆ ಇದೆ. ನೀವು ಬಯಸಿದರೆ ವಿಕಿಪೀಡಿಯಾ ಹೊರತುಪಡಿಸಿ ಬೇರೆ ವೆಬ್‌ಸೈಟ್‌ಗಳ URL ಗಳನ್ನು ನೀವು ಪ್ರಯತ್ನಿಸಬಹುದು, ಆದರೆ ಅವು ನಿಮ್ಮ trinket ‌ನಲ್ಲಿ ಕಾರ್ಯನಿರ್ವಹಿಸದೆ ಇರಬಹುದು. ಆದಾಗ್ಯೂ, ನಿಮ್ಮ ಪ್ರಾಜೆಕ್ಟ್ ಅನ್ನು ನೀವು ಡೌನ್‌ಲೋಡ್ ಮಾಡಿಕೊಂಡು ಅಂತರ್ಜಾಲ ಬ್ರೌಸರ್‌ನಲ್ಲಿ ಫೈಲ್‌ಗಳನ್ನು ವೀಕ್ಷಿಸುತ್ತಿದ್ದರೆ, ಲಿಂಕ್‌ಗಳು ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತಿರುವುದನ್ನು ನೀವು ನೋಡುತ್ತೀರಿ.

\--- /collapse \---

- `Click here` ಪದಗಳ ಬದಲು `<a> </a>` ಟ್ಯಾಗ್‌ಗಳ ನಡುವೆ ಚಿತ್ರವನ್ನು ಇರಿಸಲು ಪ್ರಯತ್ನಿಸಿ, ಈ ರೀತಿಯಾಗಿ:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">
      <img src="tito.png" alt="Tito the dog" width="100px" />
  </a>
```

- ನಿಮ್ಮ ಚಿತ್ರದ ಮೇಲೆ ಕ್ಲಿಕ್ ಮಾಡಿ. ಅದನ್ನು ಲಿಂಕ್ ಆಗಿ ಪರಿವರ್ತಿಸಲಾಗಿದೆ ಎಂದು ನೀವು ನೋಡುತ್ತೀರಾ?

ಪ್ಯಾರಾಗ್ರಾಫ್‌ನಲ್ಲಿ ಅಥವಾ ಪಟ್ಟಿಯಂತಹ ನಿಮ್ಮ ಅಂತರ್ಜಾಲ ‌ಪುಟದ ಇತರ ಅಂಶಗಳಿಗೆ ನೀವು ಲಿಂಕ್ ಅನ್ನು ಹಾಕಬಹುದು. ಅದರಲ್ಲಿ ಲಿಂಕ್ ಹೊಂದಿರುವ ವಾಕ್ಯದ ಉದಾಹರಣೆ ಇಲ್ಲಿದೆ:

```html
  <p>
    <a href="https://en.wikipedia.org/wiki/Ireland">Click here</a> to read the Wikipedia page!
  </p>
```

\--- challenge \---

## ಸವಾಲು: ಪಟ್ಟಿಯನ್ನು ಲಿಂಕ್ ಆಗಿ ಇರಿಸಿ

- ಪಟ್ಟಿ ಐಟಂಗಳೊಂದರಲ್ಲಿ ಲಿಂಕ್ ಹೊಂದಿರುವ ಪಟ್ಟಿಯನ್ನು ನೀವು ಮಾಡಬಹುದೇ ಎಂದು ನೋಡಿ.

\--- /challenge \---