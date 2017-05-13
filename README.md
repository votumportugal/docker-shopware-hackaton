# Docker/Shopware Hackaton

Pre-requisites
* Laptop with some storage available ~1Gb should do.
* GIT versioning system should be installed [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git]

1. Docker installation 

* 1.1. Install docker
[https://docs.docker.com/engine/installation/]

* 1.2 Install Docker compose
[https://docs.docker.com/compose/install/]

* 1.3 Explore

  * Explore pre-made docker containers [https://hub.docker.com/explore/]
  * Get acquainted with the docker most commonly used commands: _ps_, _exec_, _kill_, etc. 

2. Setup a LAMP stack using docker.

Objective: Play around with docker, lets build a simple LAMP stack.
- Create a web-server container.
- Create an `index.php` file in your web-server docroot to display `phpinfo();` in the browser.

Create separate containers for `web-server` and `database`, connect them using docker compose.

*Hint* Having trouble? Check [https://phpdocker.io/generator] for creating a docker compose file for a base LAMP environment.

3. Get Shopware and configure it to run in your LAMP stack

* Shopware repository:
[https://github.com/shopware/shopware]

* Get Shopware from GitHub repository into your web-server docroot e.g.
`git clone https://github.com/shopware/shopware.git htdocs`
* Follow the installation instructions on the README.md
* Make sure your Docker containers have all the required packages.

Assuming you installed the demo data. Your freshly installed shop should look like:
* http://www.shopwaredemo.de/


