---
title: CV
layout: default
---


<table class="cv">
  <tr>
    <td>
      <span class="pub_title"><font size="5"><strong>Jongyoo Kim</strong></font></span><br>
      Ph.D Candidate<br>
      <a href="http://insight.yonsei.ac.kr">Multidimensional Insight Lab.</a><br>
      <a href="http://ee.yonsei.ac.kr/">Dept. of Electrical and Electronic Engineering</a><br>
      <a href="http://yonsei.ac.kr/">Yonsei University</a><br>
      Tel.: +82-2-2123-7734<br>
      Email: jongky@yonsei.ac.kr<br>
      <a href="http://jongyookim.github.io/data/cv_jongyoo.pdf"><strong>[Download CV]</strong></a><br>
    </td>
    <td>
      <img src="jongyoo2.png" alt="Drawing" style="
      height: 240px;
      border: 5px solid #ccc;
      border-radius: 10px;
      -moz-border-radius: 10px;
      -khtml-border-radius: 10px;
      -webkit-border-radius: 10px;
      "/>
    </td>
  </tr>
</table>

<!--<div style="text-align:left">
<img src="jongyoo.jpg" alt="Drawing" style="width: 500px;"/>
</div>-->

<!--Ph.D Candidate<br>
[Multidimensional Insight Lab.](http://insight.yonsei.ac.kr)<br>
Yonsei University, Dept. of Electrical and Electronic Engineering<br>
Tel.: +82-2-2123-7734<br>
Email: jongky@yonsei.ac.kr-->

## Research Interest
- Perceptual Image and Video Quality Assessment
- Quality of Experience Assessment of 2D/3D/VR Images and Videos
- Visual Discomfort Assessment of 3D Stereoscopic and VR Contents
- Deep Learning and Convolutional Neural Networks
- Human Action Recognition
- 3D Reconstruction

## Education

<!--<style>
.blueone {
  border-collapse: collapse;
}
.blueone th, td {
  padding: 10px;
  border-bottom: 1px solid gray;
  text-align: left;
  padding: 5px 20px;
}
</style>-->

<table class="type04">
  <tr>
    <th>Mar 2011 - Present</th>
    <td>
        <strong>Ph.D. in Electrical and Electronic Engineering</strong> (4.03/4.30)<br>
        Supervised by Prof. Sanghoon Lee
        <br>
      Yonsei University, Seoul, Korea
    </td>
  </tr>
  <tr>
    <th>Mar 2007 - Feb 2011</th>
    <td>
        <strong>B.S. in Electrical and Electronic Engineering</strong> (3.67/4.30)
        <br>
      Yonsei University, Seoul, Korea
    </td>
  </tr>
</table>


## Publications

<table class="type05">

<tr>
<!--<th><img src="images/publications/kim_deep_2017.png"/></th>-->
<td>
    <span class="pub_title"><strong>Deep Learning of Human Visual Sensitivity in Image Quality Assessment Framework</strong></span><br>
    <strong>Jongyoo Kim</strong> and S. Lee<br>
    IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2017<br>
    [1]
[<a href='javascript: none'
    onclick='toggle("abs_kim_deep_2017")'>abs</a>]<br>

<div id="abs_kim_deep_2017" style="text-align: justify; display: none" markdown="1">
Since human observers are the ultimate receivers of digital images, image quality metrics should be designed from a human-oriented perspective. Conventionally, a number of full-reference image quality assessment (FR-IQA) methods adopted various computational models of the human visual system (HVS) from psychological vision science research. In this paper, we propose a novel convolutional neural networks (CNN) based FR-IQA model, named Deep Image Quality Assessment (DeepQA), where the behavior of the HVS is learned from the underlying data distribution of IQA databases. Different from previous studies, our model seeks the optimal visual weight based on understanding of database information itself without any prior knowledge of the HVS. Through the experiments, we show that the predicted visual sensitivity maps agree with the human subjective opinions. In addition, DeepQA achieves the state-of-the-art prediction accuracy among FR-IQA models.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_quality_2017.png"/></th>-->
<td>
    <span class="pub_title"><strong>Quality Assessment of Perceptual Crosstalk on Two-View Auto-Stereoscopic Displays</strong></span><br>
    <strong>Jongyoo Kim</strong>, T. Kim, S. Lee, and A. C. Bovik<br>
    IEEE Transactions on Image Processing (Accepted)<br>
    [2]
[<a href='javascript: none'
    onclick='toggle("abs_kim_quality_2017")'>abs</a>]<br>

<div id="abs_kim_quality_2017" style="text-align: justify; display: none" markdown="1">
Crosstalk is one of the most severe factors affecting the perceived quality of stereoscopic 3D (S3D) images.It arises from a leakage of light intensity between multiple views, as in auto-stereoscopic displays. Well-known determinants of crosstalk include the co-location contrast and disparity of the left and right images, which have been dealt with in prior studies. However, when a natural stereo image that contains complex naturalistic spatial characteristics is viewed on an auto-stereoscopic display, other factors may also play an important role in the perception of crosstalk. Here, we describe a new way of predicting the perceived severity of crosstalk, which we call the Binocular Perceptual Crosstalk Predictor (BPCP). BPCP uses measurements of three complementary 3D image properties (texture, structural duplication and binocular summation) in combination with two well-known factors (co-location contrast and disparity) to make predictions of crosstalk on two-view auto-stereoscopic displays. The new BPCP model includes two masking algorithms and a binocular pooling method. We explore a new masking phenomenon that we call duplicated structure masking, which arises from structural correlations between the original and distorted objects. We also utilize an advanced binocular summation model to develop a binocular pooling algorithm. Our experimental results indicate that BPCP achieves high correlations against subjective test results, improving upon those delivered by previous crosstalk prediction models.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_fully_2016.png"/></th>-->
<td>
    <span class="pub_title"><strong>Fully Deep Blind Image Quality Predictor</strong></span><br>
    <strong>Jongyoo Kim</strong> and S. Lee<br>
    IEEE Journal of Selected Topics in Signal Processing 2017<br>
    [3]
<!--[<a href='javascript: none'
    onclick='toggle("abs_kim_fully_2016")'>abs</a>]<br>-->
[<a href='javascript: none'
    onclick='toggle("abs_kim_fully_2016")'>abs</a>]<br>

<div id="abs_kim_fully_2016" style="text-align: justify; display: none" markdown="1">
In general, owing to the benefits obtained from original information, full-reference image quality assessment (FR-IQA) achieves relatively higher prediction accuracy than no-reference image quality assessment (NR-IQA). By fully utilizing reference images, conventional FR-IQA methods have been investigated to produce objective scores that are close to subjective scores. In contrast, NR-IQA does not consider reference images; thus, its performance is inferior to that of FR-IQA. To alleviate this accuracy discrepancy between FR-IQA and NR-IQA methods, we propose a blind image evaluator based on a convolutional neural network (BIECON). To imitate FR-IQA behavior, we adopt the strong representation power of a deep convolutional neural network to generate a local quality map, similar to FR-IQA. To obtain the best results from the deep neural network, replacing hand-crafted features with automatically learned features is necessary. To apply the deep model to the NR-IQA framework, three critical problems must be resolved: 1) lack of training data; 2) absence of local ground truth targets; and 3) different purposes of feature learning. BIECON follows the FR-IQA behavior using the local quality maps as intermediate targets for conventional neural networks, which leads to NR-IQA prediction accuracy that is comparable with that of state-of-the-art FR-IQA methods.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/lee_identification_2017.png"/></th>-->
<td>
    <span class="pub_title"><strong>An Identification Framework for Print-Scan Books in a Large Database</strong></span><br>
    S. Lee, <strong>Jongyoo Kim</strong>, and S. Lee<br>
    Information Sciences 2017<br>
    [4]
