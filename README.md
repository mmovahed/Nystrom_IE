# Nystrom method for solving integral equations

The Nystrom method is a discretization technique that converts integral equations into a system of linear equations by employing quadrature rules. This method is particularly advantageous when dealing with integral equations arising from boundary value problems, such as the Neumann problem for Laplace’s equation. However, when applied to domains with corners, the Nystrom method can produce ill-conditioned systems, which can be problematic for numerical stability and accuracy.

The instability arises due to the singular behavior of the integral’s kernel at the corners of the domain. To overcome this, modifications to the standard Nystrom scheme are proposed, making it mathematically equivalent to Galerkin discretization. These modifications ensure stability and allow for the accurate solution of integral equations, even in the presence of singularities at the domain’s corners.

By using appropriate discretizations and understanding the behavior of the integral’s kernel, the Nystrom method can be effectively employed to solve integral equations with high accuracy, without the computational overhead typically associated with Galerkin methods.
