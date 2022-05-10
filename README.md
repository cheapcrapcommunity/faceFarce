# faceFarce


I have always wanted an improvisation partner that would be my becking-call and
require very little equipment to perform. FaceFarce is a patch that tracks facial
movements in real time and provides audio response accordingly.

The patch uses cv.jit object to perform pattern analyse, recognition and keypoints
detection, and FaceOSC to track the pose data. Most of time, the results of whether
matching or not are sent to different audio layers in the patch for triggering or
disabling, and the pose data which contains continuous data flow such as mouth
size, are used as parameters of audio such as filter size. The data of position,
degree and strength of keypoints are mapped to notes and frequencies.

As the technology of facial tracking is still somewhat uncertain and inaccurate,
there's big room for "improvisation". Meanwhile, an intricate real-time response
system design can help create more uncertainty and even chaos. However, it reacts
to the facial changes of the performer, so it is still controllable.

It has a piano layer, two synth layer, a vocal layer, a sampler layer and a LFO layer.
In the editor view, the performer can check the details of the patch; in the
presentation view, the performer can monitor the changes of the main parameters in
different layers at the sametime.

When I play with it, I use the big viewer in the presentation view as a score board, as
it somehow indicates what I want to do next. It collects data from all parts of the
patch, including early stage of tracking and comparing, later stage of mapping and
triggering... It’s a real-time visualisation of the teamwork between the performer and
faceFarce.

![Screenshot 2022-05-10 133141](https://user-images.githubusercontent.com/76624368/167628889-e1e1d2f9-1a51-4e53-9440-17d35dadf92a.png)



https://user-images.githubusercontent.com/76624368/167628904-06a37bc3-0166-429d-a553-1910fb81d62e.mp4

