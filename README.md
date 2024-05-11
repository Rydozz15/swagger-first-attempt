<!-- PROJECT LOGO -->
<a name="readme-top"></a>
<div align="center">
  <h3 align="center">Marketplace Back-End with Express.js</h3>

  <p align="center">
    This was Desafio Latam's last exam
    <br />
    <br />
    <a href="https://marketplace-back-end-4sb8.onrender.com/api/v1/docs/">View Demo</a>
    ·
    <a href="https://market-vite-deploy.onrender.com/">View full page</a>
  </p>
</div>



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
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://marketplace-back-end-4sb8.onrender.com/api/v1/docs/)

This API RESTful was the back-end of a project as the middle man between the front-end and the PostgreSQL database. 

Functions:
* Products: All of them, in detail and the ones that the user uploaded.
* Fav Products: Wishlist, that's it.
* User: Create User and Login, including Google OAuth 2.0
* Orders: All about purchasing and updating the status of an order.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Node][node-bdg]][node-url]
* [![Express][express-bdg]][express-url]
* [![Swagger][swagger-bdg]][swagger-url]
* [![PostgreSQL][postgresql-bdg]][postgresql-url]
* [![JWT][jwt-bdg]][jwt-url]
* [![Jest][jest-bdg]][jest-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

* pnpm
  ```sh
  iwr https://get.pnpm.io/install.ps1 -useb | iex
  ```
* PostgreSQL
  [Click here](https://www.postgresql.org/download/)

* AWS Account
  [Click here](https://aws.amazon.com/account/)

### Installation

1. Create a S3 bucket
2. Clone the repo
   ```sh
   git clone git@github.com:Rydozz15/marketplace-back-end.git
   ```
3. Install PNPM packages
   ```sh
   pnpm install
   ```
4. Enter your .env in and write down this AWS Credentials aspects
   ```js
   AWS_S3_BUCKET_REGION=us-west-2
   AWS_ACCES_KEY_ID=YOUR_ACCESS_KEY_ID_PLACEHOLDER
   AWS_SECRET_ACCES_KEY=YOUR_SECRET_ACCESS_KEY_PLACEHOLDER
   AWS_BUCKET_NAME=YOUR_BUCKET_NAME_PLACEHOLDER
   ```
5. Run the scema.sql inside config>db
   ```sh
   psql -U <user> -a -f <route>
   ```
6. Enter your .env in and write down your database credentials and the port
   ```js
   DB_HOST=
   USER_DB=
   PASSWORD_DB=
   NAME_DATABASE=
   PORT=
   ```
7. In the samae fil in JWT_SECRET add yoout secret code to encrypt.
8. Enjoy!
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

You can connect your Front-End and use this as an example, or play with it on Swagger.
_Example [Front-End]([https://example.com](https://market-vite-deploy.onrender.com/))_

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Juan Pablo Fuentes - [juan.fuentes@uc.cl](mailto:juan.fuentes@uc.cl)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Thanks to my team
* Sabastián, Paula and Gabriel
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot]: https://media.licdn.com/dms/image/D4E2DAQGRNzyCxYTZtg/profile-treasury-image-shrink_800_800/0/1710872304691?e=1716004800&v=beta&t=qv8BzopY3kMX1ijaoVskBmXftadyetSr49SMpm_tZ8E
[node-bdg]: https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white
[node-url]: https://nodejs.org/
[express-bdg]: https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white 
[express-url]: https://expressjs.com/
[swagger-bdg]: https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black
[swagger-url]: https://swagger.io/
[postgresql-bdg]: https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white
[postgresql-url]: https://www.postgresql.org/
[jwt-bdg]: https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white
[jwt-url]: https://jwt.io/
[jest-bdg]: https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white
[jest-url]: https://jestjs.io/
