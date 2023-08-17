# Navigation-Website

One Paragraph of the project description


## Getting Started

These instructions will give you a copy of the project up and running on
your local machine for development and testing purposes. See deployment
for notes on deploying the project on a live system.

### Prerequisites

Requirements for the software and other tools to build, test and push 
- [Node.js](https://nodejs.org/en)
- [Python](https://www.python.org/downloads/)
- [Xampp](https://www.apachefriends.org/download.html)
- [Express](http://expressjs.com/en/starter/installing.html)

### Installing
Download the latest version of the required prerequisites from each of their website and follow the installation instruction

When the installation is finished check the node version using terminal and type the following command

    node -v

For pyhton check the version using

    python --version

For express check the version using

    npm list express

## Running the server Code

To run this program you need to open integrated terminal of the main folder and run the following command

    node server.js
What this command does is it will run the program locally on certain port on your machine.

Open the website on your browser with the following code. Dont forget to replace your_port with your port number

    localhost:your_port

## Running the data Code

This program will receive the coordinates data from sim808 and store the data to MYSQL database

To run the data code run the following command in integrated terminal of the Main folder

    pyhton data.py
    
Open the website on your browser with the following code. Dont forget to replace your_port with your port number

    localhost:your_port

## Running the API

The API will send the data stored in the MySQL database to the navigation website so that the website can obtain the user's position in real-time

To run the API run the following command in integrated terminal of the API folder

    pyhton app.py

## Built With

  - [Contributor Covenant](https://www.contributor-covenant.org/) - Used
    for the Code of Conduct
  - [Creative Commons](https://creativecommons.org/) - Used to choose
    the license

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code
of conduct, and the process for submitting pull requests to us.

## Versioning

We use [Semantic Versioning](http://semver.org/) for versioning. For the versions
available, see the [tags on this
repository](https://github.com/PurpleBooth/a-good-readme-template/tags).

## Authors

  - **Billie Thompson** - *Provided README Template* -
    [PurpleBooth](https://github.com/PurpleBooth)

See also the list of
[contributors](https://github.com/PurpleBooth/a-good-readme-template/contributors)
who participated in this project.

## License

This project is licensed under the [CC0 1.0 Universal](LICENSE.md)
Creative Commons License - see the [LICENSE.md](LICENSE.md) file for
details

## Acknowledgments

  - Hat tip to anyone whose code is used
  - Inspiration
  - etc
