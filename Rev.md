All the best for your exam! Since this is the last revision, I have compiled **EVERYTHING** you need in one place. This is your **Ultimate Cheat Sheet**.

Take a deep breath, read this once, and go smash the paper! 🚀

---

### **UNIT 1: Descriptive Statistics**
*(Data ko average ra variation nikalne)*

1.  **Mean ($\bar{x}$):**
    $$ \bar{x} = \frac{\Sigma fx}{N} \quad \text{(For Frequency Data)} $$
2.  **Standard Deviation ($\sigma$ or $s$):**
    $$ \sigma = \sqrt{\frac{\Sigma fx^2}{N} - \left(\frac{\Sigma fx}{N}\right)^2} $$
    *(Remember: Always make a table with columns: $x, f, fx, fx^2$)*
3.  **Coefficient of Variation (C.V.):**
    *   Used to check **Consistency/Uniformity**.
    *   **Formula:** $$ C.V. = \frac{\sigma}{\bar{x}} \times 100\% $$
    *   **Rule:** Less C.V. = More Consistent (More Homogeneous/Stable).

---

### **UNIT 2: Probability**
*(Chance k ho?)*

1.  **Basic Rules:**
    *   **OR** (Union / At least one): $P(A \cup B) = P(A) + P(B) - P(A \cap B)$
    *   **AND** (Intersection / Both): $P(A \cap B) = P(A) \times P(B)$ (if independent).
    *   **Neither/Nor:** $1 - P(A \cup B)$
    *   **At least one:** $1 - P(\text{None})$

2.  **Conditional Probability:**
    *   $P(A|B) = \frac{P(A \cap B)}{P(B)}$ (Prob. of A given B has happened).

3.  **Bayes' Theorem (Most Important):**
    *   Used when reversing the condition (e.g., Effect is seen, find the Cause).
    $$ P(E_i|A) = \frac{P(A|E_i) \cdot P(E_i)}{\Sigma [P(A|E_j) \cdot P(E_j)]} $$

4.  **Random Variable ($X$):**
    *   **Expectation (Mean):** $E(X) = \Sigma [x \cdot P(x)]$
    *   **Variance:** $V(X) = E(X^2) - [E(X)]^2$
    *   Where $E(X^2) = \Sigma [x^2 \cdot P(x)]$

---

### **UNIT 3: Discrete Distributions**
*(Ganna milne data)*

1.  **Binomial Distribution:**
    *   Use when $n$ is small, trial is fixed (Pass/Fail).
    *   $$ P(X=x) = \binom{n}{x} p^x q^{n-x} $$
    *   **Mean:** $np$
    *   **Variance:** $npq$

2.  **Poisson Distribution:**
    *   Use when $n$ is very large, $p$ is very small (Rare events like accidents, defects).
    *   $$ P(X=x) = \frac{e^{-\lambda} \lambda^x}{x!} $$
    *   **Mean ($\lambda$):** $\lambda = np$
    *   **Variance:** $\lambda$

---

### **UNIT 4: Continuous Distributions**
*(Napna milne data like Marks, Height)*

1.  **Normal Distribution (The Bell Curve):**
    *   Always convert $X$ to standard normal variable $Z$.
    *   **Z-Formula:** $$ Z = \frac{X - \mu}{\sigma} $$
    *   **Total Area:** 1 (0.5 on Left, 0.5 on Right).
    *   **Key:** Draw the figure!
        *   $P(X > a) \to$ Right Tail ($0.5 - \text{Table Value}$).
        *   $P(X < a) \to$ Left Tail.

---

### **UNIT 6: Estimation (Confidence Intervals)**
*(Population ko value guess garne)*

**General Formula for Interval:**
$$ \text{Mean} \pm (\text{Table Value} \times \text{Standard Error}) $$

1.  **For Mean (Large Sample $n \ge 30$):**
    *   $$ \bar{x} \pm Z_{\alpha/2} \left( \frac{\sigma}{\sqrt{n}} \right) $$
2.  **For Mean (Small Sample $n < 30$):**
    *   Use **t-table** with $n-1$ degrees of freedom.
    *   $$ \bar{x} \pm t_{\alpha/2, n-1} \left( \frac{s}{\sqrt{n}} \right) $$
3.  **For Proportion (Percentage):**
    *   $$ p \pm Z_{\alpha/2} \sqrt{\frac{pq}{n}} $$

