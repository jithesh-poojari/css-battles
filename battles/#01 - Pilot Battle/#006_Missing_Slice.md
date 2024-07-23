## CSS Battle #6 - Missing Slice

![picture of daily target](./images/006.png)  
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

### Code Explanation:

- **Universal Selector (`*`)**:
  - **Background Color**: Sets the background color of the entire page to `#E3516E`, a shade of pinkish-red.

- **Nested Universal Selector (`* *`)**:
  - **Background**: Uses `conic-gradient` to create a circular gradient with the following color stops:
    - `#FADE8B` from 0% to 25%, a light yellow.
    - `#E3516E` from 25% to 50%, matching the page background color.
    - `#F7F3D7` from 50% to 75%, a very light cream.
    - `#51B5A9` from 75% to 100%, a teal shade.
  - **Margin**: Sets the margin to `50px` top and bottom, and `100px` left and right.
  - **Border-radius**: Sets the `border-radius` to `50%`, creating a circular shape.

This setup creates a visual design with a pinkish-red background and a circular gradient with four color slices, matching the desired target image. The use of the conic-gradient, margin, and border-radius ensures precise placement and styling of the elements to achieve the required visual effect.