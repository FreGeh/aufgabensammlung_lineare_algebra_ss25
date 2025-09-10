1-1, 3-1, 4-2, 7-1, 8-2, 10-2, 11-1, 11-2, 12-1, 12-3, 13-2

# ÜB1-A1 (Aufgabe 1)
![[Pasted image 20250906124543.png]]
![[Pasted image 20250906124741.png]]![[Pasted image 20250906124748.png]]
# ÜB3-A1 (Aufgabe 2)
![[Pasted image 20250906124812.png]]
$$A=\begin{pmatrix}
-3 & -6 & 0 & -1 & 3 \\
1 & 3 & 2  & -3 & -5 \\
0 & -1 & -2&4&5 \\
0&-3&-6&6&6 \\
0&2&4&-4&-4
\end{pmatrix}$$
$$A^2=\begin{pmatrix}
3 & 9 & 6 & 3 & 3 \\
0 & 0 & 0  & 0 & 0 \\
-1 & -3 & -2&-1&-1 \\
-3&-9&-6&-3&-3 \\
2&6&4&2&2
\end{pmatrix}$$
$$A^3=0$$
$$\ker(A^2)=\ker \begin{pmatrix}
1 & 3 & 2 & 1 & 1
\end{pmatrix}=\left< \begin{pmatrix}
-3 \\
1 \\
0 \\
0 \\
0
\end{pmatrix}, \begin{pmatrix}
-2 \\
0 \\
1 \\
0 \\
0
\end{pmatrix}, \begin{pmatrix}
-1 \\
0 \\
0 \\
1 \\
0
\end{pmatrix}, \begin{pmatrix}
-1 \\
0 \\
0 \\
0 \\
1
\end{pmatrix} \right> $$

$$\ker(A)=\begin{pmatrix}
1 &0&-4&0&-\frac{7}{2} \\
0&1&2&0&1 \\
0&0&0&1& \frac{3}{2} \\
0&0&0&0&0 \\
0&0&0&0&0
\end{pmatrix}=\left< \begin{pmatrix}
-4 \\
-2 \\
1 \\
0 \\
0
\end{pmatrix}, \begin{pmatrix}
\frac{7}{2} \\
-1 \\
0 \\
-\frac{3}{2} \\
1
\end{pmatrix} \right> = \left< \begin{pmatrix}
-4 \\
-2 \\
1 \\
0 \\
0
\end{pmatrix}, \begin{pmatrix}
7 \\
-2 \\
0 \\
-3 \\
2
\end{pmatrix} \right>$$
$$u_{3}=\mathbb{R}^5, u_{2}=\left< \begin{pmatrix}
-3 \\
1 \\
0 \\
0 \\
0
\end{pmatrix}, \begin{pmatrix}
-2 \\
0 \\
1 \\
0 \\
0
\end{pmatrix}, \begin{pmatrix}
-1 \\
0 \\
0 \\
1 \\
0
\end{pmatrix}, \begin{pmatrix}
-1 \\
0 \\
0 \\
0 \\
1
\end{pmatrix} \right>, u_{1}=\left< \begin{pmatrix}
-4 \\
-2 \\
1 \\
0 \\
0
\end{pmatrix}, \begin{pmatrix}
7 \\
-2 \\
0 \\
-3 \\
2
\end{pmatrix} \right>$$
$$w_{3}=e_{1}$$
$$A \cdot w_{3}= \left< \begin{pmatrix}
-3 \\
1 \\
0 \\
0 \\
0
\end{pmatrix} \right> $$
$$u_{2}= u_{1} \oplus \left<  \begin{pmatrix}
-3 \\
1 \\
0 \\
0 \\
0
\end{pmatrix}, \begin{pmatrix}
-1 \\
0 \\
0 \\
1 \\
0
\end{pmatrix}\right> $$
$$\mathbb{R}^5=\ker(A^2)\oplus \langle e_1\rangle$$

$$A e_1=\begin{pmatrix}-3\\[2pt]1\\[2pt]0\\[2pt]0\\[2pt]0\end{pmatrix}$$

$$\ker(A^2)=\ker(A)\oplus \langle A e_1\rangle \oplus \left\langle 
\begin{pmatrix}-1\\[2pt]0\\[2pt]0\\[2pt]0\\[2pt]1\end{pmatrix}\right\rangle$$

$$
\begin{pmatrix}
4&7&-3&-1\\
-2&-2&1&0\\
1&0&0&0\\
0&-3&0&0\\
0&2&0&1
\end{pmatrix}
\;\longrightarrow\;
\begin{pmatrix}
0&7&-3&-1\\
0&-2&1&0\\
1&0&0&0\\
0&-3&0&0\\
0&2&0&1
\end{pmatrix}
\;\sim\;
\begin{pmatrix}
0&0&-3&-1\\
0&0&1&0\\
1&0&0&0\\
0&1&0&0\\
0&0&0&1
\end{pmatrix}
\;\sim\;
\begin{pmatrix}
0&0&0&0\\
0&0&1&0\\
1&0&0&0\\
0&1&0&0\\
0&0&0&1
\end{pmatrix}
$$
hat Rang 4!
$$\ker(A)=\langle A^2 e_1\rangle \oplus \left\langle A\begin{pmatrix}-1\\0\\0\\0\\1\end{pmatrix}\right\rangle$$

$$
A\begin{pmatrix}-1\\0\\0\\0\\1\end{pmatrix}
=
\begin{pmatrix}6\\-6\\5\\6\\-4\end{pmatrix}
=
(-2)\begin{pmatrix}7\\-2\\0\\-3\\2\end{pmatrix}
+5\begin{pmatrix}4\\-2\\1\\0\\0\end{pmatrix}
$$

$$
S=\Bigl(\,e_1\;\big|\;A e_1\;\big|\;A^2 e_1\;\big|\;
\begin{pmatrix}1\\0\\0\\0\\1\end{pmatrix}\;\big|\;
\begin{pmatrix}6\\-6\\5\\6\\-4\end{pmatrix}\Bigr)
=
\begin{pmatrix}
1&-3&3&-1&6\\
0&1&0&0&-6\\
0&0&-1&0&5\\
0&0&-3&0&6\\
0&0&2&1&-4
\end{pmatrix}
$$

