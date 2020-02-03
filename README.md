<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
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
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h1 align="center">MATCHA</h1>
  <p align="center">
    This project consists in creating a dating site
    <br />
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project

![Product Name Screen Shot][product-screenshot]

An application allowing a user to register and enter their personal details and preferences in the other, 
in order to be able to match another user with a more or less corresponding profile, among a
selection of profiles of other users that your site will offer.
Once they have reciprocally matched, these two profiles should be able to exchange sweet words and more if affinities via a private chat.

### Built With

* HTML
* CSS / Framework Bootstrap
* Template ejs
* Javascript
* SQL
* Node.js


<!-- GETTING STARTED -->
## Getting Started


### Installation

1. Install and update [HomeBrew](https://brew.sh/)
    
    ```bash
    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" && brew update
    ```

2. Install [docker](https://www.docker.com/) and [docker-machine](https://docs.docker.com/machine/) via HomeBrew
    
    ```bash
    brew install docker docker-machine
    ```

3. Clone or download/extract the project repository
    
    ```bash
    git clone https://github.com/gde-pass/Matcha.git && cd Matcha/Docker
    ```

4. Install depedencies
    
    ```bash
    npm install
    ```

5. Create and start a docker-machine
    
    ```bash
    docker-machine create Matcha && docker-machine start Matcha
    ```

6. Link your environment 

    ```bash
    eval $(docker-machine env Matcha)   
    ```

7. Execute the [docker-compose](https://docs.docker.com/compose/) file in the Docker folder
    
    ```bash
    docker-compose up 
    ```

8. Start the node server locate in `Matcha/app/config/server.js`

    ```bash
    node server.js
    ```

9. Here we go ! You can now visit [Matcha](http://127.0.0.1:8080) !




<!-- CONTACT -->
## Contact

ANDEOL Kévin - andeol.kevin@gmail.com

Project Link: [https://github.com/kandeol/Matcha-project-42](https://github.com/kandeol/Matcha-project-42)







<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/k%C3%A9vin-andeol-544723195/
[product-screenshot]: images/Screen_Matcha.PNG
