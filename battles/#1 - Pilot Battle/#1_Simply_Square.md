## CSS Battle #1 - Simply Square

![picture of daily target](./images/1.png)  
[see the daily target](https://cssbattle.dev/play/1)

### Challenge Overview

The goal of this challenge is to create a design resembling a square using HTML and CSS. The provided target image features a square shape against a contrasting background.

### Method 1 - Box Model Approach

**Stats:**
- **Match:** 100%
- **Score:** 779.62{84}

```html
<style>
  * {
    background: #5d3a3a;
    margin: 0;
    > * {
      background: #b5e0ba;
      width: 200;
      height: 200;
    }
  }
</style>
```

**Code Explanation:**
- **Background (`*`):** The `*` selector targets the entire page, setting its background to a warm golden shade `#5d3a3a`.
- **Container (`>`):** The `>` selector targets all child elements, ensuring they have a white background `#b5e0ba` and fixed dimensions of 200x200 pixels.

### Method 2 - Box Shadow Technique

**Stats:**
- **Match:** 100%
- **Score:** 839.08{54}

```html
<a style=box-shadow:0+0+0+2in#b5e0ba,0+0+0+5in#5d3a3a>
```

**Code Explanation:**
- **Box Shadow (`box-shadow`):** The `box-shadow` property is applied to an anchor (`<a>`) element. Two shadows are defined:
  - A 2-inch inner shadow with a white color (`#b5e0ba`).
  - A 5-inch outer shadow with a contrasting dark color (`#5d3a3a`).

### Conclusion

Both methods effectively create a square design, meeting the challenge's requirements. Method 1 utilizes the box model approach, setting background colors and dimensions. Method 2 achieves a similar result using the `box-shadow` property to simulate the square shape.