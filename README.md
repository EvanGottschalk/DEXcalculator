[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/EvanGottschalk/DEXcalculator">
    <img src="images/logo.png" alt="Logo" width="151" height="80">
  </a>

  <h3 align="center">DEXcalculator</h3>

  <p align="center">
    A simple program for calculating cryptocurrency prices on decentralized exchanges
    <br />
    <a href="https://github.com/EvanGottschalk/DEXcalculator"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/EvanGottschalk/DEXcalculator">View Demo</a>
    ·
    <a href="https://github.com/EvanGottschalk/DEXcalculator/issues">Report Bug</a>
    ·
    <a href="https://github.com/EvanGottschalk/DEXcalculator/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

I initially built `DEXcalculator` as part of a programming challenge to find arbitrage opportunities between decentralized exchanges. Its main purpose is to calculate the prices of trading particular amounts of cryptocurrencies on particular exchanges. The particulars are chosen by user input, allowing one to find better prices for certain amounts of cryptocurrencies on different exchanges at different times.


### Built With

* `Python 3.6`
* `web3`


<!-- GETTING STARTED -->
## Getting Started

Getting `DEXcalculator` up and running is easy (and free!).

### Prerequisites

Before using `DEXcalculator`, one must create a free account on [Alchemy.com](https://www.alchemy.com/) to obtain an API key. The `Web3` library is also required for `DEXcalculator` to make necessary API calls.


### Installation

1. To use `DEXcalculator`, one must obtain their own [Alchemy](https://www.alchemy.com/) API key. This is quick, simple, and free to do.
  1a. First, create a free account on [Alchemy.com](https://www.alchemy.com/).
  1b. Next, create a blank app using the "+CREATE APP" button (the app's particular parameters are not relevant to `DEXcalculator`).
  1c. That's it! The new API key will be displayed on the [Alchemy](https://www.alchemy.com/) dashboard.

2. Install the `web3` library, which is listed in `requirements.txt`. The easiest way to do this to download `requirements.txt` and use `pip`:
    ```
    pip install -r requirements.txt
    ```

3. Download `DEXcalculator.py`

4. Congratulations! `DEXcalculator` can now be used to calculate prices on decentralized exchanges. Simply run the `.py` file, input an [Alchemy](https://www.alchemy.com/) API key (or link), and choose the spending parameters to have the current price calculated! `DEXcalculator` can also be incorporated into other programs as a means of obtaining in-the-moment prices of specific amounts of cryptocurrency traded on specific exchanges.


<!-- USAGE EXAMPLES -->
## Usage

Running `DEXcalculator.py` allows one to choose a cryptocurrency to spend, a cryptocurrency to receive, an amount to spend, and a decentralized exchange to do it all on. Doing so will display the price of per spent cryptocurrency of the cryptocurrency they will receive.

Importing `DEXcalculator` enables a program to quickly access prices of different cryptocurrencies on different decentralized exchanges. For example, the [ArbitrageAggregator](https://github.com/EvanGottschalk/ArbitrageAggregator/) program uses it to find profitable arbitrage opportunities, in which a cryptocurrency is bought on one exchange and then sold on another at a higher price.


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/EvanGottschalk/DEXcalculator/issues) for a list of proposed features (and known issues).


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the GNU GPL-3 License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Evan Gottschalk - [@Fort1Evan](https://twitter.com/Fort1Evan) - magnus5557@gmail.com

Project Link: [https://github.com/EvanGottschalk/DEXcalculator](https://github.com/EvanGottschalk/DEXcalculator)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

Thinking about contributing to this project? Please do! Your Github username will then appear here.





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/EvanGottschalk/DEXcalculator.svg?style=for-the-badge
[contributors-url]: https://github.com/EvanGottschalk/DEXcalculator/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/EvanGottschalk/DEXcalculator.svg?style=for-the-badge
[forks-url]: https://github.com/EvanGottschalk/DEXcalculator/network/members
[stars-shield]: https://img.shields.io/github/stars/EvanGottschalk/DEXcalculator.svg?style=for-the-badge
[stars-url]: https://github.com/EvanGottschalk/DEXcalculator/stargazers
[issues-shield]: https://img.shields.io/github/issues/EvanGottschalk/DEXcalculator.svg?style=for-the-badge
[issues-url]: https://github.com/EvanGottschalk/DEXcalculator/issues
[license-shield]: https://img.shields.io/github/license/EvanGottschalk/DEXcalculator.svg?style=for-the-badge
[license-url]: https://github.com/EvanGottschalk/DEXcalculator/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/EvanGottschalk