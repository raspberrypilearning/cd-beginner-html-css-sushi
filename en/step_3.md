## Creating a web page

- In the left-hand panel, the **code panel**, click on the tab that says "index.html".

- Find the line that says "Welcome to Ireland!" and change it to your own home country or town, being careful not to delete the text `<p>` at the start of the line and `</p>` at the end of the line. You should see your web page updated in the right-hand panel. ![](images/egFirstHtmlCodeRun.png)

- Now on the same line, change the `<p>` and `</p>` to `<h1>` and `</h1>`. What happens?
  ```html
    <h1>Welcome to Ireland!</h1>
  ```

When you want to put text on a page, you need to put it in between two **tags** that tell your browser how to display your text. For example, the `<p> </p>` tags tell the browser it is a paragraph of text. The `<h1> </h1>` tags tell it that the text is a heading.

   A **browser** is the program you use to look at websites, for example Chrome or Firefox.

--- collapse ---
---
title: HTML and tags
---
**HTML** is the code that makes a web page.

The **.html** in the filename tells the browser that the file is a web page, so it looks for the tags telling it what to display. 

HTML **tags** define different pieces of a page, for example paragraphs and headings, or the body. The pieces are all called **elements**. Think of them as building blocks.

###Why do you need two tags? 
You have an **opening** and a **closing** tag to tell the browser where things **start** and **end**. 
So for a paragraph, the opening `<p>` tag says "here comes some text that I want you to display as a paragraph". The closing `</p>` tag tells the browser where the paragraph ends. 
Everything in between the `<body>` and `</body>` tags is your web page. 
 * Notice how the **closing** tag always has a forward slash, `/`.
  
--- /collapse ---

- Try changing the `p` to `h2` in the last paragraph, the one that says "Coding websites is fun!" Remember to change it in both the **opening** `<p>` and the **closing** `</p>` tag.

- Try changing the numbers in your **heading** tags to see the different sizes you get. They can go from `<h1>` all the way up to `<h6>`.


- Lastly, find the code for the paragraph that says "My website is about Ireland" and change it so that it looks like this:
   ```html
      <p>
         <em>My website</em> is about <strong>Ireland</strong>. 
         It is going to have the following pages: Attractions, Music, Food
      </p>
  ```
  Can you work out what the `<em> </em>` and `<strong> </strong>` tags do?


 ![Run your first HTML code](images/FirstTagsAndRun.png)

So now you've seen that a web page is just made up of text, with **tags** to control it! On the next card you will find out how to control what the **elements** on your page look like.






