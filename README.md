# Description

`arabesque_of_alkhwarizmi` is Numpy-Manim based Python library that is used for visualizing 2D and 3D representation of 3D, 4D 
and/or 5D objects e.g. 4D Platonic Solids, Hypersphere, Klein bottle etc. 
This tools help user learn interesting mathematical concept e.g. Linear Algebra, Group Theory, Lie Algebra, Topology etc 
and generating cool looking visual art.

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
5.  etc.
-   https://youtu.be/dr2sIoD7eeU?si=vF1h4ErhVPrz6SIe

I also have graphite color synesthesia and I want to know what color do the 2D representations of higher dimensional version of alphabet and number it feel for me.

# Status

This project is created in 2025, Apr 10th, it is unusable and in the MVP (minimum viable product) development process.

# Feature of MVP (minimum viable product)

The expected features of MVP include
1.  2D and 3D Linear Algebra visualization
-   Visualizing multiple linear transformed grids in 2D and 3D similar to 3Blue1Brown's Linear Algebra seires.
2.  2d image, 2d square, 3D cube, 3D simplex, 3D orthoplex, 2D triangle, 2D plane, line and point
-   Allow user to define size, color and position of only linear transformed 2d image, 2d square, 3D cube, 2D plane, 
    line and point in 2D and 3D Euclidean Space with user customized matrix (a.k.a. linear map).
-   Allow user to place objects such that it become space filling tiling e.g. 2D square grid, 2D triangle tiling, 3D cube grid etc.
3.  PCA and cross section 2D representation
-   Allow user to visualize the 2D representation of the user defined 3D objects by either by using PCA or 2D plane cross section.
4.  Solving Basic Linear Equation
-   Calculating Gaussian Elimination, Null space, 3D Cross product, Eigan Value, Eigan Vector, Inverse Matrix, Determinant, Matrix multiplication and Matrix power.

Ignore advanced features (we might add those features in the future)
1.  4D n-d higher dimensional general space
-   Define and visualizing object in 4D and higher dimensional Euclidean space, and Non-Euclidean space.
2.  Other object
-   e.g. 2D pentagon, 2D heptagon, 3D Dodecahedron, 4D cube, Torus, 2D circle, user's 3D or higher dimensional model, user high dimensional data, A B C alphabets etc.
3.  Use other dimensional reduction algorithm for visualization e.g. t-SNE, LDA etc.
4.  Analyzing the numerical error, limit, connectedness, surface area, volume, unknotting number, tangent space and other properties of shape.
5.  Check if any 2 or more objects are collided with each other.
6.  Solve more advanced Equation
-   e.g. SVD, Matrix Exponential, Symmetrical Group decomposition of the user defined symmetrical object, Linear Programming, construct the 3D model out of 2D rotated images, Matrix infinite series and product etc
7.  Other related advanced visualization e.g. Sphere packing, Euler characteristic, Lie Group for defining rotation etc.

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
