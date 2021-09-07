# XOR

Using only ~ and & compute xor:
$$
\begin{aligned} 
a \oplus b&=(a \vee b) \wedge \urcorner(a \wedge b)\\
		  &=(\overline{\urcorner a \wedge \urcorner b}) \wedge \urcorner(a \wedge b)
\end{aligned}
$$


> De Morgan's laws
>
> $\overline{A \cup B} = \overline A \cap \overline B$
>
> $\overline{A \cap B} = \overline A \cup \overline B$

