---
layout: page
title: UWNMBL
description: Projects from when I was an undergraduate student at UW-Madison as a member of the Neuromuscular Biomechanics Lab
img: assets/img/projects/work/UWNMBL/UWNMBL_logo.jpg
importance: 4
category: work
---

<div>
<h2>In vivo tendon stress measurements</h2>
</div>

<div>
Today inverse dynamics and EMG scaling are used to approximate the forces with in muscles and tendons however this approach cannot account for co-contraction.  We have developed a method for measuring tendon stress noninvasivly.  As shear wave speed is logarithmically related to the tendon stress, measuring the shear wave at two points to get phasing, the wave speed can be determined.  In practice this is done using a piezo actuator to induce the shear wave and a ultra sound probe or two accelerometers to measure the shear wave.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0-center">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Photo from Martin et al. (2018) <a href="https://www.nature.com/articles/s41467-018-03797-6"> [Link]</a>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0-center">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
This picture displays our various design stages using piezo actuators and an ultrasound probe to induce and image the wave respectively.  Further iterations have been developed using accelerometers. 
</div>

<div>
<h2>Ligament Wrapping</h2>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0-center">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Ligament wrapping using spring model, minimizing the potential energy of the spring system the seed points, a line between the insertions on the tibia and femur, can be moved to points on the exterior of the bones.  This method uses distance fields methods. 
</div>

<div>
<h2>Dynamic MRI for ACL Reconstruction Research</h2>
</div>

<div>
In order to determine cartilage contact 3D static images are acquired and segmented, these static images can then be tracked on lower resolution dynamic images taken while preforming a dynamic task during MRI.  
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0-center">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide5.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Measurement of 3D Tibiofemoral Kinematics using Volumetric SPGR-VIPR Imaging. Photos from Kaiser et al. (2013) <a href="http://doi.org/10.1002/mrm.24362"> [Link]</a>
</div>

<div>
To validate the aforementioned research to determine cartilage contact a phantom was constructed which used 3D printed bones and fiducial markers filled with agarose gel.  Agarose is visible in MRI due to its high percentage of water.  The fiducial markers were also taped with reflective tape, so that they could be imaged by a motion capture system.  Driving this phantom with a stepper motor during the MRI scan and in a motion capture lab allows for a kinematic comparison to determine the accuracy of our dynamic MRI methods.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0-center">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide6.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
CAD pictures of components. 
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0-center">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide7.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
The 3D assembled system ready for the MRI scan.
</div>

<div>
<h2>Cartilage Thickness Estimates</h2>
</div>

Another application of distance fields is finding the thickness of cartilage models created from MRI scans and laser scans.  After the cartilage thickness is determined our results were used to validate research using MRI to compute cartilage contact during the active task explained above. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0-center">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide4.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
Color map of cartilage thickness
</div>