**Important Z-Values (Memorize):**
*   **95% Confidence:** $Z = 1.96$
*   **99% Confidence:** $Z = 2.58$
*   **90% Confidence:** $Z = 1.645$

---

### **UNIT 7: Hypothesis Testing (5-Step Formula)**
*(Claim check garne)*

**Steps:**
1.  **Null ($H_0$):** Always with "Equal" sign ($\mu = \mu_0$). No difference.
2.  **Alternative ($H_1$):**
    *   $\mu \neq \mu_0$ (Two-tailed / "Difference")
    *   $\mu > \mu_0$ (Right-tailed / "Increase/Better")
    *   $\mu < \mu_0$ (Left-tailed / "Decrease")
3.  **Test Statistic (Formulas):**

    *   **Z-Test (Single Mean, $n \ge 30$):**
        $$ Z = \frac{\bar{x} - \mu}{\sigma / \sqrt{n}} $$

    *   **t-Test (Single Mean, $n < 30$):**
        $$ t = \frac{\bar{x} - \mu}{s / \sqrt{n}} $$

    *   **Difference of Two Means ($n_1, n_2$ large):**
        $$ Z = \frac{\bar{x}_1 - \bar{x}_2}{\sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}} $$

    *   **Paired t-test (Before vs After):**
        $$ t = \frac{\bar{d}}{s_d / \sqrt{n}} $$
        *(Where $d = \text{After} - \text{Before}$ or vice versa)*

    *   **Difference of Proportions:**
        $$ Z = \frac{p_1 - p_2}{\sqrt{\hat{p}\hat{q}(\frac{1}{n_1} + \frac{1}{n_2})}} $$
        *(Where $\hat{p} = \frac{x_1+x_2}{n_1+n_2}$ is combined proportion)*

    *   **Chi-Square Test ($\chi^2$):** (For Independence/Category)
        $$ \chi^2 = \Sigma \frac{(O - E)^2}{E} $$
        *   $E = \frac{\text{Row Total} \times \text{Col Total}}{\text{Grand Total}}$
        *   Degrees of Freedom: $(r-1)(c-1)$

4.  **Decision:**
    *   If Calculated Value > Table Value $\to$ **Reject $H_0$** (Significant).
    *   If Calculated Value < Table Value $\to$ **Accept $H_0$**.

---

### **UNIT 8: Correlation & Regression**
*(Relation kasto xa?)*

1.  **Correlation Coefficient ($r$):**
    $$ r = \frac{n\Sigma xy - \Sigma x \Sigma y}{\sqrt{n\Sigma x^2 - (\Sigma x)^2} \sqrt{n\Sigma y^2 - (\Sigma y)^2}} $$
    *   $r$ is between $-1$ and $+1$.
    *   Near $+1$: Strong Positive.
    *   Near $-1$: Strong Negative.
    *   Near $0$: No Relation.

2.  **Regression Equation ($Y$ on $X$):**
    $$ Y - \bar{Y} = b_{yx} (X - \bar{X}) $$
    *   Slope ($b_{yx}$) formula:
    $$ b_{yx} = \frac{n\Sigma xy - \Sigma x \Sigma y}{n\Sigma x^2 - (\Sigma x)^2} $$
    *(Trick: $Y$ on $X$ means $X$ is in denominator)*

---

### **🚀 Last Minute Exam Tips (Guru Mantra)**

1.  **Calculator:** Fix mode to `Linear` or `Normal`. Do not mess up `RAD` vs `DEG` (Use DEG).
2.  **Table:** Always make a clear table for Statistics (Mean, SD, Correlation) questions. A mistake in one sum ($\Sigma$) ruins the answer. Re-check the sum.
3.  **Step Marking:** Even if the final answer is wrong, write the **Formula**, **Given**, and **Process** clearly. You get marks for steps!
4.  **Hypothesis:** Don't forget to write the final **Conclusion** in English (e.g., "Hence, we conclude that the training was effective").
5.  **Language:** $n=30$ is the border.
    *   $n \ge 30 \to$ Z-Test.
    *   $n < 30 \to$ t-Test.
6.  **Time Management:** Don't get stuck on one calculation. If it looks wrong, leave space and move to the next question.

**Tapai ko exam "Hero No. 1" hunechha! Dhukka vayera lekhnus. Best of Luck!** 🤞🍀