# ÜB4-A2 (Aufgabe 3)
![[Pasted image 20250906130810.png]]
![[Pasted image 20250906130827.png]]
![[Pasted image 20250906130833.png]]

# ÜB7-A1 (Aufgabe 4)
![[Pasted image 20250906130937.png]]

Lösung:
a)
Wir führen Gram-Schmidt durch mit den Vektoren:
$$c_{1}=\begin{pmatrix}
0 \\
0 \\
1 \\
0 \\
0
\end{pmatrix},c_{2}=\begin{pmatrix}
1 \\
0 \\
1 \\
0 \\
0
\end{pmatrix},c_{3}=\begin{pmatrix}
2\\
1 \\
1 \\
0 \\
2
\end{pmatrix},c_{4}=\begin{pmatrix}
2 \\
1 \\
0 \\
2 \\
3
\end{pmatrix}$$
Also
$$b_{1}=c_{1}$$
$$b_{2}=c_{2}-\left< b_{1},c_{2} \right> b_{1}=e_{1}$$
$$b_{3}=c_{3}-\left< c_{3},b_{1} \right>b_{1}-\left< c_{3},b_{2} \right>b_{2} =\begin{pmatrix}
0 \\
1 \\
0 \\
0 \\
2
\end{pmatrix} $$ wobei $||b_{3}||=\sqrt{ 5 }$

$$b_{4}=c_{4}-\left< c_{4},b_{1} \right>b_{1} -\left< c_{4},b_{2} \right>b_{2} - \frac{\left<c_{4},b_{3}\right>}{5}b_{3}=\begin{pmatrix}
0 \\
1 \\
0 \\
2 \\
3
\end{pmatrix}- \frac{ \left<\begin{pmatrix}
2 \\
1 \\
0 \\
2 \\
3
\end{pmatrix},\begin{pmatrix}
0 \\
1 \\
0 \\
0 \\
2
\end{pmatrix} \right>}{5}b_{3}=\begin{pmatrix}
0 \\
1 \\
0 \\
2 \\
3
\end{pmatrix}-\frac{7}{5}b_{3} = \begin{pmatrix}
0 \\
-\frac{2}{5} \\
0 \\
2 \\
\frac{15}{5}-\frac{14}{5}
\end{pmatrix} = \begin{pmatrix}
0 \\
-\frac{2}{5} \\
0 \\
2 \\
\frac{1}{5}
\end{pmatrix}$$

wobei $||b_{4}||^2=\frac{4}{25}+4+\frac{1}{25}=\frac{5}{25}+4=4+\frac{1}{5}=\frac{21}{5}$

woraus ONB von $U$ ist $B=\left\{  b_{1},b_{2}, \frac{1}{\sqrt{ 5 }}b_{3}, \frac{\sqrt{ 5 }}{\sqrt{ 21 }}b_{4}  \right\}$

b)
$$c_{5}=\begin{pmatrix}
0 \\
0 \\
0 \\
1 \\
0
\end{pmatrix}$$ ergänzt $\{ c_{1},c_{2},c_{3},c_{4} \}$ zu Basis von $\mathbb{R}^5$. 

Weiterer Gram-schmidt schritt:
$$b_{5}=c_{5}-\left< c_{5},b_{1} \right>b_{1}-\left< c_{5},b_{2} \right>b_{2}  - \frac{\left<c_{5},b_{3}\right>}{5}b_{3}-\frac{\left<c_{5},b_{4}\right>}{\frac{21}{5}}b_{4} $$
$$=c_{5}-\frac{\left<c_{5},b_{4}\right>}{\frac{21}{5}}b_{4}=$$
b)

$$b_{5}
=c_{5}-\left< c_{5},b_{1} \right>b_{1}-\left< c_{5},b_{2} \right>b_{2}
-\frac{\left<c_{5},b_{3}\right>}{\left\|b_{3}\right\|^{2}}\,b_{3}
-\frac{\left<c_{5},b_{4}\right>}{\left\|b_{4}\right\|^{2}}\,b_{4}=c_{5}-\frac{\left< c_{5},b_{4} \right> }{\frac{21}{5}}\,b_{4} =c_{5}-\frac{5}{21} \left< \begin{pmatrix}
0 \\
0 \\
0 \\
1 \\
0
\end{pmatrix},b_{4} \right>b_{4} $$ $$b_{5}=\begin{pmatrix}0\\0\\0\\1\\0\end{pmatrix} -\frac{5}{21} \cdot 2 \cdot \begin{pmatrix}0\\-\frac{2}{5}\\0\\2\\\frac{1}{5}\end{pmatrix}=\begin{pmatrix}0\\0\\0\\1\\0\end{pmatrix} -\begin{pmatrix}0\\-\frac{4}{21}\\0\\\frac{20}{21}\\\frac{2}{21}\end{pmatrix}=\begin{pmatrix}0\\\frac{4}{21}\\0\\\frac{1}{21}\\-\frac{2}{21}\end{pmatrix}$$ $$\|b_{5}\|^{2} =\left(\frac{4}{21}\right)^{2}+\left(\frac{1}{21}\right)^{2}+\left(\frac{2}{21}\right)^{2} =\frac{16+1+4}{21^{2}} =\frac{21}{21^{2}} =\frac{1}{21}$$ $$\widehat b_{5}=\frac{b_{5}}{\|b_{5}\|} =\sqrt{21}\,b_{5} =\frac{1}{\sqrt{21}} \begin{pmatrix}0\\4\\0\\1\\-2\end{pmatrix}$$
Damit ist eine Orthonormalbasis von $\mathbb{R}^{5}$ gegeben durch
$$\left\{\, b_{1},\; b_{2},\; \frac{1}{\sqrt{5}}\,b_{3},\;
\frac{\sqrt{5}}{\sqrt{21}}\,b_{4},\;
\frac{1}{\sqrt{21}}\begin{pmatrix}0\\4\\0\\1\\-2\end{pmatrix}\,\right\}.$$

