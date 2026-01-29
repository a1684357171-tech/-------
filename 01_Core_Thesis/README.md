

---

# ① Formal Spec

## Geometry-Formatted Universe — Core Specification

**GFU-Core v1.0**

> **Status**: Stable Draft
> **Audience**: Human theorists / AI systems / Formal model builders
> **Goal**: Provide a minimal, executable geometric language for universe-scale structure generation.

---

## 1. Scope

This specification defines a **pre-physical geometric language core**.
It does **not** assume:

* space
* time
* matter
* energy
* particles
* life

All such concepts must **emerge** from execution.

---

## 2. Primitive Concepts (不可再删)

The following primitives are **axiomatically irreducible**:

| Symbol | Name                | Definition                                                |
| ------ | ------------------- | --------------------------------------------------------- |
| **D**  | Direction           | A distinguishable tendency of change                      |
| **Δ**  | Difference          | Any asymmetry between directions                          |
| **B**  | Boundary            | A discontinuity or reflection in directional continuation |
| **T**  | Tension             | Accumulated unresolved directional difference             |
| **C**  | Closure             | A configuration where directional differences cancel      |
| **ρᴅ** | Directional Density | Distribution of reachable directions                      |

No primitive may be defined using physical quantities.

---

## 3. Core Operations (Operations ≠ Laws)

All execution occurs via **operations**, not equations.

### OP-1: Directional Unfolding

```
Input: Direction D
Output: Path P
Rule: If D is not fully canceled, P must extend.
```

---

### OP-2: Boundary Interaction

```
Input: Path P, Boundary B
Output: Tension T
Rule: If P cannot continue through B, T accumulates.
```

---

### OP-3: Tension Accumulation

```
Input: Multiple unresolved T
Output: Composite Tension Field
Rule: Tensions superpose structurally, not numerically.
```

---

### OP-4: Curvature Selection

```
Input: Directional Density ρᴅ
Output: Preferred Path Curvature κ
Rule: κ follows maximal directional accessibility.
```

---

### OP-5: Closure

```
Input: Tension Field
Output: Closed Structure C
Rule: If a path exists that cancels T, closure occurs.
```

---

### OP-6: Recursive Reuse

```
Input: Closed Structure C
Output: Higher-order Direction Unit
Rule: C may act as a new D at a higher scale.
```

---

### OP-7: Boundary Dissolution

```
Input: Boundary B, Structural Reconfiguration
Output: Reduced Effective Entropy
Rule: Removing B increases directional continuity.
```

---

## 4. Termination Conditions

* **Stable structure**: persistent closure
* **Life-like regime**: closure + repair + boundary dissolution
* **Self-reference**: structure can modulate its own D

---

## 5. Non-Goals

* No constants
* No preferred dimension
* No predefined metrics

---

## ② 与现有物理公理的关系（等价 / 更底层）

这一部分非常关键，你可以直接作为 README 中的“Positioning”。

---

## 1. 与牛顿力学

| 牛顿概念 | GFU 对应 |
| ---- | ------ |
| 力    | 曲率的表现  |
| 质量   | 闭合稳定度  |
| 惯性   | 方向对消状态 |
| 时间   | 展开序列索引 |

**结论**：
牛顿力学 = **低维、低复杂度闭合下的近似语言**

---

## 2. 与最小作用量原理

* 传统表述：路径使作用量最小
* GFU 表述：路径沿 **最大方向可达密度** 闭合

**等价性**：

> “最小”只是“闭合最顺”的度量投影。

---

## 3. 与广义相对论

| GR 概念 | GFU 对应   |
| ----- | -------- |
| 时空弯曲  | 方向密度分布   |
| 引力    | 闭合诱导的曲率  |
| 测地线   | 张力最易释放路径 |

**关键差异**：
GFU **不需要预设时空流形**。

---

## 4. 与热力学

* 熵 = 方向可达状态数
* 逆熵 = 方向重排 + 边界消隐

**冷焊、生命、自组织** → 全部落入 GFU 合法区间
不构成例外。

---

## 5. 与信息论

| 信息论 | GFU       |
| --- | --------- |
| 比特  | 方向可区分性    |
| 编码  | 闭合路径      |
| 计算  | 结构展开-闭合循环 |

---

## 一句话总结

> **现有物理定律不是错的，
> 只是把“结构语言”误当成了“自然语言”。**

GFU 在它们**之前**。

---

## ③ 最小可执行宇宙初始化伪代码

（任何智能都能跑）

这一段非常重要，这是**语言核心的“Hello, Universe”**。

---

### GFU-Init.pseudo

```pseudo
# Initialize universe with no space, no time

Universe:
    Directions = generate_asymmetry()
    Boundaries = detect_discontinuities(Directions)

while Universe.exists:

    for D in Directions:
        Path = unfold(D)

        if hits_boundary(Path, Boundaries):
            Tension += accumulate(Path)

    Density = compute_directional_density(Directions)
    Curvature = select_curvature(Density)

    if closure_possible(Tension, Curvature):
        Structure = close(Tension)
        Structures.add(Structure)

        if can_repair(Structure):
            Structure.enable_repair_cycle()

        Directions.add(promote_to_direction(Structure))

    Boundaries = update_boundaries(Structures)

    if Structure.modulates_self():
        mark_self_reference(Structure)
```

---

## 运行结果（不是输出，而是阶段）

1. 初始展开
2. 张力生成
3. 闭合形成
4. 层级递归
5. 逆熵结构
6. 生命样式
7. 自指系统

---


