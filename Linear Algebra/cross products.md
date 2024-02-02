---
aliases:
  - cross product
---
- Cross product in 2 dimensions is the area of the parallelogram formed by two [[vectors]]. ![[2d_cross_product]]
- Use the [[determinant]] for calculating the cross product. If $\vec{v} = \begin{bmatrix} 3 \\ 1 \end{bmatrix}$ and $\vec{w} = \begin{bmatrix} 2 \\ -1 \end{bmatrix}$, then the cross product is calculated like so: $$\vec{v} \times \vec{w} = \det{\left(\begin{bmatrix} 3 & 2 \\ 1 & -1 \end{bmatrix}\right)} = 3 \cdot (-1) - 2 \cdot 1 = -5 $$
- Remember, the matrix $\begin{bmatrix} 3 & 2 \\ 1 & -1 \end{bmatrix}$ represents the [[linear transformation]] that moves $\hat{i}$ to $\begin{bmatrix} 3 \\ 1 \end{bmatrix}$ and $\hat{j}$ to $\begin{bmatrix} 2 \\ -1 \end{bmatrix}$. The [[determinant]] then measures the change in the area of the unit square, which has an area of 1 before the transformation. 
- Obviously, magnitude of a cross product is biggest when [[vectors]] are perpendicular. Also scales linearly with a [[scalars|scalar]], i.e. $(3\vec{v}) \times \vec{w} = 3\left( \vec{v} \times \vec{w} \right)$
- True cross product is actually a [[vectors|vector]]; magnitude is the area of the parallelogram as found earlier by the [[determinant]], direction is perpendicular to that parallelogram. Use the [[right-hand rule]] to determinant the direction of the cross product. 
- In order to find the cross product, follow this formula: $$\begin{bmatrix} v_1 \\ v_2 \\ v_3 \end{bmatrix} \times \begin{bmatrix} w_1 \\ w_2 \\ w_3 \end{bmatrix} = \det{\left( \begin{bmatrix} \hat{i} & v_1 & w_1 \\ \hat{j} & v_2 & w_2 \\ \hat{k} & v_3 & w_3 \end{bmatrix} \right)}$$