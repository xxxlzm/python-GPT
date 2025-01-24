以下是图片中出现的公式的LaTeX表示形式：

1. 能量信号与功率信号定义：
   $$
   E = \lim_{a \to \infty} \int_{-a}^{a} |f(t)|^2 \, dt, \quad P = \lim_{a \to \infty} \frac{1}{2a} \int_{-a}^{a} |f(t)|^2 \, dt
   $$

2. 指数函数：
   $$
   f(t) = Ke^{at}
   $$

3. 抽样函数：
   $$
   Sa(t) = \frac{\sin(\pi t)}{\pi t}, \quad Sa(t) = Sa(at), \quad \lim_{a \to 0} Sa(at) = 1, \quad \lim_{a \to \infty} Sa(at) = 0
   $$
   特性：
   $$
   t = k\pi, \, n = 1, 2, 3, 4, \ldots
   $$
   $$
   \int_{-\infty}^{\infty} Sa(t) \, dt = \pi, \quad \int_{0}^{\infty} Sa(t) \, dt = \frac{\pi}{2}
   $$

4. 门函数：
   $$
   f(t) = u\left(t + \frac{\tau}{2}\right) - u\left(t - \frac{\tau}{2}\right) = g_{\tau}(t)
   $$

5. 符号函数：
   $$
   sgn(t) = \begin{cases} 1 & t > 0 \\-1 & t< 0 \end{cases}
   $$
   或
   $$
   sgn(t) = -u(-t) + u(t) = 2u(t) - 1 = \frac{1}{2} \left[ sgn(t) + 1 \right]
   $$

6. 信号的基本运算与基本变换，包括加（减）、乘（除）、微分（积分）