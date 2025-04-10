This folder contains function (a.k.a. map or transformation) script that compute output geometric object base on the user's input. I don't use name `map/` to prevent confusion with map (the 2d visual image that indicate the 2D position of object).

This folder contains 2 Python files
1.  `dimensional_reduction/`
-   Purpose : Compute the 2D representation of 3D object via PCA, 2D hyperplane cross section etc. In this MVP, we only focus on PCA and 2D hyperplane cross section implementation.
2.  `linear_function/`
-   Purpose : Allow user to apply linear function in every points that belong to the user's defined objects.

Linear function L have 2 properties
1.  For all x, y in Ring: L(x) + L(y) = L(x + y)
2.  For all x, y in Ring: x * L(y) = L(x * y)

Note that
-   Ring is the number system e.g. Integer, Fractional number, Real number, Complex number etc. However the formal definition of ring is out of scope of the MVP version of this project.
-   Example of Linear function include scalar multiplication, matrix multiplication, integration, differentiation etc. However we will only focus on scalar multiplication and matrix multiplication in the MVP version of this project.
