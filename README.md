# Project Title

CS-4366

## Project Overview

We are developing an application, that allows users to practice trading, with virtual money.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

# Installation

Follow these step-by-step instructions to install and set up your project:

### Repository

1. **Accept the invitation:**

   - Go to your notifications and accept the repository invite.

2. **Sign In:**

   - Sign into Git through your integrated development environment (IDE).

3. **Clone the repository:**
   - Open the terminal and run the following command:
     ```
     git clone https://github.com/wilcoxsonethan/capstone.git
     ```

---

## Backend

#### Docker

1. **Install Docker:**

   - Download and install Docker from the official website <img src="https://www.docker.com/wp-content/uploads/2022/03/vertical-logo-monochromatic.png" alt="Docker Logo" width="50"/>(https://www.docker.com/products/docker-desktop/).

2. **Update .env:**

   - If necessary update .env values in Backend folder.

3. **Build Docker Image:**
   - Open the Docker application on you desktop. Then navigate to the root directory of the folder 'CS-4366', run the following command to build the Docker image.
     ```
     docker-compose build
     ```
4. **Build Docker Container:**
   - In the terminal, while staying in the folder 'CS-4366', run the following command to build Docker container:
     ```
     docker-compose up
     ```
5. **Run Docker Container:**
   - Go to your browswer and put http://localhost:8000 or http://127.0.0.1:8000/ in your url and your all set to go.


---

### FrontendMobile

1. **Install Node JS:**

   - Download and install Node JS from the official website <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/2560px-Node.js_logo.svg.png" alt="Node Logo" width="50"/> (https://nodejs.org/en/download).

2. **Install npm:**
   - Open your terminal or command prompt and navigate to the directory where your package.json file is located. Run the following command to install the project dependencies listed in the package.json file:
     ```
     npm install
     ```

##### You have now successfully installed and set up the project with its required dependencies. Happy coding!

---

## Usage

Provide instructions on how to use your project. Include examples and code snippets if applicable. Explain any configuration or customization options that are available.

## Features

- Registration
- Login

## Contributing

Explain how others can contribute to your project. Provide guidelines for submitting bug reports, feature requests, and pull requests. Include information about your code style, testing procedures, and any other relevant contribution guidelines.

## License

Specify the license under which your project is distributed. Include a link to the license file if applicable.

## Contact
Anthony Humphreys
- anthony.j.humphreys@ttu.edu

Mason Weaver
- mason.weaver@ttu.edu

Ethan Wilcoxson
- ethan.wilcoxson@ttu.edu

Akeem Mohammed
- akeem.mohammed@ttu.edu


## Links

- <img src="https://cdn-icons-png.flaticon.com/512/5968/5968517.png" alt="Google Logo" width="50"/>[SRS Docs](https://docs.google.com/document/d/186xzn5aaJwDDPEja_z0jfcJbAy0yTiYRcdzv19_IqtE/edit)
- <img src="https://upload.wikimedia.org/wikipedia/commons/a/ad/Figma-1-logo.png" alt="Figma Logo" width="50"/>[UI/UX Figma](https://www.figma.com/file/q06ojDSwbAXetcZ4fXMLKZ/CS-4366?type=design&node-id=0-1&mode=design&t=BSmTqzWeZAesWNLN-0)
