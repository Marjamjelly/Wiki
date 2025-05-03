# My Wiki
I am proud to announce I will soon be releasing my own wiki! Yay!


\documentclass{article}
\usepackage{amsmath}

\begin{document}

\section*{False Proof: $3.5 = 4$ via Integration (Incorrect Reasoning)}

Let \( f(x) = x \) for \( x \in [3.5, 4] \).

We compute the definite integral:
\[
\int_{3.5}^{4} f(x) \, dx = \int_{3.5}^{4} x \, dx = \left[ \frac{x^2}{2} \right]_{3.5}^{4}
= \frac{4^2}{2} - \frac{3.5^2}{2} = \frac{16}{2} - \frac{12.25}{2} = 8 - 6.125 = 1.875
\]

By the Mean Value Theorem for integrals, there exists a \( c \in [3.5, 4] \) such that:
\[
f(c) (4 - 3.5) = 1.875
\quad \Rightarrow \quad f(c) \cdot 0.5 = 1.875
\quad \Rightarrow \quad f(c) = \frac{1.875}{0.5} = 3.75
\]

Now make the (false) argument: Since \( c \approx 3.75 \) and \( f(c) \approx 3.75 \), we must have \( 3.75 \approx 4 \), and therefore:
\[
\boxed{3.5 = 4}
\]

\textbf{Fallacy:} The Mean Value Theorem only guarantees the \emph{existence} of some \( c \) in the interval—not that either endpoint equals the mean value. Additionally, rounding from \( 3.75 \approx 4 \) to \( 3.5 = 4 \) is completely unjustified.

\end{document}