[<a href='javascript: none'
    onclick='toggle("abs_lee_identification_2017")'>abs</a>]<br>

<div id="abs_lee_identification_2017" style="text-align: justify; display: none" markdown="1">
In this paper, we propose an identification framework to determine copyright infringement in the form of illegally distributed print-scan books in a large database. The framework contains following main stages: image pre-processing, feature vector extraction, clustering, and indexing, and hierarchical search. The image pre-processing stage provides methods for alleviating the distortions induced by a scanner or digital camera. From the pre-processed image, we propose to generate feature vectors that are robust against distortion. To enhance the clustering performance in a large database, we use a clustering method based on the parallel-distributed computing of Hadoop MapReduce. In addition, to store the clustered feature vectors efficiently and minimize the searching time, we investigate an inverted index for feature vectors. Finally, we implement a two-step hierarchical search to achieve fast and accurate on-line identification. In a simulation, the proposed identification framework shows accurate and robust in the presence of print-scan distortions. The processing time analysis in a parallel computing environment gives extensibility of the proposed framework to massive data. In the matching performance analysis, we empirically and theoretically find that in terms of query time, the optimal number of clusters scales with O ( N ) for N print-scan books.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_blind_2016-1.png"/></th>-->
<td>
    <span class="pub_title"><strong>Blind Sharpness Prediction for Ultra-High-Definition Video Based on Human Visual Resolution</strong></span><br>
    H. Kim, <strong>Jongyoo Kim</strong>, T. Oh, and S. Lee<br>
    IEEE Transactions on Circuits and Systems for Video Technology 2016<br>
    [5]