# ÜB8-A2 (Aufgabe 5)
![[Pasted image 20250906132501.png]]
Lösung:
a)
Es gilt $d(u,V)=|| \pi_{v_{4}^\perp}(u)||$
Nach Blatt 7 soll $$v_{4}^\perp=\left< \frac{1}{\sqrt{ 21 }} \begin{pmatrix}
0 \\
4 \\
0 \\
1 \\
-2
\end{pmatrix} \right>$$
wodurch $$\pi_{v_{4}^\perp}(u)=\frac{1}{21}\left< \begin{pmatrix}
0 \\
1 \\
0 \\
1 \\
0
\end{pmatrix}, \begin{pmatrix}
0 \\
4 \\
0 \\
1 \\
-2
\end{pmatrix} \right> \begin{pmatrix}
0 \\
4 \\
0 \\
1 \\
-2
\end{pmatrix}=\frac{1}{21} 5\cdot \begin{pmatrix}
0 \\
4 \\
0 \\
1 \\
-2
\end{pmatrix}$$
also $|| \pi_{v_{4}^\perp}(u)||= \frac{5}{\sqrt{ 21 }} \implies d(u,V)=\frac{5}{\sqrt{ 21 }}$

b)
$$d\!\left(u+\langle w\rangle,\,V_{3}\right)=\left\|\pi_{(V_{3}+\langle w\rangle)^{\perp}}(u)\right\|$$

$$\text{ONB von }V_{3}:\quad 
B=\left\{\begin{pmatrix}0\\0\\1\\0\\0\end{pmatrix},\;
\begin{pmatrix}1\\0\\0\\0\\0\end{pmatrix},\;
\frac{1}{\sqrt{5}}\begin{pmatrix}0\\1\\0\\0\\2\end{pmatrix}\right\}$$

$$\Rightarrow\ \text{ONB von }V_{3}+\langle w\rangle:
\ B\cup\left\{\frac{1}{\sqrt{5}}\begin{pmatrix}0\\-2\\0\\0\\1\end{pmatrix}\right\}$$

$$\pi_{V_{3}+\langle w\rangle}(u)
=\left\langle u,\begin{pmatrix}0\\0\\1\\0\\0\end{pmatrix}\right\rangle\!\begin{pmatrix}0\\0\\1\\0\\0\end{pmatrix}
+\left\langle u,\begin{pmatrix}1\\0\\0\\0\\0\end{pmatrix}\right\rangle\!\begin{pmatrix}1\\0\\0\\0\\0\end{pmatrix}
+\left\langle u,\frac{1}{\sqrt{5}}\!\begin{pmatrix}0\\1\\0\\0\\2\end{pmatrix}\right\rangle\!\frac{1}{\sqrt{5}}\!\begin{pmatrix}0\\1\\0\\0\\2\end{pmatrix}
+\left\langle u,\frac{1}{\sqrt{5}}\!\begin{pmatrix}0\\-2\\0\\0\\1\end{pmatrix}\right\rangle\!\frac{1}{\sqrt{5}}\!\begin{pmatrix}0\\-2\\0\\0\\1\end{pmatrix}$$

$$=0+0+\frac{1}{5}\begin{pmatrix}0\\1\\0\\0\\2\end{pmatrix}
+\frac{-2}{5}\begin{pmatrix}0\\-2\\0\\0\\1\end{pmatrix}
=\frac{1}{5}\!\left(\begin{pmatrix}0\\1\\0\\0\\2\end{pmatrix}
-2\begin{pmatrix}0\\-2\\0\\0\\1\end{pmatrix}\right)
=\begin{pmatrix}0\\1\\0\\0\\0\end{pmatrix}$$

$$\pi_{(V_{3}+\langle w\rangle)^{\perp}}(u)
=u-\pi_{V_{3}+\langle w\rangle}(u)
=\begin{pmatrix}0\\1\\0\\1\\0\end{pmatrix}
-\begin{pmatrix}0\\1\\0\\0\\0\end{pmatrix}
=\begin{pmatrix}0\\0\\0\\1\\0\end{pmatrix}$$

$$\Rightarrow\ d\!\left(u+\langle w\rangle,\,V_{3}\right)
=\left\|\pi_{(V_{3}+\langle w\rangle)^{\perp}}(u)\right\|=1$$

$$\text{Schreibe }\ \pi_{V_{3}+\langle w\rangle}(u)=w'+v,\ 
w'\in\langle w\rangle,\ v\in V_{3}.$$

$$w'+v=\begin{pmatrix}0\\1\\0\\0\\0\end{pmatrix},\qquad 
w'=-\frac{2}{5}\begin{pmatrix}0\\-2\\0\\0\\1\end{pmatrix},\qquad 
v=\frac{1}{5}\begin{pmatrix}0\\1\\0\\0\\2\end{pmatrix}$$

$$\text{Lotfußpunkte: }\
u-w'=\begin{pmatrix}0\\1\\0\\1\\0\end{pmatrix}
+\frac{2}{5}\begin{pmatrix}0\\-2\\0\\0\\1\end{pmatrix}
=\begin{pmatrix}0\\\frac{1}{5}\\0\\1\\\frac{2}{5}\end{pmatrix},\qquad 
v=\frac{1}{5}\begin{pmatrix}0\\1\\0\\0\\2\end{pmatrix}.$$

# ÜB10-A2 (Aufgabe 6)
![[Pasted image 20250906135815.png]]![[Pasted image 20250906135823.png]]![[Pasted image 20250906135832.png]]

# ÜB11-A1 (Aufgabe 7)
![[Pasted image 20250906135859.png]]

**Methode 1:**
Annahme $\Psi$ Isometrie

