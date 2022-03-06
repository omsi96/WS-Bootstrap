# Bootstrap Variables
Bootstrap uses CSS variables and you can find them in the `_variables.scss` file. We want to override their color CSS variables to use our own. 
<br/>
Does this mean we should modify the `_variables.scss` file? Absolutely not 💣. 
<br/>
***Do not*** modify a library or framework’s source code. You might end up breaking things and the consequences will haunt you in your dreams 👻.
<br/>
Let's add the following list:
```html
<ul class="d-flex list-unstyled p-2 mb-2 p-sm-4">
    <li class="text-uppercase text-primary me-4">all</li>
    <li class="text-uppercase text-primary me-4">foundations</li>
    <li class="text-uppercase text-primary me-4">react</li>
    <li class="text-uppercase text-primary me-4">mobx</li>
    <li class="text-uppercase text-primary">react</li>
</ul>
```
![initial bootstrap css variables](https://user-images.githubusercontent.com/18662979/156927976-414858f2-9450-41e5-9c57-298b21fdf591.JPG)

Notice they have the default blue because of the `text-primary` class. Use your browser's developer tools to see which Bootstrap CSS variable we will need to override 🔎.
```CSS
:root{
    --logo-color:#3A3A5A;
    --bs-primary-rgb: 38, 51, 169;
}
```
<br/>
Now our page looks more like a Warehouse clone.

![css bootstrap variables](https://user-images.githubusercontent.com/18662979/156928467-b0ce53ec-39cc-4691-96f2-2b66b8dfd3af.JPG)


