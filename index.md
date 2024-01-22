<script>
  MathJax = {
    tex: {
      inlineMath: [['$', '$']],
      displayMath: [['$$', '$$'], ['\[', '\]']]
    },
    startup: {
      ready: () => {
        MathJax.startup.defaultReady();
        document.getElementById('MathJax-script').remove();
      }
    }
  };
</script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js">
</script>


<link rel="shortcut icon" type="image/x-icon" href="/favicon.ico">

Trans rights are human rights! niko83c

Testing preview $1 + 2 = 4$

\[
  \\{\pi \cdot e, \pi + e\\} \cap (\mathbb R \setminus \mathbb Q) \ne \emptyset  
\]


$$
\pi_1(X_1 \times X_2, (x_1,x_2)) \cong \pi_1(X_1,x_1) \times \pi_1(X_2,x_2)
$$

$$
a^2 + b^2 = c^2
$$

$$
\begin{align*}
3x - 2y &= 5 \\
2x + 3y &= 10
\end{align*}
$$

$$
\pi = \frac1{\frac1\pi}
$$

This is some in-line math: because it is true that $1 + 1$ indeed does equal $2$.

For let $S \colon \mathbb N \to \mathbb N$ be the successor function, then $1 + 1 = 1 + S(0) = S(1 + 0) = S(1) = 2$.
