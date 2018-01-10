## Making a list

On this card you will learn how to turn a list of items, such as "unicorns, robots, cats" into a nicer looking list that you can do cool things with later.
  
- In the index.html file, add the following code just above the line with `</main>` on it:

```html
    <ul>
        <li>Cows</li>
        <li>Sheep</li>
        <li>Foxes</li>
        <li>Bats</li>
    </ul>
```

The result should be a nice list like this: 

![Unordered list](images/egUnorderedList.png)

Notice that there is a separate pair of `<li> </li>` tags around each thing in the list. 

This is a list of some animals you might see in Ireland. You can change the items on the list to things that make sense for your website, and add a **paragraph** above the list to describe what it's a list of, if you like!

How about if you wanted a numbered list? It's almost the same, but instead of `ul`, you use `ol`. A numbered list is also called an **ordered** list. 

- Add the following code underneath the code you just wrote \(make sure it's **after** the `</ul>` tag!\):

```html
    <p>
        My favourite things to eat and drink in Ireland are:
    </p>
    <ol>
        <li>Tea</li>
        <li>Crisp sandwiches</li>
        <li>Sausages</li>
    </ol>
```

Here's what it should look like now:

![Ordered list](images/egOrderedList.png)

### Challenge
- See if you can add **CSS rules** to your stylesheet to change how your lists look.

