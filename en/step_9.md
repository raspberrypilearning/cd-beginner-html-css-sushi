## Adding more pages

This card will show you how to add more pages to your website.

- At the top of the code panel, click on the **+** symbol next to the tabs and type in a name for your new file. It must end in **.html** \(including the dot!\) so that the browser knows it's a web page.

![Adding a new file in Trinket](images/tktNewFileArrows.png)

--- collapse ---
---
title: Renaming or deleting a file
---

If you want to change the name of a file, click on the cog icon to the right of the filename, and click the pencil. Type in the new name and press Enter. You can also delete a file by clicking the bin icon instead of the pencil.
![](images/EditFilename.png)

You might be wondering why you can't change the name of the index.html file. "index.html" is a special name used for the **homepage** of a website. That's the first page you land on when you visit a website. When you go to a website's homepage, the browser looks for the file called "index.html" and displays it on your screen.

--- /collapse ---

- Find the file **blank\_page.html** and **copy** and **paste** all of the code from it into your new file.

--- collapse ---
---
title: How to copy and paste
---
- Go the the file blank\_page.html in the code panel \(by clicking on the tab with that name\). Select all of the text in the file by doing the following: Click anywhere on the code, then press and hold the **Ctrl** key \(or if you are using a Mac, the **cmd** key\) and while holding it, press the **A** key at the same time. Notice how all the text becomes highlighted.

![All the code selected in the blank_page.html file](images/egBlankPageSelectAll.png)

- Now, with the text selected, press and hold the **Ctrl** \(or **cmd**\) key again and then while holding it press the **C** key. This **copies** everything that was selected.

- Go to your new file and click inside the code panel \(which is blank at the moment\). Press and hold the **Ctrl** \(or **cmd**\) key and then while holding it, press the **V** key. This **pastes** everything that was copied into your new page.

![After pasting the code into another html file](images/egBlankPageCodePasted.png)
  You can use these keyboard shortcuts in most programs to **copy** and **paste** stuff, including text and files!
--- /collapse ---

- Change the text in between the `<title> </title>` tags so your new page has a suitable title. Trinket won't display the title, but you'll see it at the top of your browser window when you download your project later.

- In between the `<main> </main>` tags in the new file, use the tags you have learned to add stuff to the page, such as paragraphs, headings, images and lists!

- Repeat the steps above for each new page that you want to add. 

- When there are too many tabs to be able to see them all, you can use the **<** and **>** icons in the top left corner of the tabs to scroll between them.

![The buttons for scrolling the tabs](images/tktScrollTabIcons.png)

Now you need to make links so that you can get to each of your new pages! Let's put all the links in a list.

- In the **index.html** file, add the following code:
   ```html
   <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="attractions.html">Places to visit</a></li>
      <li><a href="music.html">Music</a></li>
      <li><a href="food.html">Things to eat</a></li>
   </ul>
   ```

- Change the value of the `href` **attribute** for each link \(rememeber, that's the text inside the quotation marks\) so that it exactly matches the name of each new file that you created. 

- Change the text in between the `<a> </a>` tags to suitable descriptions of your pages.

Now you can navigate to your new pages! 

![Example list of links on a web page](images/egListOfPageLinks.png)

