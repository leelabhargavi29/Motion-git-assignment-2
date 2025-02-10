Step-by-Step Instructions:
Part 1: Create an AWS Account
Visit the AWS Signup Page:

Go to the AWS signup page: https://aws.amazon.com/.
Start the Signup Process:

Click on the "Sign Up" button.
Provide Account Information:

Enter your email address, choose a password, and select an AWS account name.
Contact Information:

Provide your personal or company contact information.
Payment Information:

Enter your credit card or direct debit information. AWS will charge a small amount to verify the card, which will be refunded.
Identity Verification:

Verify your identity using phone verification (AWS will call or text with a verification code).
Select an AWS Support Plan:

Choose the Free Tier unless you require additional support.
Complete the Signup:

Finish the signup process, wait for the confirmation email, and log in to the AWS Management Console.
Part 2: Set Up a Basic EC2 Instance
Log in to AWS Management Console:

Navigate to the AWS Management Console: https://aws.amazon.com/console/.
Launch EC2 Dashboard:

Find and click on "EC2" under the "Compute" section to go to the EC2 Dashboard.
Launch Instance:

Click the "Launch Instance" button to begin the creation process.
Choose an Amazon Machine Image (AMI):

Select an AMI. For basic purposes, use an Amazon Linux 2 AMI, which is free tier eligible.
Choose an Instance Type:

Select an instance type. For basic needs, select t2.micro, which is free tier eligible.
Configure Instance Details:

Click "Next: Configure Instance Details".
Leave the default settings, unless you need specific configurations (e.g., multiple instances, network settings).
Add Storage:

Review the storage settings and proceed. The default storage setting is usually sufficient.
Add Tags:

Add tags to help identify your instance (optional).
Configure Security Group:

Create a new security group or select an existing one.
Add rules to allow inbound SSH (port 22) and HTTP (port 80) traffic.
Review and Launch:

Review the instance configuration, click "Launch".
Choose or create a new key pair. Download and securely store the key pair (.pem file).
Part 3: Deploy a Sample Python Script
Connect to the EC2 Instance:

Use an SSH client to connect to your instance.
The connection string will look like: ssh -i "your-key-pair.pem" ec2-user@your-ec2-public-dns.
Update the Instance:

Once connected, update the instance packages to ensure the latest security updates are installed.
Install Python:

Install Python if it's not already installed on the AMI.
Create the Python Script:

Use a text editor (like nano or vim) to create a Python script.
Example script content: a script that adds two numbers and prints the result.
Run the Python Script:

Execute the Python script.
Verify the output to ensure the script works as intended.
Optimized Approach:
Account Creation: Follow a streamlined process for accurately setting up an AWS account.
Instance Setup: Use minimal required configurations (Free Tier eligible options) to ensure cost efficiency and simplicity.
Deployment: Maintain the environment with updated packages and ensure secure connections.
Testing: Validate the script functionality immediately upon deployment to detect and fix any issues early.
By following these steps, you ensure a smooth process in setting up cloud infrastructure on AWS and prepare for deploying basic scripts while adhering to best practices. This approach is designed to handle competitive programming test cases efficiently.



# Motion-git-assignment-2
