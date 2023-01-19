---
layout: page
title: UWNMBL
description: a project with a background image
img: assets/img/projects/work/UWNMBL/Slide2.png
importance: 4
category: example
---

Test. Test. Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide4.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide5.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide6.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/work/UWNMBL/Slide7.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>


UW - Neuromuscular Biomechanics Lab
In vivo tendon stress measurements

Today inverse dynamics and EMG scaling are used to approximate the forces with in muscles and tendons however this approach cannot account for co-contraction.  We have developed a method for measuring tendon stress noninvasivly.  As shear wave speed is logarithmically related to the tendon stress, measuring the shear wave at two points to get phasing, the wave speed can be determined.  In practice this is done using a piezo actuator to induce the shear wave and a ultra sound probe or two accelerometers to measure the shear wave 

Jack A. Martin, Emily M. Keuler, James R. Hermus, Mikel R. Stiffler, Matthew S. Allen, and Darryl G. Thelen. ULTRASONIC IMAGING OF IN VIVO ACHILLES TENDON STRESS DURING WALKING

This picture displays our various design stages using piezo actuators and an ultrasound probe to induce and image the wave respectively.  Further iterations have been developed using accelerometers. 

Ligament Wrapping

Ligament wrapping using spring model, minimizing the potential energy of the spring system the seed points, a line between the insertions on the tibia and femur, can be moved to points on the exterior of the bones.  This method uses distance fields from CITE QUEENS CODE 

Dynamic MRI for ACL Reconstruction Research

In order to determine cartilage contact 3D static images are acquired and segmented, these static images can then be tracked on lower resolution dynamic images taken while preforming a dynamic task during MRI.  

Kaiser, J., Bradford, R., Johnson, K., Wieben, O., & Thelen, D. G. (2013). Measurement of 3D Tibiofemoral Kinematics using Volumetric SPGR-VIPR Imaging. Magnetic Resonance in Medicine : Official Journal of the Society of Magnetic Resonance in Medicine / Society of Magnetic Resonance in Medicine, 69(5), 1310–1316. http://doi.org/10.1002/mrm.24362

To validate the aforementioned research to determine cartilage contact a phantom was constructed which used 3D printed bones and fiducial markers filled with agarose gel.  Agarose is visible in MRI due to its high percentage of water.  The fiducial markers were also taped with reflective tape, so that they could be imaged by a motion capture system.  Driving this phantom with a stepper motor during the MRI scan and in a motion capture lab allows for a kinematic comparison to determine the accuracy of our dynamic MRI methods. 

Another application of distance fields is finding the thickness of cartilage models created from MRI scans and laser scans.  After the cartilage thickness is determined our results were used to validate research using MRI to compute cartilage contact during the active task explained above.  




