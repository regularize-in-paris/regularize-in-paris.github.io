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
    <td>A. Montanari (4/4)</td>
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
    <td>C. Fernandez-Granda</td>
    <td>É. Chouzenoux</td>
    <td>C. Boyer</td>
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
    <td>L. Rosasco (1/4)</td>
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
    <td>L. Rosasco (2/4)</td>
    <td>L. Rosasco (4/4)</td>
  </tr>
  </table>


___
<mark>Start:</mark> We welcome the participants on Monday June 19th from 9h to 9h30 at IHP.

Abstracts
-------


**Francis Bach (INRIA)**: Submodular Functions: from Discrete to Continuous Domains <br/>
_Abstract:_ Submodular set-functions have many applications in combinatorial optimization, as they can be minimized and approximately maximized in polynomial time. A key element in many of the algorithms and analyses is the possibility of extending the submodular set-function to a convex function, which opens up tools from convex optimization. Submodularity goes beyond set-functions and has naturally been considered for problems with multiple labels or for functions defined on continuous domains, where it corresponds essentially to cross second-derivatives being nonpositive. In this talk, I will show that most results relating submodularity and convexity for set-functions can be extended to all submodular functions. In particular, (a) I will naturally define a continuous extension in a set of probability measures, (b) show that the extension is convex if and only if the original function is submodular, (c) prove that the problem of minimizing a submodular function is equivalent to a typically non-smooth convex optimization problem. Most of these extensions from the set-function situation are obtained by drawing links with the theory of multi-marginal optimal transport, which provides also a new interpretation of existing results for set-functions. I will then provide practical algorithms to minimize generic submodular functions on discrete domains, with associated convergence rates, and an application to proximal operators for non-convex penalty functions. [Preprint available here](https://hal.archives-ouvertes.fr/hal-01222319v2/document).


**Claire Boyer (UPMC)** Towards realistic compressed sensing
<br/>
_Abstract:_  First, we will theoretically justify the applicability of compressed sensing (CS) in real-life applications. To do so, CS theorems compatible with physical acquisition constraints will be presented. These new results do not only encompass structure in the acquisition but also structured sparsity of the signal of interest. They also provide insight on the choice of the optimal sampling strategy. Then, we will present a way to generate constrained subsampling schemes that can be implemented on real sensors while mimicking sampling strategies known to be theoretically optimal but unusable in practice. This sampling scheme generation give good reconstruction results in simulation.
This work relies on measure projection and will be illustrated in the case of MRI.

**Emilie Chouzenoux (Paris-Est)**: Majorization-Minimization Subspace Algorithms for Large Scale Data Processing<br/>
_Abstract:_ Recent developments in data processing drive the need for solving optimization problems with increasingly large sizes, stretching traditional techniques to their limits. New optimization algorithms have thus to be designed, paying attention to computational complexity, scalability, and robustness. Majorization-Minimization (MM) approaches have become increasingly popular recently, in both signal/image processing and machine learning areas. Our talk will present new theoretical and practical results regarding the MM subspace algorithm [1], where the update of each iterate is restricted to a subspace spanned by few directions. We will first present the extension of this method to the online case when only a stochastic approximation of the criterion is employed at each iteration [2], and we will analyse its convergence rate properties [3]. In a second part of the talk, a novel block parallel MM subspace algorithm will be introduced, which can take advantage of the potential acceleration provided by multicore architectures [4]. Several examples, in the context of signal/image processing will be presented, to illustrate the efficiency of these methods. <br/>
[1] E. Chouzenoux, A. Jezierska, J.-C. Pesquet and H. Talbot. A Majorize-Minimize Subspace Approach for l2-l0 Image Regularization. SIAM Journal on Imaging Science, Vol. 6, No. 1, pages 563-591, 2013. <br/>
[2] E. Chouzenoux and J.-C. Pesquet. A Stochastic Majorize-Minimize Subspace Algorithm for Online Penalized Least Squares Estimation. [Tech. Rep.](http://arxiv.org/abs/1512.08722), 2016. <br/>
[3] E. Chouzenoux and J.-C. Pesquet. Convergence Rate Analysis of the Majorize-Minimize Subspace Algorithm. IEEE Signal Processing Letters, Vol. 23, No. 9, pages 1284-1288, Septembre 2016. <br/>
[4] S. Cadoni, E. Chouzenoux, J.-C. Pesquet and C. Chaux. A Block Parallel Majorize-Minimize Memory Gradient Algorithm. In Proceedings of the 23rd IEEE International Conference on Image Processing (ICIP 2016), pages 3194-3198, Phoenix, Arizona, 25-28 septembre 2016.

**Carlos Fernandez-Granda (NYU)**: A sampling theorem for robust deconvolution<br/>
_Abstract:_ In the 70s and 80s geophysicists proposed using l1-norm regularization for deconvolution problem in the context of reflection seismology. Since then such methods have had a great impact in high-dimensional statistics and in signal-processing applications, but until recently their performance on the original deconvolution problem was not well understood theoretically. In this talk we provide an analysis of optimization-based methods for the deconvolution problem, including results on irregular sampling and sparse corruptions that highlight the modeling flexibility of these techniques.



**Anders Hansen  (Cambridge)**  Lectures 1 and 2: Compressed Sensing: Structure and Imaging
<br/>
_Abstract:_ The above heading is the title of a new book to be published by Cambridge University Press. In these lectures I will cover some of the main issues discussed in this monograph/textbook. In particular, we will discuss how the key to the success of compressed sensing applied in imaging lies in the structure. For example images are not just sparse in an X-let expansion, they have a very specific sparsity structure in levels according to the X-let scales. Similarly, when considering Total Variation, the gradient coefficients are also highly structured. Moreover, in most realistic sampling scenarios, the sampling operator combined with any X-let transform yields a matrix with a very specific coherence structure. The key to successfully use compressed sensing is therefore to understand how to utilise these structures in an optimal way, in particular in the sampling procedure. In addition, as the coherence and sparsity structures have very particular asymptotic behaviour, the performance of compressed sensing varies greatly with dimension, and so does the optimal way of sampling. Fortunately, there is now a developed theory that can guide the user in detail on how to optimise the use of compressed sensing in inverse and imaging problems. I will cover several of the key aspects of the theory accompanied with real-world examples from Magnetic Resonance Imaging (MRI), Nuclear Magnetic Resonance (NMR), Surface Scattering, Electron Microscopy, Fluorescence Microscopy etc.  

_Recommended readings:_ (lectures 1 and 2)

- Chapter 4, 6 and 12 in “A mathematical introduction to compressed sensing” (Foucard/Rauhut)
- [Breaking the coherence barrier: A new theory for compressed sensing](https://www.cambridge.org/core/journals/forum-of-mathematics-sigma/article/div-classtitlebreaking-the-coherence-barrier-a-new-theory-for-compressed-sensingdiv/455E5F506912B78E9647CD7A7488530B)
- [On asymptotic structure in compressed sensing](https://arxiv.org/pdf/1406.4178.pdf)
- [Structure dependent sampling in compressed sensing: theoretical guarantees for tight frames](http://www.damtp.cam.ac.uk/user/cmhsp2/frames_revised.pdf)

Lectures 3 and 4: On Foundational Computational Problems in l1 and Total Variation Regularisation
<br/>
_Abstract:_  The use of regularisation techniques such as l1 and Total Variation in Basis Pursuit and Lasso has been a great success in wide areas of mathematics and statistics over the last decades. However, in these lectures I will discuss the following paradox: it is impossible to design algorithms to solve these general problems accurately when given inaccurate input data, even when the inaccuracies can be made arbitrarily small. As a simple number such as root(2) never comes with an exact numerical representation, inaccurate data input is a daily encounter. The impossibility result implies that for any algorithm designed to solve these problems there will be cases where the algorithm fails in the following way: For fixed dimensions and any small accuracy parameter epsilon > 0, one can choose an arbitrary large time T and find an input such that the algorithm will run for longer than T and still not have reached epsilon accuracy. Moreover, it is impossible to determine when the algorithm should halt to achieve an epsilon accurate solution, and hence the algorithm will never be able to produce an output where one knows that the output is at least epsilon accurate. The largest epsilon for which this failure happens is called the Breakdown-epsilon. For Basis Pursuit and Lasso, the breakdown epsilon is greater than 1/3 even when the input is well conditioned. <br/>
The paradox opens up for a new rather delicate classification theory of which problems can be computed accurately. For example, given standard assumptions from sparse recovery, there are algorithms that can compute a solution to Basis Pursuit accurately, however, this is impossible for Lasso and Basis Pursuit with noise parameter delta > 0. However, one can compute a solution accurately up to the Breakdown-epsilon that tends to zero when delta tends to zero, and coincides with the error bound provided in the theory of sparse recovery. This helps explaining the success of many modern algorithms applied in numerous real-world scenarios, and also explains the cases where algorithms will fail and why.

_Recommended readings:_ (lectures 3 and 4)
- Chapter 3 and 15 in [A mathematical introduction to compressed sensing](http://www.springer.com/de/book/9780817649470) (Foucard/Rauhut).
- [A first-order primal-dual algorithm for convex problems with applications to imaging](https://hal.archives-ouvertes.fr/hal-00490826/document)


**Andrea Montanari (Stanford)**: Matrix and graph estimation
<br/>
_Abstract:_ Many statistics and unsupervised learning problems can be formalized as
estimating a structured matrix or a graph from noisy or incomplete observations.
These problems present a large variety of challenges, and an intriguing interplay between computational and statistical barriers. I will provide an introduction to recent work  in the area, with an emphasis on general methods and unifying themes.
<br/>
1) Random matrix theory and spectral methods.<br/>
2) The semidefinite programming approach to graph clustering.<br/>
3) Local algorithms and graphical models. The hidden clique problem.<br/>
4) Non-negative matrix factorization.<br/>


**Lorenzo Rosasco (Genova and MIT)**: Regularization Methods for Large Scale Machine Learning
<br/>
_Abstract:_ Regularization techniques originally developed to solve linear  inverse problems can be extended to derive nonparametric machine learning methods.  These methods perform well in practice and can be shown to have optimal  statistical guarantees, however, computational requirements  can prevent application to large scale scenarios. In this talk, we will describe recent attempts  to tackle this challenge. Our presentation will be divided in two parts. In the first part, we will discuss so called iterative regularization, aka early stopping regularization. In particular, we will discuss accelerated and stochastic variants of this method and show how they allow to control at the same time the statistical and time complexities of the obtained solutions. In the second part, we will discuss  novel regularization schemes obtained combining regularization with stochastic projections. These latter methods allow to control not only the statistical and time complexities of the obtained solutions but also the memory requirements.
