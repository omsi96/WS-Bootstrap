# Bootstrap Classes
We will be using Bootstrap’s text utilities to transform our navbar to look more similar to Warehouse’s. Have a look at Bootstrap’s text utilities module in their documentation before moving on. 🏃‍
<br/>
The CSS classes in Bootstrap use a shorthand syntax, for example `margin-top:2rem` would be `mt-2`. Another example is `text-align: center;` would be `text-center`.
<br/>
Let’s compare our current navbar to warehouse’s real one:
<br/>
![edited navbar](https://user-images.githubusercontent.com/18662979/154293564-ce507d52-37fa-44f5-9c3b-c2781101ab1e.png)
<br/>
![warehouse navbar](https://user-images.githubusercontent.com/18662979/154307168-138a30ac-278e-4e78-879d-f60fac6d8ccc.png)
<br/>
One of the differences is that their text is all-caps while ours isn’t. Bootstrap has a handy CSS class called `text-uppercase` that we can use. 
<br/>
```html
<header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand text-uppercase" href="#">warehouse</a>
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
            </div>
        </div>
     </nav>
</header>
```
![navbar uppercase](https://user-images.githubusercontent.com/18662979/155175456-c2af1cf6-0917-4eed-9096-61c52fc01ad1.png)
<br/>
We also notice that the logo’s font weight should be bold, and of course Bootstrap has a class called `fw-bold` to do that. 
<br/>
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
            </div>
        </div>
    </nav>
</header>
```
![navbar bold](https://user-images.githubusercontent.com/18662979/155175480-2dcf7d91-24d7-48ff-b40c-4bc0d1c7014b.png)
