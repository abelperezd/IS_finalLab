# Repository information
In this repository we find the final project of the subject Interactive Systems, done in the third year.

This is a full body interaction game developed in Unity using the API of PoseNet (https://www.tensorflow.org/lite/models/pose_estimation/overview).

In addition to the files, there is a demonstration video and a presentation in which we explain the game.

### Story
Given the circumstances caused by the Covid-19, we decided to develop a children's game so that they could play sport from home. Considering the situation, we also gave it an educational approach in which they could indirectly learn concepts such as hand washing and the use of masks to prevent contagion.

### Instructions for Windows
1. Download the files from the repository and the assets from the following address and include all of them in the same folder: https://drive.google.com/drive/folders/1iwrOZm08Vex6FY9V4Xqyhn32wa1kd6_b?usp=sharing

2. Install outbuildings.
- Install node from https://nodejs.org/en/download/
- Install Yarn package manager (download msi installer). https://classic.yarnpkg.com/en/docs/install/#windows-stable
- Open command line and install the dependencies (for a few minutes it will download and install packages and dependencies) *>yarn*
- Go to the folder posenetosc-master, open a command line and type *>node bridge.js*
- Open a new command line in the same folder and type (opens a browser) *>yarn watch*

3. Keep the browser open with PoseNet running.

4. Open the project with Unity and start the game from the *Title* scene.
