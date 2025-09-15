**basics:**
- 
- 
- *vector projection:*
  - 
  - ![](./images/image_1.a2a38ccd.emf)

**cross product:**
- for vectors $\stackrel{~}{\bm{a}}$ and $\stackrel{~}{\bm{b}}$, the cross product $\stackrel{~}{\bm{a}}\times \stackrel{~}{\bm{b}}$ is a vector perpendicular to $\stackrel{~}{\bm{a}}$ and $\stackrel{~}{\bm{b}}$
  - *i.e.* it is normal to the plane containing $\stackrel{~}{\bm{a}}$ and $\stackrel{~}{\bm{b}}$
- $\left|\stackrel{~}{\bm{a}}\times \stackrel{~}{\bm{b}}\right|=\left|\stackrel{~}{\bm{a}}\right|\left|\stackrel{~}{\bm{b}}\right|\mathrm{sin}\mathit{\theta}$, where $\theta $ is the angle between $\stackrel{~}{\bm{a}}$ and $\stackrel{~}{\bm{b}}$
  - this also gives the area bounded by the parallelogram formed from $\stackrel{~}{\bm{a}}$ and $\stackrel{~}{\bm{b}}$
- *manually calculating cross product:*
  - ![](./images/image_2.7bab86df.emf)

**lines:**
- consider a line passing through $\left(\begin{array}{c}2\\ -1\\ 3\end{array}\right)$ and parallel to $\left(\begin{array}{c}1\\ 2\\ 3\end{array}\right)$
- *vector equation:*
  - 
- *parametric equation:*
  - 
- *cartesian equation:*
  - 
**planes:**
- consider a line passing through position vector $\stackrel{~}{a}$ and containing two non-parallel vectors $\stackrel{~}{b}$ and $\stackrel{~}{c}$
- *vector equation:*
  - 
  - ![](./images/image_3.57965e1e.emf)
- *cartesian equation:*
  - ![](./images/image_4.9942acb4.emf)
   $\stackrel{\u20d1}{\bm{A}\bm{R}}$ is always perpendicular to $\stackrel{~}{\bm{n}}$
  
  
  
  
  
**spheres:**
- *vector equation:*
  - 
  - where:
    -  $r$ is the radius
    -  $\stackrel{~}{\bm{c}}$ is the position vector of the centre
  - ![](./images/image_5.ca78936e.emf)
- *cartesian equation:*
  - 
  - where:
    -  $r$ is the radius
    -  $\left(\begin{array}{c}a\\ b\\ c\end{array}\right)$ is the position vector of the centre

**systems of linear equations:**
- *gaussian elimination:*
  1. form an augmented matrix from equations
    - ![](./images/image_6.d2f641e0.emf)
  2. conduct forward elimination
    - choose a pivot entry and eliminate all entries below the pivot by replacing rows
    - repeat for each column until the matrix is in row echelon form
    - ![](./images/image_7.49b6a461.emf)
  3. conduct back-substitution to solve for variables
    - ![](./images/image_8.5d9d05cd.emf)
note that cases 1,2, and 3 have no simultaneous solution as no point lies on all three planes at once
1. three parallel planes
  - all 3 normals are parallel (multiples of each other)
  - the constants at the end of the cartesian equation distinguish the planes
2. two planes parallel and one intersecting
  - two normals are parallel while one isn’t
3. planes intersecting in pairs of parallel lines
  - all 3 normals are non-parallel
  - one normal is a linear combination of the other two
4. planes intersecting in a line
  - one plane is a linear combination of the other planes
  - all 3 normals are non-parallel
5. planes intersecting at a point
  - if the triple scalar product of the normals does not equal zero, there is a single point of intersection
  - *i.e. *${\stackrel{~}{n}}_{1}\cdot \left({\stackrel{~}{n}}_{2}\times {\stackrel{~}{n}}_{3}\right)\ne 0$
- note that cases 1,2, and 3 have no simultaneous solution as no point lies on all three planes at once
**closest distance:**
- *line to point:*
  - ![](./images/image_9.d0e0c80b.emf)
- *plane to point:*
  - ![](./images/image_10.1e6361a2.emf)
- *line to line:*
  - ![](./images/image_11.0adeadff.emf)

-----
