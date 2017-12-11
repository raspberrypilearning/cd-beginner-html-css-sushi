## Adding pictures

- Click on the image icon next to the **+** sign. This is where you can see the pictures that can be used on your website. For now you can use the picture included with the project. 

- Go to the index.html file in the code panel. After the `</ul>` tag, type the following: 
    ```html
    <img src="tito.png" alt="Tito the dog" width="100px" />
    ```
    Here's what it should look like
    
   ![Picture of Tito](images/ImgTito2.png)

- Notice that the `<img>` tag is different from the other tags you've used so far: 

   There is no closing `</img>` tag. Instead it is **self closing**: the opening tag has `/>` at the end. This is because there is no "start" and "end" like there is when you are putting text on the page. 

   The tag contains three extra pieces of information inside it called **attributes**. The `src` attribute tells the browser what file to use for the picture. The `alt` attribute is a short description that the browser will show if it cannot display the picture. 

- What do you think the `width` attribute does? 

--- hints ---

--- hint ---
**px** is short for **pixels**, the teeny-tiny dots that make up your screen

--- /hint ---

--- /hints ---

  Try experimenting with different numbers! Don't delete the letters `px`. 

- To add a picture of your own to the website, click on the image icon again, and click "Add Image". Click "Upload" and then select "Click To Select Files". Select the file on your computer that you want to upload and click "Open". Click "Done" when you are finished uploading files.

    ![Upload files](images/UploadFilesWider.png)

- Once you have uploaded a picture you can add it to your website using the `<img>` tag as before. Change the value of the `src` attribute so that it exactly matches the name of the file with your picture. 

- Change the value of the `alt` attribute to a short description of the picture. 
  _Important:_ Attribute values like the filename and the alt text must be inside quotation marks!

- Click Save to save your work and Run to see how it looks.



