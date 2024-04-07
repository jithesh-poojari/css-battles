## CSS Battle #4 - Ups n Downs

![picture of daily target](./images/04.png)  
[See the daily target](https://cssbattle.dev/play/4)

### Challenge Overview

The challenge requires creating a design that resembles a push button using HTML and CSS. The target image displays a square-shaped button against a contrasting background.

### Method 1 - Reflection Button

**Stats:**

- **Match:** 100%
- **Score:** 637.27{249}

### Code

```html
<p><p a><p b>
<style>
  body{
    background:#62306D;
  }
  p{
    position:absolute;
    width:100;
    height:100;
    background:#F7EC7D;
    border-radius:100px 100px 0 0;
    bottom:44.5%;
    left:150;
  }
  [b],[a]{
    rotate:180deg;
    top:44.5%;
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

- **Background (`body`):** The `body` background color is set to a vibrant blue shade (`#6592cf`), providing a visually appealing backdrop for the button.

- **Button (`a`):** The `<a>` element represents the button shape, styled with a background color of `#243d83`, creating a contrast with the background.

- **Button (`p`):** The `<p>` element forms the circular shape inside the button, giving it a distinctive appearance. It is positioned at the center of the button, with a background color of `#eeb850` and a border to create a button-like effect.

- **Reflection Effect (`box-shadow`):** The `box-shadow` property is applied to the circular shape (`p`) to create a reflection effect. It adds a shadow with a large spread value to mimic a reflection, enhancing the visual appeal of the button.

This method effectively creates a button-like design with a reflection effect, achieving a perfect match and a high score.

### Method 1 - Reflection Button

**Stats:**

- **Match:** 100%
- **Score:** 637.27{249}

### Code

```html
<p></p><p a>
<style>
  *{margin:0}
  body{
    background:#62306D;
    display:grid;
    place-content:center;
  }
  p{
    width:100;
    height:100;
    background:#F7EC7D;
    border-radius:100px 100px 0 0;
  }
  [a]{
    rotate:180deg;
    background:#62306D;
    color:#F7EC7D;
    box-shadow:100px 0,-100px 0
  }
</style>
```

**Code Explanation:**

- **Background (`body`):** The `body` background color is set to a vibrant blue shade (`#6592cf`), providing a visually appealing backdrop for the button.

- **Button (`a`):** The `<a>` element represents the button shape, styled with a background color of `#243d83`, creating a contrast with the background.

- **Button (`p`):** The `<p>` element forms the circular shape inside the button, giving it a distinctive appearance. It is positioned at the center of the button, with a background color of `#eeb850` and a border to create a button-like effect.

- **Reflection Effect (`box-shadow`):** The `box-shadow` property is applied to the circular shape (`p`) to create a reflection effect. It adds a shadow with a large spread value to mimic a reflection, enhancing the visual appeal of the button.

This method effectively creates a button-like design with a reflection effect, achieving a perfect match and a high score.