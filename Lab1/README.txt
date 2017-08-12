

push index.php to /var/www/html 

1. create a new repository on git hub 
ex AWS-LAB

2. creat index.php

3. creat new repository on local pc 

git add . 
git commit -m "LAB 1 create"
git remote add origin git@github.com:L98222006/AWS-Lab.git
git push -u origin master 


4. EC2 

ssh 

cd ~
sudo git clone https://github.com/L98222006/AWS-Lab.git

cd Lab1 

sudo cp index.php /var/www/html/proj1 && cd /var/www/html/proj1

http://x.x.x.x/proj1 

5. 

vim index.php 
git add .
git commit -m "change index.php"
git push -u orgin master 


6. EC2 

cd ~
cd /AWS-LAB/
sudo git pull 
sudo cp index.php /var/www/html/proj1 && cd /var/www/html/proj1