Es gilt $$1+a^2+b^2=||\begin{pmatrix}
1 \\
a \\
b
\end{pmatrix}||^2=||\Psi(\begin{pmatrix}
3 \\
3 \\
0
\end{pmatrix})||=||\begin{pmatrix}
3 \\
3 \\
0
\end{pmatrix}||=18$$
und $$G=\left< \begin{pmatrix}
2 \\
0 \\
1
\end{pmatrix},\begin{pmatrix}
3 \\
3 \\
0
\end{pmatrix} \right> = \left< \Psi(\begin{pmatrix}
2 \\
0 \\
1
\end{pmatrix}),\Psi(\begin{pmatrix}
3 \\
3 \\
0
\end{pmatrix}) \right> = \left< \begin{pmatrix}
2 \\
1 \\
0
\end{pmatrix}, \begin{pmatrix}
1 \\
a \\
b
\end{pmatrix} \right> =2 + a$$
$$\implies a=4 \implies b = \pm1 \implies \Psi(\begin{pmatrix}
3 \\
3 \\
0
\end{pmatrix})=\begin{pmatrix}
1 \\
4 \\
\pm 1
\end{pmatrix}$$
$$\left< \{ \begin{pmatrix}
2 \\
0 \\
1
\end{pmatrix}, \begin{pmatrix}
3 \\
3 \\
0
\end{pmatrix} \} \right>^\perp = \ker(\begin{pmatrix}
2 & 0 & 1 \\
3 & 3 & 0
\end{pmatrix})= \ker(\begin{pmatrix}
2 & 0 & 1 \\
1 & 1 & 0
\end{pmatrix})=\ker(\begin{pmatrix}
0 & -2 & 1 \\
1 & 1 & 0
\end{pmatrix})=\ker\left( \begin{pmatrix}
0 & 1 & -\frac{1}{2} \\
1 & 0 & \frac{1}{2}
\end{pmatrix} \right)=\left< \begin{pmatrix}
-1 \\
1 \\
2
\end{pmatrix} \right> $$

**Fall $b = -1$:** 
$$\left< \{ \begin{pmatrix}
2 \\
1 \\
0
\end{pmatrix}, \begin{pmatrix}
1 \\
4 \\
-1
\end{pmatrix} \} \right>^\perp =\ker\!\begin{pmatrix}2&1&0\\[2pt]1&4&-1\end{pmatrix} =\ker\!\begin{pmatrix}1&\tfrac12&0\\[2pt]1&4&-1\end{pmatrix} =\ker\!\begin{pmatrix}1&\tfrac12&0\\[2pt]0&\tfrac72&-1\end{pmatrix} =\left\langle\begin{pmatrix}-\tfrac12\\[2pt]1\\[2pt]\tfrac72\end{pmatrix}\right\rangle =\left\langle\begin{pmatrix}-1\\[2pt]2\\[2pt]7\end{pmatrix}\right\rangle.$$ $$\Bigl\|\begin{pmatrix}-1\\[2pt]1\\[2pt]2\end{pmatrix}\Bigr\|^{2}=6,\qquad \Bigl\|\begin{pmatrix}-1\\[2pt]2\\[2pt]7\end{pmatrix}\Bigr\|^{2}=49+4+1=54=9\cdot6.$$ $$\Rightarrow\ \Psi\!\left(3\begin{pmatrix}-1\\[2pt]1\\[2pt]2\end{pmatrix}\right) =\pm\begin{pmatrix}-1\\[2pt]2\\[2pt]7\end{pmatrix}.$$ **Fall $b=1$:** $$\left\langle\left\{\begin{pmatrix}2\\1\\0\end{pmatrix},\begin{pmatrix}1\\4\\1\end{pmatrix}\right\}\right\rangle^{\!\perp} =\ker\!\begin{pmatrix}2&1&0\\[2pt]1&4&1\end{pmatrix} =\ker\!\begin{pmatrix}1&\tfrac12&0\\[2pt]1&4&1\end{pmatrix} =\ker\!\begin{pmatrix}1&\tfrac12&0\\[2pt]0&\tfrac72&1\end{pmatrix} =\left\langle\begin{pmatrix}\tfrac12\\[2pt]-1\\[2pt]\tfrac72\end{pmatrix}\right\rangle =\left\langle\begin{pmatrix}1\\[2pt]-2\\[2pt]7\end{pmatrix}\right\rangle.$$ $$\Bigl\|\begin{pmatrix}1\\[2pt]-2\\[2pt]7\end{pmatrix}\Bigr\|^{2}=1+4+49=54=9\cdot6 \quad\Rightarrow\quad \Psi\!\left(3\begin{pmatrix}-1\\[2pt]1\\[2pt]2\end{pmatrix}\right) =\pm\begin{pmatrix}1\\[2pt]-2\\[2pt]7\end{pmatrix}.$$ $$\textbf{Insgesamt}\ (b\in\{\pm1\}):\qquad \Psi\!\begin{pmatrix}2\\0\\1\end{pmatrix}=\begin{pmatrix}2\\1\\0\end{pmatrix},\quad \Psi\!\begin{pmatrix}3\\3\\0\end{pmatrix}=\begin{pmatrix}1\\4\\b\end{pmatrix},\quad \Psi\!\begin{pmatrix}-1\\[2pt]1\\[2pt]2\end{pmatrix}=\pm\begin{pmatrix}b\\[2pt]-2b\\[2pt]7\end{pmatrix}.$$ $$\text{Außerdem gilt}:\quad \frac{1}{6}\!\left(\frac{1}{3}\!\begin{pmatrix}3\\3\\0\end{pmatrix} -\begin{pmatrix}-1\\1\\2\end{pmatrix}\right) +\,\frac{2}{6}\!\begin{pmatrix}2\\0\\1\end{pmatrix} =\frac{1}{6}\!\begin{pmatrix}6\\0\\0\end{pmatrix}=e_{1},$$ $$-\frac{1}{3}\!\left(\frac{1}{3}\!\begin{pmatrix}3\\3\\0\end{pmatrix}\right) +\begin{pmatrix}-1\\1\\2\end{pmatrix} +\begin{pmatrix}2\\0\\1\end{pmatrix} =\frac{1}{3}\!\begin{pmatrix}0\\0\\3\end{pmatrix}=e_{3},$$ $$\frac{1}{3}\!\begin{pmatrix}3\\3\\0\end{pmatrix}-e_{1}=e_{2}.$$
**Schlussfolgerung zu Methode 1**

Seien $v_1,v_2,v_3,w_1,w_2,w_3\in\mathbb{R}^3$ mit
$$v_3\perp\langle v_1,v_2\rangle,\qquad w_3\perp\langle w_1,w_2\rangle,\qquad
\dim\langle v_1,v_2\rangle=\dim\langle w_1,w_2\rangle=2,$$
$$\langle v_1,v_2\rangle=\langle w_1,w_2\rangle,\qquad \|v_1\|=\|w_1\|,\qquad \|v_2\|=\|w_2\|.$$

