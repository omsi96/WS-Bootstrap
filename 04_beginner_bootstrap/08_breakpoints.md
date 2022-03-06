# Breakpoints
Bootstrap provides you with some responsive-friendly classes, this means you can also indicate whether something should be applied ***only*** on certain viewport widths 🤯. 
<br/>
For example, `mt-md-2` means a `margin top of 2rem` will be applied to viewports ***medium width and larger***.
<br/>
But what do we mean by medium? Is there a small? Large?
<br/>
These cutoffs points are known as breakpoints. Why? 
<br/>
They are called breakpoints because these are usually the points where your UI starts to break and look distorted 💔.
<br/>
Bootstrap includes ***six*** default breakpoints to help you build responsive UI. To learn more about them, check the [documentation](https://getbootstrap.com/docs/5.0/layout/breakpoints/).
<br/>
You don’t need to memorize these classes, always refer to the documentation!
Bootstrap uses the `mobile-first` design approach which means that we start designing for ***smaller*** viewports and then we ***adjust*** for ***larger*** viewports. 
<br/>
For example, let’s add `m-2 m-sm-4` instead of `m-2` to our cards `div`. This means it will add a padding of `2rem`, unless the screen size is ***small and larger***, then it would apply `4rem`.
<br/>

```html
<div class="m-2 m-sm-4 d-flex flex-wrap justify-content-center gap-4">
```
![cards final](https://user-images.githubusercontent.com/18662979/156927017-284e0338-b08a-4b8c-a22f-f1e1ca8a5ac4.JPG)