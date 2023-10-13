---
marp: true
theme: mcs
size: 16:9
paginate: true
_paginate: false
style: |
  /* Define a rule to center images */
  img[alt~="center"] {
    display: block;
    margin: 0 auto;
  }
---

<!-- _class: cover  -->
# Marp Template Sample
Ronny Wegener
1\. January 2000

---

<!-- _class: toc  -->
# Index
- Alpha
- Beta
- Gamma
- Delta

---

<!-- _class: chapter  -->
# Chapter
## A Chapter Slide
- Alpha
- Beta
- Gamma
- Delta

---

# Content
## A Content Slide
- **Bold**
- _Italic_
- Normal
- `Code`

---

# Image
![width:640 center](https://images.pexels.com/photos/1640775/pexels-photo-1640775.jpeg?h=720)

---

![bg left:33% blur:2px](https://images.pexels.com/photos/357573/pexels-photo-357573.jpeg?h=720)
# Background
## A Content Slide
- Alpha
- Beta
- Gamma
- Delta

---

# Table
## A Simple Table
|     | Align Left | Align Center | Align Right |
| --- | :--- | :----: | ----: |
| Row | A | 1 | 😀 |
| Row | B | 2 | 😎 |

---

# Code Fence
## C# with Syntax Highlighting
```csharp
public class Cat {
    public string Speak(double volume = 35.0) {
        return volume != 50 ? "meow" : "MEOW";
    }
}
```

---

# Math
## Typesetting
Render formulas $ax^2+bx+c$ inline or as block:

$$ I_{xx}=\int\int_Ry^2f(x,y)\cdot{}dydx $$

$$
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
$$

---

<!-- _class: chapter  -->
# References
## Further Reading
- Better Data Science, _2021-10-07_
  [MARP - Make Presentations with Markdown in VSCode](https://www.youtube.com/watch?v=OmKtuBXNjac)
- Yuki Hattori, _2019-09-16_
  [Marp Basic Example](https://speakerdeck.com/yhatt/marp-basic-example)
- Marp Team, _2022-01-10_
  [Markdown Presentation Ecosystem](https://marp.app)
- Markdown Guide, _2022-01-10_
  [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
- Marp Markdown, _2022-01-28_
  [GitHub README](https://github.com/marp-team/marp-core#marp-markdown)