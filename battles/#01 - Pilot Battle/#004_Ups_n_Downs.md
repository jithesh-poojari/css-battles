## CSS Battle #4 - Ups n Downs

![picture of daily target](./images/004.png)  
[See the daily target](https://cssbattle.dev/play/4)


### Method 1 

**YouTube Video**: [see video](https://www.youtube.com/watch?v=JAJQJuOZ0RA)

**Stats:**

- **Match:** 100%
- **Score:** 642.59{235}

### Code

```html
<p><p a><p b>
<style>
  *{
    background:#62306D
  }
  p{
    position:absolute;
    width:100;
    height:100;
    background:#F7EC7D;
    border-radius:50%50%0 0;
    bottom:44.5%;
    left:150
  }
  [a],[b]{
    rotate:180deg;
    top:44.5%
  }
  [a]{
    left:50
  }
  [b]{
    left:250
  }
</style>
```

**Code Explanation:**

- **Background (`body`):** The `body` background color is set to a dark purple shade (`#62306D`), providing a visually appealing backdrop for the button.

- **Button (`p`):** Three `<p>` elements are used to create the button shape. They are positioned absolutely and styled with a yellow background color (`#F7EC7D`) and border-radius to form a rounded shape resembling a push button.

- **Reflection Effect (`[a], [b]`):** Two pseudo-elements `[a]` and `[b]` are used to create the reflection effect on the button. They are positioned at the top of the button, rotated 180 degrees, and styled with a dark purple background color (`#62306D`), creating the illusion of a reflection.

This method effectively creates a button-like design with a reflection effect, achieving a near-perfect match and a high score.

### Method 2 

**YouTube Video**: [see video](https://www.youtube.com/watch?v=8DrxnGBVwiE)

**Stats:**

- **Match:** 100%
- **Score:** 642.59{235}

### Code

```html
<p></p><p a>
<style>
*{
  margin:0;
  +*{
    background:#62306D;
    display:grid;
    place-content:center
  }
}
  p{
    width:100;
    height:100;
    background:#F7EC7D;
    border-radius:100q 100q 0 0
  }
  [a]{
    rotate:180deg;
    background:#62306D;
    color:#F7EC7D;
    box-shadow:100px 0,-100px 0
  }
</style>
```

### Code Explanation:

- **Background:** The background color is set to a dark purple shade (`#62306D`), providing a visually appealing backdrop for the button.

- **Button (`p`):** Two `<p>` elements are used to create the button shape and its reflection. They are styled with a yellow background color (`#F7EC7D`) and border-radius to form a rounded shape resembling a push button. The first `<p>` element represents the button, and the second `<p>` element represents its reflection.

- **Styling (`[a]`):** A pseudo-element `[a]` is used to create the reflection effect on the button. It is positioned behind the button, rotated 180 degrees, and styled with a dark purple background color (`#62306D`) and white text color (`#F7EC7D`), creating the illusion of a reflection. Additionally, a box-shadow is applied to create the reflection effect.

This method effectively creates a button-like design with a reflection effect, achieving a perfect match and a high score.

### Method 3 

**YouTube Video**: [see video](https://www.youtube.com/watch?v=aDoQr2jYwZE)

**Stats:**

- **Match:** 100%
- **Score:** 680.66{168}

### Code

```html
<p><a>
<style>
*{
  background:#62306D
}
  p,a{
    position:fixed;
    background:#F7EC7D;
    padding:50;
    margin:42 142;
    border-radius:60q 60q 0 0
  }
  a{
    scale:-1;
    margin:50;
    box-shadow:212q 0#F7EC7D
  }
</style>
```

### Code Explanation:

- **Background:** The background color is set to a dark purple shade (`#62306D`), providing a visually appealing backdrop for the elements.

- **Styles for `p` and `a` Tags**:
  - **Position**: Uses `fixed` to position the `p` and `a` elements relative to the viewport, ensuring they stay in place as the page is scrolled.
  - **Background Color**: Sets the background color of the `p` and `a` elements to `#F7EC7D`, a light yellow shade.
  - **Padding**: Adds `50px` padding to control the size of the elements.
  - **Margin**: Sets the margin of the `p` and `a` elements to `42px` top and bottom, and `142px` left and right.
  - **Border-radius**: Sets the `border-radius` to `60px` for the top-left and top-right corners, creating a rounded top shape.

- **Styles for `a` Tag**:
  - **Scale**: Uses `scale` to flip the `a` element horizontally, creating a reflection effect.
  - **Margin**: Sets the margin of the `a` element to `50px` on all sides.
  - **Box-shadow**: Creates a shadow with a value of `212px` to the right, matching the background color to enhance the visual effect of the reflection.

This setup creates a visual design with a dark purple background and two light yellow elements positioned around the page, matching the desired target image. The use of fixed positioning, padding, margin, border-radius, scale, and box-shadow ensures precise placement of the elements to achieve the required visual effect.