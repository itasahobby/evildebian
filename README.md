[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]




<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Infosec Debian</h3>

  <p align="center">
    Packer infosec setup using debian 11
    <br />
    <a href="https://github.com/itasahobby/infosec_debian"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/itasahobby/infosec_debian">View Demo</a>
    ·
    <a href="https://github.com/itasahobby/infosec_debian/issues">Report Bug</a>
    ·
    <a href="https://github.com/itasahobby/infosec_debian/issues">Request Feature</a>
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
    <li><a href="#getting-started">Getting Started</a></li>
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

Configuration to setup declarative a Debian 11 VMwware machine using packer and ansible.

Project inspired by this [repo](https://github.com/eaksel/packer-Debian10/tree/master/http)

### Built With

* [Packer](https://www.packer.io/)
* [Ansible](https://www.ansible.com/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

1. Clone the repo
   ```sh
   git clone https://github.com/itasahobby/infosec_debian.git
   ```
2. Step into the cloned directory
   ```sh
   cd infosec_debian
   ```
3. Execute the ansible playbook
    ```sh
    packer.exe build -only=vmware-iso .\infosec_debian.json
    ```

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/itasahobby/infosec_debian/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- CONTACT -->
## Contact

[@jusepe_it](https://twitter.com/jusepe_it)

Project Link: [https://github.com/itasahobby/infosec_debian](https://github.com/itasahobby/infosec_debian)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/itasahobby/infosec_debian.svg?style=for-the-badge
[contributors-url]: https://github.com/itasahobby/infosec_debian/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/itasahobby/infosec_debian.svg?style=for-the-badge
[forks-url]: https://github.com/itasahobby/infosec_debian/network/members
[stars-shield]: https://img.shields.io/github/stars/itasahobby/infosec_debian.svg?style=for-the-badge
[stars-url]: https://github.com/itasahobby/infosec_debian/stargazers
[issues-shield]: https://img.shields.io/github/issues/itasahobby/infosec_debian.svg?style=for-the-badge
[issues-url]: https://github.com/itasahobby/infosec_debian/issues