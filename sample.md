---
marp: true
math: mathjax
paginate: true
theme: class
---

<!-- _paginate: false -->

# 授業を代表する見出し

- 学年科目名
- 年-月-日

---

## 見出し2 (H2)

セクションの見出しに使います。本文テキストはここに書きます。

---

### 見出し3 (H3)

小見出しとして使います。

本文テキストが続きます。複数の段落も書けます。

---

## 箇条書き (深さ 1)

- 項目 A
- 項目 B
- 項目 C

---

## 箇条書き (深さ 2)

- 項目 A
  - 子項目 A-1
  - 子項目 A-2
- 項目 B
  - 子項目 B-1

---

## 箇条書き (深さ 3)

- 項目 A
  - 子項目 A-1
    - 孫項目 A-1-a
    - 孫項目 A-1-b
  - 子項目 A-2
- 項目 B
  - 子項目 B-1
    - 孫項目 B-1-a

---

## 数式 (インライン)

質量とエネルギーの等価性 $E = mc^2$ はアインシュタインが導きました。

正規分布の確率密度関数は $f(x) = \dfrac{1}{\sqrt{2\pi}\sigma} \exp\!\left(-\dfrac{(x-\mu)^2}{2\sigma^2}\right)$ です。

---

## 数式 (ブロック)

ベイズの定理：

$$
P(A \mid B) = \frac{P(B \mid A)\, P(A)}{P(B)}
$$

---

## 数式 (ブロック) — 複数行

マクスウェル方程式：

$$
\begin{aligned}
\nabla \cdot \mathbf{E} &= \frac{\rho}{\varepsilon_0} \\
\nabla \cdot \mathbf{B} &= 0 \\
\nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
\nabla \times \mathbf{B} &= \mu_0 \mathbf{J} + \mu_0\varepsilon_0 \frac{\partial \mathbf{E}}{\partial t}
\end{aligned}
$$

---

## 箇条書き＋数式の組み合わせ

- 平均：$\mu = \dfrac{1}{n}\sum_{i=1}^{n} x_i$
- 分散：$\sigma^2 = \dfrac{1}{n}\sum_{i=1}^{n}(x_i - \mu)^2$
  - 標準偏差は $\sigma = \sqrt{\sigma^2}$
    - 単位は元データと同じになる

---

## 画像 (単体)

![](./images/ms.png)

---

## 画像 (右半分)

![bg right:50% contain](./images/ms.png)

左半分にテキストを書きます。

- 箇条書きも入ります
- 図の説明など

---

## 画像 (2カラム, 1:1)

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; align-items: start;">
<div>

左カラムにテキストを書きます。

- 箇条書きも入ります
- 図の説明など

</div>
<div>

![w:100%](./images/ms.png)

</div>
</div>

---

## 画像 (2カラム, 2:1)

<div style="display: grid; grid-template-columns: 2fr 1fr; gap: 20px; align-items: start;">
<div>

左カラムにテキストを書きます。

- 箇条書きも入ります
- 図の説明など

</div>
<div>

![w:100%](./images/ms.png)

</div>
</div>

---

# まとめ

- **H1 〜 H3** の見出し
- 深さ **3** までの箇条書き
- インライン数式とブロック数式
