## CSS Battle #7 - Leafy Trail

![picture of daily target](./images/07.png)  
[See the daily target](https://cssbattle.dev/play/7)

### Method 1

**YouTube Video**: [see video](https://www.youtube.com/watch?v=b7JMJ0U1GK0)

**Stats:**

- **Match:** 100%
- **Score:** 716.98{129}

### Code

```html
<style>
*{
  background:#0B2429;
  *{
    background:#F3AC3C;
    margin:75 75 75 175;
    border-radius:105q 0;
    box-shadow:-53q 0#998235,-106q 0#1A4341
  }
}
</style>
```

### Code Explanation:

- **Universal Selector (`*`)**:
  - **Background Color**: Sets the background color of the entire page to `#0B2429`, a dark teal shade.

- **Nested Universal Selector (`* *`)**:
  - **Background Color**: Sets the background color of the nested elements to `#F3AC3C`, a mustard yellow shade.
  - **Margin**: Sets the margin to `75px` top, bottom, and left, and `175px` right. This positions the elements accordingly.
  - **Border-radius**: Sets the `border-radius` to `105px` for the top-left and bottom-left corners, and `0` for the top-right and bottom-right corners, creating a leaf-like shape.
  - **Box-shadow**: Creates shadows with the following values:
    - `-53px 0 #998235`: A shadow positioned `53px` to the left with a color of `#998235`, a darker mustard shade.
    - `-106px 0 #1A4341`: A shadow positioned `106px` to the left with a color of `#1A4341`, a dark green shade.

This setup creates a visual design with a dark teal background and several mustard yellow leaf-like shapes positioned around the page, matching the desired target image. The use of background color, margin, border-radius, and box-shadow ensures precise placement and styling of the elements to achieve the required visual effect.