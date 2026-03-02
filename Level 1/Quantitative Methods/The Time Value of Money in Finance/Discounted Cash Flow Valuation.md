# Discounted Cash Flow Valuation

---

## 1️⃣ Fundamental PV Formulas
The relationship between present and future values can be demonstrated as:
* **Future Value (FV):**
  $$FV = PV(1+r)^t$$
* **Present Value (PV):**
  $$PV = \frac{FV}{(1+r)^t} = FV(1+r)^{-t}$$

 **Note:**
 * $r$ = interest rate per compounding period.
 * $t$ = numbers of compounding periods.

#### Continuous Compounding (连续复利)
If we are using continuous compounding, then:

* **Future Value:** $$FV = PV \times e^{rt}$$
* **Present Value:** $$PV = FV \times e^{-rt}$$

---

## 2️⃣ Fixed-Income Securities 固定收益证券
Fixed-income securities provide a stream of predetermined future cash flows.

### 1. Zero-Coupon Bonds 零息债券
Zero-coupon bonds pay no interest and are issued at a discount to their face value.

$$PV = \frac{FV}{(1+r)^t}$$

### 2. Coupon-Paying Bonds 付息债券
The value is the sum of the present value of all future coupon payments plus the present value of the face value paid at maturity.

$$\text{Bond Value} = \frac{FV}{(1+r)^n} + \sum_{t=1}^{n} \frac{PMT}{(1+r)^t}$$

 **Note:** 
 * $PMT$ is the coupon payment.

### 3. Perpetuities 永续年金
Perpetuities are financial instruments that promise to pay a fixed amount forever.

$$\text{PV of a perpetuity} = \frac{\text{payment}}{r}$$

### 4. Amortizing Bonds 摊销债券
An amortizing bond is one that pays a level amount each period, including its maturity period.

$$\text{annuity payment} = \frac{r \times PV}{1 - (1+r)^{-t}}$$

 **Note:** 
 * $r$ is the interest rate per period
 * $t$ is the number of periods
 * $PV$ is the present value (principal)
   
---

## 3️⃣ Equity Securities 权益证券
Unlike bonds, equity cash flows (dividends) are often expected to grow over time.

### 1. Preferred Stock 优先股
Preferred stock pays a fixed dividend that is stated as a percentage of its par value.

$$\text{preferred stock value} = \frac{D_p}{K_p}$$

 **Note:** 
 * $D_p$ is the dividend per period.
 * $K_p$ is the market's required return on the preferred stock.

### 2. Common Stock 普通股
#### (1) Gordon Growth Model (GGM) 戈登增长模型
GGM is used for stocks where dividends are expected to grow at a constant rate forever.

$$V_0 = \frac{D_1}{k_e - g_c}$$

 **Note:**
 * $V_0$ is the value of a share this period.
 * $D_1$ is the dividend expected to be paid next period ($D_1 = D_0(1+g_c)$).
 * $k_e$ is the required return on common equity.
 * $g_c$ is the constant growth rate of dividends.

#### (2) Multistage Dividend Discount Model (DDM)
DDM is used for companies experiencing a period of high/unstable growth before reaching a mature, constant growth phase.

**Steps:**
1. Forecast and discount each individual dividend during high-growth period.
2. Calculate the **Terminal Value** at the point where constant growth begins using GGM.
3. Discount the Terminal Value back to present.
4. Sum all present values.
