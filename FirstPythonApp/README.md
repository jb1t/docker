## Docker Python Application

This is my first sample docker application. After getting this running I tested it out by creating an Azure Ubuntu VM and installing docker. Then I ran the command "sudo docker run -d -p 80:80 jb1t/getting-started:part2". Locally I was able to verify it worked by doing a wget 0.0.0.0:80. Then I opened the firewall so HTTP traffic could get to my new VM and tested the website from my browser and it worked!

Pretty cool!
