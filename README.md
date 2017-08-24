
## Getting Started:
##### Live Demo: [Registrations Web App](http://registrations-numbers-webapp.herokuapp.com/)


## Developer Use
### Fork and Clone Repository

- First get this repository on your local machine by forking it, to fork this repository click on the fork button in the upper right corner:

![fork-screenshot](https://user-images.githubusercontent.com/22448019/29610658-33ca45b4-87fb-11e7-8b94-021e343f691d.png)

- Then clone the forked repo from your github account to your local machine.
- Click on the clone or download button on the forked repo and copy the SSH or HTTPS link to your clipboard.

![clone-screenshot](https://user-images.githubusercontent.com/22448019/29613928-6bc780a0-8808-11e7-9d23-9355a7dbe7eb.png)

- In your terminal navigate to your projects folder and clone the repo using:
  ```
	git clone (url link)
	```
### Setting Up Development Environment

##### You will require the following:
- Nodejs
- Expressjs
- Mongoose
- MongoDB
- Mocha

##### NodeJS
- To check if you have NodeJS installed on your local machine run this command in the terminal:
  ```
  node -v
  ```
- If this command fails, install Nodejs on your machine - <a href="">here</a>

##### NPM Install
- To install the modules used in this app run the following command in the terminal:
  ```
  npm install
  ```
- This will install the node_modules such required and specified in the package.json file within the cloned repo.
##### MongoDB

- Install <a href="https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-mongodb-on-ubuntu-16-04"> MongoDB</a>

##### Mocha
- If you want to run some tests  you don't have it, install Mocha by running the following command in the terminal:
  ```
  sudo npm install -g mocha
  ```
-  Now in your cloned repo you can run the command below to run some tests.
  ```
  mocha
  ```