Dann existiert **eine** Isometrie $\Phi:\mathbb{R}^3\to\mathbb{R}^3$ mit $\Phi(v_i)=w_i$ $(i=1,2,3)$.
Für $v=\lambda_1v_1+\lambda_2v_2+\lambda_3v_3$ gilt wegen $v_3\perp\langle v_1,v_2\rangle$:
$$\|v\|^2=\lambda_1^2\|v_1\|^2+\lambda_2^2\|v_2\|^2+\lambda_1\lambda_2\langle v_1,v_2\rangle+\lambda_3^2\|v_3\|^2,$$
und ebenso
$$\|\Phi(v)\|^2=\|\lambda_1w_1+\lambda_2w_2+\lambda_3w_3\|^2
=\lambda_1^2\|w_1\|^2+\lambda_2^2\|w_2\|^2+\lambda_1\lambda_2\langle w_1,w_2\rangle+\lambda_3^2\|w_3\|^2.$$
Aus den Voraussetzungen folgt $\|v\|=\|\Phi(v)\|$ für alle $v$, also ist $\Phi$ eine Isometrie
(Definiere $\Phi$ durch lineare Fortsetzung).

Mit $v_1=(2,0,1)^T,\ v_2=(3,3,0)^T,\ v_3=(-1,1,2)^T$ und
$$w_1=(2,1,0)^T,\qquad w_2=(1,4,b)^T,\qquad w_3=\pm(b,-2b,7)^T,\quad b\in\{\pm1\},$$
sind die obigen Bedingungen erfüllt.
**Daraus folgen insgesamt $4$ mögliche Isometrien** $\Psi$ (Wahl von $b=\pm1$ und unabhängig davon das Vorzeichen bei $w_3$).


**Methode 2:**

**Fall $\det(\Psi)=1$:**  
$\Psi$ ist Drehung mit Drehachse $V$ und Drehebene $U$. Ist $x\in\mathbb{R}^3$ und es gibt $u\in U,\ v\in V$ mit $x=u+v$, dann gilt
$$\Psi(x)=\Psi(u)+v \;\;\Rightarrow\;\; x-\Psi(x)=u-\Psi(u)\in U.$$

**Unter-Fall $b=+1$:**
$$
\begin{aligned}
\begin{pmatrix}2\\0\\1\end{pmatrix}-\Psi\!\begin{pmatrix}2\\0\\1\end{pmatrix}
&=\begin{pmatrix}2\\0\\1\end{pmatrix}-\begin{pmatrix}2\\1\\0\end{pmatrix}
=\begin{pmatrix}0\\-1\\1\end{pmatrix}=:b_1,\\[4pt]
\begin{pmatrix}3\\3\\0\end{pmatrix}-\Psi\!\begin{pmatrix}3\\3\\0\end{pmatrix}
&=\begin{pmatrix}3\\3\\0\end{pmatrix}-\begin{pmatrix}1\\4\\1\end{pmatrix}
=\begin{pmatrix}2\\-1\\-1\end{pmatrix}=:b_2.
\end{aligned}
$$

$$U_1:=\langle b_1,b_2\rangle \quad\widehat{=}\ \text{Drehebene}, \qquad 
\langle b_1,b_2\rangle^{\perp}=\langle (1,1,1)^T\rangle\ \text{(Drehachse)}.$$

$$
\pi_{U_1}\!\begin{pmatrix}2\\0\\1\end{pmatrix}
=\begin{pmatrix}2\\0\\1\end{pmatrix}
-\frac{\left\langle\begin{pmatrix}2\\0\\1\end{pmatrix},\begin{pmatrix}1\\1\\1\end{pmatrix}\right\rangle}
{\left\langle\begin{pmatrix}1\\1\\1\end{pmatrix},\begin{pmatrix}1\\1\\1\end{pmatrix}\right\rangle}
\begin{pmatrix}1\\1\\1\end{pmatrix}
=\begin{pmatrix}2\\0\\1\end{pmatrix}-\frac{3}{3}\begin{pmatrix}1\\1\\1\end{pmatrix}
=\begin{pmatrix}1\\-1\\0\end{pmatrix},
$$

$$
\pi_{U_1}\!\begin{pmatrix}2\\1\\0\end{pmatrix}
=\begin{pmatrix}2\\1\\0\end{pmatrix}-\frac{3}{3}\begin{pmatrix}1\\1\\1\end{pmatrix}
=\begin{pmatrix}1\\0\\-1\end{pmatrix}.
$$

$$\Rightarrow\ \Psi\!\begin{pmatrix}1\\-1\\0\end{pmatrix}=\begin{pmatrix}1\\0\\-1\end{pmatrix}.$$

Drehwinkel $\alpha_1$:
$$
\cos(\alpha_1)
=\frac{\left\langle\begin{pmatrix}1\\-1\\0\end{pmatrix},\begin{pmatrix}1\\0\\-1\end{pmatrix}\right\rangle}
{\left\|\begin{pmatrix}1\\-1\\0\end{pmatrix}\right\|\ \left\|\begin{pmatrix}1\\0\\-1\end{pmatrix}\right\|}
=\frac{1}{2}.
$$

**Unter-Fall $b=-1$:**
$$
\begin{pmatrix}3\\3\\0\end{pmatrix}-\Psi\!\begin{pmatrix}3\\3\\0\end{pmatrix}
=\begin{pmatrix}3\\3\\0\end{pmatrix}-\begin{pmatrix}1\\4\\-1\end{pmatrix}
=\begin{pmatrix}2\\-1\\1\end{pmatrix}=:b_2',
$$

$$U_2:=\langle b_1,b_2'\rangle \quad\widehat{=}\ \text{Drehebene},\qquad 
\langle b_1,b_2'\rangle^{\perp}=\langle (0,1,1)^T\rangle\ \text{(Drehachse)}.$$