[<a href='javascript: none'
    onclick='toggle("abs_kim_blind_2016-1")'>abs</a>]<br>

<div id="abs_kim_blind_2016-1" style="text-align: justify; display: none" markdown="1">
We explore a no-reference sharpness assessment model for predicting the perceptual sharpness of ultra-highdefinition (UHD) videos through analysis of visual resolution variation in terms of viewing geometry and scene characteristics. The quality and sharpness of UHD videos are influenced by viewer perception of the spatial resolution afforded by the UHD display, which depends on viewing geometry parameters including display resolution, display size, and viewing distance. In addition, viewers may perceive different degrees of quality and sharpness according to the statistical behavior of the visual signals, such as the motion, texture, and edge, which vary over both spatial and temporal domains. The model also accounts for the resolution variation associated with fixation and foveal regions, which is another important factor affecting the sharpness prediction of UHD video over the spatial domain, and which is caused by the nonuniform distribution of the photoreceptors. We calculate the transition of the visually salient statistical characteristics resulting from changing the display's screen size and resolution. Moreover, we calculated the temporal variation in sharpness over consecutive frames in order to evaluate the temporal sharpness perception of UHD video. We verify that the proposed model outperforms other sharpness models in both spatial and temporal sharpness assessments.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_perceptual_2016.png"/></th>-->
<td>
    <span class="pub_title"><strong>Perceptual Crosstalk Prediction on Autostereoscopic 3D Display</strong></span><br>
    T. Kim, <strong>Jongyoo Kim</strong>, S. Kim, S. Cho, and S. Lee<br>
    IEEE Transactions on Circuits and Systems for Video Technology 2016<br>
    [6]
[<a href='javascript: none'
    onclick='toggle("abs_kim_perceptual_2016")'>abs</a>]<br>

<div id="abs_kim_perceptual_2016" style="text-align: justify; display: none" markdown="1">
Perceptual crosstalk prediction for autostereoscopic 3D displays is of fundamental importance in determining the level of quality perceived by humans in terms of the display performance and the 3D viewing experience. However, no robust framework exists to quantify perceptual crosstalk while taking into account the hardware structure of a display as well as its content characteristics via content analysis. In this paper, we present a 3D Perceptual Crosstalk Predictor (3D-PCP) that can be used to predict crosstalk in a unique way when viewing autostereoscopic 3D displays. 3D-PCP captures hardware features using an Optical Fourier transform - Light Measurement Device and content features through content analysis based on information theory. By deriving the disparity, luminance, color, and texture maps, this approach defines the visual entropy, mutual information, and relative entropy in order to investigate the influences of the 3D scene characteristics on perceptual crosstalk. The experimental results demonstrate that the 3D-PCP output is highly correlated with subjective scores.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_no-reference_2016.png"/></th>-->
<td>
    <span class="pub_title"><strong>No-Reference Perceptual Sharpness Assessment for Ultra-High-Definition Images</strong></span><br>
    W. Kim, H. Kim, H. Oh, <strong>Jongyoo Kim</strong>, and S. Lee<br>
    IEEE International Conference on Image Processing (ICIP) 2016<br>
    [7]
