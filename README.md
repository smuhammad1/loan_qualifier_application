<!-- TABLE OF CONTENTS -->
<details open="open">
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
        <li><a href="#installation-and-technologies">Installation and Technologies</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
	<!-- <li><a href="#license">License</a></li> -->
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This is a python command-line interface application that allows users to see the loans they qualify for based on criteria from a `daily_rate_sheet` from various loan providers, then prompting the user to input their personal relevant information, and returning a set of avaliable loans with an option to save those loans to a specefic path (in this case, a csv file).

### Built With

<!-- This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples. -->

* [Python](https://www.python.org/)
* [Python CSV Reading/Writing](https://docs.python.org/3/library/csv.html)
* [Python fire](https://pypi.org/project/fire/)
* [Python questionary](https://pypi.org/project/questionary/)

<!-- GETTING STARTED -->
## Getting Started

<!-- This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps. -->

### Prerequisites

<!-- This is an example of how to list things you need to use the software and how to install them. -->
* Python

### Installation and Technologies

1. Clone your local repository.
   ```sh
   git clone https://github.com/smuhammad1/loan_qualifier_application.git
   ```
2. Install pip - package installer for Python
   [here](https://pip.pypa.io/en/stable/installation/)
3. Install Python packages

For this project, you will need to utilize python 3.7 of the following packages:

   ```sh
   import csv - For importing a csv file that will display the specific loans the user qualifies for.
   pip install pathlib - For loading and saving files from and to specefic paths.
   pip install fire - For the command line interface, help page, and entrypoint.
   pip install questionary - For interactive user prompts and dialogs.
   ```
---

## Usage

This app is used by cloning the repository and running the app.py with python on a local terminal or command line: 

`python app.py`

<img width="873" alt="Screen Shot 2022-01-16 at 10 13 56 PM" src="https://user-images.githubusercontent.com/96351123/149717095-dd71d79d-cd8b-4c1e-bb2e-7e446b438f35.png">

This project is a loan application that prompts the user to enter financial and private data to determine if an applicant qualifies for a loan and the type of loan the applicant qualifies for. It also asks the user to save the qualifying loans as a new CSV file.

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/smuhammad1/loan_qualifier_application/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->
<!-- ## License

Distributed under the MIT License. See `LICENSE` for more information.
 -->

<!-- CONTACT -->
## Contact

Sumayyah Muhammad - [@somayaann][linkedin-url] - sumayyahmuhammadts@gmail.com

Project Link: [https://github.com/smuhammad1/loan_qualifier_application](https://github.com/smuhammad1/loan_qualifier_application)

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/smuhammad1/loan_qualifier_application.svg?style=for-the-badge
[contributors-url]: https://github.com/smuhammad1/loan_qualifier_application/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/smuhammad1/loan_qualifier_application.svg?style=for-the-badge
[forks-url]: https://github.com/smuhammad1/loan_qualifier_application/network/members
[stars-shield]: https://img.shields.io/github/stars/smuhammad1/loan_qualifier_application.svg?style=for-the-badge
[stars-url]: https://github.com/smuhammad1/loan_qualifier_application/stargazers
[issues-shield]: https://img.shields.io/github/issues/smuhammad1/loan_qualifier_application/network/members?style=for-the-badge
[issues-url]: https://github.com/smuhammad1/loan_qualifier_application/issues
<!-- [license-shield]: 
[license-url]:  -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/sumayyahmuhammadofficial/
