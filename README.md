Cloud Service Models (Categories of Cloud Services)
The services offered by CSPs(cloud service providers) can be grouped into 3 categories based on how much control and responsibility you have over the service’s configuration. These are:

1. IaaS (Infrastructure as a Service)
2. PaaS (Platform as a Service)
3. SaaS (Software as a Service)


IaaS (for IT administrators and infrastructure managers)
- IaaS allows you to manage the virtualized infrastructure resources, such as servers, storage, and network, while the csp  manages the physical hardware and the technology that makes virtualization possible. It allows you to configure and customize your environment from the hardware up.
- It gives you more control over the virtualized infrastructure resources than the CSP.
- It offers the highest level of user customization and control, but requires the greatest amount of user administration including the OS, but not phyiscal hardware.
- IaaS services are the most similar to existing on-premises computing resources that many IT departments are familiar with.
- Examples of AWS services that can be categorized as IaaS are Amazon EC2, Amazon S3, Amazon EFS, Amazon EBS, Amazon Route53, Amazon CloudFront, Amazon ELB, Amazon CloudWatch, Amazon VPC, and AWS Direct Connect.

PaaS (for developers)
- PaaS allows you to focus on the development of your apps, including the app code and data, while the CSP manages the virtual infrastructure, the OS, and the runtime environment.
- Offers a balance between customization and user control.
- Examples of AWS services that can be categorized as PaaS are AWS Elastic Beanstalk, AWS Lambda, Amazon RDS, Amazon DynamoDB, Amazon Elasticache, Amazon SQS, Amazon SNS, AWS Step Functions, Amazon MQ, and AWS App Runner

SaaS (for end-users and business professionals)
- SaaS allows you to use and interact with the software app provided by the CSP, while the CSP manages the underlying infrastructure, software maintenance, and service delivery.
- It requires no software installation and focuses on design simplicity and ease of use. It offers a minimal level of service customization.
- Examples of AWS services that can be categorized as SaaS are AWS Trusted Advisor, AWS Shield, Amazon Connect, Amazon WorkDocs, Amazon Chime, Amazon Honeycode, and Amazon WorkMail.

Linux Command Hands-on

ls (List):

Purpose: Lists the contents of a directory.
Usage: ls [options] [directory]
Example: ls -l displays the contents in long format.

cd (Change Directory):

Purpose: Changes the current working directory.
Usage: cd [directory]
Example: cd Documents changes to the "Documents" directory.

pwd (Print Working Directory):

Purpose: Displays the current working directory path.
Usage: pwd
Example: Output might be /home/username/Documents.

touch:

Purpose: Creates an empty file or updates the access and modification timestamp of an existing file.
Usage: touch [filename]
Example: touch file.txt creates an empty file named "file.txt."

rm (Remove):

Purpose: Deletes files or directories.
Usage: rm [options] [file/directory]
Example: rm file.txt deletes the file "file.txt."

cp (Copy):

Purpose: Copies files or directories from one location to another.
Usage: cp [options] source destination
Example: cp file.txt /backup copies "file.txt" to the "backup" directory.

mv (Move):

Purpose: Moves or renames files and directories.
Usage: mv [options] source destination
Example: mv file.txt /new_location moves "file.txt" to "/new_location."

cat (Concatenate):

Purpose: Displays the content of a file or concatenates files and displays the output.
Usage: cat [options] [file]
Example: cat file.txt displays the content of "file.txt."

echo:

Purpose: Prints text or variables to the terminal.
Usage: echo [text or variable]
Example: echo Hello, World! prints "Hello, World!" to the terminal.

man (Manual):

Purpose: Displays the manual pages for a command.
Usage: man [command]
Example: man ls displays the manual for the ls command.

sudo (Superuser Do):

Purpose: Allows a permitted user to execute a command as the superuser or another user.
Usage: sudo [command]
Example: sudo ls /root executes ls with superuser privileges in the "/root" directory.

apt-get:

Purpose: Package management command for Debian-based systems (e.g., Ubuntu).
Usage: apt-get [options] [command] [package]
Example: apt-get install firefox installs the Firefox browser.

chmod (Change Mode):

Purpose: Changes the file permissions.
Usage: chmod [options] permissions file/directory
Example: chmod +x script.sh adds execute permission to "script.sh."

chown (Change Owner):

Purpose: Changes the owner of a file or directory.
Usage: chown [options] new_owner:new_group file/directory
Example: chown user:group file.txt changes the owner of "file.txt."