# nodejs project
# step 1 update the packages
sudo apt update -y
# install nodejs with npm
sudo apt install nodejs npm -y
#  check the version of node and npm to mke sure it is installed
node -v
npm -v
# make and directory to for nodeapp
sudo mkdir nodeapp
create a file for nodeapp in which requirements of app are stored
# install npm
npm is a tool that installs and manages packages
# after that install nginx 
start the nginx 
go to nginx configuration block 
pass the proxy in location block so that request reaches to nginx first and then it will forwad it to nodejs
restart the nginx
# install pm2
pm2 is installed to keep your app running in the background
add port 3000 of nodejs to security group 
hit the ip on browser to check the app is working or not.
