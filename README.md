[![standard-readme compliant](https://img.shields.io/badge/bootstrap%20studio-v5.0-blue.svg?style=flat-square)](https://getbootstrap.com/docs/5.0/getting-started/introduction/)

# Bootstrap-Studio

Get started with Bootstrap, the world’s most popular framework for building responsive, mobile-first sites, with jsDelivr and a template starter page.

# CSS

Copy-paste the stylesheet <link> into your <head> before all other stylesheets to load our CSS.

  ```erb
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
```
# JS

  Many of our components require the use of JavaScript to function. Specifically, they require our own JavaScript plugins and Popper. Place one of the following <script>s near the end of your pages, right before the closing </body> tag, to enable them.
 
  ```erb
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
```
  
  # JavaScript plugins
  
  ```erb
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>
  ```
  # Modules
If you use <script type="module">, please refer to our [using bootstrap as a module](https://getbootstrap.com/docs/5.0/getting-started/javascript/#using-bootstrap-as-a-module) section.

  # Responsive meta tag
Bootstrap is developed mobile first, a strategy in which we optimize code for mobile devices first and then scale up components as necessary using CSS media queries. To ensure proper rendering and touch zooming for all devices, add the responsive viewport meta tag to your <head>.

```erb
<meta name="viewport" content="width=device-width, initial-scale=1">
 ``` 
