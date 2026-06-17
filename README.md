<!-- BACK TO TOP ANCHOR -->
<a id="readme-top"></a>

<!-- LOGO -->
<div align="center">
  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/powermedia">
    <img src="www/imagens/logo_branco.jpg" alt="Logo" height="80" />
  </a>

  <h1 align="center">PowerMedia Organizer</h1>

  <p align="center">PowerMedia Organizer is a PHP/MySQL catalog and print-production system built for a client to manage a large CD/DVD media collection, from title registration to printable catalogs and disc labels.</p>

  <p align="center">// media cataloging · client project</p>

  <br />

  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/powermedia"
    ><strong>View it live »</strong></a>
</div>

<br />

<!-- SHIELDS -->
<div align="center">

[![Creator Website][website-shield]][website-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Released][year-shield]][year-url]

</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#screenshots">Screenshots</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Screenshot][product-screenshot]](https://leonardo-vasconcellos.vercel.app/portfolio/powermedia)

<!-- PROJECT INTRO: 260 chars max -->

PowerMedia Organizer is a PHP/MySQL system built for a client to catalog a large CD/DVD library, turning entries into printable catalogs and disc labels.

<!-- END INTRO -->

PowerMedia Organizer is a catalog and print-production system built in PHP and MySQL for a client managing a large physical CD/DVD library. It handles the full lifecycle of a media catalog: registering titles with front and back cover art, grouping them under configurable media types, and browsing/searching the collection through a paginated, sortable list or icon grid.

The core business problem it solved was production overhead: generating printed catalogs and disc labels by hand for a large, growing collection. PowerMedia replaced that with a configurable print pipeline — page layout, cover dimensions, font sizes, and items-per-page are all adjustable — so catalogs and labels could be regenerated on demand instead of rebuilt manually each time. A dedicated cover-printing workflow let staff batch-select which covers go to print, and a "gravação" (burn queue) screen tracked which titles were queued to be recorded to disc. A dynamic image-resizing endpoint served each cover at whatever size a screen needed from a single stored file, and a Flash-based viewer let staff inspect cover art closely before printing.

**Key features:**

- Delivered a full CRUD catalog system (titles, media types, front/back cover art) on PHP + MySQL, replacing the client's manual tracking of a large physical media library (980+ titles in the sample data) with a searchable, sortable, paginated system.
- Designed a configurable catalog & label print pipeline (custom page sizes, cover dimensions, font sizes, items-per-row), turning a recurring manual production task — printing catalogs and disc labels — into a few-click, repeatable workflow.
- Built a dynamic image-resizing endpoint and integrated a Flash-based cover zoom viewer so the client could store one cover image per title and have it rendered correctly across thumbnails, print layouts, and detail views — cutting storage overhead and manual image prep.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SCREENSHOTS -->
## Screenshots

<div align="center" style="display:flex;flex-wrap:wrap;gap:8px;justify-content:center;">
  <a href="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%281%29.png"><img src="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%281%29.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%282%29.png"><img src="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%282%29.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%283%29.png"><img src="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%283%29.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%284%29.png"><img src="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%284%29.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%285%29.png"><img src="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%285%29.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%286%29.png"><img src="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20%20%286%29.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20.png"><img src="screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- BUILT WITH -->
## Built With

<!-- LANGUAGES -->

**Languages**

|                                                                                                              | Language   | Version |
| ------------------------------------------------------------------------------------------------------------ | ---------- | ------- |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="20" />             | PHP        | 5.x     |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="20" /> | JavaScript | —       |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="20" />          | HTML       | 5       |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="20" />            | CSS        | 3       |

<!-- FRAMEWORKS & LIBRARIES -->

**Frameworks & Libraries**

|                                                                                                     | Framework | Version |
| ----------------------------------------------------------------------------------------------------- | --------- | ------- |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="20" /> | MySQL     | 4.x     |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

This project repository is for archive purposes only. No new features or issues are being tracked.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTORS -->
## Contributors

<a href="https://github.com/llvasconcellos2/powermedia/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=llvasconcellos2/powermedia" alt="Contributors" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

[Leonardo Vasconcellos - Website](https://leonardo-vasconcellos.vercel.app/) — [LinkedIn](https://www.linkedin.com/in/llvasconcellos)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[website-shield]: https://img.shields.io/badge/Creator_Website-%E2%86%97-2eba7a?style=for-the-badge
[website-url]: https://leonardo-vasconcellos.vercel.app/
[contributors-shield]: https://img.shields.io/github/contributors/llvasconcellos2/powermedia.svg?style=for-the-badge
[contributors-url]: https://github.com/llvasconcellos2/powermedia/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/llvasconcellos2/powermedia.svg?style=for-the-badge
[forks-url]: https://github.com/llvasconcellos2/powermedia/network/members
[issues-shield]: https://img.shields.io/github/issues/llvasconcellos2/powermedia.svg?style=for-the-badge
[issues-url]: https://github.com/llvasconcellos2/powermedia/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/llvasconcellos
[year-shield]: https://img.shields.io/badge/Released-2006-gray?style=for-the-badge
[year-url]: #
[product-screenshot]: screenshots/-%20%20%20POWERMEDIA%20ORGANIZER%20%20%20%20.png
