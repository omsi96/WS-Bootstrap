# Buttons
We notice that Warehouse’s navbar has a logout button: 
![navbar button original](https://user-images.githubusercontent.com/18662979/155177208-bfc96a3d-c2e2-4f8d-a77c-94d32696ffca.png)
<br/>
Take a cruise in [Bootstrap’s button documentation](https://getbootstrap.com/docs/5.0/components/buttons/) and explore their different options. 
<br/>
You’ll notice the `btn-outline-secondary` is the most similar to what we want. Add the button after the search button and make sure to add `text-uppercase`.
```html
<header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand text-uppercase fw-bold" href="#">warehouse</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                <a class="nav-link active text-uppercase" aria-current="page" href="#">learn</a>
                </li>
                <li class="nav-item">
                <a class="nav-link text-uppercase" href="#">practice</a>
                </li>
                <li class="nav-item">
                <a class="nav-link text-uppercase" href="#">dashboard</a>
                </li>
            </ul>
            <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
            <button class="btn btn-outline-secondary text-uppercase">log out</button>
            </div>
        </div>
    </nav>
</header>
```
![navbar button edited](https://user-images.githubusercontent.com/18662979/155175838-a7d75afc-1a8c-4384-99af-9bd8c5a6b53b.png)

