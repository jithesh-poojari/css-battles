## CSS Battle #3 - Push Button

![picture of daily target](./images/03.png)  
[See the daily target](https://cssbattle.dev/play/3)

### Challenge Overview

The challenge requires creating a design that resembles a push button using HTML and CSS. The target image displays a square-shaped button against a contrasting background.

### Method 1 - Reflection Button

**YouTube Video**: [see video](https://www.youtube.com/watch?v=sg5pY_UA6AM)

**Stats:**

- **Match:** 100%
- **Score:** 637.27{249}

### Code

```html
<a></a>
<p>
  <style>
    body {
      background: #6592cf;
      display: grid;
      place-items: center;
    }
    a,
    p {
      position: absolute;
    }
    a {
      width: 300px;
      height: 150px;
      background: #243d83;
    }
    p {
      background: #eeb850;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      border: 50px solid #243d83;
      box-shadow: 0 0 0 50px #6592cf;
    }
  </style>
</p>
```

**Code Explanation:**

- **Background (`body`):** The `body` background color is set to a vibrant blue shade (`#6592cf`), providing a visually appealing backdrop for the button.

- **Button (`a`):** The `<a>` element represents the button shape, styled with a background color of `#243d83`, creating a contrast with the background.

- **Button (`p`):** The `<p>` element forms the circular shape inside the button, giving it a distinctive appearance. It is positioned at the center of the button, with a background color of `#eeb850` and a border to create a button-like effect.

- **Reflection Effect (`box-shadow`):** The `box-shadow` property is applied to the circular shape (`p`) to create a reflection effect. It adds a shadow with a large spread value to mimic a reflection, enhancing the visual appeal of the button.

This method effectively creates a button-like design with a reflection effect, achieving a perfect match and a high score.

### Method 2

**YouTube Video**: [see video](https://www.youtube.com/watch?v=AzTLd7KipZs)

**Stats:**

- **Match:** 100%
- **Score:** 673.33{178}

### Code

```html
<p>
  <style>
    * {
      background: #6592cf;
      * {
        background: #243d83;
        margin: 75 50;
      }
    }
    p {
      background: #eeb850;
      padding: 25;
      border-radius: 50%;
      margin: 0 75;
      border: 53Q solid#243D83;
      box-shadow: 0 0 0 53q#6592CF;
    }
  </style>
</p>
```

### Code Explanation

- **Universal Selector (`*`)**:

  - **Background Color**: Sets the background color of the entire page to `#6592CF`, a vibrant blue shade.

- **Nested Universal Selector (`*` inside `*`)**:

  - **Background Color**: Sets the background color of the nested elements to `#243D83`, a deep blue shade.
  - **Margin**: Sets the margins of the nested elements to `75px` top and bottom, and `50px` left and right.

- **Styles for `p` Tag**:
  - **Background Color**: Sets the background color of the `p` element to `#EEB850`, a golden yellow shade.
  - **Padding**: Adds `25px` padding to the `p` element to control its size.
  - **Border-radius**: Sets the `border-radius` to `50%`, making the `p` element circular.
  - **Margin**: Sets the margin of the `p` element to `0` top and bottom, and `75px` left and right.
  - **Border**: Adds a `53px` solid border with a color of `#243D83`, matching the background color of the nested elements.
  - **Box-shadow**: Creates a shadow around the `p` element with the following values:
    - `0 0 0 53px #6592CF`: A shadow with no offset or blur, but with a spread radius of `53px` and a color of `#6592CF`, matching the background color of the page.

This setup creates a visual design with a vibrant blue background and a central circular element with a golden yellow center, a deep blue border, and a matching blue shadow. The use of margin, padding, border-radius, border, and box-shadow ensures precise placement of the elements to achieve the required visual effect, matching the desired target image.
