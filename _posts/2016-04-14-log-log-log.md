---
title: Log Log Log
---

\\[
\\begin{align}
K^2! &= \\sqrt{\\frac{\\log n}{\\log \\log n}}^2!\\\\\\\\
&= \\frac{\\log n}{\\log \\log n}!\\\\\\\\
\\lim\_{K^2 \\to \\infty} K^2! &= \\sqrt{2\\pi \\frac{\\log n}{\\log \\log n}}
\\left( \\frac{\\frac{\\log n}{\\log \\log n}}{e}\\right)^\\frac{\\log n}{\\log \\log
n}\\\\\\\\
\\lim\_{n \\to \\infty} K^2! &= \\sqrt{2\\pi \\frac{\\log n}{\\log \\log n}}
\\left( \\frac{\\frac{\\log n}{\\log \\log n}}{e}\\right)^\\frac{\\log n}{\\log \\log
n}\\\\\\\\
&= \\sqrt{2\\pi \\frac{\\log n}{\\log \\log n}}
\\left( \\frac{\\log n}{e \\log \\log n}\\right)^\\frac{\\log n}{\\log \\log n}\\\\\\\\
&= \\sqrt{2\\pi \\frac{\\log n}{\\log \\log n}}
\\frac{2^{\\log \\log n\\frac{\\log n}{\\log \\log n}}}{2^{\\log \\log \\log n\\frac{\\log n}{\\log \\log n}}
2^{\\log e\\frac{\\log n}{\\log \\log n}}
}\\\\\\\\
&= \\sqrt{2\\pi \\frac{\\log n}{\\log \\log n}}
\\frac{n}{n^{\\frac{\\log \\log \\log n}{\\log \\log n}}
n^{\\frac{\\log e}{\\log \\log n}}
}\\\\\\\\
&= \\sqrt{2\\pi \\frac{2^{\\log \\log n}}{2^{\\log \\log \\log n}}}
\\frac{n}{n^{\\frac{\\log \\log \\log n}{\\log \\log n}}
n^{\\frac{\\log e}{\\log \\log n}}
}\\\\\\\\
&= \\sqrt{2\\pi \\frac{n^{\\frac{\\log \\log n}{\\log n}}}{n^{\\frac{\\log \\log \\log
n}{\\log n}}}}
\\frac{n}{n^{\\frac{\\log \\log \\log n}{\\log \\log n}}
n^{\\frac{\\log e}{\\log \\log n}}
}\\\\\\\\
&= \\sqrt{2\\pi} \\frac{n^{\\frac{\\log \\log n}{2\\log n}}}{n^{\\frac{\\log \\log \\log
n}{2\\log n}}}
\\frac{n}{n^{\\frac{\\log \\log \\log n}{\\log \\log n}}
n^{\\frac{\\log e}{\\log \\log n}}
}\\\\\\\\
&= \\sqrt{2\\pi} \\frac{n^{\\frac{\\log \\log n}{2\\log n}}}{n^{\\frac{\\log \\log \\log
n}{2\\log n}}}
\\frac{n}{n^{\\frac{\\log \\log \\log n + \\log e}{\\log \\log n}}
}\\\\\\\\
&= \\sqrt{2\\pi} \\frac{n^{\\frac{(\\log \\log n)^2}{2\\log n\\log\\log
n}}}{n^{\\frac{\\log \\log n \\log
\\log \\log n}{2\\log n \\log \\log n}}}
\\frac{n}{n^{\\frac{2 \\log n \\log \\log \\log n + 2 \\log n \\log e}{2\\log n \\log \\log n}}
}\\\\\\\\
&= \\sqrt{2\\pi}
\\frac{n}{n^{\\frac{2 \\log e \\log n + 2 \\log n \\log \\log \\log n + \\log \\log n
\\log \\log \\log n - (\\log \\log n)^2}{2\\log n \\log \\log n}}
}\\\\\\\\
&= \\sqrt{2\\pi}
\\frac{n}{n^{\\frac{2 \\log n \\log \\log \\log n}{2\\log n \\log \\log n}}
}\\\\\\\\
&= \\sqrt{2\\pi}
\\frac{n}{n^{\\frac{\\log \\log \\log n}{\\log \\log n}}
}\\\\\\\\
&= \\sqrt{2\\pi} n^{1 - \\frac{\\log \\log \\log n}{\\log \\log n}}\\\\\\\\
&= O(n)
\\end{align}
\\]