# Cards
Bootstrap already has a card utility that we can use to build the Warehouse cards. Copy the card code from [Bootstrap’s documentation](https://getbootstrap.com/docs/5.0/components/card/).
<br/>
We'll create a `div` with a class of `m-2` inside the `main` tag to contain the cards. Change the card's `image`, `title` and `subtitle` to match one of Warehouse’s cards.
<br/>
Remove the button since we don’t need it.
<br/>
```html
<main>
    <div class="m-2">
        <div class="card" style="width: 18rem;">
            <img src="./card-img.png" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">0. System Setup</h5>
                <p class="card-text">Required installations</p>
            </div>
        </div>
    </div>
</main>
```
![initial card](https://user-images.githubusercontent.com/18662979/156925942-e80e5e28-d1ea-4dd9-8e30-00cf0d7e365b.JPG)

Let's make the card look more like the one in Warehouse. Let's add the text utility class `text-muted` to the subtitle to make it grey.
```html
<main>
    <div class="m-2">
        <div class="card" style="width: 18rem;">
            <img src="./card-img.png" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">0. System Setup</h5>
                <p class="card-text text-muted">Required installations</p>
            </div>
        </div>
    </div>
</main>
```
![card with text-muted](https://user-images.githubusercontent.com/18662979/156926081-11de5ac3-062c-4a48-9e46-2177438ff87f.JPG)
