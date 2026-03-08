# EC2 Nginx Website Deployment

## Steps performed

1. Logged into AWS Console
2. Opened EC2 service
3. Launched Ubuntu 22.04 instance
4. Selected instance type t2.micro
5. Created key pair for SSH
6. Configured security group:
   - Port 22 (SSH) from my IP
   - Port 80 (HTTP) from anywhere
7. Launched instance
8. Connected using SSH:
   ssh -i key.pem ubuntu@<public-ip>
9. Updated system:
   sudo apt update -y
10. Installed nginx:
   sudo apt install nginx -y
11. Started nginx:
   sudo systemctl start nginx
12. Enabled nginx:
   sudo systemctl enable nginx
13. Edited website file:
   sudo nano /var/www/html/index.html
14. Opened browser and accessed:
   http://<public-ip>


   08/03/2026

   I was busy while travelling because i am having my second sem in poland so i was unable to update github.

   today i tried to host a website on s3 but some how i was unable to do that 
   steps i tried are
   1. created a bucket
   2. upload a html file in it
   3. now i got stuked in CLI
   4. 
