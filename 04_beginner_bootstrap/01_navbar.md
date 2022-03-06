# Navbar
Bootstrap provides with a navbar that looks great on desktop and mobile. Go to Bootstrap’s documentation and search for the navbar.
<br/>
You will see an example of a navbar with a code snippet. Copy the code and paste it into `index.html` into the `header`.
<br/>
![navbar original](https://user-images.githubusercontent.com/18662979/155157486-2181454f-5224-4268-91ee-42e24114e93e.png)
<br/>
You’ll notice the navbar includes examples of different elements that could be used inside it. Remove the unnecessary ones to match it to Warehouse’s navbar.
<br/>
```html
 <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">warehouse</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">learn</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link " href="#">practice</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link " href="#">dashboard</a>
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
![edited navbar2](https://user-images.githubusercontent.com/18662979/155157773-0d2ba88d-4dee-4835-aca4-7e8c57ff3cba.png)

