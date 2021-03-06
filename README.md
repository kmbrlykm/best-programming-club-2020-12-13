# best-programming-club-2020-12-13

## Kim's method

Add an empty section for available vegetables to be added to programatically. Every vegetable is an object, which lives inside a list, titled Vegetable. And the list lives inside availableProductsData, an object. Inside initializeProducts(), locate the empty section for vegetables. Run a forEach loop on the vegetables list, then create a new list item with the vegetable's name. Append the list item to the vegetables section. We then make a new button with the vegetable's details, and append it to the list item. 

### Challenges and Questions

1. I think the most challenging part was figuring out the structure of lists where fruits and vegetables live. So a fruit is an object, which is inside a fruit list, inside a bigger object. So fruits and veggies can be seprated but still be kinda together.

2. itemData vs. item: I see Sua used itemData when running forEach on the fruit list, but I used item on vegie list. Everything seems to work. But I'm still googling the difference. Is it interchangeable?

3. ~~When we're appending buttons to the unordered list, it seems to magically appear next to the vegetable. I thought it would appear under, because it looks like these button items are being added as a new list item.~~ I see the button is NOT being added as a new list item, instead we append the button to the list item that was already created with product name. 


## Assignment

Add a new section for vegetables under "Products" so that users can buy vegetables.

Try to do this programmatically.

Hint 1: Start with the HTML, using the available fruit section for reference.

Hint 2: The data for fruit is around line 32. The data for vegetables is around line 42.

Hint 3: All of the Javascript for programmatically creating the fruit section is inside `initializeProducts`.

### Getting the assignment

[Fork this repository](https://guides.github.com/activities/forking/)

[Install Prettier for VSCode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### Completing the assignment

Make sure to commit your changes as you're making progress on the assignment. You'll receive feedback on the commit messages. Remember, commit messages should be short and sweet, in present-tense with an imperative tone. For example:

```
rename cart variable
```

### Remember...

- Google as much as you can, using the keywords you've learned. For example, search _"how to create HTML from javascript"_ or _"what is javascript forEach"_ or _"what is javascript dataset"_. MDN is a great keyword to include in your searches for reference materal, for example _"MDN javascript array"_.
- Don't be afraid to commit code that's not working yet.
- Don't get discouraged if you can't get it to work--focus on reading the existing code and making your best guess at what the code might look like.

## The "answers"

TBD
