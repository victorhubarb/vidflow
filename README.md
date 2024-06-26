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
Website for video sharing, similar to the famous current YouTube. It includes navigation tabs with subscriptions, history, search bar, and other menu options for navigation. The main content contains videos and buttons for video filtering.
<p align="right">(<a href="#readme-top">back to top</a>)</p>
 
## Features and Application Demonstration
- `Feature 1`: Implementation of filters, such as the search bar, and we filter the application with category buttons, such as mobile, front-end, and data science.
- `Feature 2`: To fetch videos for the application, we consume an API using promise methods.
- `Feature 3`: Responsive project, developed for various screen sizes as well.
- `Feature 4`: Implementation of a button in the top right corner for switching to night mode.
- `Feature 5`: Project developed using WAI-ARIA to enhance accessibility. Tested using keyboard navigation as well as a third-party screen reader application, specifically NVDA.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Project Access
Project requirements:
- Have your preferred IDE installed on your computer.

Have the code on your computer:
- Access the project source code [here](https://github.com/victorhubarb/vidflow) or download the project [here](https://github.com/victorhubarb/jogo-numero-secreto/archive/refs/heads/main.zip). After one of these steps, and also unzip it on your computer in case of download, open the project in your preferred IDE.

- Clone repository with the following steps:
1. Open the terminal
2. git clone [https://github.com/victorhubarb/vidflow.git](https://github.com/victorhubarb/vidflow.git)
3. Press ENTER to create your clone
4. Have your prefered IDE installed in your computer.

Follow the steps below to make use of the fake API or mock API created for use only in this project:
1. Install Node.js:
	- Before we begin, it's important to have Node.js installed on your system. Click [here](https://nodejs.org/en/download/) to be redirected to the website for installation.

2. JSON Server Installation:
	- Open your terminal or command prompt
	- To install JSON Server globally, you just need to type the following command and press "Enter"
	- `npm install -g json-server`
	- This will install JSON Server globally on your system, and you'll be ready to use it in any project.

3. Allowing script execution policy (Windows only). If you're using Windows, you need to follow these steps to run JSON Server:
	- Open PowerShell as an administrator. To do this, search for "PowerShell" in the Start menu, right-click on "Windows PowerShell" (or "Windows Terminal"), and select "Run as administrator".
	- The execution policy may be "Restricted," which is the default setting that prevents script execution. In PowerShell, you can check the current execution policy with the following command:
	- `Get-ExecutionPolicy`
	- Run the following command to allow script execution on your computer:
	- `Set-ExecutionPolicy RemoteSigned`
	- PowerShell may ask for confirmation to perform the operation. Press "S" (Yes) or "Y" (Yes) depending on the language of your terminal and press Enter to confirm.
	- After completing the task, it's a good practice to revert the script execution policy to the original value to ensure system security. You can do this by setting the execution policy back to "Restricted" with the following command:
	- `Set-ExecutionPolicy Restricted`
	- However, if you want to use JSON Server again, you'll need to change the execution policy to "RemoteSigned" once more.

4. Starting JSON Server:
	- Open the integrated terminal of VSCode or your preferred IDE, so the terminal will automatically open within the project folder. Run the following command to start JSON Server and use it with the videos.json file:
	- `json-server --watch backend/videos.json`
	- JSON Server will be started and will begin serving a fake REST API based on the data from the videos.json file, allowing us to consume the data for VidFlow.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

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
