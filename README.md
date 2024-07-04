<h1 align="center" id="title">Static Website Deployment</h1>
<p id="description"> Deployment of a Static Website on AWS EC2 with NGINX
First, an AWS EC2 Instance will be set up, launched and connected. See the below:

<img width="958" alt="Screenshot 2024-07-04 003525" src="https://github.com/Iyewumi-Adesupo/static-website-deployment/assets/135404420/c5fd7930-1c7a-43eb-a80d-051c9f2be946">

Secondly, Install, Start and Enable NGINX on the EC2 Instance that is running and connected. See below:

<img width="959" alt="2" src="https://github.com/Iyewumi-Adesupo/static-website-deployment/assets/135404420/3e54efc2-8d54-4bdc-8db9-7d2e3b6f5636">

<img width="956" alt="3 install nginx" src="https://github.com/Iyewumi-Adesupo/static-website-deployment/assets/135404420/6e35fea6-bd79-4f57-9fb9-50c64bb78e2f">

<img width="945" alt="4 enable and start nginx" src="https://github.com/Iyewumi-Adesupo/static-website-deployment/assets/135404420/baccf7c5-db78-4d11-b4e9-78ac70a8d6cd">

Thirdly, created an index.html file for the website

<img width="959" alt="index" src="https://github.com/Iyewumi-Adesupo/static-website-deployment/assets/135404420/231a73af-7e44-4b18-a675-6e7d1ec3252d">

The fourth step, secure copy to transfer files from the local machine to EC2 instances. See below:

<img width="942" alt="5 secure copy to transfer files from local machine to ec2 instances" src="https://github.com/Iyewumi-Adesupo/static-website-deployment/assets/135404420/1e850961-14f4-4599-b4eb-39af5186c7d4">

The Fifth, Configure NGINX to Serve Static Website. See below:

<img width="944" alt="6 configure nginx by moving files to the nginx root directory" src="https://github.com/Iyewumi-Adesupo/static-website-deployment/assets/135404420/c0565adb-bdee-465f-a8d7-86d725fd0d1a">

The Sixth step is to Test the NGINX Configuration:

<img width="945" alt="test the nginx config" src="https://github.com/Iyewumi-Adesupo/static-website-deployment/assets/135404420/0ed1e8da-44d5-438e-98ba-8ec9ac244c39">

The next step is to Reload NGINX to Apply the Changes. See below:

<img width="946" alt="nginx reload" src="https://github.com/Iyewumi-Adesupo/static-website-deployment/assets/135404420/f1c6b9c5-9e44-412f-84b3-eb4d674b4ca2">

Lastly, Static Website is deployed stating name, email address, username and also mentioned the internship programme and the link. The website is accessibled with the port 80 after deployment.
