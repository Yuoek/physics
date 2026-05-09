# Physics

TODO 2026-05-09 09:49

## 梯度

*二维*
$$
\nabla f(x,y) = \left( \frac{\partial f}{\partial x},\frac{\partial f}{\partial y} \right)
$$

*三维*
$$
\nabla f(x,y,z) = \left( \frac{\partial f}{\partial x},\frac{\partial f}{\partial y},\frac{\partial f}{\partial z} \right)
$$

## 散度

$$
\nabla\cdot\vec{A} = \frac{\partial A_x}{\partial x} + \frac{\partial A_y}{\partial y} + \frac{\partial A_z}{\partial z}
$$

$$
\oiint_{S} \vec{A}\cdot d\vec{S} = \iiint_{V} \nabla\cdot\vec{A}\,dV
$$

## 旋度

$$
\nabla\times\vec{A} =
\begin{vmatrix}
\boldsymbol{i} & \boldsymbol{j} & \boldsymbol{k} \\
\dfrac{\partial}{\partial x} & \dfrac{\partial}{\partial y} & \dfrac{\partial}{\partial z} \\
A_x & A_y & A_z
\end{vmatrix}
$$

