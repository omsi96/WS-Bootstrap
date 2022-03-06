# Badges
Bootstrap has a handy utility for creating [badges](https://getbootstrap.com/docs/5.0/components/badge/), which we will use to create the tags on the Warehouse cards.
<br/>
Choose the badge most similar to our Warehouse cards. Add two of them inside a `div` within the `card body`. Add a margin to the start of the second badge to space it away from the first one.
<br/>
```html
<main>
    <div class="m-2">
        <div class="card" style="width: 18rem;">
            <img src="./card-img.png" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">0. System Setup</h5>
                <p class="card-text text-muted">Required installations</p>
                <div>
                    <span class="badge bg-secondary me-1">Foundations</span>
                    <span class="badge bg-secondary">PreCourse</span>
                </div>
            </div>
        </div>
    </div>
</main>
```
![card with badges](https://user-images.githubusercontent.com/18662979/156926331-27161068-9a41-4821-8266-844e3c0cff7b.JPG)

