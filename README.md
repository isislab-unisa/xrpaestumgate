<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![project_license][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/isislab-unisa/xrpaestumgate">
    <img src="images/logo/xpg.png" alt="Logo" width="240" height="110">
  </a>

<h3 align="center">XR-PaestumGate</h3>

  <p align="center">
    XR-PaestumGate explores the potential of immersive technologies such as
    Virtual Reality (VR) in the field of cultural heritage valorization. The open source project extends the virtual reconstruction of the
    archaeological site of Paestum through the design and implementation of
    a serious game (SG) in VR integrating game mechanics designed to increase user involvement and interest.The experience consists of various activities, from exploring the environment to discover its key places to the possibility of driving a roman chariot
    <br/>
    <a href="https://github.com/isislab-unisa/xrpaestumgate"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="#download">Download</a>
    &middot;
    <a href="https://github.com/isislab-unisa/xrpaestumgate/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/isislab-unisa/xrpaestumgate/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
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
## About The Project

[![Trailer](images/trailer_thumbnail.png)](https://drive.google.com/file/d/1E4MpI946NDz0M1To-rnbPUO_zsutUqrt/view?usp=sharing)

XR-PaestumGate is an open source serious game developed in Unity for desktop device and VR headset.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* Unity version 2022.3.53f1 LTS
* C#
* Meta All in One SDK
* 3DS Studio Max

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
To get a local copy up and running follow these simple steps:

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
Before starting, ensure you have the following installed:
- **Unity Hub** (latest version recommended)
- **Unity Editor**
- **Git** (for cloning the repository)
- **Visual Studio** (or another compatible IDE for script editing)
- **Meta Quest Link** and **Meta Quest Developer Hub** (if you have a Meta standalone VR device). Alternatively, download the software from the producer of your vr device
- **3DS Studio Max** (latest version recommended) for import all the scene's prefab. The software is available on a pay-per-use licence, but a 7-day trial is sufficient to import the necessary project requirements


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/isislab-unisa/xrpaestumgate.git
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
  - Open the **Package Manager** (`Window` > `Package Manager`)
  - Install any missing dependencies or packages
  - If required, configure **Oculus Plugin Management** for VR support
8. Build
  - Go to File > Build Settings
  - Select the platform: Android
  - Click Switch Platform if needed
  - Setup the *Scenes in Build* with the project Scenes (it is recommended to use the menu scene as first in the list). an example of what it should look like in the image below
  <p align="center">
    <img src="images/project/build.jpg" alt="Logo" width="380">
  </p>

9. Run the project
  - Click Play in the Unity Editor to test the game
  - For a standalone build, click **Build and Run** in the Build Settings window. The result is an **apk** file for your VR device

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage
The versions (VR and desktop) of the game are divided in two different directories, both have the same game modes:
- Exploration: freely explore the ancient site of Paestum on foot or using the chariot
- Chariot Run: timed chariot race along a predefined route
- Key Places: explore the map and locate the points of interest on the map within a time limit

The following is the Scenes directories:
  <p align="center">
    <img src="images/project/scenes.jpg" alt="Scenes" width="400">
  </p>
The subdirectories contains all the Scenes for Desktop and VR version of XR-PaestumGate as visible from the images below
<p align="center">
    <img src="images/project/dtscenes.jpg" alt="Desktop" width="220">
    <img src="images/project/vrscenes.jpg" alt="Desktop" width="280">
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Download
Dowload the desktop version or the VR version of XR-PaestumGate \
How to install:
1. Download the installer
2. Install it on your device
3. Enjoy it

[Desktop exe]()

[Headset apk]()

## Troubleshooting
- If errors occur, check the **Console** for logs
- Ensure all **Unity packages** are installed and up to date
- Restart Unity or delete the `Library` folder if necessary
- Verify that **Oculus software** is running (for VR projects)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- ROADMAP -->

## Roadmap

- [ ] New modalities
- [ ] Add hint for keyplaces modality
- [ ] Minimap for VR mode

See the [open issues](https://github.com/isislab-unisa/xrpaestumgate/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors:

<a href="https://github.com/isislab-unisa/xrpaestumgate/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=isislab-unisa/xrpaestumgate" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the Apache License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Francesco Pio Covino: francescop.covino@gmail.com

Project Link: [https://github.com/isislab-unisa/xrpaestumgate](https://github.com/isislab-unisa/xrpaestumgate)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []() Unity
* []() C#
* []() Virtual Reality concepts

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
[Unity]: https://img.shields.io/badge/-Unity-%23444444?style=for-the-badge&logo=unity&logoColor=black
[Unity-url]: https://unity.com/