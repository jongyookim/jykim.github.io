---
title: Welcome
layout: default
---



I am a third-year Computer Science Ph.D. student at Carnegie Mellon University and am supported by an NSF graduate research fellowship. I spent the first two years of my Ph.D. working between mobile systems and applied machine learning and I now work with [Zico Kolter](http://zicokolter.com/) on machine learning and optimization. I am particularly interested in improving our understanding of important modeling problems in computer vision, language, and reinforcement learning through the use of deep learning, optimization (sometimes convex), theory, and statistics. As examples, see our [input-convex neural network](https://arxiv.org/abs/1609.07152) and [OptNet](https://arxiv.org/abs/1703.00443) papers.

I strongly believe in open science and reproducible research and actively publish code on [my Github profile](https://github.com/bamos). I am also the author of [OpenFace](https://cmusatyalab.github.io/openface/), which is an open source face recognition project that uses deep learning.


## <i class="fa fa-chevron-right"></i> Education

<table class="table table-hover">
  <tr>
    <td class="col-md-3">Aug 2014 - Present</td>
    <td>
        <strong>Ph.D. in Computer Science</strong>
        <br>
      Carnegie Mellon University
    </td>
  </tr>
  <tr>
    <td class="col-md-3">Aug 2014 - May 2016</td>
    <td>
        <strong>M.S. in Computer Science</strong>
        <br>
      Carnegie Mellon University
    </td>
  </tr>
  <tr>
    <td class="col-md-3">Aug 2011 - May 2014</td>
    <td>
        <strong>B.S. in Computer Science</strong>
          (3.99/4.00)
        <br>
      Virginia Tech
    </td>
  </tr>
  <tr>
    <td class="col-md-3">May 2011</td>
    <td>
      Northside High School (Roanoke, Virginia)
    </td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Research Experience
<table class="table table-hover">
<tr>
  <td class='col-md-3'>Apr 2016 - Present</td>
  <td>
    <strong>Carnegie Mellon University</strong>, Prof. Zico Kolter <br>
    Machine learning and optimization
  </td>
</tr>
<tr>
  <td class='col-md-3'>Aug 2014 - Apr 2016</td>
  <td>
    <strong>Carnegie Mellon University</strong>, Prof. Mahadev Satyanarayanan <br>
    Applied machine learning and mobile systems
  </td>
</tr>
<tr>
  <td class='col-md-3'>May 2012 - May 2014</td>
  <td>
    <strong>Virginia Tech</strong>, Prof. Jules White <br>
    Mobile systems, cyber-physical systems, and security
  </td>
</tr>
<tr>
  <td class='col-md-3'>Jan 2013 - May 2014</td>
  <td>
    <strong>Virginia Tech</strong>, Prof. Layne Watson <br>
    Scientific computing, global/stochastic optimization, and bioinformatics
  </td>
</tr>
<tr>
  <td class='col-md-3'>Nov 2012 - Mar 2014</td>
  <td>
    <strong>Virginia Tech</strong>, Prof. Binoy Ravindran <br>
    Heterogeneous compilers
  </td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Selected Publications <a href="https://github.com/bamos/cv/blob/master/publications/selected.bib"><i class="fa fa-code-fork" aria-hidden="true"></i></a>

<a href="https://scholar.google.com/citations?user=CZwrwHAAAAAJ" class="btn btn-primary" style="padding: 0.3em;">
  <i class="ai ai-google-scholar"></i> Google Scholar
</a>

<table class="table table-hover">

<tr>
<td class="col-md-3"><a href='http://arxiv.org/abs/1703.00443' target='_blank'><img src="images/publications/amos2017optnet.png"/></a> </td>
<td>
    <strong>OptNet: Differentiable Optimization as a Layer in Neural Networks</strong><br>
    <strong>B. Amos</strong> and J. Kolter<br>
    arXiv 2017<br>
    [1]
[<a href='javascript: none'
    onclick='$("#abs_amos2017optnet").toggle()'>abs</a>] [<a href='http://arxiv.org/abs/1703.00443' target='_blank'>pdf</a>]  [<a href='https://github.com/locuslab/optnet' target='_blank'>code</a>] <br>

<div id="abs_amos2017optnet" style="text-align: justify; display: none" markdown="1">
This paper presents OptNet, a network architecture that integrates
optimization problems (here, specifically in the form of quadratic
programs) as individual layers in larger end-to-end trainable deep
networks. These layers allow complex dependencies between the hidden
states to be captured that traditional convolutional and
fully-connected layers are not able to capture. In this paper, we
develop the foundations for such an architecture: we derive the
equations to perform exact differentiation through these layers and
with respect to layer parameters; we develop a highly efficient solver
for these layers that exploits fast GPU-based batch solves within a
primal-dual interior point method, and which provides backpropagation
gradients with virtually no additional cost on top of the solve; and
we highlight the application of these approaches in several
problems. In one particularly standout example, we show that the
method is capable of learning to play Sudoku given just input and
output games, with no a priori information about the rules of the
game; this task is virtually impossible for other neural network
architectures that we have experimented with, and highlights the
representation capabilities of our approach.
</div>

</td>
</tr>


<tr>
<td class="col-md-3"><a href='http://arxiv.org/abs/1703.04529' target='_blank'><img src="images/publications/donti2017task.png"/></a> </td>
<td>
    <strong>Task-based End-to-end Model Learning</strong><br>
    P. Donti, <strong>B. Amos</strong>, and J. Kolter<br>
    arXiv 2017<br>
    [2]
[<a href='javascript: none'
    onclick='$("#abs_donti2017task").toggle()'>abs</a>] [<a href='http://arxiv.org/abs/1703.04529' target='_blank'>pdf</a>]  [<a href='https://github.com/locuslab/e2e-model-learning' target='_blank'>code</a>] <br>

<div id="abs_donti2017task" style="text-align: justify; display: none" markdown="1">
As machine learning techniques have become more ubiquitous, it has
become common to see machine learning prediction algorithms operating
within some larger process. However, the criteria by which we train
machine learning algorithms often differ from the ultimate criteria on
which we evaluate them. This paper proposes an end-to-end approach for
learning probabilistic machine learning models within the context of
stochastic programming, in a manner that directly captures the
ultimate task-based objective for which they will be used. We then
present two experimental evaluations of the proposed approach, one as
applied to a generic inventory stock problem and the second to a
real-world electrical grid scheduling task. In both cases, we show
that the proposed approach can outperform both a traditional modeling
approach and a purely black-box policy optimization approach.
</div>

</td>
</tr>


<tr>
<td class="col-md-3"><a href='http://arxiv.org/abs/1609.07152' target='_blank'><img src="images/publications/amos2016input.png"/></a> </td>
<td>
    <strong>Input Convex Neural Networks</strong><br>
    <strong>B. Amos</strong>, L. Xu, and J. Kolter<br>
    arXiv 2016<br>
    [3]
[<a href='javascript: none'
    onclick='$("#abs_amos2016input").toggle()'>abs</a>] [<a href='http://arxiv.org/abs/1609.07152' target='_blank'>pdf</a>]  [<a href='https://github.com/locuslab/icnn' target='_blank'>code</a>] <br>

<div id="abs_amos2016input" style="text-align: justify; display: none" markdown="1">
This paper presents the input convex neural network
architecture. These are scalar-valued (potentially deep) neural
networks with constraints on the network parameters such that the
output of the network is a convex function of (some of) the
inputs. The networks allow for efficient inference via optimization
over some inputs to the network given others, and can be applied to
settings including structured prediction, data imputation, reinforcement learning, and others. In this paper we lay the basic
groundwork for these models, proposing methods for inference, optimization and learning, and analyze their representational
power. We show that many existing neural network architectures can be
made input-convex with only minor modification, and develop
specialized optimization algorithms tailored to this setting. Finally, we highlight the performance of the methods on multi-label prediction, image completion, and reinforcement learning problems, where we show
improvement over the existing state of the art in many cases.
</div>

</td>
</tr>


<tr>
<td class="col-md-3"><a href='http://www.cs.cmu.edu/~hzhao1/papers/ICML2016/BL-SPN-main.pdf' target='_blank'><img src="images/publications/zhao2016collapsed.png"/></a> </td>
<td>
    <strong>Collapsed Variational Inference for Sum-Product Networks</strong><br>
    H. Zhao, T. Adel, G. Gordon, and <strong>B. Amos</strong><br>
    ICML 2016<br>
    [4]
[<a href='javascript: none'
    onclick='$("#abs_zhao2016collapsed").toggle()'>abs</a>] [<a href='http://www.cs.cmu.edu/~hzhao1/papers/ICML2016/BL-SPN-main.pdf' target='_blank'>pdf</a>] <br>

<div id="abs_zhao2016collapsed" style="text-align: justify; display: none" markdown="1">
Sum-Product Networks (SPNs) are probabilistic inference machines that admit
exact inference in linear time in the size of the network. Existing
parameter learning approaches for SPNs are largely based on the maximum
likelihood principle and hence are subject to overfitting compared to
more Bayesian approaches. Exact Bayesian posterior inference for SPNs is
computationally intractable. Both standard variational inference and
posterior sampling for SPNs are computationally infeasible even for
networks of moderate size due to the large number of local latent
variables per instance. In this work, we propose a novel deterministic
collapsed variational inference algorithm for SPNs that is
computationally efficient, easy to implement and at the same time allows
us to incorporate prior information into the optimization formulation.
Extensive experiments show a significant improvement in accuracy compared
with a maximum likelihood based approach.
</div>

</td>
</tr>


<tr>
<td class="col-md-3"><a href='http://reports-archive.adm.cs.cmu.edu/anon/anon/2016/CMU-CS-16-118.pdf' target='_blank'><img src="images/publications/amos2016openface.png"/></a> </td>
<td>
    <strong>OpenFace: A general-purpose face recognition library with mobile applications</strong><br>
    <strong>B. Amos</strong>, B. Ludwiczuk, and M. Satyanarayanan<br>
    CMU 2016<br>
    [5]
[<a href='javascript: none'
    onclick='$("#abs_amos2016openface").toggle()'>abs</a>] [<a href='http://reports-archive.adm.cs.cmu.edu/anon/anon/2016/CMU-CS-16-118.pdf' target='_blank'>pdf</a>]  [<a href='https://cmusatyalab.github.io/openface' target='_blank'>code</a>] <br>

<div id="abs_amos2016openface" style="text-align: justify; display: none" markdown="1">
Cameras are becoming ubiquitous in the Internet of Things (IoT) and
can use face recognition technology to improve context. There is a
large accuracy gap between today's publicly available face recognition
systems and the state-of-the-art private face recognition
systems. This paper presents our OpenFace face recognition library
that bridges this accuracy gap. We show that OpenFace provides
near-human accuracy on the LFW benchmark and present a new
classification benchmark for mobile scenarios. This paper is intended
for non-experts interested in using OpenFace and provides a light
introduction to the deep neural network techniques we use.

We released OpenFace in October 2015 as an open source library under
the Apache 2.0 license. It is available at:
<http://cmusatyalab.github.io/openface/>
</div>

</td>
</tr>


<tr>
<td class="col-md-3"><a href='https://vtechworks.lib.vt.edu/bitstream/handle/10919/49672/qnTOMS14.pdf' target='_blank'><img src="images/publications/amos2014QNSTOP.png"/></a> </td>
<td>
    <strong>QNSTOP-QuasiNewton Algorithm for Stochastic Optimization</strong><br>
    <strong>B. Amos</strong>, D. Easterling, L. Watson, W. Thacker, B. Castle, and M. Trosset<br>
    VT 2014<br>
    [6]
[<a href='javascript: none'
    onclick='$("#abs_amos2014QNSTOP").toggle()'>abs</a>] [<a href='https://vtechworks.lib.vt.edu/bitstream/handle/10919/49672/qnTOMS14.pdf' target='_blank'>pdf</a>] <br>

<div id="abs_amos2014QNSTOP" style="text-align: justify; display: none" markdown="1">
QNSTOP consists of serial and parallel (OpenMP) Fortran 2003 codes for the
quasi-Newton stochastic optimization method of Castle and Trosset. For
stochastic problems, convergence theory exists for the particular
algorithmic choices and parameter values used in QNSTOP. Both the parallel
driver subroutine, which offers several parallel decomposition strategies, and the serial driver subroutine can be used for stochastic optimization or
deterministic global optimization, based on an input switch. QNSTOP is
particularly effective for “noisy” deterministic problems, using only
objective function values. Some performance data for computational systems
biology problems is given.
</div>

</td>
</tr>


</table>


## <i class="fa fa-chevron-right"></i> Industry Experience
<table class="table table-hover">
<tr>
  <td class='col-md-3'>May 2014 - Aug 2014</td>
  <td><strong>Adobe Research</strong>, Data Scientist Intern</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I built a web analytics processing engine using **Scala**, **Spark**, **Spray**, **Parquet**, and **HDFS**.
</li>
</ul>
</td>
</tr>
<tr>
  <td class='col-md-3'>Dec 2013 - Jan 2014</td>
  <td><strong>Snowplow Analytics</strong>, Software Engineer Intern</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
Open-source **Scala** development with a startup on the Snowplow analytics platform. My commits are online at [https://github.com/snowplow/snowplow/commits?author=bamos](https://github.com/snowplow/snowplow/commits?author=bamos).
</li>
<li markdown="1">
Developed a new server using **Spray** and **Actors** to store **Thrift** events on **Amazon Kinesis**.
</li>
</ul>
</td>
</tr>
<tr>
  <td class='col-md-3'>May 2013 - Aug 2013</td>
  <td><strong>Qualcomm</strong>, Software Engineer Intern</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I created a specification format language translator for fuzz testing with Python.
</li>
</ul>
</td>
</tr>
<tr>
  <td class='col-md-3'>May 2012 - Aug 2012</td>
  <td><strong>Phoenix Integration</strong>, Software Engineer Intern</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I developed industry software for software integration and design process optimization in **VC++**, **VC\#**, and **Java**.
</li>
</ul>
</td>
</tr>
<tr>
  <td class='col-md-3'>Jan 2011 - Aug 2011</td>
  <td><strong>Sunapsys</strong>, Network Administrator Intern</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
Internship in high school to replace Windows domain, mail, DHCP, and DNS servers with virtual **Linux** servers using **KVM** and **virsh**.
</li>
</ul>
</td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> CMU Graduate Coursework
+ Statistical Machine Learning (10-702, Au), L. Wasserman, S2017
+ Deep Reinforcement Learning (10-703), R. Salakhutdinov and A. Fragkiadaki, S2017
+ Intermediate Statistics (10-705, Au), L. Wasserman, F2016
+ Topics in Deep Learning (10-807), R. Salakhutdinov, F2016
+ Convex Optimization (10-725), R. J. Tibshirani, F2015
+ Algorithms in the Real World (15-853), G. Blelloch and A. Gupta, F2015
+ Semantics of Programming Languages (15-812), A. Platzer, S2015
+ Optimizing Compilers for Modern Architecture (15-745), T. Mowry, S2015
+ Advanced Operating and Distributed Systems (15-712), D. Andersen, F2014
+ Mobile and Pervasive Computing (15-812), M. Satyanarayanan and D. Siewiorek, F2014


## <i class="fa fa-chevron-right"></i> Honors & Awards
<table class="table table-hover">
<tr>
  <td class='col-md-2'>2016 - 2019</td>
  <td>
    NSF Graduate Research Fellowship
    <!--  -->
  </td>
</tr>
<tr>
  <td class='col-md-2'>2014</td>
  <td>
    1st Place Undergraduate Senior Capstone Award, Virginia Tech Computer Science
    <!--  -->
  </td>
</tr>
<tr>
  <td class='col-md-2'>2014</td>
  <td>
    David Heilman Research Award, Virginia Tech Computer Science
    <!--  -->
  </td>
</tr>
<tr>
  <td class='col-md-2'>2014</td>
  <td>
    Senior Scholar Award, Virginia Tech Computer Science
    <!--  -->
  </td>
</tr>
<tr>
  <td class='col-md-2'>2014</td>
  <td>
    Honorable Mention, CRA Outstanding Undergraduate Researcher Award
    <!--  -->
  </td>
</tr>
<tr>
  <td class='col-md-2'>2011 - 2014</td>
  <td>
    Awarded eight undergraduate merit scholarships
    <!--  -->
  </td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Skills
<table class="table table-hover">
<tr>
  <td class='col-md-2'>Languages</td>
  <td markdown="1">
Bash, C, C++, CSS, Fortran, Haskell, HTML, Java, JavaScript, LaTeX, Lua, Make, *Mathematica*, Python, R, Scala
  </td>
</tr>
<tr>
  <td class='col-md-2'>Frameworks</td>
  <td markdown="1">
Akka, Android SDK/NDK, Caffe, Node.js, NumPy, TensorFlow, Torch7, Pandas, SciPy, scikit-learn, Spark, Spray
  </td>
</tr>
<tr>
  <td class='col-md-2'>Systems</td>
  <td markdown="1">
Linux, OSX
  </td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> All Publications <a href="https://github.com/bamos/cv/blob/master/publications/"><i class="fa fa-code-fork" aria-hidden="true"></i></a>

<a href="https://scholar.google.com/citations?user=CZwrwHAAAAAJ" class="btn btn-primary" style="padding: 0.3em;">
  <i class="ai ai-google-scholar"></i> Google Scholar
</a>


### Journal Articles <a href="https://github.com/bamos/cv/blob/master/publications/tech-reports.bib"><i class="fa fa-code-fork" aria-hidden="true"></i></a>

<table class="table table-hover">

<tr>
<td>
    <strong>OptNet: Differentiable Optimization as a Layer in Neural Networks</strong><br>
    <strong>B. Amos</strong> and J. Kolter<br>
    arXiv 2017<br>
    [P1]
[<a href='javascript: none'
    onclick='$("#abs_amos2017optnetP").toggle()'>abs</a>] [<a href='http://arxiv.org/abs/1703.00443' target='_blank'>pdf</a>]  [<a href='https://github.com/locuslab/optnet' target='_blank'>code</a>] <br>

<div id="abs_amos2017optnetP" style="text-align: justify; display: none" markdown="1">
This paper presents OptNet, a network architecture that integrates
optimization problems (here, specifically in the form of quadratic
programs) as individual layers in larger end-to-end trainable deep
networks. These layers allow complex dependencies between the hidden
states to be captured that traditional convolutional and
fully-connected layers are not able to capture. In this paper, we
develop the foundations for such an architecture: we derive the
equations to perform exact differentiation through these layers and
with respect to layer parameters; we develop a highly efficient solver
for these layers that exploits fast GPU-based batch solves within a
primal-dual interior point method, and which provides backpropagation
gradients with virtually no additional cost on top of the solve; and
we highlight the application of these approaches in several
problems. In one particularly standout example, we show that the
method is capable of learning to play Sudoku given just input and
output games, with no a priori information about the rules of the
game; this task is virtually impossible for other neural network
architectures that we have experimented with, and highlights the
representation capabilities of our approach.
</div>

</td>
</tr>


<tr>
<td>
    <strong>Task-based End-to-end Model Learning</strong><br>
    P. Donti, <strong>B. Amos</strong>, and J. Kolter<br>
    arXiv 2017<br>
    [P2]
[<a href='javascript: none'
    onclick='$("#abs_donti2017taskP").toggle()'>abs</a>] [<a href='http://arxiv.org/abs/1703.04529' target='_blank'>pdf</a>]  [<a href='https://github.com/locuslab/e2e-model-learning' target='_blank'>code</a>] <br>

<div id="abs_donti2017taskP" style="text-align: justify; display: none" markdown="1">
As machine learning techniques have become more ubiquitous, it has
become common to see machine learning prediction algorithms operating
within some larger process. However, the criteria by which we train
machine learning algorithms often differ from the ultimate criteria on
which we evaluate them. This paper proposes an end-to-end approach for
learning probabilistic machine learning models within the context of
stochastic programming, in a manner that directly captures the
ultimate task-based objective for which they will be used. We then
present two experimental evaluations of the proposed approach, one as
applied to a generic inventory stock problem and the second to a
real-world electrical grid scheduling task. In both cases, we show
that the proposed approach can outperform both a traditional modeling
approach and a purely black-box policy optimization approach.
</div>

</td>
</tr>


<tr>
<td>
    <strong>Input Convex Neural Networks</strong><br>
    <strong>B. Amos</strong>, L. Xu, and J. Kolter<br>
    arXiv 2016<br>
    [P3]
[<a href='javascript: none'
    onclick='$("#abs_amos2016inputP").toggle()'>abs</a>] [<a href='http://arxiv.org/abs/1609.07152' target='_blank'>pdf</a>]  [<a href='https://github.com/locuslab/icnn' target='_blank'>code</a>] <br>

<div id="abs_amos2016inputP" style="text-align: justify; display: none" markdown="1">
This paper presents the input convex neural network
architecture. These are scalar-valued (potentially deep) neural
networks with constraints on the network parameters such that the
output of the network is a convex function of (some of) the
inputs. The networks allow for efficient inference via optimization
over some inputs to the network given others, and can be applied to
settings including structured prediction, data imputation, reinforcement learning, and others. In this paper we lay the basic
groundwork for these models, proposing methods for inference, optimization and learning, and analyze their representational
power. We show that many existing neural network architectures can be
made input-convex with only minor modification, and develop
specialized optimization algorithms tailored to this setting. Finally, we highlight the performance of the methods on multi-label prediction, image completion, and reinforcement learning problems, where we show
improvement over the existing state of the art in many cases.
</div>

</td>
</tr>


<tr>
<td>
    <strong>OpenFace: A general-purpose face recognition library with mobile applications</strong><br>
    <strong>B. Amos</strong>, B. Ludwiczuk, and M. Satyanarayanan<br>
    CMU 2016<br>
    [P4]
[<a href='javascript: none'
    onclick='$("#abs_amos2016openfaceP").toggle()'>abs</a>] [<a href='http://reports-archive.adm.cs.cmu.edu/anon/anon/2016/CMU-CS-16-118.pdf' target='_blank'>pdf</a>]  [<a href='https://cmusatyalab.github.io/openface' target='_blank'>code</a>] <br>

<div id="abs_amos2016openfaceP" style="text-align: justify; display: none" markdown="1">
Cameras are becoming ubiquitous in the Internet of Things (IoT) and
can use face recognition technology to improve context. There is a
large accuracy gap between today's publicly available face recognition
systems and the state-of-the-art private face recognition
systems. This paper presents our OpenFace face recognition library
that bridges this accuracy gap. We show that OpenFace provides
near-human accuracy on the LFW benchmark and present a new
classification benchmark for mobile scenarios. This paper is intended
for non-experts interested in using OpenFace and provides a light
introduction to the deep neural network techniques we use.

We released OpenFace in October 2015 as an open source library under
the Apache 2.0 license. It is available at:
<http://cmusatyalab.github.io/openface/>
</div>

</td>
</tr>


<tr>
<td>
    <strong>Are Cloudlets Necessary?</strong><br>
    Y. Gao, W. Hu, K. Ha, <strong>B. Amos</strong>, P. Pillai, and M. Satyanarayanan<br>
    CMU 2015<br>
    [P5]
[<a href='javascript: none'
    onclick='$("#abs_gao2015cloudletsP").toggle()'>abs</a>] [<a href='http://reports-archive.adm.cs.cmu.edu/anon/anon/2015/CMU-CS-15-139.pdf' target='_blank'>pdf</a>] <br>

<div id="abs_gao2015cloudletsP" style="text-align: justify; display: none" markdown="1">
We present experimental results from Wi-Fi and 4G LTE networks to validate the
intuition that low end-to-end latency of cloud services improves application
response time and reduces energy consumption on mobile devices. We focus
specifically on computational offloading as a cloud service. Using a wide
range of applications, and exploring both pre-partitioned and dynamically
partitioned approaches, we demonstrate the importance of low latency for
cloud offload services. We show the best performance is achieved by
offloading to cloudlets, which are small-scale edge-located data centers. Our
results show that cloudlets can improve response times 51% and reduce energy
consumption in a mobile device by up to 42% compared to cloud offload.
</div>

</td>
</tr>


<tr>
<td>
    <strong>Adaptive VM handoff across cloudlets</strong><br>
    K. Ha, Y. Abe, Z. Chen, W. Hu, <strong>B. Amos</strong>, P. Pillai, and M. Satyanarayanan<br>
    CMU 2015<br>
    [P6]
[<a href='javascript: none'
    onclick='$("#abs_ha2015adaptiveP").toggle()'>abs</a>] [<a href='http://ra.adm.cs.cmu.edu/anon/2015/CMU-CS-15-113.pdf' target='_blank'>pdf</a>] <br>

<div id="abs_ha2015adaptiveP" style="text-align: justify; display: none" markdown="1">
Cloudlet offload is a valuable technique for ensuring low end-to-end latency of
resource-intensive cloud processing for many emerging mobile applications.
This paper examines the impact of user mobility on cloudlet offload, and
shows that even modest user mobility can result in significant network
degradation. We propose VM handoff as a technique for seamlessly transferring
VMencapsulated execution to a more optimal offload site as users move. Our
approach can perform handoff in roughly a minute even over limited WANs by
adaptively reducing data transferred. We present experimental results to
validate our implementation and to demonstrate effectiveness of adaptation to
changing network conditions and processing capacity
</div>

</td>
</tr>


<tr>
<td>
    <strong>QNSTOP-QuasiNewton Algorithm for Stochastic Optimization</strong><br>
    <strong>B. Amos</strong>, D. Easterling, L. Watson, W. Thacker, B. Castle, and M. Trosset<br>
    VT 2014<br>
    [P7]
[<a href='javascript: none'
    onclick='$("#abs_amos2014QNSTOPP").toggle()'>abs</a>] [<a href='https://vtechworks.lib.vt.edu/bitstream/handle/10919/49672/qnTOMS14.pdf' target='_blank'>pdf</a>] <br>

<div id="abs_amos2014QNSTOPP" style="text-align: justify; display: none" markdown="1">
QNSTOP consists of serial and parallel (OpenMP) Fortran 2003 codes for the
quasi-Newton stochastic optimization method of Castle and Trosset. For
stochastic problems, convergence theory exists for the particular
algorithmic choices and parameter values used in QNSTOP. Both the parallel
driver subroutine, which offers several parallel decomposition strategies, and the serial driver subroutine can be used for stochastic optimization or
deterministic global optimization, based on an input switch. QNSTOP is
particularly effective for “noisy” deterministic problems, using only
objective function values. Some performance data for computational systems
biology problems is given.
</div>

</td>
</tr>


</table>

### Conference Proceedings <a href="https://github.com/bamos/cv/blob/master/publications/conference.bib"><i class="fa fa-code-fork" aria-hidden="true"></i></a>

<table class="table table-hover">

<tr>
<td>
    <strong>Collapsed Variational Inference for Sum-Product Networks</strong><br>
    H. Zhao, T. Adel, G. Gordon, and <strong>B. Amos</strong><br>
    ICML 2016<br>
    [C1]
[<a href='javascript: none'
    onclick='$("#abs_zhao2016collapsedC").toggle()'>abs</a>] [<a href='http://www.cs.cmu.edu/~hzhao1/papers/ICML2016/BL-SPN-main.pdf' target='_blank'>pdf</a>] <br>

<div id="abs_zhao2016collapsedC" style="text-align: justify; display: none" markdown="1">
Sum-Product Networks (SPNs) are probabilistic inference machines that admit
exact inference in linear time in the size of the network. Existing
parameter learning approaches for SPNs are largely based on the maximum
likelihood principle and hence are subject to overfitting compared to
more Bayesian approaches. Exact Bayesian posterior inference for SPNs is
computationally intractable. Both standard variational inference and
posterior sampling for SPNs are computationally infeasible even for
networks of moderate size due to the large number of local latent
variables per instance. In this work, we propose a novel deterministic
collapsed variational inference algorithm for SPNs that is
computationally efficient, easy to implement and at the same time allows
us to incorporate prior information into the optimization formulation.
Extensive experiments show a significant improvement in accuracy compared
with a maximum likelihood based approach.
</div>

</td>
</tr>


<tr>
<td>
    <strong>Applying machine learning classifiers to dynamic Android malware detection at scale</strong><br>
    <strong>B. Amos</strong>, H. Turner, and J. White<br>
    IWCMC 2013<br>
    [C2]
[<a href='javascript: none'
    onclick='$("#abs_amos2013applyingC").toggle()'>abs</a>] [<a href='http://bamos.github.io/data/papers/amos-iwcmc2013.pdf' target='_blank'>pdf</a>]  [<a href='https://github.com/VT-Magnum-Research/antimalware' target='_blank'>code</a>] <br>

<div id="abs_amos2013applyingC" style="text-align: justify; display: none" markdown="1">
The widespread adoption and contextually sensitive
nature of smartphone devices has increased concerns over smartphone
malware. Machine learning classifiers are a current method
for detecting malicious applications on smartphone systems. This
paper presents the evaluation of a number of existing classifiers, using a dataset containing thousands of real (i.e. not synthetic)
applications. We also present our STREAM framework, which
was developed to enable rapid large-scale validation of mobile
malware machine learning classifiers.
</div>

</td>
</tr>


</table>
