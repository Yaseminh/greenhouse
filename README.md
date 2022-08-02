# 5GPPGreenhouse website



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

## How to access the azure server?
username:IP

http://5gppgreenhouse.com/

netasuser@52.168.120.196
Password: 0X45rUa0E5Z6FW9T

http://52.168.120.196:3000/
## focus the website files. the website runs on 3000 port. http://5gppgreenhouse.com/
cd /home/impaqt/5GPPGreenhouse_website

## How to run?
### 1. Preps
You will need to have <a href="https://nodejs.org/">Node JS</a> installed on your pc. 

To get this version, you can use the apt package manager. Refresh your local package index first by typing:



    sudo apt update
    
    

Then install Node.js:



    sudo apt install nodejs
    
    

Check that the install was successful by querying node for its version number:



    node -v
    
    



Output
v10.19.0


Install NPM:


    sudo apt install npm
    
    

Install yarn via npm

It is recommended to install Yarn through the npm package manager, which comes bundled with Node.js when you install it on your system.

Once you have npm installed you can run the following both to install and upgrade Yarn:

npm install --global yarn

Alternatives
Click to expand / collapse
Check installation

Check that Yarn is installed by running:

yarn --version

 ###How to start? 
 
-> yarn start &

###How to stop current processor?




sudo netstat -nlp|grep 3000

sudo kill -9 <PID>



### 2. Clone Files
After cloning the files, you will have to run ```yarn``` followed by ```yarn start``` in the CLI
### 3. Add your own data 
Change the data in the ```data.json``` file as well as add any images to ```public/img/```
You can also change styles by modifying the ```public/css``` files.