[<a href='javascript: none'
    onclick='toggle("abs_kim_no-reference_2016")'>abs</a>]<br>

<div id="abs_kim_no-reference_2016" style="text-align: justify; display: none" markdown="1">
Since ultra-high-definition (UHD) display has larger resolution and various display size, it is necessary to measure image sharpness considering variation in visual resolution caused by diverse viewing geometry. In this paper, we propose a no-reference perceptual sharpness assessment model of UHD images. The proposed model analyzes viewing geometry in terms of display resolution and viewing environment. Then, we measure the local adaptive sharpness score in accordance with the textural motion blur, texture, and edge. In addition, we propose a spatial pooling method associated with foveal regions, which is caused by nonuniform distribution of the photoreceptors on a human retina. Through the rigorous experiments, we demonstrate that the proposed model can measure the sharpness of UHD images more accurately than other image sharpness assessment methods.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_human_2016.png"/></th>-->
<td>
    <span class="pub_title"><strong>Human Gait Prediction Method Using Microsoft Kinect</strong></span><br>
    J. Kim, D. Kim, I. Lee, <strong>Jongyoo Kim</strong>, H. Oh, and S. Lee<br>
    International Workshop on Advanced Image Technology (IWAIT) 2016<br>
    [8]
[<a href='javascript: none'
    onclick='toggle("abs_kim_human_2016")'>abs</a>]<br>

<div id="abs_kim_human_2016" style="text-align: justify; display: none" markdown="1">
Real-time monitoring of elderly movement can provide valuable information regarding an individual's degree of functional rehabilitation. Many laboratory-based studies have described various gait detection systems with different wearable inertial sensors, but only limited number of papers addressed the issues by using some non-wearable sensors. A practical method of gait information detection and gait analysis is proposed in the paper using an inexpensive Microsoft Kinect fixed on the midpoint of lower extremity rehabilitation robot. The horizontal distances between Kinect plane and every mark pasted on lower extremity are acquired. Taken the characteristics of gait distance series into consideration, the Autoregressive Moving Average (ARMA) model is established to reflect the changing rule of gait status. Combined with the Kalman filter, gait information reflecting rehabilitation status at next moment is predicted accurately. The method regarding the gait detection and gait analysis is verified by amounts of gait experiments finally.
</div>


</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_implementation_2015.png"/></th>-->
<td>
    <span class="pub_title"><strong>Implementation of an Omnidirectional Human Motion Capture System Using Multiple Kinect Sensors</strong></span><br>
    J. Kim, I. Lee, <strong>Jongyoo Kim</strong>, and S. Lee<br>
    IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences 2015<br>
    [9]
[<a href='javascript: none'
    onclick='toggle("abs_kim_implementation_2015")'>abs</a>]<br>

<div id="abs_kim_implementation_2015" style="text-align: justify; display: none" markdown="1">
Due to ease of implementation for various user interactive applications, much research on motion recognition has been completed using Kinect. However, one drawback of Kinect is that the skeletal information obtained is provided under the assumption that the user faces Kinect. Thus, the skeletal information is likely incorrect when the user turns his back to Kinect, which may lead to difficulty in motion recognition from the application. In this paper, we implement a highly accurate human motion capture system by installing six Kinect sensors over 360 degrees. The proposed method enables skeleton to be obtained more accurately by assigning higher weights to skeletons captured by Kinect in which the user faces forward. Toward this goal, the front vector of the user is temporally traced to determine whether the user is facing Kinect. Then, more reliable joint information is utilized to construct a skeletal representation of each user.
</div>


</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_video_2015.png"/></th>-->
<td>
    <span class="pub_title"><strong>Video Sharpness Prediction Based on Motion Blur Analysis</strong></span><br>
    <strong>Jongyoo Kim</strong>, J. Kim, W. Kim, J. Lee, and S. Lee<br>
    IEEE International Conference on Multimedia and Expo (ICME) 2015<br>
    [10]
