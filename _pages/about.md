---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Research Engineer at [Meta Reality Labs](https://about.meta.com/realitylabs/). I earned my master's degree in [Computer Vision](https://www.ri.cmu.edu/education/academic-programs/master-of-science-computer-vision/) at [Carnegie Mellon University](https://www.cmu.edu/). Previously, I completed my bachelor's degree in [Computer Science and Technology](http://www.en.cs.zju.edu.cn/22145/list.htm) at [Zhejiang University](https://www.zju.edu.cn/english/), advised by Prof. [Hongzhi Wu](http://hongzhiwu.com/).

My interest includes Computer Graphics and 3D Vision.

# 📖 Education

<div style="width: 100%;">
<div>
	<div style="width:20%;float:left">
        <img src="../images/CMU.png" style="border:1vw solid transparent;">
	</div>
	<div style="width:80%;float:left">
        <p>
            <b>Carnegie Mellon University</b>, Pittsburgh, U.S.
  	        <span style="float:right;">
                <i>Sep 2023 - Dec 2024</i>
  	        </span>
        </p>
        <p>
            <ul style="list-style-type:circle;">
                <li><b>Program</b>: Master of Science in Computer Vision</li>
                <li><b>Cumulative QPA</b>: 4.0/4.0</li>
            </ul>
        </p>
    </div>
</div>
</div>
<div style="clear:both"></div>

<div style="width: 100%;">
<div>
	<div style="width:20%;float:left">
        <img src="../images/ZJU.png" style="border:1vw solid transparent;">
	</div>
	<div style="width:80%;float:left">
        <p>
            <b>Zhejiang University</b>, Hangzhou, China
  	        <span style="float:right;">
                <i>Sep 2019 - Jun 2023</i>
  	        </span>
        </p>
        <p>
            <ul style="list-style-type:circle;">
                <li><b>Degree</b>: Bachelor of Engineering
                    <ul style="list-style-type:square;">
                		<li><b>Honors degree</b> from Chu Kochen Honors College</li>
                    </ul>
                </li>
                <li><b>Major</b>: Computer Science and Technology</li>
                <li><b>Overall GPA</b>: &nbsp;&nbsp;&nbsp;94.6/100&nbsp;&nbsp;&nbsp;3.98/4</li>
                <li><b>Ranking</b>: &nbsp;&nbsp;&nbsp;1/125</li>
            </ul>
        </p>
    </div>
</div>
</div>
<div style="clear:both"></div>

# 💻 Experience

<div style="width: 100%;">
<div>
	<div style="width:20%;float:left">
        <img src="../images/Meta.png" style="border:1vw solid transparent;">
	</div>
	<div style="width:80%;float:left">
        <p>
            <b>Meta</b>, Pittsburgh, U.S.
  	        <span style="float:right;">
                <i>Jan 2025 - Present</i>
  	        </span>
        </p>
        <p>
            <ul style="list-style-type:circle;">
                <li><b>Position</b>: Research Engineer</li>
            </ul>
        </p>
    </div>
</div>
</div>
<div style="clear:both"></div>
<hr width="100%" size="1" align="center">
<div style="width: 100%;">
<div>
	<div style="width:20%;float:left">
        <img src="../images/ByteDance.png" style="border:1vw solid transparent;">
	</div>
	<div style="width:80%;float:left">
        <p>
            <b>ByteDance</b>, San Jose, U.S.
  	        <span style="float:right;">
                <i>May 2024 - Aug 2024</i>
  	        </span>
        </p>
        <p>
            <ul style="list-style-type:circle;">
                <li><b>Position</b>: AR Effect Engineer Intern</li>
            </ul>
        </p>
    </div>
</div>
</div>
<div style="clear:both"></div>
<hr width="100%" size="1" align="center">
<div style="width: 100%;">
<div>
	<div style="width:20%;float:left">
        <img src="../images/MSRA.png" style="border:1vw solid transparent;">
	</div>
	<div style="width:80%;float:left">
        <p>
            <b>Microsoft Research Asia</b>, Beijing, China
  	        <span style="float:right;">
                <i>Mar 2022.3 - Jun 2023</i>
  	        </span>
        </p>
        <p>
            <ul style="list-style-type:circle;">
                <li><b>Position</b>: Research Intern of <a href="https://www.microsoft.com/en-us/research/group/internet-graphics/">Internet Graphics</a> group</li>
                <li><b>Advisor</b>: Dr. <a href="https://yizhongzhang1989.github.io/">Yizhong Zhang</a>, Dr. <a href="https://xueyuhanlang.github.io/">Yang Liu</a></li>
            </ul>
        </p>
    </div>
</div>
</div>
<div style="clear:both"></div>
<hr width="100%" size="1" align="center">

# 📝 Projects

<div style="width: 100%;">
<div>
	<div style="width:30%;float:left">
        <img src="../images/MultiCaliAnything.png" style="border:1vw solid transparent;">
	</div>
	<div style="width:70%;float:left">
        <p>
            <b>Multi-Cali Anything <a href="https://wanghewei16.github.io/Multi-Cali-Anything">[Project Page]</a> <a href="https://arxiv.org/abs/2503.00737">[Paper]</a> <a href="https://github.com/YJJfish/Multi-Cali-Anything">[Code]</a></b>
  	        <span style="float:right;">
                <i>Sep 2024 - Dec 2024</i>
  	        </span>
        </p>
        <p>
            <i>Research Project at CMU; Accepted at IROS 2025</i>
        </p>
        <p>
            Calibrating large-scale camera arrays, such as those in dome-based setups, is time-intensive and typically requires dedicated captures of known patterns. We propose a dense-feature-driven multi-frame calibration method that refines intrinsics directly from scene data, eliminating the necessity for additional calibration captures. Our approach enhances traditional Structure-from-Motion (SfM) pipelines by introducing an extrinsics regularization term to progressively align estimated extrinsics with ground-truth values, a dense feature reprojection term to reduce keypoint errors by minimizing reprojection loss in the feature space, and an intrinsics variance term for joint optimization across multiple frames. Experiments on the <a href="https://github.com/facebookresearch/multiface">Multiface</a> dataset show that our method achieves nearly the same precision as dedicated calibration processes, and significantly enhances intrinsics and 3D reconstruction accuracy. Fully compatible with existing SfM pipelines, our method provides an efficient and practical plug-and-play solution for large-scale camera setups.
        </p>
    </div>
</div>
</div>
<div style="clear:both"></div>
<hr width="100%" size="1" align="center">

<div style="width: 100%;">
<div>
	<div style="width:30%;float:left">
        <img src="../images/VFX FFD.png" style="border:1vw solid transparent;">
	</div>
	<div style="width:70%;float:left">
        <p>
            <b>Optimizing and designing features for Effect House's Visual Effects system</b>
  	        <span style="float:right;">
                <i>May 2024 - Aug 2024</i>
  	        </span>
        </p>
        <p>
            <i>Internship Project at ByteDance</i>
        </p>
        <p>
            In this internship project, I optimized the particle attribute buffer in Effect House's Visual Effects (VFX) system, which saved more than 50% memory for most template VFX effects in Effect House. Besides, I implemented simulation node in VFX graph editor which allows users to use the VFX system as a general compute pipeline, apart from a GPU particle system. The users can use simulation node to achieve custom physics simulation effects. Finally, I implemented a 3D Gaussian Splatting output node to render 3D scenes using VFX particles.
        </p>
    </div>
</div>
</div>
<div style="clear:both"></div>
<hr width="100%" size="1" align="center">

<div style="width: 100%;">
<div>
	<div style="width:30%;float:left">
        <img src="../images/KinectFusion.png" style="border:1vw solid transparent;">
	</div>
	<div style="width:70%;float:left">
        <p>
            <b>KinectFusion - Vulkan <a href="https://github.com/YJJfish/KinectFusion-Vulkan">[Project Page]</a></b>
  	        <span style="float:right;">
                <i>Mar 2024 - Apr 2024</i>
  	        </span>
        </p>
        <p>
            <i>Course Project of Robot Localization and Mapping (16-833)</i>
        </p>
        <p>
            In this project, I implemented <a href="https://ieeexplore.ieee.org/document/6162880">KinectFusion</a> based on Vulkan. Different from CUDA, Vulkan is a cross-platform graphics API that supports both graphics rendering and parallel computing. Therefore, my implementation is cross-platform and supports real-time camera tracking, scene reconstruction, and graphics rendering at the same time. The estimated camera poses can also be used to render AR objects onto the input RGB images to achieve AR effects.
        </p>
    </div>
</div>
</div>
<div style="clear:both"></div>
<hr width="100%" size="1" align="center">

<div style="width: 100%;">
<div>
	<div style="width:30%;float:left">
        <img src="../images/Render72.png" style="border:1vw solid transparent;">
	</div>
	<div style="width:70%;float:left">
        <p>
            <b>Render72: A real-time renderer based on Vulkan <a href="https://github.com/YJJfish/Renderer72">[Project Page]</a></b>
  	        <span style="float:right;">
                <i>Jan 2024 - Apr 2024</i>
  	        </span>
        </p>
        <p>
            <i>Course Project of Real-Time Graphics (15-472)</i>
        </p>
        <p>
            I developed a real-time renderer based on Vulkan. It supports multiple material types like mirror, lambertian, and pbr. The scene can have an environment map that can be used for image-based lighting by precomputing radiance/irradiance lookup tables.  The renderer also supports analytical lighting with shadow mapping (perspective / omnidirectional / cascade). It also supports deferred shading and screen space ambient occlusion (SSAO).
        </p>
    </div>
</div>
</div>
<div style="clear:both"></div>
<hr width="100%" size="1" align="center">

<div style="width: 100%;">
<div>
	<div style="width:30%;float:left">
        <img src="../images/Anti_Blur_Fusion.png" style="border:1vw solid transparent;">
	</div>
	<div style="width:70%;float:left">
        <p>
            <b>Anti-Blur Depth Fusion based on Vision Cone Model</b>
  	        <span style="float:right;">
                <i>Nov 2022 - Jun 2023</i>
  	        </span>
        </p>
        <p>
            <i>Research Project at Microsoft Research Asia</i>
        </p>
        <p>
            We proposed a depth fusion method to fuse low-resolution depth images while still maintaining high resolution information in the global model. Traditional methods like KinectFusion optimize the reconstruction by minimizing the difference between the reconstruction depths and captured depths. Therefore, they may produce blurred or aliased reconstructions when the image resolution is low. Our method is based on the assumption that the captured depth of a pixel equals to the average of actual depths within the pixel's vision cone. We designed loss functions to minimize difference between the average of reconstruction depths and captured depth. We have tested our method on both SDF voxel and mesh representations and got better reconstruction results than KinectFusion.
        </p>
    </div>
</div>
</div>
<div style="clear:both"></div>
<hr width="100%" size="1" align="center">

<div style="width: 100%;">
<div>
	<div style="width:30%;float:left">
        <img src="../images/Real-Time_SLAM_System_based_on_ARKit_Framework.png" style="border:1vw solid transparent;">
	</div>
	<div style="width:70%;float:left">
        <p>
            <b>Real-Time SLAM System based on ARKit Framework</b>
  	        <span style="float:right;">
                <i>Mar 2022 - Oct 2022</i>
  	        </span>
        </p>
        <p>
            <i>Research Project at Microsoft Research Asia</i>
        </p>
        <p>
            We developed a SLAM system for real-time tracking of camera trajectory when scanning indoor scenes with rich planar structures, using only an IOS device like iPhone or iPad. Our system gets the RGB-D data from the LiDAR camera, along with estimated camera poses computed by ARKit framework. It then searches for coplanar and parallel planes in the scene and uses them to optimize camera poses. Meanwhile, it uses a vocabulary tree and a confusion map to detect loops globally. Additionally, it allows users to confirm detected loops via the UI to improve the precision. Also, to avoid memory overflow in long time scan, it uses an embedded database to store infrequently visited data. Experiments show that our method improves the performance of camera localization and loop detection algorithms of ARKit. It allows users to scan large indoor scenes while still runs at real-time frame rate to give feedback to users.
        </p>
    </div>
</div>
</div>
<div style="clear:both"></div>
<hr width="100%" size="1" align="center">

# 🔧 Skills

- **Programming Language**: C/C++, Python, JavaScript, Swift, Objective-C, Verilog
- **Tool&Framework**: Vulkan, OpenGL, Metal, OpenCV, CUDA, PyTorch, NumPy, Doxygen, CMake
