# Cloud-Computing-Research-Task-Internship-INSAID-
INSAID-Internship Cloud Task for internship project.

1. Describe basic aspects of AWS Elastic Compute Cloud.

Ans: AWS Elastic Compute Cloud is a basic virtual machine with customizable hardware components and an OS. The system allows you to run various virtual computers and manage the same with a single hardware.Elastic Compute Cloud is the highly used and primary service system in the massive AWS ecosystem. The cloud system provides multiple features, for instance, it facilitates computing on-demand and scales the Computing capacity in the Amazon cloud system.

2. How to create a virtual machine instance in AWS EC2.

Ans: 
step 1:-Login and access to AWS services.

Step 2: Choose AMI.

step 3: Choose EC2 Instance Types.

step 4: Configure Instance.

step 5: Add Storage.

step 6: Tag Instance.

step 7: Configure Security Groups.

step 8: Review Instances.

AWS stores the private key in the instance, and you are asked to download the private key. Make sure you download the key and keep it safe and secured.
Create a new key pair
Give a name to your key
Download and save it in your secured folder.

3. How to install an Apache webserver on AWS EC2 Instance.

Ans:  install Apache Web Server on EC2 Instance using User data script.
Connect to your EC2 instance and install the Apache web server.  
sudo yum update -y

sudo yum install -y httpd.x86_64

sudo systemctl start httpd.service

sudo systemctl enable httpd.service

I used sudo nano command to create the file and put content into it.

sudo nano /var/www/html/index.html

4. How we can connect an AWS EC2 instance to a MySQL server database.

Open MySQL Workbench.

Select MySQL New Connection and enter a connection name
.
Choose the Connection Method, and select Standard TCP/IP over SSH.

For SSH Hostname, enter the public IP address of your EC2 instance.

For SSH Username, enter the default SSH user name to connect to your EC2 instance.

Choose SSH Key File, and select the .pem file used to connect from your file system.

For MySQL Hostname, enter the database endpoint name.

For MySQL Server Port, enter the port number that you use to connect to your database.

For Username, enter the user name that you use to connect to your database.

For Password, enter the MySQL user password.

Choose Test Connection. After the test is successful, choose OK to save the connection.

After the connection is configured, you can connect to your private RDS DB instance using an SSH tunnel.

5. How to connect a domain to your website using Route 53.

Step 1: Register a custom domain with Route 53. ...

Step 2: Create two buckets. ...

Step 3: Configure your root domain bucket for website hosting. ...

Step 4: Configure your subdomain bucket for website redirect. ...

Step 5: Configure logging for website traffic. ...

Step 6: Upload index and website content. ...

Step 7: Upload an error document.
