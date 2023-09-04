# Emoji_app

The code starts by getting references to HTML elements: searchField, submitButton, and searchResultContainer.

The searchEmoji function is defined to perform emoji searches and display results.

It checks if the searchField is not empty. If it's not empty, it displays the submitButton, otherwise, it hides it.

It gets the value entered in the searchField.

It filters the emojiList based on the search value, looking for matches in aliases and tags.

It clears the searchResultContainer.

It creates HTML elements for each filtered emoji (emoji, description, and category) and appends them to the searchResultContainer.

Initially, it hides the submitButton if the search field is empty.

Event listeners are added to the submitButton and searchField to trigger the searchEmoji function when clicked or when a key is released.

Lastly, the searchEmoji function is called automatically when the page loads.

his code allows users to search for emojis based on their aliases or tags and displays the results dynamically as they type in the search field. The submit button is shown or hidden depending on whether the search field is empty or not.
