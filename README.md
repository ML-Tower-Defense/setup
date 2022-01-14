# Setup

This repo contains instructions for installing the Unity project locally.

## Prerequisites

* [Unity Hub](https://unity3d.com/get-unity/download)
* [GitHub Desktop](https://desktop.github.com/)

## Installation

1. Open up a terminal and find a folder where you will put this project inside.
2. Clone the repo by entering this command line into the terminal.
   ```sh
   git clone https://github.com/ML-Tower-Defense/capstone.git
   ```
3. Open up the GitHub Desktop app and log into your account.
4. In GitHub Desktop, navigate to `File > Add local repository...` at the top.
Find the folder where you cloned the repo and choose the folder named `capstone` to be the local path. The local path should end in `\capstone`. After the local path has been chosen, click the `Add repository` button.

![Image 01][image01]

5. In this screen, GitHub Desktop will show all of the file differences when you start making changes to the project.

![Image 02][image02]

6. Open up the Unity Hub app. Make sure that you have the `2020.3.21` version of Unity Editor which you can check under the `Installs` tab. If it is not, you can find the `2020.3.21` version [here](https://unity3d.com/get-unity/download/archive) and download it by clicking the green `Unity Hub` button.

![Image 06][image06]

7. In Unity Hub under the `Projects` tab, click the `Open` button. Find the folder where you cloned the repo and inside of the `capstone` folder, choose the folder named `Tower Defense` as the folder to open. Unity Hub will add the `Tower Defense` project and open it.

![Image 03][image03]

8. When Unity Hub has finished opening the project in the Unity Editor, navigate to `Edit > Project Settings...` at the top. Under the `Editor` tab, find `Asset Serialization` and make sure `Mode` is set to `Force Text`. Under the `Version Control` tab, make sure `Mode` is set to `Visible Meta Files`.

![Image 04][image04]

![Image 05][image05]

[image01]: docs/images/image01.png
[image02]: docs/images/image02.png
[image03]: docs/images/image03.png
[image04]: docs/images/image04.png
[image05]: docs/images/image05.png
[image06]: docs/images/image06.png
