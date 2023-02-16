# thefinisher-nodeapp
node app using expressjs

Reference - 
https://expressjs.com/en/starter/generator.html

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
nvm install node

npm install -g express-generator

express -h

express app
cd app 
npm install 
npm start 

Building Dockerimage 

docker build -t thefinisher-nodeapp .

Run locally using docker.

docker run -it -p 3000:3000 thefinisher-nodeapp
 
