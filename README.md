# VidFlow <a name="readme-top"></a>
![Static Badge](https://img.shields.io/badge/status-completed-green?style=for-the-badge)

## Introduction
**VidFlow** is a video-sharing platform, similar to YouTube. Built using HTML, CSS, and JavaScript, the platform offers a fluid user experience, with features such as dynamic video display, search, category filters, and switching between light and dark modes.

## Live Application
[VidFlow Demonstration](https://vidflow-five.vercel.app)

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [Contributors](#contributors)

## Installation

### Prerequisites
- [Node.js](https://nodejs.org/)
- A text editor, such as VSCode

### Steps to run
1. Clone the repository:
   ```bash
   git clone https://github.com/victorhubarb/vidflow.git
   cd vidflow
   ```
2. Install JSON Server globally:
   ```bash
   npm install -g json-server
   ```
3. Start the JSON Server to simulate an API:
   ```bash
   json-server --watch backend/videos.json
   ```

## Usage
Open the `index.html` file in your browser or use a local server to view the application. The interface will allow you to search and filter videos, switch between light and dark modes, and browse available videos.

## Features
- **Dynamic Video Display**: Videos are dynamically loaded from a JSON file simulating an API.
- **Video Search**: Includes a search bar that filters videos based on the text entered.
- **Category Filter**: Videos can be filtered by category for easier navigation.
- **Light/Dark Mode**: Toggles between light and dark themes to improve the user experience.
- **Thumbnails and Metadata**: Displays the title, previews, and channel name next to each video thumbnail.

## Technologies
- **HTML5**
- **CSS3**
- **JavaScript**
- **JSON Server** (to simulate an API)

## Contributors
- [Victor Barbosa](https://github.com/victorhubarb)
<p align="right">(<a href="#readme-top">back to top</a>)</p>
