# CSS Variables
We can have custom `CSS properties` (also known as `CSS variables`) to contain specific values that can be ***reused***. Declaring a custom property is done using a custom property name that begins with a double hyphen `(--)`, and a property value that can be any ***valid CSS value***.
<br/>
For example: `--variable-name: value;`
<br/>
A common best practice is to define CSS variables on the `:root` pseudo-class, so that it can be applied globally across your CSS:
```CSS
:root{
    --my-margin:5em;
}
```
<br/>
Let's create a stylesheet and link it. Inside our stylesheet, we are going to define our own color CSS variable:

```CSS
:root{
    --logo-color:#3A3A5A;
}
```
<br/>
But where are we going to use it? 
<br/>
We will create a CSS class that uses this variable:

```CSS
.navbar a.navbar-brand{
    color:var(--logo-color);
}
```
![logo css variable](https://user-images.githubusercontent.com/18662979/156927670-962a6671-3634-4425-adb7-eed2f6550098.JPG)
