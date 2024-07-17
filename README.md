# VidFlow <a name="readme-top"></a>
![Static Badge](https://img.shields.io/badge/status-completed-green?style=for-the-badge)

## Table of Contents 
* [Title and Cover Image](#title-and-cover-image)
* [Badges](#badges)
* [Table of Contents](#table-of-contents)
* [Project Description](#project-description)
* [Features and Application Demonstration](#features-and-application-demonstration)
* [Project Access](#project-access)
* [Technologies Used](#technologies-used)
* [Project Developers](#project-developers)

## Project Description
VidFlow is a dynamic video platform developed using HTML, CSS, and JavaScript, designed to offer a user experience similar to popular video streaming services like YouTube. The platform features a responsive design that supports a light and dark mode switch and incorporates an intuitive interface for seamless navigation and video discovery. VidFlow leverages a fake API stored as a JSON file in the project's directory to dynamically display video content, making it an excellent tool for showcasing video-based projects or for developers looking to understand video platform functionalities.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Live Application
[VidFlow Demonstration]()
 
## Features
- **Dynamic Video Display**: Videos are dynamically loaded and displayed using data from a local JSON file, simulating a real API response.
- **Responsive Search Functionality**: The platform includes a search bar that filters videos based on user input, showcasing only relevant results instantly.
- **Category Filtering**: Users can filter videos by categories, which reorganizes the video display to match the selected category, enhancing content discoverability.
- **Light/Dark Mode Toggle**: Features a mode toggle switch that allows users to switch between light and dark themes, catering to different viewing preferences and conditions.
- **Interactive Sidebar Menu**: Includes a navigational sidebar with expandable sections for different content categories like Home, Explore, and Subscriptions, improving site navigation and user experience.
- **Video Thumbnails and Metadata**: Displays essential information such as video title, views, and channel name alongside each video thumbnail, providing a snapshot of the video content at a glance.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Project Access

### Prerequisites
- **Integrated Development Environment (IDE)**: Ensure you have your preferred IDE installed on your computer, such as Visual Studio Code.
- **Node.js**: Essential for running certain backend simulations like JSON Server. [Install Node.js here](https://nodejs.org/en/download/).

### Obtaining the Code
You can access and set up the project source code in a few different ways:
- **Direct Download**:
  - [Download the project ZIP file here](https://github.com/victorhubarb/vidflow/archive/refs/heads/main.zip), unzip it on your computer and open the project in your IDE.
- **Clone via Git**:
  ```bash
  # Open your terminal
  git clone https://github.com/victorhubarb/vidflow.git
  
  # Navigate to the project directory
  cd vidflow
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Setting up JSON Server
To simulate a backend for development purposes using JSON Server:
- **Install JSON Server**:
  ```bash
  npm install -g json-server
  ```

- **For Windows Users**:
You may need to adjust the script execution policy to use JSON Server. Open 		PowerShell as an administrator and run:
  ```bash
  Set-ExecutionPolicy RemoteSigned
  ```

To revert the policy after usage:
  ```bash
  Set-ExecutionPolicy Restricted
  ```

### Running the Project
- **Starting JSON Server**:
  ```bash
  # Navigate to the project directory where the `videos.json` is located
  json-server --watch backend/videos.json
  ```
This will start JSON Server, which hosts a fake REST API from your videos.json file.
- **Open the Project**:
  Open your project in the IDE and run your local server or simply open the index.html file in a browser to see the project in action.
- **Note on Security**:
  Reverting the PowerShell execution policy to its default setting (Restricted) after using JSON Server is recommended to ensure system security.

## Technologies Used
![Static Badge](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Static Badge](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Static Badge](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Static Badge](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Static Badge](https://img.shields.io/badge/json%20web%20tokens-323330?style=for-the-badge&logo=json-web-tokens&logoColor=pink)
![Static Badge](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Project Developers
| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/80085116?v=4" width=115><br><sub>Victor Barbosa</sub>](https://github.com/victorhubarb) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/4975968?s=200&v=4" width=115><br><sub>Alura</sub>](https://github.com/alura-cursos) |
| :---: | :--: |
<p align="right">(<a href="#readme-top">back to top</a>)</p>
