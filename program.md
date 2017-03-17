---
layout: page
title: "Structured Regularization Summer School"
description: "Program"
header-img: "img/ihp2.jpg"
---

<table style="align:center" border="1">
  <tr style="color:red">
    <th style="width:14%"></th>
    <th style="width:21%">Mon 19</th>
    <th style="width:21%">Tue 20</th>
    <th style="width:21%">Wed 21</th>
    <th style="width:21%">Thu 22</th>
  </tr>
  <tr style="color:black">
    <td>9h30-11h</td>
    <td>A. Hansen (1/4)</td>
    <td>A. Hansen (3/4)</td>
    <td>A. Montanari (3/4)</td>
    <td>L. Rosasco (2/4)</td>
  </tr>
  <tr color="black">
    <td>11h-11h30 </td>
    <td>Coffee break</td>
    <td>Coffee break</td>
    <td>Coffee break</td>
    <td>Coffee break</td>
  </tr>
    <tr color="black">
    <td>11h30-12h30</td>
    <td>F. Bach</td>
    <td>É. Chouzenoux</td>
    <td>C. Fernandez-Granda</td>
    <td>R. Ward</td>
  </tr>
    <tr color="black">
    <td>12h30-14h</td>
    <td>Lunch</td>
    <td>Lunch</td>
    <td>Lunch</td>
    <td>Lunch</td>
  </tr>
    <tr color="black">
    <td>14h-15h30</td>
    <td>A. Hansen (2/4)</td>
    <td>A. Hansen (4/4)</td>
    <td>A. Montanari (4/4)</td>
    <td>L. Rosasco (3/4)</td>
  </tr>
    <tr color="black">
    <td>15h30-16h</td>
    <td>Coffee break</td>
    <td>Coffee break</td>
    <td>Coffee break</td>
    <td>Coffee break</td>
  </tr>
    <tr color="black">
    <td>16h-17h30</td>
    <td>A. Montanari (1/4)</td>
    <td>A. Montanari (2/4)</td>
    <td>L. Rosasco (1/4)</td>
    <td>L. Rosasco (4/4)</td>
  </tr>
  </table>


___
<mark>Start:</mark> We welcome the participants on Monday June 19th from 9h to 9h30 at IHP.

Abstracts
-------


**Francis Bach (INRIA)**: Submodular Functions: from Discrete to Continuous Domains <br/>
_Abstract:_ Submodular set-functions have many applications in combinatorial optimization, as they can be minimized and approximately maximized in polynomial time. A key element in many of the algorithms and analyses is the possibility of extending the submodular set-function to a convex function, which opens up tools from convex optimization. Submodularity goes beyond set-functions and has naturally been considered for problems with multiple labels or for functions defined on continuous domains, where it corresponds essentially to cross second-derivatives being nonpositive. In this talk, I will show that most results relating submodularity and convexity for set-functions can be extended to all submodular functions. In particular, (a) I will naturally define a continuous extension in a set of probability measures, (b) show that the extension is convex if and only if the original function is submodular, (c) prove that the problem of minimizing a submodular function is equivalent to a typically non-smooth convex optimization problem. Most of these extensions from the set-function situation are obtained by drawing links with the theory of multi-marginal optimal transport, which provides also a new interpretation of existing results for set-functions. I will then provide practical algorithms to minimize generic submodular functions on discrete domains, with associated convergence rates, and an application to proximal operators for non-convex penalty functions. [Preprint available here](https://hal.archives-ouvertes.fr/hal-01222319v2/document).

**Emilie Chouzenoux (Paris-Est)**: Majorization-Minimization Subspace Algorithms for Large Scale Data Processing<br/>
_Abstract:_ Recent developments in data processing drive the need for solving optimization problems with increasingly large sizes, stretching traditional techniques to their limits. New optimization algorithms have thus to be designed, paying attention to computational complexity, scalability, and robustness. Majorization-Minimization (MM) approaches have become increasingly popular recently, in both signal/image processing and machine learning areas. Our talk will present new theoretical and practical results regarding the MM subspace algorithm [1], where the update of each iterate is restricted to a subspace spanned by few directions. We will first present the extension of this method to the online case when only a stochastic approximation of the criterion is employed at each iteration [2], and we will analyse its convergence rate properties [3]. In a second part of the talk, a novel block parallel MM subspace algorithm will be introduced, which can take advantage of the potential acceleration provided by multicore architectures [4]. Several examples, in the context of signal/image processing will be presented, to illustrate the efficiency of these methods. <br/>
[1] E. Chouzenoux, A. Jezierska, J.-C. Pesquet and H. Talbot. A Majorize-Minimize Subspace Approach for l2-l0 Image Regularization. SIAM Journal on Imaging Science, Vol. 6, No. 1, pages 563-591, 2013. <br/>
[2] E. Chouzenoux and J.-C. Pesquet. A Stochastic Majorize-Minimize Subspace Algorithm for Online Penalized Least Squares Estimation. [Tech. Rep.](http://arxiv.org/abs/1512.08722), 2016. <br/>
[3] E. Chouzenoux and J.-C. Pesquet. Convergence Rate Analysis of the Majorize-Minimize Subspace Algorithm. IEEE Signal Processing Letters, Vol. 23, No. 9, pages 1284-1288, Septembre 2016. <br/>
[4] S. Cadoni, E. Chouzenoux, J.-C. Pesquet and C. Chaux. A Block Parallel Majorize-Minimize Memory Gradient Algorithm. In Proceedings of the 23rd IEEE International Conference on Image Processing (ICIP 2016), pages 3194-3198, Phoenix, Arizona, 25-28 septembre 2016.

**Carlos Fernandez-Granda (NYU)**: A sampling theorem for robust deconvolution

**Lorenzo Rosasco (Genova and MIT)**: Regularization Methods for Large Scale Machine Learning
<br/>
_Abstract:_ Regularization techniques originally developed to solve linear  inverse problems can be extended to derive nonparametric machine learning methods.  These methods perform well in practice and can be shown to have optimal  statistical guarantees, however, computational requirements  can prevent application to large scale scenarios. In this talk, we will describe recent attempts  to tackle this challenge. Our presentation will be divided in two parts. In the first part, we will discuss so called iterative regularization, aka early stopping regularization. In particular, we will discuss accelerated and stochastic variants of this method and show how they allow to control at the same time the statistical and time complexities of the obtained solutions. In the second part, we will discuss  novel regularization schemes obtained combining regularization with stochastic projections. These latter methods allow to control not only the statistical and time complexities of the obtained solutions but also the memory requirements.
