# Description

`arabesque_of_alkhwarizmi` is Numpy-Manim based Python library that is used for visualizing 2D and 3D representation of linear algebra related concept and user defined dataset. This tools help user learn interesting mathematical concept e.g. Linear Algebra, Group Theory, Lie Algebra, Topology etc, gain visual intuition of high dimensional geometry and generating cool looking visual art.

# Inspiration

Before I started to learn to code for the first time in 2021, I used to like drawing, especially by draw multiple straight lines and grids 
as the basis of my artwork such that I can draw symmetrical pattern and/or 3D perspective art. The 3Blue1Brown's Linear Algebra visualization (https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) also reminds me of how I drew my artworks. 
However in my opinion, visual art is boring because many artists try to create new artworks when the visual art is limited in 5D rgbxy Euclidean Space where there is rarely anythings new to be created.

One of multiple ways to creating new interesting artworks is to create the 2D representation of higher dimensional objects.

High dimensional geometry also have very interesting unexpected properties such as
1.  There are 6 Platonic solids in 4D Euclidean Space.
-   https://youtu.be/2s4TqVAbfz4?si=kpwvDm6EmWmQQApF
2.  4D Object can have 2 independent axis where the object is rotated at the same time.
-   https://youtu.be/POzuXyuF9DQ?si=WpHf0W2jAePgayPf
3.  Cross product only exists in 3D and 7D Vector Space
-   https://en.wikipedia.org/wiki/Cross_product#Generalizations
4.  The Quaternions Ring is the 4D Vector Space that can be used for describe rotation of 3D Object.
-   https://youtu.be/zjMuIxRvygQ?si=-UFgbKB1eu5stJrf
5.  Hypersphere have weird property
-   https://youtu.be/zwAD6dRSVyI?si=O7BCp7T_rkXYK8lm
6.  etc.
-   https://youtu.be/dr2sIoD7eeU?si=vF1h4ErhVPrz6SIe

I also have graphite color synesthesia and I want to know what color do the 2D representations of higher dimensional version of alphabet and number it feel for me.

# Status

This project is created in 2025, Apr 10th, it is unusable and in the MVP (minimum viable product) development process.

# Feature of MVP (minimum viable product)

## The expected features in MVP

1.  Allow user to define vector (a.k.a. point, defined by only 2D or 3D numpy float array) only in 2D and 3D Vector space over Real number manually or via their dataset (similar or same as Numpy and Pandas).
2.  Allow user to compose vector as 
    1.  straight line (defined by 2 vectors, both 2 ends of the line are defined by vectors)
    2.  long straight line (defined by 2 vectors, the line is long indefinitely, both 2 ends of line are defined by the boundary of visualization canvas)
    3.  2D polytope (defined by multiple straight lines)
    4.  3D polytope (defined by multiple 2D polytope)
    5.  tiling (defined by multiple straight lines and/or multiple long straight lines)
    6.  hyperplain (defined by one normal vector and one center vector)
2.  Allow user to use predefined 2D polytopes
    1.  2D square
    2.  2D equilateral triangle
    3.  2D hexagon
3.  Allow user to use predefined 2D tilings
    1.  multiple parallel straight lines with equal space in 2D subspace
    2.  2D square tiling
    3.  2D triangle tiling
4.  Allow user to use predefined 3D polytopes
    1.  3D cube
    2.  3D simplex
    3.  3D cross polytope
5.  Allow user to use predefined 3D tiling
    1.  3D cube tiling
