# Spacing
Bootstrap comes equipped with several CSS classes that you can use to add spacing to your elements. Whether its margin, or spacing, Bootstrap has you covered!
<br/>
Using Bootstrap’s spacing classes helps you keep your spacing consistent. Consistency is extremely important to the user, the difference between these two pictures is just spacing! 🤯
<br/>
![spacing example](https://user-images.githubusercontent.com/18662979/155178824-32eb7ac9-42d7-4790-9be7-7c7df180e0be.JPG)
<br/>
With time and practice, your eyes will be trained to help you choose the right amount of spacing.
Notice how our search and logout buttons are stuck together?
![navbar button edited](https://user-images.githubusercontent.com/18662979/155175838-a7d75afc-1a8c-4384-99af-9bd8c5a6b53b.png)
<br/>
Let’s apply a margin to its left to space it away from the search button.
In Bootstrap, margins are categorized by: `top`, `bottom`, `start`, and `end`. In our case, applying a `margin to the right` of the logout button will space it away.
<br/>
Let’s apply `ms-2`
```html
<button class="btn btn-outline-secondary text-uppercase ms-2">log out</button>
```
![navbar button margin](https://user-images.githubusercontent.com/18662979/155180164-a4d2d1fd-eabf-4723-be24-b5872a6789d1.png)

