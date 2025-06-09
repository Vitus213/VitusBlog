---
title: Latex语法备忘录
published: 2024-12-29 11:05:00
updated: 2024-12-29 11:05:00
tags: [学习笔记]
description: 不想频繁搜Latex语法，记个属于自己的语法书。
category: EATPOOP
id: latex_use
---

## 希腊字母

```tex
αA \alpha A
β B \beta B
γ Γ \gamma \Gamma
δ Δ \delta \Delta
ϵ ε E \epsilon \varepsilon E
ζ Z \zeta Z
ηH \eta H
θ ϑ Θ \theta \vartheta \Theta
ι I \iota I
κ K \kappa K
λ Λ \lambda \Lambda
μ M \mu M
ν V \nu V
ξ Ξ \xi \Xi
ο O o O
π Π \pi \Pi
ρ ϱ P \rho \varrho P
σ Σ \sigma \Sigma
τ T \tau T
υ Υ \upsilon \Upsilon
ϕ φ Φ \phi \varphi \Phi
χ X \chi X
ψ Ψ \psi \Psi
ω Ω \omega \Omega
```



### 求和符号

在 LaTeX 中，你可以使用 `\sum` 命令插入求和符号。例如，要创建 $\sum_{i=1}^{n} i$（从 1 求和到 n），你可以这样编写：

```
latex $\sum_{i=1}^{n} i$
```

### 积分符号

LaTeX 提供了多种类型的积分符号，如不定积分、定积分、重积分等。以下是一些常见的积分符号示例：

- 不定积分：使用 `\int` 命令，例如 $\int f(x) \, dx$。
- 定积分：使用 `\int_{a}^{b}` 命令，例如 $\int_{a}^{b} f(x) \, dx$。
- 重积分：使用 `\iint` 或 `\iiint` 命令，例如 $\iint_{D} f(x, y) \, dA$。

### 极限符号

要插入极限符号，可以使用 `\lim` 命令。例如，要创建 $\lim_{x \to \infty} f(x)$，你可以这样编写：

```
latex $\lim_{x \to \infty} f(x)$
```

字母上方右箭头
$\mathop{A}\limits ^{\rightarrow}$

```
 \vec{A} 
```

$\vec{A}$

字母上方左箭头

```
$\mathop{A}\limits ^{\leftarrow}$
```

$\mathop{A}\limits ^{\leftarrow}$