6.  Allow user to transform all the vectors with defined linear map (only 2D and 3D square matrix) based on float numpy array.
7.  Visualizing the 2D representation of user defined 3D geometric objects (3d polytopes, 3d tiling, 2d hyperplain, 
    3d straight line and 3d long straight line) with the following methods
    1.  2D hyperplane cross section of 3D geometric objects
    2.  Use the projection algorithm that 3B1B demonstrate in this video (https://youtu.be/IQqtsm-bBRU?si=kFzA0KgvUY0ysyXQ) at 19:50 to 22:05.
    3.  Multiple 3D vector with singular matrix (matrix with determinant equal to 0)
8.  Compute basic linear algebra related algorithm.
    1.  Addition of Numpy array
    2.  Dot product
    3.  Matrix and scalar multiplication
    4.  Matrix power
    5.  Length of vector
    6.  Angle between 2 vectors
    7.  Vector projection to another vector
    8.  3D Cross product
    9.  Gaussian Elimination
    10. Null space
    11. Inverse Matrix
    12. Determinant
    13. Eigan Value
    14. Eigan Vector

## Future Plan after finish MVP

1.  Extend the MVP with higher dimensional Vector space over Real.
    1.  Allow user to define other linear transformed geometric object in higher dimensional Vector Space over Real.
    2.  Creating the 2D and 3D representation of higher dimensional geometric object via the same 3 algorithms in the MVP.
    3.  Hardware evaluation and optimization for defining higher dimensional objects.
2.  Add other dimensional reduction algorithms for creating 2D and 3D representation of high dimensional objects e.g. PCA, t-SNE, LDA etc.
3.  Add other famous geometric objects e.g. 4D platonic solid, sphere, torus, Möbius strip, Klein Bottle, multi dimensional Bezier curve, Archimedean solids, A, B, C, Z, Number 9, Number 3 etc.
4.  Check if 2 or more objects are collided with each other.
5.  Add domain specific features base on practical users, educational and/or ethical demand (https://80000hours.org/career-guide/most-pressing-problems/?int_campaign=2023-05--primary-navigation__career-guide)
    1.  More advanced linear algebra related features e.g. SVD, Matrix factorization, LU decomposition, Affine Transformation, Markov chain, Matrix exponential, randomized numerical linear algebra, Linear Programming, Random Matrix Theory etc.
    2.  More geometric algebra related features.
    3.  AI Transparency and optimization
    4.  Analyzing, optimizing and/or compressing high dimensional dataset
    5.  Relativity visualization
    6.  Lean Proof Assistent Integration for assisting pure mathematical research
    7.  Extend the Vector Space over Real to Module over commutative ring for specific domain e.g. cryptography, error correction etc.
    8.  Quantum Physic
    9.  Reinforcement learning framework for pure mathematical research e.g. Sphere Packing, Numerical Algorithm related optimization etc.
    10. Group decomposition of high dimensional tiling and polytopes.
    11. Other useful features.

# Folder structures

This project compose of the following sub folders
1.  `basic_script/`
-   Contains: user friendly Python script
2.  `canvas/`
-   Contains: Python scripts that allow user to visualize user's customized object in 2D and/or 3D Euclidean space.
3.  `doc/`
-   Contains: other additional documentation about our project.
4.  `doc_tutorial/`
-   Contains: other additional documentation about useful tool e.g. Python virtual environment, Git, Manim etc.
5.  `function/`
-   Contains: Function (a.k.a. map or transformation) script that compute output geometric object base on the user's input. I don't use name `map/` to prevent confusion with map (the 2d visual image that indicate the 2D position of object).
-   Examples: `linear_function/` and `dimensional_reduction/`
6.  `include/`
-   Contains: Class interface of `canvas/`, `function/` and `object/` for enhancing SOLID coding practice.
7.  `shape/`
-   Contains: Shape (a.k.a. Set of vectors that form shape e.g. cube, plane, triangle, 3D simplex, 2D alphabet etc.) and collection of shape that form tessellation e.g. 2D and 3D square Grid, 2D triangle grid etc.
8.  `tests/`
-   Contains: Coding scripts that check if our code works as expected.
9.  `utility/`
-   Contains: Python files for other purpose e.g. check hardware performance, save Manim output video and float-string type conversion etc

# How to Set up our project ?

1.  Click `<> Code` green button.
2.  Copy URL or `Download Zip`
3.  Install Python and pip
4.  `pip install -r requirements.txt`

Read this for more detail.
1.  How to install Python ?
-   https://www.python.org/downloads/
2.  How to install pip ?
-   https://pip.pypa.io/en/stable/installation/
3.  How to use Git ?
-   https://youtu.be/hwP7WQkmECE?si=3dpwnxaAztigW7x-
-   https://colab.research.google.com/drive/1ERz9tNhId3gBNsxGpvRWnqfY6x0LJFs-?usp=sharing
-   https://youtu.be/tRZGeaHPoaw?si=qNfziX2r9p-XARow

# How to help developing this project ?

You can help us by add new feature in `Feature of MVP (minimum viable product)` section, check if our project works as expected and/or write user tutorial. Thank you for your contribution.

# Recommended things to learn for this project

Recommended Things to learn
1.  Python, VSCode and Jupyter Notebook
2.  Numpy
3.  Matplotlib
4.  Manim
5.  Basic 2D Euclidean Geometry
6.  Linear Algebra
7.  PCA

Recommended Learning Resource
1.  Python for Everybody - Full University Python Course
-   This course is for anyone who never learn to code. I recommend you to watch first 6 hours of this video and code with both Jupyter Notebook (a.k.a. Google Colab) and VSCode actively.
-   https://youtu.be/8DvywoWv6fI?si=pFdGTq9ShrrHUedg
2.  3B1B's Linear Algebra Series
-   https://www.3blue1brown.com/topics/linear-algebra
3.  Linear Algebra Done Right
-   This book is not the prerequisite for this project but it provide insight about linear algebra.
-   https://linear.axler.net/

# Additional Information

-	Read `doc/` for more additional information about our project.
