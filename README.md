<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![project_license][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="images/logo/logo_xrp.png" alt="Logo" width="240" height="140">

<h3 align="center">XR-PaestumGate</h3>

  <p align="center">
    XR-PaestumGate is an immersive, VR-based serious game set within a diachronic reconstruction of the ancient city of Paestum. Players can freely walk through the city or ride a horse-drawn Roman chariot, engaging in open-ended exploration or taking on challenges such as locating key historical landmarks.
    <br/>
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#download">Download</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## 📖 About The Project

<p align="center">
  <a href="https://drive.google.com/file/d/1dYe6lTOAooo5yCHFJmVbvBWD9cKLIUQ2/view?usp=sharing">
    <img src="images/thumb.png" alt="thumbnail" width="300" height="300">
  </a>
</p>

XR-PaestumGate explores the potential of immersive technologies such as
Virtual Reality (VR) in the field of cultural heritage valorization. The open source project extends the virtual reconstruction of the
archaeological site of Paestum through the design and implementation of
a serious game (SG) in VR integrating game mechanics designed to increase user involvement and interest. The experience consists of various activities, from exploring the environment to discover its key places to the possibility of driving a roman chariot

The game is divided into three interactive modes:

-   **Exploration Mode**: Offers free roaming within the reconstructed city, either on foot or aboard a chariot,
    allowing users to passively discover the city and its monuments at their own pace.
-   **Chariot Race**: A time-based race in which players must complete a predefined route as quickly as possible,
    competing for top scores on a leaderboard.
-   **Key Points of Interest Identification**: A challenge-based mode where players must identify and reach six
    designated cultural landmarks within a 10-minute time frame.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### 🛠 Built With

-   [![Unity][Unity]][Unity-url]
-   ![Csharp][Csharp]
-   [![MetaSDK][MetaSDK]][MetaSDK-url]
-   [![3DS][3DS]][3DS-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 🚀 Getting Started

To get a local copy up and running follow these simple steps:

### 📌 Prerequisites

This is an example of how to list things you need to use the software and how to install them.
Before starting, ensure you have the following installed:

-   **Unity Hub** (version recommended: 2022.3.53f1)
-   **Unity Editor**
-   **Git** (for cloning the repository)
-   **Visual Studio** (or another compatible IDE for script editing)
-   **Meta Quest Link** and **Meta Quest Developer Hub** (if you have a Meta standalone VR device). Alternatively, download the software from the producer of your vr device
-   **3DS Studio Max** (latest version recommended) for import all the scene's prefab. The software is available on a pay-per-use licence, but a 7-day trial is sufficient to import the necessary project requirements

### 🔧 Installation

1. Clone the repo
    ```sh
    git clone https://github.com/user/xrpaestumgate.git
    ```
2. Change git remote url to avoid accidental pushes to base project
    ```sh
    git remote set-url origin github_username/repo_name
    git remote -v # confirm the changes
    ```
3. Open Unity Hub
4. Click **Open** and select the cloned project folder
5. Ensure you have the correct Unity version (2022.3.53f1) installed.
6. Wait for Unity to load the project and compile assets. (ensure you have 3DS Max installed and with active license)
7. Install Dependencies

-   Open the **Package Manager** (`Window` > `Package Manager`)
-   Install any missing dependencies or packages
-   If required, configure **Oculus Plugin Management** for VR support

8. Build

-   Go to File > Build Settings
-   Select the platform: Android
-   Click Switch Platform if needed
-   Setup the _Scenes in Build_ with the project Scenes (it is recommended to use the menu scene as first in the list). an example of what it should look like in the image below
<p align="center">
  <img src="images/project/build.jpg" alt="Logo" width="380">
</p>

9. Run the project

-   Click Play in the Unity Editor to test the game
-   For a standalone build, click **Build and Run** in the Build Settings window. The result is an **apk** file for your VR device

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## 🎮 Usage

The versions (VR and desktop) of the game are divided in two different directories, both have the same game modes. The following are the Scenes directories:

  <p align="center">
    <img src="images/project/scenes.jpg" alt="Scenes" width="400">
  </p>
The subdirectories contains all the Scenes for Desktop and VR version of XR-PaestumGate as visible from the images below
<p align="center">
    <img src="images/project/dtscenes.jpg" alt="Desktop" width="220">
    <img src="images/project/vrscenes.jpg" alt="Desktop" width="280">
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⬇️ Download

Dowload the desktop version or the VR version of XR-PaestumGate \
How to install the apk on your VR Headset:

#### Using SideQuest

1. **Download and Install SideQuest**

    - Visit [SideQuest](https://sidequestvr.com/) and download the appropriate version for your operating system.
    - Install the software on your computer.

2. **Enable Developer Mode on Your VR Device**

    - Open the Meta Quest mobile app on your smartphone.
    - Go to **Settings** > Select your device > **Developer Mode**.
    - Toggle **Developer Mode** on and restart your headset.

3. **Connect Your VR Device to the Computer**

    - Use a USB cable to connect your headset to your PC.
    - Put on the headset and allow USB debugging when prompted.

4. **Install the APK**
    - Open SideQuest and ensure your device is detected (green dot in the top left corner).
    - Click the **Install APK file from folder** button (⬇ icon).
    - Select the APK file you want to install and wait for the installation to complete.

#### Using Meta Developer Hub

1. **Download and Install Meta Developer Hub**

    - Visit [Meta Developer Hub](https://developer.oculus.com/) and download the tool.
    - Install it on your computer.

2. **Enable Developer Mode** (Follow the same steps as for SideQuest).

3. **Connect Your VR Device**

    - Use a USB cable to connect your headset to your PC.
    - Accept the debugging prompt in the headset.

4. **Install the APK**
    - Open Meta Developer Hub.
    - Navigate to the **Device Manager**.
    - Click on **Install APK** and select your file.
    - Wait for the installation to complete.

#### Verifying the Installation

-   Put on your headset and go to **Apps** > **Unknown Sources**.
-   Locate your installed APK and launch it.

[xrpaestumgate.apk for VR headset](https://drive.google.com/file/d/1LxJJYaQu3V6OZmpYUbYrPDduHl-ivwzi/view?usp=sharing)

#### Download desktop version for Windows, MacOS and Linux
[xrpaestumgate.exe](https://drive.google.com/file/d/1otAMUh9wdDExBaoH9injB27eEAh-HUC6/view?usp=sharing)



## 🆘 Troubleshooting

-   If errors occur, check the **Console** for logs
-   Ensure all **Unity packages** are installed and up to date
-   Restart Unity or delete the `Library` folder if necessary
-   Verify that **Oculus software** is running (for VR projects)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- ROADMAP -->

<!-- LICENSE -->

## 📜 License

Distributed under the Apache License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## 🎖️ Acknowledgments

-   MalbersAnimation (https://malbersanimations.gitbook.io/animal-controller)
-   Optimaze cable and ropes (https://assetstore.unity.com/packages/tools/physics/optimized-ropes-and-cables-tool-287164)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/isislab-unisa/xrpaestumgate.svg?style=for-the-badge
[contributors-url]: https://github.com/isislab-unisa/xrpaestumgate/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/isislab-unisa/xrpaestumgate.svg?style=for-the-badge
[forks-url]: https://github.com/isislab-unisa/xrpaestumgate/network/members
[stars-shield]: https://img.shields.io/github/stars/isislab-unisa/xrpaestumgate.svg?style=for-the-badge
[stars-url]: https://github.com/isislab-unisa/xrpaestumgate/stargazers
[issues-shield]: https://img.shields.io/github/issues/isislab-unisa/xrpaestumgate.svg?style=for-the-badge
[issues-url]: https://github.com/isislab-unisa/xrpaestumgate/issues
[license-shield]: https://img.shields.io/github/license/isislab-unisa/xrpaestumgate.svg?style=for-the-badge
[license-url]: https://github.com/isislab-unisa/xrpaestumgate/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/francesco-pio-covino-583128217
[product-screenshot]: images/pg_explore.png
[MetaSDK]: https://img.shields.io/badge/MetaSDK-004480?style=for-the-badge&logo=meta&logoColor=white
[MetaSDK-url]: https://assetstore.unity.com/packages/tools/integration/meta-xr-all-in-one-sdk-269657?srsltid=AfmBOoqObQxPqmkF85OxNLQzknZ7oVrC0elOFHLKG1Rf2uxe7eLfJfUQ
[3DS]: https://img.shields.io/badge/3DSStudioMax-004480?style=for-the-badge&logo=3ds&logoColor=white
[3DS-url]: https://www.autodesk.com/it/products/3ds-max/
[Unity]: https://img.shields.io/badge/unity-000000?style=for-the-badge&logo=unity&logoColor=white
[Unity-url]: https://unity.com/
[Csharp]: https://img.shields.io/badge/C%23-00C244?style=for-the-badge
