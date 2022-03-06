# Flex
You can use all of your knowledge on flexbox here too! Bootstrap has a flex utility to help you manage your layout. 
<br/>
Duplicate your cards a few times 🃏. 
![cards](https://user-images.githubusercontent.com/18662979/156926411-5f4149f7-4b12-4622-81d4-e6abbd35107a.JPG)

The cards are now below each other, which is not what we want 🤔. Let’s add `d-flex` to their parent `div` to have them side by side.
```html
 <div class="m-2 d-flex">
```
But the cards don’t fit anymore 😭.
![card with d-flex](https://user-images.githubusercontent.com/18662979/156926496-044784b4-fcdc-459c-bfcb-bbf26d6d8d55.JPG)

lets fix that by adding `flex-wrap`. And let's center the items by using `justify-content-center`
```html
<div class="m-2 d-flex flex-wrap justify-content-center">
```
![card with flex-wrap](https://user-images.githubusercontent.com/18662979/156926546-3fbc4ea8-9918-4064-8713-a2c8d65cc553.JPG)

Much better 😍.
<br/>
Now let’s add some spacing between the cards by using `gap-4`.
```html
<div class="m-2 d-flex flex-wrap justify-content-center gap-4">
```
![cards with gap-4](https://user-images.githubusercontent.com/18662979/156926623-dfd0eee2-c6eb-4f3b-a39f-bc73989e3ab7.JPG)
<br/>
