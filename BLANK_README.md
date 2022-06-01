<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="https://user-images.githubusercontent.com/50400038/171317628-fc79e6f8-16a9-44eb-9555-6aab8498bb9c.png" width="700" height="370">
  </a>

  <h3 align="center">Topic Classification for Training Courses</h3>
</div>



<!-- TABLE OF CONTENTS -->
<details align="center">
  <summary>Table of Contents</summary>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#libraries-built-with">Libraries Built With</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul class ="center">
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project aims to automate the process of classifying the course titles to the related course topics. Currently, the organisation where this need arose from does it manually, which is inefficient, time-consuming and low levels of accuracy due to human subjective understanding of the course titles and available topics to tag it with. The solution was to use a supervised machine learning model, train it on exisitng tagged data and deploy the model for used for future classification exercise. This done in hopes to reduce time and effort spent by about 50% to avail resources for more indepth analysis.
<p align="left">(<a href="#top">back to top</a>)</p>

### Libraries Built With

* Text Processing/NLP
  - [NLTK](https://www.nltk.org/): Stopwords, tokenization, Lemmatization etc.
  - [Contractions](https://github.com/kootenpv/contractions)
* Wrangling of Data to required features and labels
  - [PANDAS](https://pandas.pydata.org/docs/reference/io.html#)
  - [NUMPY](https://numpy.org/doc/stable/reference/index.html#reference)
* Pre-processing and Model Training
  - [SKLearn](https://scikit-learn.org/stable/modules/classes.html)
<p align="left">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

