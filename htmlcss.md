### id & class in CSS is case sensitive!!!        id & class in CSS is case sensitive!!! {#important}

* **body font color was overridden by：**

```css
<style>
  body {
    background-color: black;
    font-family: Monospace;
    color: green;
  }
```

* **class declarations**

```css
  .pink-text {
    color: pink !important；
  }
```

* **subsequent class declarations**

```css
  .blue-text {
    color: blue;
  }
```

* **id declarations**

```css
  #orange-text {
    color: orange;
  }
</style>
```

* **In-line styles.**

```css
<h1 id="orange-text" class="pink-text blue-text" style="color: white">Hello World!</h1>
```

* #### `!important`

---

* comment out\(HTML\):

```
<!--    -->
```

* comment out\(CSS\):

```css
/*
*/
```



