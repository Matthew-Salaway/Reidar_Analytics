# Reidar DAO Investment Portfolio Analytics

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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

### [Check out the website!](https://reidarchart.web.app/)
<img width="600" alt="Production Site Photo" src="https://user-images.githubusercontent.com/60244026/193508932-93ea6290-19eb-4185-b621-471590bf97f8.png">



<!-- ABOUT THE PROJECT -->
## About The Project

The Reidar DAO specializes in strategic investments for cryptocurrencies and digital assets. This is the analytics website I created for them to showcase their assets and investment portfolio!

Key Aspects:
* Price per token historical chart
* NFT asset information, current price in ETH, and predictive preformance (click the image!)
* Token asset information, current price in ETH

For anyone who wants to replicate this website with thier own assets, check out <a href="#getting-started">Getting Started</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With

#### Front-end
* [![React][React.js]][React-url]
* Javascript
* Chart.js

#### Back-end
* Firebase
* Node.js

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Matthew-Salaway/Reidar_Analytics.git 
   ```
2. Install Packages with Yarn
   ```
   yarn install
   ```
3. Set up a database 
  - I utilized firebase real time database to store the asset data and price chart information
  - Then I get the data with my firebase configuration that I store in a .env file
  - The front-end does not update the database, as my backend does that
4. Host the Site
  - I used firebase to host my website 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage
  - Shareholders: Check the preformance of thier investment
  - Management: See the current price and predictive preformance of assets
  - Potential Investors: See analysis of investment portfolio

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



<!-- LICENSE -->
## License

Distributed under the MIT License

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Matthew Salaway - matthewsalaway@gmail.com

Project Link: [https://github.com/Matthew-Salaway/Reidar_Analytics](https://github.com/Matthew-Salaway/Reidar_Analytics)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
