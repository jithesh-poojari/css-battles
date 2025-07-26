# ✅ CSS Battle #235 - Website

![Target](./images/235.png)  
[Play Challenge](https://cssbattle.dev/play/235)  
[Watch Solution Video](https://www.youtube.com/watch?v=kfDOPvIHbcg)

---

## 🔢 Stats

**Match**: ✅ 100%  
**Score**: 🟢 624.04 (Characters: 295)

---

## ✅ Code

```html
<p><a><b>
<style>
*{
  background:#FDFFE9;
  +*{
    background:#ADB274;
    margin:20;
    *{
      position:fixed
    }
  }
}
  p{
    padding:5+200;
    margin:30 0;
    color:FDFFE9;
    box-shadow:0 201q,95q 53q,95q 127q
  }
  a{
    padding:95+5;
    margin:0-120
  }
  b{
    padding:10;
    background:#555A2A;
    margin:105 85;
    color:555A2A;
    box-shadow:32q 0,-32q 0,-175q -244q,175q -244q
  }
</style>
```

---

## ✅ Code Explanation

This solution recreates the look of a **watch with a strap** using just a single `<p>` tag, cleverly enhanced by two inner tags: `<a>` and `<b>`. The key technique is aggressive use of universal selectors, shorthand CSS, and box shadows — all optimized for character count.

---

### 🎯 Visual Structure

* The **background** is a soft yellow-green (`#FDFFE9`) that fills the canvas.
* A large, centered **olive-green circle** (`#ADB274`) acts as the main watch body.
* Inside it:

  * The `<a>` element adds an **inner ring** using padding and a shifted margin to create layered depth.
  * The `<b>` element becomes the **dark inner dial**, centered via margin and accentuated with shadows that simulate the strap ends and a central horizontal bar.

---

### 🧠 Key Techniques

* **Universal + Adjacent Sibling Selector**: `* + *` is used to reduce code footprint while still applying rules to specific elements. Here, it styles the first real element (`<p>`), setting background and margin while nesting more rules inside.
* **Nested Selectors**: Rather than applying position or box-shadow to every element manually, child selectors inside a universal cascade (`* *`) apply `position: fixed` globally inside the target, ensuring precise, fixed placement of internal parts.
* **Box Shadows for Structure**: Shadows are used to draw the **side straps** and top extensions of the watch using offset circular "dots" or blobs. They simulate visual elements without needing extra HTML.
* **Q units (quarter-em)**: Used for ultra-precise and character-efficient sizing/spacing. For example, `95q` creates distances needed for aligning dots or parts of the strap.
* **Shorthand Everywhere**: Padding and margin are declared using compressed values like `5+200`, which is interpreted as top padding `5px`, bottom `200px`, and similarly for margins — minimizing character usage.
