# ✅ CSS Battle #239 - Waves

![Target](./images/239.png)  
[Play Challenge](https://cssbattle.dev/play/239)  
[Watch Solution Video](https://www.youtube.com/watch?v=vCbE47TM0PM)

---

## 🔢 Stats

**Match**: ✅ 100%  
**Score**: 🟢 632.93 (Characters: 262)

---

## ✅ Code

```html
<p><a><b><c>
<style>
*{
  background:#CEEDFF;
  position:fixed;
  color:48BF7D
}
  p,a,b{
    padding:50+120;
    margin:162-3;
    border-style:solid;
    border-width:0 0 30 30;
    border-radius:0 0 0 2in
  }
  a,b{
    margin:-50-20
  }
  c{
    border:16q solid;
    margin:-65-410;
    border-radius:50%;
    box-shadow:138q 0,275q 0
  }
</style>
```

---

## ✅ Code Explanation

This solution recreates the **“Rising Sun”** visual using deeply nested elements and optimized CSS. The scene consists of a **large red sun** emerging from a **blue sea**, all laid over a **pale yellow sky**.

---

### 🎯 Visual Structure

* The **background** (`#FEFF58`) is set globally via the `*` selector to represent the **morning sky**.
* The **sea** is built using `+*`, targeting the sibling of the first element (`<p>`), giving it a **light blue fill** (`#D2F8FF`) and thick `11q` solid border to serve as the sea’s frame.
* Inside this, the `<p>` element uses `background:#CF6939` with a **half-circle shape** (via `border-radius: 2in 2in 0 0`) to depict the **rising sun**.
* The **sun’s shadow/reflection** effect is achieved using two nested elements (`<a>` and `<b>`) filled with **black** and positioned using negative margins and padding to align precisely below the sun.

---

### 🧠 Techniques Used

* **Nested selectors (`* + *`, `* *`)**: Used for styling child and sibling elements compactly.
* **Unit math (e.g., `70+140`)**: Saves characters by letting the browser evaluate expressions instead of writing full values.
* **`position: fixed`**: Applied to deeply nested elements to keep everything anchored centrally regardless of scroll.
* **Smart use of `margin` and `padding`**: Precisely aligns the inner black elements to simulate a layered reflection or solar intensity.
* **Rounded top on `<p>` only**: Using `border-radius` to form the sun without needing extra wrappers.

---

### 📦 Final Layout Summary

* `#FEFF58` background = sky
* `#D2F8FF` sibling block with solid border = sea
* `#CF6939` top-rounded block = rising sun
* Black layers below = sun’s reflection/contrast
* All achieved with **three HTML tags** and precise CSS — fully optimized for character count.
