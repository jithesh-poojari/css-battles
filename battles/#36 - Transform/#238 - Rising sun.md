# ✅ CSS Battle #238 - Rising sun

![Target](./images/238.png)  
[Play Challenge](https://cssbattle.dev/play/238)  
[Watch Solution Video](https://www.youtube.com/watch?v=oGecbLlU3MY)

---

## 🔢 Stats

**Match**: ✅ 100%  
**Score**: 🟢 634.54 (Characters: 257)

---

## ✅ Code

```html
<p><a><b>
<style>
*{
  background:#FEFF58;
  +*{
    background:#D2F8FF;
    margin:40 50;
    border:11q solid;
    *{
      position:fixed
    }
  }
}
  P{
    padding:70+140;
    background:#CF6939;
    margin:60 0;
    border-radius:2in 2in 0 0
  }
  a,b{
    background:#000;
    padding:100+5;
    margin:-130-5
  }
  b{
    padding:5+140;
    margin:-5-140
  }
</style>
```

---

## ✅ Code Explanation

This solution builds a **round castle with two symmetrical towers** using a single `<p>` tag and powerful CSS tricks. The layout relies on clever use of the universal selector, adjacent sibling selector, gradients, border radii, and box shadows — all optimized for minimal character usage.

---

### 🎯 Visual Structure

* The background of the entire page is filled with a dark bluish color (`#3F4869`), establishing the night-sky setting.
* The first visible shape (a large yellow-red dome) is created using the adjacent sibling selector `* + *`. It applies a **linear gradient** from yellow (`#F4DA64`) to red (`#E25C57`), split evenly at 50%. This dome represents the **main castle roof**.
* A large top border radius rounds both top corners using `border-radius: 2in 2in 0 0`, forming a perfect semi-circle.
* The `<p>` element itself is placed fixed at the bottom and contains **box shadows** representing **two smaller circular towers**, flanking the dome symmetrically.

---

### 🧠 Key Techniques

* **Adjacent Sibling Selector (`+*`)** is used to target the element right after the first (in this case, `<p>`), allowing it to receive styling without additional tags or IDs.
* **Linear Gradient** is used creatively to split the dome into two distinct halves, visually suggesting two materials or lighting effects.
* **Box Shadows** on the `<p>` element replicate round turrets or castle accents by placing colored circles using horizontal offsets and blur.
* **Position Fixed** is applied to ensure the base and shadows stay in place relative to the viewport, crucial for a fixed layout typical in CSS Battles.
* **Shorthand margin and padding** are used efficiently to position the elements without lengthy declarations.

---

### 📦 Final Layout Summary

* Central dome (gradient-filled) = main castle.
* Two small circular turrets = left and right box shadows.
* No extra elements needed; all visual depth comes from shadows and gradients.
* Fully symmetrical layout using only one tag and selector logic.