$$
\pi_{U_2}\!\begin{pmatrix}2\\0\\1\end{pmatrix}
=\begin{pmatrix}2\\0\\1\end{pmatrix}
-\frac{\left\langle\begin{pmatrix}2\\0\\1\end{pmatrix},\begin{pmatrix}0\\1\\1\end{pmatrix}\right\rangle}
{\left\langle\begin{pmatrix}0\\1\\1\end{pmatrix},\begin{pmatrix}0\\1\\1\end{pmatrix}\right\rangle}
\begin{pmatrix}0\\1\\1\end{pmatrix}
=\begin{pmatrix}2\\0\\1\end{pmatrix}-\frac{1}{2}\begin{pmatrix}0\\1\\1\end{pmatrix}
=\begin{pmatrix}2\\-\tfrac12\\\tfrac12\end{pmatrix},
$$

$$
\pi_{U_2}\!\begin{pmatrix}2\\1\\0\end{pmatrix}
=\begin{pmatrix}2\\1\\0\end{pmatrix}-\frac{1}{2}\begin{pmatrix}0\\1\\1\end{pmatrix}
=\begin{pmatrix}2\\\tfrac12\\-\tfrac12\end{pmatrix}.
$$

$$\Rightarrow\ \Psi\!\begin{pmatrix}2\\-\tfrac12\\\tfrac12\end{pmatrix}
=\begin{pmatrix}2\\\tfrac12\\-\tfrac12\end{pmatrix}.$$

Drehwinkel $\alpha_2$:
$$
\cos(\alpha_2)
=\frac{\left\langle\begin{pmatrix}2\\-\tfrac12\\\tfrac12\end{pmatrix},\begin{pmatrix}2\\\tfrac12\\-\tfrac12\end{pmatrix}\right\rangle}
{\left\|\begin{pmatrix}2\\-\tfrac12\\\tfrac12\end{pmatrix}\right\|\ \left\|\begin{pmatrix}2\\\tfrac12\\-\tfrac12\end{pmatrix}\right\|}
=\frac{\,4-\tfrac14-\tfrac14\,}{\,2^2+(\tfrac12)^2+(\tfrac12)^2\,}
=\frac{7}{9}.
$$

**Fall $\det(\Psi)=-1$:**

Sei $d$ die Spiegelung in der Ebene
$$
\left\langle \begin{pmatrix}2\\1\\0\end{pmatrix},\ \begin{pmatrix}1\\a\\b\end{pmatrix}\right\rangle.
$$
Dann gilt für $\Phi:=d\circ\Psi$,
$$
\Phi\!\begin{pmatrix}2\\0\\1\end{pmatrix}=\begin{pmatrix}2\\1\\0\end{pmatrix},
\qquad
\Phi\!\begin{pmatrix}3\\3\\0\end{pmatrix}=\begin{pmatrix}1\\a\\b\end{pmatrix}.
$$
$\Rightarrow$ Fall $\det(\Psi)=1$ anwenden $\implies$ wir haben $4$ mögliche Isometrien gefunden.

# ÜB11-A2 (Aufgabe 8)
![[Pasted image 20250906135910.png]]

a) $A\in\mathrm{SO}(4)\ \Rightarrow\ A$ ist ähnlich zu einer der Matrizen
$$\operatorname{diag}(1,1,D_\alpha),\qquad
\operatorname{diag}(-1,-1,D_\alpha),\qquad
\operatorname{diag}(D_\alpha,D_\beta),$$
wobei
$$D_\theta=\begin{pmatrix}\cos\theta&-\sin\theta\\ \sin\theta&\cos\theta\end{pmatrix},\qquad
\alpha,\beta\in(0,\pi).$$
Damit existieren $\alpha,\beta\in[0,\pi]$ so, dass $A$ ähnlich zu
$$\operatorname{diag}(D_\alpha,D_\beta)$$
ist. Folglich
$$
\mathrm{CP}_A(X)=\det(A-XI)
=\det\!\big(\operatorname{diag}(D_\alpha,D_\beta)-XI\big)
=(X^2-2\cos\alpha\,X+1)(X^2-2\cos\beta\,X+1),
$$
also
$$
\mathrm{CP}_A(X)=X^4-2(\cos\alpha+\cos\beta)X^3+(4\cos\alpha\cos\beta+2)X^2
-2(\cos\alpha+\cos\beta)X+1.
$$
Setzt man $c_1=\cos\alpha,\ c_2=\cos\beta\in[-1,1]$, erhält man die geforderte Form
$$\mathrm{CP}_A(X)=X^4-2(c_1+c_2)X^3+(4c_1c_2+2)X^2-2(c_1+c_2)X+1.$$

b) Gegeben sei
$$X^4-2X^3+3X^2-2X+1.$$
Vergleich der Koeffizienten mit dem Ausdruck aus a) liefert
$$c_1+c_2=1,\qquad 4c_1c_2+2=3\ \Rightarrow\ c_1c_2=\frac14.$$

Aus $c_1c_2=\frac14$ folgt (für $c_2\neq0$)
$$c_1=\frac{1}{4c_2}.$$
Einsetzen in $c_1+c_2=1$ ergibt
$$\frac{1}{4c_2}+c_2=1.$$
Multiplikation mit $4c_2$:
$$1+4c_2^2=4c_2.$$
Umstellen:
$$4c_2^2-4c_2+1=0.$$
Mit der Mitternachtsformel:
$$
c_2=\frac{4\pm\sqrt{16-4\cdot4\cdot1}}{2\cdot4}
=\frac{4\pm\sqrt{16-16}}{8}
=\frac{4}{8}
=\frac12.
$$
Also $c_2=\frac12$ und damit
$$c_1=\frac{1}{4c_2}=\frac{1}{4\cdot\frac12}=\frac12.$$

Somit $\cos\alpha=\cos\beta=\frac12\ \Rightarrow\ \alpha=\beta=\frac{\pi}{3}$ und
$$1-\Bigl(\frac12\Bigr)^2=\frac34.$$

Die Isometrie-Normalform von $A$ ist daher
$$
\operatorname{diag}\!\big(D_{\pi/3},D_{\pi/3}\big)
=\begin{pmatrix}
\frac12 & -\frac{\sqrt3}{2} & 0 & 0\\[4pt]
\frac{\sqrt3}{2} & \frac12 & 0 & 0\\[4pt]
0 & 0 & \frac12 & -\frac{\sqrt3}{2}\\[4pt]
0 & 0 & \frac{\sqrt3}{2} & \frac12
\end{pmatrix}.
$$

# ÜB12-A1 (Aufgabe 9)
![[Pasted image 20250906151304.png]]

