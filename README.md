# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

### NAME: SUPRIYA V
### REG NO: 212225100052

# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure
### a) Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console Go to https://console.aws.amazon.com/s3. 

Step 2: Open the S3 Service In the console, type S3 in the search bar and select S3 to open the service dashboard. 

Step 3: Create Bucket Click the Create bucket button. 

Step 4: Configure Bucket Settings

• Bucket name: Choose a globally unique name. • AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership Choose between: ▪ ACLs disabled (recommended) – Bucket owner has full control. ▪ ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings By default, all public access is blocked. Leave it as-is unless you need public access. 

Step 7: Bucket Versioning (optional) Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional) Select encryption options (SSE-S3, SSE-KMS, or none). 

Step 9: Advanced Settings (optional) Add tags, configure logging, etc. 

Step 10: Create the Bucket Click Create bucket at the bottom of the page.

### b) Steps to launch an EC2 Instance

Go to the EC2 Dashboard in AWS Console.

Click on “Launch Instance”.

Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).

Select an instance type (e.g., t2.micro for Free Tier).

Create or choose a key pair for SSH access.

Configure network settings (use default VPC/subnet).

Configure storage (default root volume is fine).

Review the settings and click “Launch Instance”.

Wait for the instance to enter the running state.

### c) Step 3: Connect to Your Instance

• Linux: Use SSH command with your .pem key. • Windows: Use RDP with decrypted admin password.

### d) Steps to Clean Up (Terminate the Instance)

Go to EC2 Instances.
Select your instance → Instance State → Terminate.

# Output:

## Creating S3 Bucket:


<img width="960" height="540" alt="Screenshot 2026-11-03 094513" src="https://github.com/user-attachments/assets/4b89e14d-26be-4291-894a-f88e56fa9c8d" />


## Uploading Files in Bucket:


<img width="960" height="540" alt="Screenshot 2026-10-31 081720" src="https://github.com/user-attachments/assets/99969e5d-9636-447f-81c9-3a9b58e25c93" />



## Launching EC2 Instance:

<img width="960" height="540" alt="Screenshot 2026-10-31 085040" src="https://github.com/user-attachments/assets/7fcaf8c9-05a2-41d1-b8d1-2b24dc589fce" />



## Connecting Instance:

<img width="960" height="540" alt="Screenshot 2026-10-31 085544" src="https://github.com/user-attachments/assets/f890df99-983f-42aa-acbf-4015a16bbebe" />



## Stopping the Instance:

<img width="960" height="540" alt="Screenshot 2026-11-03 093126" src="https://github.com/user-attachments/assets/50cf4e48-ca5c-499e-b9c0-f6badca7d18f" />


# Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS





.



























.

































.








































.































.
























.







































.






















.


























































.
