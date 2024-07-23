## CSS Battle #6 - Missing Slice

![picture of daily target](./images/06.png)  
[See the daily target](https://cssbattle.dev/play/6)

### Method 1

**YouTube Video**: [see video](https://www.youtube.com/watch?v=xgSBFYonUuA)

**Stats:**

- **Match:** 100%
- **Score:** 707.36{138}

### Code

```html
<style>
*{
  background:#E3516E;
  *{
    background:conic-gradient(#FADE8B 25%,#E3516E 0 50%,#F7F3D7 0 75%,#51B5A9 0);
    margin:50 100;
    border-radius:50%
  }
}
</style>
```

**Code Explanation:**

- **Universal Selector (`*`)**:
  - **Background Color**: Sets the background color of the entire page to `#0B2429`, a dark teal shade.

- **Element Selectors (`p, a`)**:
  - **Position**: Uses `fixed` to position the elements relative to the viewport, ensuring they stay in place as the page is scrolled.
  - **Background Color**: Sets the background color of the elements to `#F3AC3C`, a mustard yellow shade.
  - **Padding**: Adds `60px` padding to control the size of the elements.
  - **Margin**: Sets the margin of the elements to `22px` top and bottom, and `192px` left and right.
  - **Border-radius**: Sets the `border-radius` to `65px` for three corners and `0` for the bottom-left corner, creating a unique shape.

- **Element Selector (`a`)**:
  - **Transform**: Uses `scale(-1, 1)` to flip the element horizontally.
  - **Margin**: Adjusts the margin of the element to `60px` top and bottom, and `-180px` left and right.
  - **Box-shadow**: Creates a shadow with `-64px 64px #998235`, positioning the shadow to the left and below the element with a color of `#998235`, a darker mustard shade.

This setup creates a visual design with a dark teal background and two mustard yellow shapes positioned around the page, matching the desired target image. The use of fixed positioning, padding, margin, border-radius, transform, and box-shadow ensures precise placement of the elements to achieve the required visual effect.