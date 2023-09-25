---
marp: true
theme: uncover
# Invert the colors
class: invert
# convert to formulas - can also use katex(style)
math: mathjax 
# show slide numbers
paginate: true
# Can use custom css/html to manipulate the slides
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
---

# <!--fit--> An Intro to Marp :rocket:

<span style="color:grey">By:</span> Max Ekstedt

---

## Slide Header

* Use Markdown to write slides!
* This is a bullet point that is fragmented
  * This is a sub-bullet point

---

## Some form of topic

- This bulletpoint is not fragmented
- So this bulletpoint will show up at the same time as the previous one

---

## :snake: Code! :computer:

<div class="columns">
<div>
<h3>Python<h3>

```python
def main():
    print("Hello World!")

def markdown():
    isCool = True
    if isCool:
        print("Markdown is cool!")
    else:
        print("Markdown is not cool :(")
```
</div>
<div>

<h3>JavaScript<h3>

```javascript
function main() {
    console.log("Hello World!");
}

function markdown() {
    let isCool = true;
    if (isCool) {
        console.log("Markdown is cool!");
    } else {
        console.log("Markdown is not cool :(");
    }
}
```
</div>

---

## Math! :mortar_board:

A single line expression: 

$e^{i\pi} + 1 = 0$

OR, a multi-line expression:

$$
\begin{align}
\frac{d}{dx} \left( \int_{0}^{x} f(u)\,du\right) &= f(x) \\
\frac{d}{dx} \left( \int_{a(x)}^{b(x)} f(u,v)\,du\right) &= f(b(x),x) b'(x) - f(a(x),x) a'(x) + \int_{a(x)}^{b(x)} \frac{\partial}{\partial x} f(u,v)\,du
\end{align}

$$

---

## Images!

![height:4in](https://raw.githubusercontent.com/marp-team/marp/master/marp.png)

---

## Image and Text side by side!

![bg left height:2in](https://raw.githubusercontent.com/marp-team/marp/master/marp.png)

* Image on the left
* Text on the right

---
<!--_color: red-->
<!--_backgroundColor: black-->
# <!--fit -->HUGE

---

## Two text columns! :+1:

<div class="columns">
<div>

* Left column
* Left column
* Left column

</div>

<div>

* Right column
* Right column
* Right column

</div>
</div>