[<a href='javascript: none'
    onclick='toggle("abs_kim_video_2015")'>abs</a>]<br>

<div id="abs_kim_video_2015" style="text-align: justify; display: none" markdown="1">
For high bit rate video, it is important to acquire the video contents with high resolution, the quality of which may be degraded due to the motion blur from the movement of an object(s) or the camera. However, conventional sharpness assessments are designed to find focal blur caused either by defocusing or by compression distortion targeted for low bit rates. To overcome this limitation, we present a no-reference framework of a visual sharpness assessment (VSA) for high-resolution video based on the motion and scene classification. In the proposed framework, the accuracy of the sharpness estimation can be improved via pooling weighted by the visual perception from the object and camera movements and by the strong influence from the region with the highest sharpness. Based on the motion blur characteristics, the variance and the contrast over the spectral domain are used to quantify the perceived sharpness. Moreover, for the VSA, we extract the highly influential sharper regions and emphasize them by utilizing the scene adaptive pooling.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/oh_3d_2015.png"/></th>-->
<td>
    <span class="pub_title"><strong>3D Visual Discomfort Predictor Based on Neural Activity Statistics</strong></span><br>
    H. Oh, <strong>Jongyoo Kim</strong>, S. Lee, and A. C. Bovik<br>
    IEEE International Conference on Image Processing (ICIP) 2015<br>
    [11]
[<a href='javascript: none'
    onclick='toggle("abs_oh_3d_2015")'>abs</a>]<br>

<div id="abs_oh_3d_2015" style="text-align: justify; display: none" markdown="1">
Visual discomfort assessment (VDA) on stereoscopic images is of fundamental importance for making decisions regarding visual fatigue caused by unnatural binocular alignment. Nevertheless, no solid framework exists to quantify this discomfort using models of the responses of visual neurons. Binocular vision is realized by means of neural mechanisms that subserve the sensorimotor control of eye movements. We propose a neuronal model-based framework called Neural 3D Visual Discomfort Predictor (N3D-VDP) that automatically predicts the level of visual discomfort experienced when viewing stereoscopic 3D (S3D) images. The N3D-VDP model extracts features derived by estimating the neural activity associated with the processing of binocular disparities. In this regard we deploy a model of disparity processing in the extra-striate middle temporal (MT) region of occipital lobe. We compare the performance of N3D-VDP with other recent VDA algorithms using correlations against reported subjective visual discomfort, and show that N3D-VDP is statistically superior to the other methods.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/kwon_implementation_2015.png"/></th>-->
<td>
    <span class="pub_title"><strong>Implementation of Human Action Recognition System Using Multiple Kinect Sensors</strong></span><br>
    B. Kwon, D. Kim, J. Kim, I. Lee, <strong>Jongyoo Kim</strong>, H. Oh, H. Kim, and S. Lee<br>
    Advances in Multimedia Information Processing - PCM 2015<br>
    [12]
[<a href='javascript: none'
    onclick='toggle("abs_kwon_implementation_2015")'>abs</a>]<br>

<div id="abs_kwon_implementation_2015" style="text-align: justify; display: none" markdown="1">
Human action recognition is an important research topic that has many potential applications such as video surveillance, human-computer interaction and virtual reality combat training. However, many researches of human action recognition have been performed in single camera system, and has low performance due to vulnerability to partial occlusion. In this paper, we propose a human action recognition system using multiple Kinect sensors to overcome the limitation of conventional single camera based human action recognition system. To test feasibility of the proposed system, we use the snapshot and temporal features which are extracted from three-dimensional (3D) skeleton data sequences, and apply the support vector machine (SVM) for classification of human action. The experiment results demonstrate the feasibility of the proposed system.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_quality_2014.png"/></th>-->
<td>
    <span class="pub_title"><strong>Quality Assessment of Perceptual Crosstalk in Autostereoscopic Display</strong></span><br>
    <strong>Jongyoo Kim</strong>, T. Kim, and S. Lee<br>
    IEEE International Conference on Image Processing (ICIP) 2014<br>
    [13]
