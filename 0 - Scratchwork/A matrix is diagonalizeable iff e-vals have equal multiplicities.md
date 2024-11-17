2024-09-27 11:19
Status:
Tags:

# A matrix is diagonalizeable iff e-vals have equal multiplicities

Thm: A is diagonal if and only if the geometric multiplicity of $\lambda$ = algebraic multiplicity of $\lambda$ for each $\lambda$. 
##### Observation:
$S^{-1}A S$ have the same characteristic polynomial. Notice:
det($xI-S^{-1}AS$) = det($xS^{-1}S - S^{-1}AS)$ = det$(S^{-1}(xI-A)S)$ 
= det($S^-1$) det($xI-A)$det($S$)

##### Observation 2:
$\lambda$ =  e-value of A with geom. mult m, then $\lambda$ = e-value of $S^{-1}AS$ with geom multm.
Proof:
Let {$\vec{v}_i$}$^{d}_{i=1}$ = basis of e-space for $A_{1}\lambda$.
{$S^{-1}\vec{v}_{i}$}$^{d}_{i=1}$ is LI (he cited homework)
$S^{-1}AS S^{-1} \vec{v}_i$ = $S^{-1}A\vec{v}_{i}= \lambda S^{-1}\vec{v}_i$
So $S^{-1}\vec{v}_i$ is in the eigenspace for $S^{-1}AS$ and $\lambda$ dim of that eigenspace is $\geq d$. Conjugation by an invertible matrix can only increase the geometric multiplicity of the eigenvalues. By a symmetry argument, the geometric multiplicity has to stay the same.

##### Observation 3: 
For a diagonal matrix, the geometric multiplicity always equals the algebraic multiplicity. Why is this true? Consider a lambda diagonal matrix. Suppose lambda is an eigen value, so the geometric multiplicity of lambda s.t. $\lambda_j$ = lambda. Where $\lambda_{j}$ is a lambda on the diagonal. The eigenspace is the span{$\vec{e}_{j} : \lambda_{j}=\lambda$}. Then det($xI-D$) = $\prod^{n}_{j=1}(x-\lambda_j)$. Algebraic multiplicity = # j : $\lambda_{j}= \lambda$

## Thm Proof:
Suppose that we can diagonalize the matrix A, so suppose $S^{-1}AS = D$. Now we want to show that the geometric and algebraic multiplicity is the same for each eigen value. $\lambda =$ e-value of A. The geometric multiplicity of $\lambda$ as an e-value of A is equal to the geometric multiplicity of $\lambda$ as an e-value of D. (By Observation 2).  By Observation 3, the algebraic multiplicity of $lambda$ as e-value of A is the same as the algebraic multiplicity of $\lambda$ as an e-value of D.

(ii) assume the converse i.e.
Assume all e-values of A have their geometric and algebraic multiplicities equal. Then $\sum$ alg. mult. = n.
Then $\sum\limits$ geom. mult. = n. Now for each eigenspace (eigenvalue = $\lambda_{1}, \lambda{2}, ..., \lambda_m$), we write down a basis. Let {$\vec{v}_{j,i}$}$^{d(\lambda_i)}_{j=1}$ be a basis for the eigenspace of $\lambda_i$ and A. d($\lambda_i$)=dim ofthat eigenspace.
So $\sum^{m}_{i=1} d(\lambda_{i)}= n$. If we show that the {{$\vec{v}_{j,i}$}$^{d(\lambda_i)}_{j=1}$}$_{i=1}^m$ is LI, then we have n LI in $\mathbb{C}^n$, i.e. we have a basis for $\mathbb{C}^n$ made up of e-vectors of A, which implies A is diagonalizeable.

$\sum^{m}_{i=1} \sum^{d(\lambda_i)}_{j=1} c_{j,i} \vec{V}_{j,i} = \vec{0}$  (he branched out like an asshole to two different things like a tree)

(1) Mult by A: $\sum^{m}_{i=1} \sum^{d(\lambda_i)}_{j=1} c_{j,i} \lambda_i \vec{V}_{j,i}$ 
(2) Mult $\lambda_m$ $\sum^{m}_{i=1} \sum^{d(\lambda_i)}_{j=1} c_{j,i} \lambda_m \vec{V}_{j,i} = \vec{0}$ .
Suptract (1) and (2) we get 
$$\sum^{m}_{i=1} \sum^{d(\lambda_i)}_{j=1} c_{j,i} (\lambda{i}-\lambda{m}) \vec{V}_{j,i} = \vec{0}$$

Repeat this with replacing $\lambda_m$ by $\lambda_{m-1}$ and just keep going down with it until you get down to the last two eigen values. Getting a whole bunch of extra factors and pairing them.

Since {$\vec{v}_{j,i}$}$^{d(\lambda_i)}_{j=1}$ LI, this implies that $c_{k,1} (\lambda_{1}- \lambda_{m})...(\lambda_{1}- \lambda_{2)}= 0$ for all j this implies
$c_{j,1} = 0$ for all j.

$\sum^{m}_{i=1} \sum^{d(\lambda_i)}_{j=1} c_{j,i} \vec{V}_{j,i} = \vec{0}$ repeat as above implies that $c_{j,2} = 0$ for all j etc.
Implies: $c_{j,i} = 0$ for all j,i.

### Example:

# References