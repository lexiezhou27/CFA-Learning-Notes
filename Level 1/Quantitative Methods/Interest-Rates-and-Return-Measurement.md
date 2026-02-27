# Interest Rates and Return Measurement  利率与回报衡量  

---
 
**LOS 1.a: Interpret interest rates and explain the components of interest rates**   解释利率的含义及其组成部分  

---

### 1️⃣ Three Interpretations of Interest Rates   利率的三种解读方式  

- **Required Rate of Return（必要回报率）**  
  The minimum return I need to feel this investment is worth the risk.

- **Discount Rate（折现率）**  
  The rate I use to turn future money into today's money.

- **Opportunity Cost（机会成本）**  
  The return I give up by choosing this option instead of the second best one.

---

### 2️⃣ Components of Interest Rate  利率的组成要素  

名义利率由真实无风险利率与多项风险溢价组成。

#### 📌 General Formula

$$
\text{Nominal Interest Rate} =
\text{Real Risk-Free Rate}
+ \text{Inflation Premium}
+ \text{Default Risk Premium}
+ \text{Liquidity Premium}
+ \text{Maturity Premium}
$$

---

#### Real Risk-Free Rate（真实无风险利率）

- 理论上的单期贷款利率  
- 假设无通胀且无违约风险  
- 反映投资者的 **Time Preference（时间偏好）**

---

#### Inflation Premium（通胀溢价）

补偿投资者预期未来购买力下降的风险。

> Nominal Risk-Free Rate = Real Risk-Free Rate + Inflation Premium  
> 例如：T-bills（短期国债收益率）

---

#### Default Risk Premium（违约风险溢价）

补偿借款人无法按时偿还本金或利息的风险。

---

#### Liquidity Premium（流动性风险溢价）

补偿资产无法迅速以公平价格变现的风险。

---

#### Maturity Premium（期限风险溢价）

补偿长期债券由于期限较长而面临更大价格波动风险。

---

## LOS 1.b  
**Calculate and interpret different approaches to return measurement**  
计算并解释不同的回报衡量方法  

---

### 1️⃣ Holding Period Return (HPR)  
持有期回报率  

衡量特定持有期间资产价值增长的百分比。

#### 📌 Formula

$$
\text{HPR} =
\frac{\text{Ending Value} - \text{Beginning Value} + \text{Cash Flow}}
{\text{Beginning Value}}
$$

---

#### Multi-Period HPR

$$
HPR_{total} =
[(1+R_1)(1+R_2)(1+R_3)] - 1
$$

---

### 2️⃣ Average Returns  
不同平均回报率方法  

| Type | Formula | Application |
|------|----------|-------------|
| **Arithmetic Mean** | $\frac{\sum R_i}{n}$ | 单期未来回报的无偏估计 |
| **Geometric Mean** | $\left(\prod (1+R_i)\right)^{1/n} - 1$ | 衡量复合增长率 |
| **Harmonic Mean** | $\frac{n}{\sum (1/X_i)}$ | 用于平均成本（如定投） |
| **Trimmed / Winsorized Mean** | Remove or adjust outliers | 减少极端值影响 |

---

### 📌 Professor’s Note

当各期收益率不相等时：

$$
\text{Arithmetic Mean}
>
\text{Geometric Mean}
>
\text{Harmonic Mean}
$$

---
