Status: #baby 
Tags: 

# Unitary Matrices

A matrix U is unitary if its conjugate transpose $U^* = U^{-1}$. Recall $Av \cdot w$ = $v \cdot (A^{*}w)$. U unitary, $v \cdot w = (U^{-1} Uv)$ = ($U^{*} Uv$)$\cdot w$ = ($Uv$)$\cdot$($Uw$). Therefore multiplication by a unitary matrix preserves angles. (Unitary matrices are some compositions of rotations and reflections.) We want to show that multiplication by a unitary matrix preserves dot product. 

Recall $\vec{e}_{j}$ is a vector with all 0s except in the $j^{th}$ coordinate. Consider $\vec{e}_{j} \cdot \vec{e}_k$ = ($U \vec{e}_j$) $\cdot (U \vec{e}_k)$. Note that these are the $j^{th}$ column of U and the $k^{th}$ column of U respectively.

U is a unitary matrix if and only if its columns form and orthonormal set if and only if its rows form an orthonormal set. This is true because U is unitary if and only if $U^{*}$ is unitary. Recall $(U^{*})^{-1} = (U^{-1})^{*}$. 

Theorem: U unitary. $\lambda =$ eigenvalue for U. Then $|\lambda| = 1$. Proof: U$\vec{v} = \lambda \vec{v}$, with v not the zero vector. $\vec{v} \cdot \vec{v}$  = $(U \vec{v}) \cdot (U \vec{v})$ = $(\lambda \vec{v}) \cdot (\lambda \vec{v})$ = $\lambda \cdot \lambda conj$ $(\vec{v} \cdot \vec{v})$ = $|\lambda|^{2}$ ($\vec{v} \cdot \vec{v}$). $|\lambda|^{2}$ = 1.

An invertible matrix nxn. $\vec{a}_{1}, ...,\vec{a}_{n}$ are the columns of A. A inverse implies ${\vec{a}_{j}}^{n}$ from j = 1 (this is in brackets) is a basic for $\mathbb{C}^n$. More in physical notes.

# References