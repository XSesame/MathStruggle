# 运算符

- 乘号 - `\times` - $\times$   `\cdot` - $\cdot$   除号 - `\div` - $\div$   斜杠 `/`

- 不等于 -  `\neq` - $\neq$   小于等于 - `\leq` - $\leq$    大于等于 -  `\geq` - $\geq$   

- 约等于 -  `\approx` - $\approx$   加减号: `\pm` - $\pm$   同构 - `\cong` - $\cong$

- 因此 - `\therefore` - $\therefore$   因为 -  `\because` - $\because$

# 希腊字母

- 大写的希腊字母 `A`, `B`, `E`, `Z`, `H`, `I`, `K`, `M`, `N`, `O`, `P`, `T`, `X`  就是英文本身。

- `\alpha` - $\alpha$   `\beta` - $\beta$   `\gamma` - $\gamma$   `\delta` - $\delta$   `\epsilon` - $\epsilon$   `\zeta` - $\zeta$

- `\eta` - $\eta$     `\theta` - $\theta$   `\iota` - $\iota$    `\kappa` - $\kappa$   `\lambda` - $\lambda$    `\mu` - $\mu$

- `\nu` - $\nu$    `\xi` - $\xi$   `o` - $o$   `\pi` - $\pi$   `\rho` - $\rho$   `\sigma` - $\sigma$

- `\tau` - $\tau$   `\upsilon` - $\upsilon$    `\phi` - $\phi$   `\chi` - $\chi$   `\psi` - $\psi$   `\omega` - $\omega$

- `\Gamma` - $\Gamma$   `\Delta` - $\Delta$   `\Theta` - $\Theta$   `\Lambda` - $\Lambda$   `\Xi` - $\Xi$  `\Pi` - $\Pi$

- `\Sigma` - $\Sigma$   `\Upsilon` - $\Upsilon$   `\Phi` - $\Phi$   `\Psi` - $\Psi$   `\Omega` - $\Omega$

# 集合

- 属于 - `\in` - $\in$   不属于 - `\notin` - $\notin$

- 包含于 - `\subset` - $\subset$   包含 -  `\supset` - $\supset$

- 交集 - `\cap` - $\cap$  并集 - `\cup` - $\cup$    空集 - `\varthing`  -  $\varnothing$

# 逻辑符号

- 且: `\land` - $\land$    或: `\lor` - $\lor$   非: `\neg` - $\neg$

- 如果...那么: `\Rightarrow` - $\Rightarrow$   当且仅当: `\Leftrightarrow` - $\Leftrightarrow$

# 微积分和导数

- 极限 - `\lim` - $\lim$  无穷大 - `\infty` - $\infty$ 导数 - `\prime` - $\prime$   偏导数 - `\partial` - $\partial$

- 积分 - `\int` - $\int$   双重积分 - `\iint` - $\iint$   三重积分 - `\iiint` - $\iiint$

# 重音符号

- 单位向量 - `\hat{a}` - $\hat{a}$   向量 `\vec{a}` - $\vec{a}$   变量的估计值或变换 `\tilde{a}` - $\tilde{a}$

- `\bar{a}` - $\bar{a}$    `\acute{a}` - $\acute{a}$   `\breve{a}`  - $\breve{a}$  `\grave{a}` - $\grave{a}$   

- 平均值 - `\bar{a}` - $\bar{a}$    导数 - `\dot{a}` - $\dot{a}$   二阶导数 - `\ddot{a}` - $\ddot{a}$

- 宽帽子 - `\widehat{abc}` - $\widehat{abc}$    宽波浪线 - `\widetilde{abc}` - $\widetilde{abc}$

- `\mathring{a}` - $\mathring{a}$

# 图形符号

- 角度: `\angle` - $\angle$    圆: `\circ` - $\circ$   

- 平行: `\parallel` - $\parallel$    垂直: `\perp` - $\perp$

- 三角形: `\triangle` - $\triangle$   三角形（倒置）: `\triangledown` - $\triangledown$  正方形: `\square` - $\square$

- 上: `\uparrow` - $\uparrow$  下: `\downarrow` - $\downarrow$   左: `\leftarrow` - $\leftarrow$ 右: `\rightarrow` - $\rightarrow$

- 左右: `\leftrightarrow` - $\leftrightarrow$  

# 线性代数

- 向量 - `\mathbf{v}` - $\mathbf{v}$   `\vec{v}`  -  $\vec{v}$

- 矩阵 - 使用 `amsmath` 包中的 `matrix` 环境来表示：

$$\begin{matrix}
   a & b \\
   c & d \\
   \end{matrix}$$

```latex
   \begin{matrix}
   a & b \\
   c & d \\
   \end{matrix}
   ```

- **增广矩阵**：使用 `array` 环境：

$$\left[\begin{array}{cc|c}
   1 & 2 & 3 \\
   4 & 5 & 6 \\
   \end{array}\right]$$

 ```latex
   \left[\begin{array}{cc|c}
   1 & 2 & 3 \\
   4 & 5 & 6 \\
   \end{array}\right]
   ```

- **行列式**：使用 `det` 环境：

$$\begin{vmatrix}
   a & b \\
   c & d \\
   \end{vmatrix}$$

 ```latex
   \begin{vmatrix}
   a & b \\
   c & d \\
   \end{vmatrix}
   ```

- 转置矩阵：`\mathbf{A}^T`  -  $\mathbf{A}^T$   `\mathbf{A}^{\top}`  - $\mathbf{A}^{\top}$

- 逆矩阵：`\mathbf{A}^{-1}` 生成 $\mathbf{A}^{-1}$

- 线性方程组：使用 `align` 或 `array` 环境：

$$\begin{align}
   x + y &= 1 \\
   2x - y &= 3
   \end{align}$$

```latex
   \begin{align}
   x + y &= 1 \\
   2x - y &= 3
   \end{align}
   ```

- **特征值和特征向量**：
	- 特征值：`\lambda` 生成 $\lambda$
	- 特征向量：`\mathbf{v}` 生成 $\mathbf{v}$
	- 特征方程：`A\mathbf{v} = \lambda\mathbf{v}` 生成 $A\mathbf{v} = \lambda\mathbf{v}$


- **迹（Trace）**：`\text{tr}(\mathbf{A})` 生成 $\text{tr}(\mathbf{A})$

-  **范数（Norm）**：`\|\mathbf{v}\|` 生成 $\|\mathbf{v}\|$