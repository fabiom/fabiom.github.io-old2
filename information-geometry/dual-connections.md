---
layout: default
title: Information Geometry/ Dual connections
katex: true
---

# Information Geometry/ Dual connections

Let $$(M,g)$$ be a Riemannian manifold, and $$\nabla$$ be an any affine connection. The **dual connection** of $$\nabla$$ with respect to $$g$$ is a connection $$\nabla^*$$ such that

$$X \langle Y,Z \rangle = \langle \nabla_X Y,Z \rangle + \langle Y, \nabla^*_X Z \rangle$$

for $$X,Y,Z$$ vector fields. The triple $$(g,\nabla,\nabla^*)$$ is called a **dualistic structure** for $$M$$.

### Properties
1. The dual is unique.
2. $$\nabla^{**} = \nabla$$.
3. $$\overline\nabla = \frac{1}{2} (\nabla+\nabla^*)$$ is a metric connection. In particular, if $$\nabla,\nabla^*$$ are torsion-free, it is the Levi-Civita connection.
4. Let $$\nabla$$ be torsion-free. Then $$\nabla^*$$ is torsion-free iff $$\nabla g$$ is symmetric.
5. If $$X,Y \in T_p M$$ and $$\Pi_\gamma, \Pi^*_\gamma$$ denote parallel transport along a curve $$\gamma$$, with respect to $$\nabla$$ and $$\nabla^*$$ respectively, then $$\langle X,Y \rangle_p = \langle \Pi_\gamma X, \Pi^*_\gamma Y \rangle_q$$
6. Dual Riemann curvature tensors satisfy $$\langle R(X,Y)Z, W \rangle = - \langle R^* (X,Y)W, Z \rangle$$.
7. (Important!) $$\nabla$$ is flat iff $$\nabla^*$$ is flat.

The most important examples of dualistic structures in information geometry are the family of [$$\alpha$$-connections](#), and in particular the e/m-connections.
