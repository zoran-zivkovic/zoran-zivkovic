## Zoran Zivkovic
- 📫 How to reach me: [LinkedIn](https://www.linkedin.com/in/zoran-zivkovic/),[Google scholar](https://scholar.google.com/citations?user=GeO26QwAAAAJ&hl=en)
- 🔭 I’m currently working on probabilistic radio signals modelling


## Radio signals:

...

## Old stuff:

### Probabilistic modelling:

Probablistic modelling is the main principle behind my work and my main background. I had the privilege to learn from some realy great people at University of Amsterdam [ML lab](https://amlab.science.uva.nl/). Here are a few selected interesting things I did in the past:

- Mixture modelling and on-the fly model selection - an approximate method based on the Minimum Message Length for adaptive model selection ([paper](./papers/zivkovic2004PAMI.pdf),[matlab code](./code/demoEM1.zip))

- Background modelling - the adaptive model from above and some other non parametric models are used to model background pixels ([paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1.4658&rep=rep1&type=pdf), [original c code](./code/CvBSLib.zip)). The code was merged into the Intel [OpenCV](https://opencv.org/) and is the main image background modelling for many years ([video](https://youtu.be/_A_Pw3NEON8), [video(depth camera)](https://youtu.be/VBisVCnXxjI)). The OpenCV names of the two methods are: cv::BackgroundSubtractorMOG2 and cv::BackgroundSubtractorKNN.

- Robust mode finding - inspired by some notes from Tom Minka I derived this extension of the popular mean-shift mode finding. The mode position and the covariance can be simultaneoisly estimated in an Expectation maximization type of inference ([paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.77.7277&rep=rep1&type=pdf),[matlab code](./code/EMShiftDemo.zip)). The method is general but it was used for object tracking and integrated with other common tracking methods as particle filters and mixture Kalman filters ([paper](./papers/zivkovicCVIU2009.pdf), [matlab code](./code/EMShiftDemo2.zip), [video](https://youtu.be/SB-1kHjzaHQ)) 

- Layered video modelling - inspired by the "flexible sprites" of B. Frey and N. Jojic, I introduced binary mask layers which are much more appropriate than Gaussian disrtibution. The approximate Bayesian inference can still be applied ([paper](./papers/Transformation_invariant_component_analysis_for_binary_images.pdf), [matlab code](./code/BTPCA1_0.zip), [video](https://youtu.be/CbuCG9Gd2O4)) 

- Part based modelling - I really liked the "constellation models" from M. Weber, M. Welling, and P. Perona. Multiple detections are combined using a proper probablistic model. I extended and applied this model to various real-time multisensor systems ([paper](./papers/zivkovickroseIROS2007)):
    - [video (omnidirectional camera)](https://youtu.be/KK3U4tBNGgQ)
    - [video (camera and laser range scanner)](https://youtu.be/K9KY-1rGf4Q)
    - [video (wireless embedded cameras)](https://youtu.be/PDrSal76q50)

### User interfaces:

I was always interested in the new user interfaces. Often this was my hobby in the background of other activites:

- Starting my PhD: ICCV 2001 demo and paper on camera based 3D face tracing. Real time demo on Intel Pentium III 450MHz processor! ([paper](./papers/zivkovic2001RATFGRTS.pdf), [video](https://youtu.be/DHVFyeE4R2o))

- Camera based games using optical flow -  ([paper](./papers/zivkovic2004ICEC.pdf))

- Sceen interaction with active illumination (WO Patent 2012175703 A1) - invisible modulated active illumination is put into the TV screen [paper](./papers/MidAirInteractiveDisplay_ICCE2012.pdf), [video1](https://youtu.be/T4kF3N92G78), [video2](https://youtu.be/cwX9sAtTBgs)

- Light sensor design and gesture control: [paper](./papers/Air_gesture_control_using_5-pixel_light_sensor.pdf), [video](https://youtu.be/TVX_xg4Ipbs)

### Robot navigation:

For a while I was busy with the robot navigation and multi-view geometry. The main theme was to find the proper ballance between the geometry and the more abstract graph representations of the environment.
 
- The geometry was important so we carefully designed and calibrated an omnidirectional system on a robot: [report](https://www.academia.edu/download/53367313/a_hyperbolic_mirror_experiment_info.pdf), [video](https://youtu.be/Yw3e9puy2W0). Also we derived a minimal maximum likelihood 2 point algorithm: [paper](./papers/planarPoseRSS10.pdf).

- A few sample papers graph reasoning including geometric concepts: [paper](./papers/zivkovicbooijkroseRAS2007.pdf), [paper](./papers/zivkovicbakkerICRA2006.pdf), [paper](https://www.academia.edu/download/53367341/Sampling_in_image_space_for_vision_based20170602-3060-1yit476.pdf)
