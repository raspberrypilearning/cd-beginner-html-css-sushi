## إضافة المزيد من الصفحات

ستوضح لك هذه البطاقة كيفية إضافة المزيد من الصفحات إلى موقعك على الويب.

- At the top of the code panel, click on the **+** symbol next to the tabs, and type in a name for your new file. يجب أن ينتهي بـ `.html ` (بما في ذلك النقطة!) بحيث يعرف المتصفح أنها صفحة ويب.

![إضافة ملف جديد في Trinket](images/tktNewFileArrows.png)

## \--- collapse \---

## title: Renaming or deleting a file

If you want to change the name of a file, click on the **cog** icon to the right of the file name, and then click the **pencil** icon. اكتب الاسم الجديد واضغط على زر** Enter **. You can also delete a file by clicking the **bin** icon instead of the **pencil** icon.

![](images/EditFilename.png)

You might be wondering why you can't change the name of the `index.html` file. `index.html` is a special name used for the **homepage** of a website. That's the first page you land on when you visit a website. Whenever you go to a website's homepage, the browser looks for the file called `index.html` and displays it on your screen.

\--- /collapse \---

- Find the file `blank_page.html` and copy and paste all of the code from it into your new file. نظرًا لأنك ترغب في نسخ كل شيء ، يمكنك النقر في أي مكان على الكود واستخدام اختصار لوحة المفاتيح <kbd> Ctrl </kbd> (أو <kbd> cmd </kbd>) و <kbd>A</kbd> لتحديد الكل في نفس الوقت.

- غير النص بين الرمزين `<title> </title>` ليكون لصفحتك الجديدة عنوان مناسب. Trinket won't display the title, but you can see it at the top of your browser window if you download your project.

![The page title showing in the browser tab](images/egLocalFileWindowTitle.png)

- In between the `<main> </main>` tags in the new file, use the tags you have learned about to add stuff to the page, such as paragraphs, headings, images, and lists!

- كرر الخطوات المذكورة أعلاه لكل صفحة جديدة تريد إضافتها.

When there are too many tabs for Trinket to show at once, you can use the **<** and **>** icons in the top left-hand corner of the tabs to scroll between them.

![The buttons for scrolling the tabs](images/tktScrollTabIcons.png)

Now you need to make links so that you can get to each of your new pages! Let's put all the links in a list.

- في ملف ` index.html `، أضف الكود التالي إلى محتوى صفحة الويب الخاصة بك:

```html
    <ul>
       <li><a href="index.html">الرئيسية</a></li>
       <li><a href="attractions.html">أماكن للزيارة</a></li>
       <li><a href="music.html">موسيقى</a></li>
       <li><a href="food.html">مأكولات</a></li>
    </ul>
```

- غيّر قيمة سمة `href` لكل رابط (تذكر ، هذا هو النص الموجود داخل علامات الاقتباس) بحيث يطابق تمامًا اسم كل ملف HTML قمت بإنشائه.

- غير النص بين رموز `<a> و</a>` إلى وصف مناسبة لصفحاتك.

Now you can navigate to your new pages!

![Example list of links on a web page](images/egListOfPageLinks.png)