[<a href='javascript: none'
    onclick='toggle("abs_kim_quality_2014")'>abs</a>]<br>

<div id="abs_kim_quality_2014" style="text-align: justify; display: none" markdown="1">
Crosstalk is one of the most annoying problems in an autostereoscopic display causing perceptual quality degradation and visual discomfort. To predict the perceived crosstalk when viewing an autostereoscopic display, it is necessary to consider the characteristics of human perception, displaying mechanism, viewing environment and so on. Therefor, we propose a novel metric for predicting the perceptual crosstalk that is based on human visual system (HVS); non-linear sensitivity of luminance and masking effects. The proposed model adopts the duplicated structure masking, yielding predictive power that is statistically superior to prior models that rely on 2D quality metric.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_ego_2013.png"/></th>-->
<td>
    <span class="pub_title"><strong>Ego Motion Induced Visual Discomfort of Stereoscopic Video</strong></span><br>
    <strong>Jongyoo Kim</strong>, K. Oh, and S. Lee<br>
    Asia-Pacific Signal and Information Processing Association Annual Summit and Conference 2013<br>
    [14]
[<a href='javascript: none'
    onclick='toggle("abs_kim_ego_2013")'>abs</a>]<br>

<div id="abs_kim_ego_2013" style="text-align: justify; display: none" markdown="1">
When each video sequence is captured, an inappropriate camera motion should be one of crucial factors leading to visual discomfort and distortion. The well known symptom, visually induced motion sickness (VIMS) is caused by the illusion of self motion by perceiving the video with ego motion. In particular, for the stereoscopic 3D video, it can be easily observed that the viewers have dominantly feel much more severe symptoms of visual discomfort. In this paper, we analyze the ego motion of the stereoscopic video and predict the effects. We attempt a novel approach by exploiting the computer vision algorithm. We propose a novel method which can estimate the perceptual 3D ego motion from the stereoscopic video. Then we analyze the ego motion components to predict the visual discomfort of stereoscopic video.
</div>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/oh_construction_2013.png"/></th>-->
<td>
    <span class="pub_title"><strong>Construction of Stereoscopic 3D Video Database</strong></span><br>
    H. Oh, <strong>Jongyoo Kim</strong>, and S. Lee<br>
    Global 3D TECH Forum 2013<br>
    [15]<br>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_effects_2012.png"/></th>-->
<td>
    <span class="pub_title"><strong>Effects on 3D Experience by Space Distortion in Stereoscopic Video</strong></span><br>
    <strong>Jongyoo Kim</strong> and S. Lee<br>
    Global 3D TECH Forum 2012<br>
    [16]<br>

</td>
</tr>


<tr>
<!--<th><img src="images/publications/kim_visual_2012.png"/></th>-->
<td>
    <span class="pub_title"><strong>Visual Stimuli Using 3D Graphic Software for 3D Quality Assessment</strong></span><br>
    <strong>Jongyoo Kim</strong> and S. Lee<br>
    International Conference on 3D Systems and Applications (3DSA) 2012<br>
    [17]<br>

</td>
</tr>


</table>


## Tech Reports & Standardization Documents
<table class="type04">
<tr>
  <th>2015</th>
  <td>
    IEEE Standard for Quality of Experience (QoE) and Visual-Comfort Assessments of Three-Dimensional (3D) Contents Based on Psychophysical Studies, in IEEE Std 3333.1.1-2015
    <!--  -->
  </td>
</tr>
<tr>
  <th>2015</th>
  <td>
    3DTV Broadcasting Safety Guideline, 2015PG802-042, TTA
    <!--  -->
  </td>
</tr>
</table>


## Honors & Awards
<table class="type04">
<tr>
  <th>2015 - Present</th>
  <td>
    Secretary of the IEEE Human Factors for Visual Experiences WG (P3333.1.1/2)
  </td>
</tr>
<tr>
  <th>2016</th>
  <td>
    Bronze Best Paper Award in IEEE Seoul Section Student Paper Contest 2016
  </td>
</tr>
<tr>
  <th>2011 - 2016</th>
  <td>
    Global Ph.D Fellowship, National Research Foundation of Korea
  </td>
