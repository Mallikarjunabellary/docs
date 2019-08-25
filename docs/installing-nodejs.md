# Installing Nodejs in CentOS7

```sh
sudo yum install nodejs -y
```


installing npm modules in production

# Using PM2

```sh
sudo npm i -g pm2
cd ~/client
git clone https://github.com/client/project.git
cd project
npm i --prod

pm2 start server/app.js --name client_project
```
