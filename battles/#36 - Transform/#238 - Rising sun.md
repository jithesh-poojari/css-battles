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
