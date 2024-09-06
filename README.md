# TRACE

**Collected data visualized**

Court lines, ball, and player landmarks identified.

![Video](https://github.com/hgupt3/TRACE/assets/112455192/627e8ca6-86c1-4409-938d-2b45e875bbfa)


**Top-down view**

This view is extrapolated from data collected.

![Final](https://github.com/hgupt3/TRACE/assets/112455192/916287fb-e507-40a1-8bb8-7ab9f3dafbc3)


**Required Libraries**

cv2

torch

mediapipe

numpy

math

os

sys



**Ball detection from:**

Yu-Chuan Huang, "TrackNet: Tennis Ball Tracking from Broadcast Video by Deep Learning Networks," Master Thesis, advised by Tsì-Uí İk and Guan-Hua Huang, National Chiao Tung University, Taiwan, April 2018.

Prerequisites

    Python 3.x
    Install the required libraries using:

    bash

    pip install cv2 torch mediapipe numpy

Steps for Ball Detection

    Clone the Repository: First, clone the TRACE repository to your local machine.

    bash

git clone https://github.com/hgupt3/TRACE.git
cd TRACE

Prepare the Input Video: Ensure you have a video file (tennis match) ready to process. The video should be placed in the appropriate directory within the project.

Run Ball Detection Script: The repository includes a script named BallDetection.py, which is designed to detect the ball in a tennis match. Execute the script as follows:

bash

    python BallDetection.py --input <path_to_video>

    This will process the video and detect the ball in each frame.

    View Output: After processing, the output video with ball tracking will be saved in the specified output directory. The top-view and ball trajectory can also be visualized as shown in the examples from the repository.

Additional Information

The project builds on TrackNet, a deep learning network for tennis ball tracking. The results show the trajectory of the ball in both the original and extrapolated top-down view.

To explore further, you can tweak or modify other scripts in the repository such as:

    CourtDetection.py for court detection.
    BodyTracking.py for player tracking.

For more details, visit the repository README file.
