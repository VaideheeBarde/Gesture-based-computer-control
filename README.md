# GestureBasedComputerControl

SUMMARY -

- Implementation platform used is MATLAB
- Engineered the cursor to move on a monitor screen in co-ordination with the finger movements captured by the web camera
- Developed a program which apprehended samples of input finger movements from the web camera on a frame-by-frame basis
- Implemented blob analysis and computed the RGB to gray conversion for each frame
- Detected high intensity areas in each frame and programmed the cursor to move to these high intensity areas

ABSTRACT -

This provides immersive virtualization and a high degree of accessibility giving the users innovative technology at interpreting human gestures via mathematical algorithms. 
Gesture recognition enables humans to communicate with the machine (HMI). This could potentially make conventional input devices such as mouse, keyboards and even touch-screens redundant.
Thus, moving ahead with technological innovations, it provides a familiarity of interaction of a physical mouse without actually needing a real hardware mouse. An advantage of multiple computer control can be utilized from this development. Here, the hand movements are translated into cursor movements thus interfacing physical world with a digital world.  This suite provides a base which will enable in creating new ways to interact with your device and your applications.

HIGH LEVEL DESIGN -

In gesture recognition technology, a camera reads the movements of the human body and communicates the data to a device that uses the gestures as input to control devices or 
applications. Gesture recognition is a topic in computer science and language technology with the goal of interpreting human gestures via mathematical algorithms. Gestures can originate from any bodily motion or state but commonly originate from the face or hand. Current focuses in the field include emotion recognition from the hand gesture recognition.  The main objective of gesture recognition review is: 
- Study of various types of gestures 
- Study  of various types of gesture recognition 
- Applications of gesture recognition
 
LOGICAL STRUCTURE -

- Requirements - a. Camera b. Laptop/Desktop supporting MATLAB software. This code has been tested on MATLAB R2011.
- Logical Structure of High Level Design -

![Gesture_Recognition_Logical_Structure](https://user-images.githubusercontent.com/22990797/124095553-a5bdaa80-da0e-11eb-93b9-d73f2abaa420.PNG)

3.) Appearance based models -
- Parameters are derived directly from images or videos or features derived from these.
Approach 1 - Parameters are based on deformable 2D templates of the human parts of the body
a. 2D templates of the human body are captured as images
b. sets of points on the outline of an object, used as interpolation nodes for the object’s outline approximation. Interpolation function is linear which performs an average shape from point sets, point variability parameters and external deformators.
Approach 2 - Using image sequences as gesture templates
b. Parameters are not derived from spatial representation of the body.
 
4.) Blob analysis
- Blob detection refers to mathematical methods that are aimed at detecting regions in a digital image for further processing that differ in properties, such as brightness or colour, compared to areas surrounding those regions. A blob is a region of a digital image in which some properties are constant or vary within a prescribed range of values.
- Blob analysis offers complementary information about regions, which is not obtained from edge detectors or corner detectors.
- Object recognition, object tracking, ridge detection to signal the presence of elongated objects.

5.) Limitations -
- Efficient camera, to avoid lag in the simulation of images
- Color caps on the fingers as the code runs on RGB color scale of the frame.