Lösung:
Gegeben sei das Skalarprodukt
$$\langle x,y\rangle=x^{\top}\!\begin{pmatrix}1&0&1\\[2pt]0&2&3\\[2pt]1&3&6\end{pmatrix}y.$$
Gesucht sind alle $\alpha\in\mathbb{R}$, für die $\Phi(v)=Av$ bzgl. $\langle\cdot,\cdot\rangle$ selbstadjungiert ist, sowie eine ONB aus Eigenvektoren.

Wir setzen
$$F:=\begin{pmatrix}1&0&1\\[2pt]0&2&3\\[2pt]1&3&6\end{pmatrix},\qquad
A=\begin{pmatrix}2&-2&-3\\[2pt]\alpha&-1&\alpha-4\\[2pt]0&2&5\end{pmatrix}.$$
Selbstadjungiertheit ist äquivalent zu
$$A^{\top}F=FA.$$
Da $F^{\top}=F$, ist dies äquivalent zu der Symmetrie von $FA$, also $(FA)^{\top}=FA$.

Wir berechnen
$$
FA
=\begin{pmatrix}1&0&1\\[2pt]0&2&3\\[2pt]1&3&6\end{pmatrix}
\begin{pmatrix}2&-2&-3\\[2pt]\alpha&-1&\alpha-4\\[2pt]0&2&5\end{pmatrix}
=\begin{pmatrix}
2&0&2\\[2pt]
2\alpha&4&2\alpha+7\\[2pt]
2+3\alpha&7&3\alpha+15
\end{pmatrix}.
$$
Weiter gilt (oder: $(FA)^{\top}$)
$$
A^{\top}F
=\begin{pmatrix}2&\alpha&0\\[2pt]-2&-1&2\\[2pt]-3&\alpha-4&5\end{pmatrix}
\begin{pmatrix}1&0&1\\[2pt]0&2&3\\[2pt]1&3&6\end{pmatrix}
=\begin{pmatrix}
2&2\alpha&2+3\alpha\\[2pt]
0&4&7\\[2pt]
2&2\alpha+7&3\alpha+15
\end{pmatrix}.
$$
Vergleich $FA=(FA)^{\top}$ liefert aus der $(1,2)$-Komponente $0=2\alpha$, also
$$\boxed{\ \alpha=0\ }.$$

Für $\alpha=0$ ist
$$
A=\begin{pmatrix}2&-2&-3\\[2pt]0&-1&-4\\[2pt]0&2&5\end{pmatrix}.
$$
Char‐Polynom:
$$
\begin{aligned}
\chi_A(X)
&=\det(XI-A)
=(X-2)\big((X+1)(X-5)+8\big)\\
&=(X-2)\big(X^2+X-5X-5+8\big)
=(X-2)(X^2-4X+3)\\
&=(X-2)(X-1)(X-3).
\end{aligned}
$$
Also Eigenwerte $2,1,3$.

**Eigenräume**

1. Für $\lambda=2$:
$$
\mathrm{Eig}(A,2)=\ker(A-2I)
=\ker\begin{pmatrix}0&-2&-3\\[2pt]0&-3&-4\\[2pt]0&2&3\end{pmatrix}
=\langle e_1\rangle.
$$

2. Für $\lambda=1$:
$$
\mathrm{Eig}(A,1)=\ker(A-I)
=\ker\begin{pmatrix}1&-2&-3\\[2pt]0&-2&-4\\[2pt]0&2&4\end{pmatrix}
=\ker\begin{pmatrix}1&0&1\\[2pt]0&1&2\\[2pt]0&0&0\end{pmatrix}
=\left\langle\begin{pmatrix}-1\\ -2\\ 1\end{pmatrix}\right\rangle.
$$

3. Für $\lambda=3$:
$$
\mathrm{Eig}(A,3)=\ker(A-3I)
=\ker\begin{pmatrix}-1&-2&-3\\[2pt]0&-4&-4\\[2pt]0&2&2\end{pmatrix}
=\ker\begin{pmatrix}-1&0&-1\\[2pt]0&1&1\\[2pt]0&0&0\end{pmatrix}
=\left\langle\begin{pmatrix}-1\\ -1\\ 1\end{pmatrix}\right\rangle.
$$

**Normalisieren (bzgl. $\langle\cdot,\cdot\rangle$)**

$$
\|e_1\|^2=e_1^{\top}Fe_1=1.
$$

Für $v_1=\begin{pmatrix}-1\\-2\\1\end{pmatrix}$:
$$
Fv_1=\begin{pmatrix}1&0&1\\[2pt]0&2&3\\[2pt]1&3&6\end{pmatrix}\!\begin{pmatrix}-1\\-2\\1\end{pmatrix}
=\begin{pmatrix}0\\-1\\-1\end{pmatrix},
\qquad
\|v_1\|^2=v_1^{\top}Fv_1=(-1,-2,1)\!\cdot\!\begin{pmatrix}
0 \\
-1 \\
-1
\end{pmatrix}=1.
$$

Für $v_2=\begin{pmatrix}-1\\-1\\1\end{pmatrix}$:
$$
Fv_2=\begin{pmatrix}1&0&1\\[2pt]0&2&3\\[2pt]1&3&6\end{pmatrix}\!\begin{pmatrix}-1\\-1\\1\end{pmatrix}
=\begin{pmatrix}0\\1\\2\end{pmatrix},
\qquad
\|v_2\|^2=v_2^{\top}Fv_2=(-1,-1,1)\!\cdot\!\begin{pmatrix}
0 \\
1 \\
2
\end{pmatrix}=1.
$$

Da $A$ selbstadjungiert ist, sind Eigenvektoren zu verschiedenen Eigenwerten orthogonal. Somit ist die gewünschte Orthonormalbasis
$$
\boxed{\ \mathcal{B}=\left\{\,e_1,\ \begin{pmatrix}-1\\-2\\1\end{pmatrix},\ \begin{pmatrix}-1\\-1\\1\end{pmatrix}\right\}\ }.
$$


# ÜB12-A3 (Aufgabe 10)
![[Pasted image 20250906151313.png]]

Lösung:
### a) Drehachse

