The goal is to express the angle $\chi$ in such a way that it is not dependent on unknown angles. In particular, we need to get rid of the angle $\Gamma$ used in intermediate calculations.

Step 1: Analyze the triangles, verify identities like $\sin{(\chi + \chi')}=1$ and $\chi + \chi' = \frac{\pi}{2}$, which reiterate the convention of the model where $\xi = \alpha + \beta$ and the fact that the enveloping triangle is isosceles.

Step 2: Use the sine rule to find $\sin{\chi}$ in the larger triangle.

$$
\sin{\chi} = \frac{\sin{\alpha} \sin{\varphi}}{\sin{\Gamma}}
$$

Step 3: Use the cosine rule for sides to find $\cos{\alpha}$. Then get an expression for $\cos{\chi}$.

$$
\begin{align*}
\cos{\alpha} &= \cos{\xi} \cos{\Gamma} + \sin{\xi} \sin{\Gamma} \cos{\chi}\\\\
\cos{\chi} &= \frac{\cos{\alpha} - \cos{\xi} \cos{\Gamma}}{\sin{\xi} \sin{\Gamma}}
\end{align*}
$$

Step 4: Divide $\sin{\chi}$ by $\cos{\chi}$ to get $\tan{\chi}$.

$$
\tan{\chi} = \frac{\sin{\alpha} \sin{\varphi} \sin{\xi}}{\cos{\alpha} - \cos{\xi} \cos{\Gamma}}
$$

Step 5: Use the cosine rule for sides on the larger triangle to find an expression for $\cos{\Gamma}$.

$$
\cos{\Gamma} = \cos{\alpha} \cos{\xi} + \sin{\alpha} \sin{\xi} \cos{\varphi}
$$

Step 6: Substitute $\cos{\Gamma}$ and simplify.

$$
\begin{align*}
\tan{\chi} &= \frac{\sin{\alpha} \sin{\varphi} \sin{\xi}}{\cos{\alpha} - \cos{\xi} \cos{\Gamma}}\\\\
&= \frac{\sin{\alpha} \sin{\varphi} \sin{\xi}}{\cos{\alpha} \sin^2{\xi} - \sin{\alpha} \cos{\varphi} \sin{\xi} \cos{\xi}}\\\\
\tan{\chi} &= \frac{\sin{\alpha} \sin{\varphi}}{\cos{\alpha} \sin{\xi} - \sin{\alpha} \cos{\varphi} \cos{\xi}}\\\\
\end{align*}
$$