</tr>
<tr>
  <th>2013</th>
  <td>
    IEEE IVMSP Workshop 2013 Volunteer Award, IEEE Signal Processing Society
  </td>
</tr>
</table>


## Software Engineering Skills
<table class="type04">
<tr>
  <th>Languages</th>
  <td markdown="1">
C, C++, Java, Mathematica, Matlab, Python
  </td>
</tr>
<tr>
  <th>Frameworks</th>
  <td markdown="1">
Theano, TensorFlow, Android SDK/NDK, NumPy, OpenCV
  </td>
</tr>
</table>



<h2>Selected Project Experience
<a href='javascript: none' onclick='toggle("proj_exp")'><font size="3">[+]</font></a><br>
</h2>
<div id="proj_exp" style="display: none" markdown="1">

<table class="type04">

<tr>
  <th>Apr 2017 -- Present</th>
  <td><strong>Research on Controlling Human Factors for Generation and Utilization of Safe VR/AR Contents</strong>, Institute for Information & Communications Technology Promotion (IITP)</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I developed an algorithm of quality of experience assessment of VR and AR contents based on psychophysical and clinical analysis.
</li>
</ul>
</td>
</tr>

<tr>
  <th>Jan 2017 -- Present</th>
  <td><strong>Development of GPU Hardware for Real-time and Realistic Virtual Reality</strong>, Institute for Information & Communications Technology Promotion (IITP)</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I developed a perceptual quality assessment algorithm of GPU-rendered images for VR application.
</li>
</ul>
</td>
</tr>


<tr>
  <th>Jul 2016 -- Present</th>
  <td><strong>A VR Emotion Study Based on Visual Perception and Artificial Intelligence</strong>, National Research Foundation of Korea (NRF)</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I developed a convolutional neural network based no-reference image and stereoscopic 3D image quality assessment algorithm.
</li>
</ul>
</td>
</tr>


<tr>
  <th>Jun 2015 -- Present</th>
  <td><strong>Research on Video Coding Scheme by Predicting Quality Processing</strong>, Samsung Electronics</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I developed a video quality assessment algorithm to enhance the video coding scheme.
</li>
</ul>
</td>
</tr>


<tr>
  <th>Apr 2014 -- Feb 2017</th>
  <td><strong>Research on Human Safety and Contents Quality Assessment for Realistic Broadcasting</strong>, Institute for Information & Communications Technology Promotion (IITP)</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I developed a visual discomfort prediction method of 3D stereoscopic images and videos.
</li>
</ul>
</td>
</tr>


<tr>
  <th>May 2013 -- Feb 2017</th>
  <td><strong>Development of ODM-interactive Software Technology supporting Live-Virtual Soldier Exercises</strong>, Institute for Information & Communications Technology Promotion (IITP)</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I developed a real-time human pose estimation system where six Microsoft Kinects and omni-directional treadmill are used.
In addition, I developed a real-time human action recognition algorithm for virtual interface.
</li>
</ul>
</td>
</tr>


<tr>
  <th>Mar 2015 -- Feb 2016</th>
  <td><strong>Identification and Copy Protection Technology of Book-scanned Text/Comic Books</strong>, Korea Copyright Commission</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I developed an efficient algorithm for searching and matching an input comic book from a database.
</li>
</ul>
</td>
</tr>


<tr>
  <th>Mar 2015 -- Feb 2016</th>
  <td><strong>Research on Feature Extraction and DB Construction for Image-based Indoor Localization</strong>, Electronics and Telecommunications Research Institute (ETRI)</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I developed a SLAM algorithm using stereoscopic video streams.
</li>
</ul>
</td>
</tr>


<tr>
  <th>Feb 2012 -- Apr 2014</th>
  <td><strong>Implementation of Automatic Measure For 3D Quality Enhancement</strong>, Samsung Electronics
</td>
</tr>
<tr>
<td colspan="100%">
<ul>
<li markdown="1">
I developed a quality measuring model considering display geometry to find optimal enhancement degree.
</li>
</ul>
</td>
</tr>

</table>

</div>