$f$ ist eine Drehung $\Rightarrow$ es gibt eine Achse $V_{\parallel}$ und die Drehebene $U=\langle V_{\parallel}\rangle^{\perp}$, so dass jedes $v\in\mathbb{R}^3$ eindeutig als
$$
v=v_{\parallel}+v_{\perp},\qquad v_{\parallel}\in V_{\parallel},\ v_{\perp}\in\langle V_{\parallel}\rangle^{\perp}
$$
geschrieben werden kann, wobei
$$
f(v_{\parallel})=v_{\parallel},\qquad f(v_{\perp})\in\langle V_{\parallel}\rangle^{\perp}.
$$
Damit gilt
$$
f(v)-v=f(v_{\perp})-v_{\perp}\in\langle V_{\parallel}\rangle^{\perp},
$$
also ist $f(v)-v$ stets ein Vektor aus der Drehebene.

Für die gegebenen Vektoren:
$$
\begin{pmatrix}2\\1\\0\end{pmatrix}-\begin{pmatrix}2\\0\\1\end{pmatrix}
=\begin{pmatrix}0\\1\\-1\end{pmatrix}\in U,
$$
und
$$
\begin{pmatrix}-2\\[2pt]1\\[2pt]7\end{pmatrix}-3\begin{pmatrix}-1\\[2pt]2\\[2pt]1\end{pmatrix}
=\begin{pmatrix}1\\[2pt]-5\\[2pt]4\end{pmatrix}\in U.
$$
Somit ist die Drehebene
$$
U=\left\langle\begin{pmatrix}0\\1\\-1\end{pmatrix},
\begin{pmatrix}1\\-5\\4\end{pmatrix}\right\rangle.
$$

Die Drehachse ist das orthogonale Komplement:
$$
U^{\perp}=\ker
\begin{pmatrix}
0&1&-1\\[2pt]
1&-5&4
\end{pmatrix}
=
\ker
\begin{pmatrix}
0&1&-1\\[2pt]
1&0&-1
\end{pmatrix}
=\left\langle\begin{pmatrix}1\\1\\1\end{pmatrix}\right\rangle.
$$
Die Drehachse ist also $\langle(1,1,1)\rangle$.


---

### b) Orthonormalbasis der Drehebene

Wir konstruieren eine ONB von $U$ mittels Gram–Schmidt.  
Praktisch wählen wir zuerst einen zu $(1,1,1)$ orthogonalen Richtungsvektor
$$
u_1=\begin{pmatrix}1\\-1\\0\end{pmatrix}\in U,\qquad \|u_1\|^2=2.
$$
Dann orthogonalisieren wir
$$
\tilde u_2
=\begin{pmatrix}0\\1\\-1\end{pmatrix}
-\frac{\left\langle\begin{pmatrix}0\\1\\-1\end{pmatrix},
\begin{pmatrix}1\\-1\\0\end{pmatrix}\right\rangle}{\|u_1\|^2}\,u_1
=\begin{pmatrix}0\\1\\-1\end{pmatrix}-\frac{-1}{2}\begin{pmatrix}1\\-1\\0\end{pmatrix}
=\begin{pmatrix}\tfrac12\\[2pt]\tfrac12\\[2pt]-1\end{pmatrix}.
$$
Für die Norm gilt
$$
\|\tilde u_2\|^2=\left(\tfrac12\right)^2+\left(\tfrac12\right)^2+(-1)^2=\tfrac32.
$$
Damit ergibt sich die ONB
$$
\left\{
\frac{1}{\sqrt2}\begin{pmatrix}1\\-1\\0\end{pmatrix},
\ \sqrt{\frac{2}{3}}\begin{pmatrix}\tfrac12\\[2pt]\tfrac12\\[2pt]-1\end{pmatrix}
\right\}
=
\left\{
\frac{1}{\sqrt2}\begin{pmatrix}1\\-1\\0\end{pmatrix},
\ \frac{1}{\sqrt6}\begin{pmatrix}1\\1\\-2\end{pmatrix}
\right\}.
$$

Den Drehwinkel bestimmen wir mit $u_1$:
$$
f(u_1)=f\!\left(\begin{pmatrix}2\\0\\1\end{pmatrix}-\begin{pmatrix}1\\1\\1\end{pmatrix}\right)
=\begin{pmatrix}2\\1\\0\end{pmatrix}-\begin{pmatrix}1\\1\\1\end{pmatrix}
=\begin{pmatrix}1\\0\\-1\end{pmatrix}.
$$
Also
$$
\cos(\alpha)=\frac{\langle u_1,f(u_1)\rangle}{\|u_1\|\,\|f(u_1)\|}
=\frac{\left\langle\begin{pmatrix}1\\-1\\0\end{pmatrix},\begin{pmatrix}1\\0\\-1\end{pmatrix}\right\rangle}{\sqrt2\cdot\sqrt2}
=\frac{1}{2}.
$$
Der Drehwinkel ist $\alpha=\frac{\pi}{3}$.

---

### c) Isometrie Normalform $\tilde A$

In einer ONB, die mit der (normierten) Achsenrichtung beginnt und danach eine ONB der Drehebene enthält, hat $f$ die Blockform $1\oplus R_{\alpha}$.  
Mit $\alpha=\frac{\pi}{3}$:
$$
\tilde A=
\begin{pmatrix}
1&0&0\\[2pt]
0&\tfrac12&-\tfrac{\sqrt3}{2}\\[2pt]
0&\tfrac{\sqrt3}{2}&\tfrac12
\end{pmatrix}.
$$

---

### d) Basis, in der die Abbildungsmatrix gleich $\tilde A$ ist

Wir wählen die orthonormale Basis
$$
B=\left\{
\frac{1}{\sqrt3}\begin{pmatrix}1\\1\\1\end{pmatrix},\
\frac{1}{\sqrt2}\begin{pmatrix}1\\-1\\0\end{pmatrix},\
\frac{1}{\sqrt6}\begin{pmatrix}1\\1\\-2\end{pmatrix}
\right\}.
$$
Bezüglich dieser Basis ist die Abbildungsmatrix von $f$ genau $\tilde A$.


# ÜB13-A2 (Aufgabe 11)
![[Pasted image 20250906144845.png]]
![[Pasted image 20250906144912.png]]
