🚀 DevOps Journey: Week 2 – Deep Dive into Cloud, SSH, CLI, and Team Dynamics
Hello DevOps community! 👋
I'm excited to share the highlights and achievements of my Week 2 in the DevOps journey. This week was intense, insightful, and filled with hands-on experience across AWS, Azure, SSH, Linux commands, CLI tools, and team collaboration frameworks.

☁️ Cloud Platforms – AWS and Azure
This week, I took a deep dive into AWS and Azure, focusing on real-world, hands-on learning.

✅ Key Accomplishments:
✅ Created AWS and Azure accounts.

✅ Launched and configured virtual machines (instances) on AWS.

✅ Learned to create EC2 instances on AWS and manage key configurations.

✅ Successfully connected to AWS instances using SSH via private .pem key files.

⚠️ Major Challenge (And Proud Moment):
I created the instance from Windows, which downloaded the private key file there. Then I had to connect the Ubuntu system to the AWS instance.

To solve this:

I shared the .pem file from Windows to Ubuntu.

Used Add Location via file manager, input the system IP, and securely moved the .pem file.

In VirtualBox, I used Shared Folders to manage file access between host and VM.

This took almost 2 days of research and troubleshooting, but I cracked it! 💪

🔐 SSH, Linux, and Shell Scripting
Understanding how to securely connect and automate processes is vital in DevOps.

💻 Linux Commands Mastered:
history – track command history

ls -ltr, cat, touch, cd, pwd – navigation and file handling

nproc – check CPU cores

chmod 777 – permission setup

sudo – run commands as superuser

💡 SSH & Shell Scripting:
Connected to EC2 instances using ssh -i "key.pem" ubuntu@ip-address.

Created automated tasks via Shell Scripting, instead of executing commands one by one.

Sample shell workflow:

bash
Copy
Edit
#!/bin/bash
sudo apt update
sudo apt install apache2 -y
echo "Apache Installed Successfully!"
🧠 AWS CLI and S3
I also started working with AWS CLI to perform cloud operations from the terminal.

📁 Hands-On with AWS CLI:
Installed and configured AWS CLI using aws configure.

Created S3 buckets using CLI.

Uploaded folders and files to AWS S3 via CLI.

Learned to manage access policies and permissions.

👨‍💼 Team Collaboration & Agile Methodologies
This week, I also explored how cross-functional teams work in a DevOps environment.

🧩 Understanding Team Roles:
Business Analyst – Gathers user requirements.

Product Owner – Prioritizes and refines requirements.

Product Manager – Aligns product roadmap and business goals.

Software Architect – Designs system architecture.

UI/UX Designer – Plans user interface and experience.

Developers – Implement features.

QA/Testers – Ensure quality through testing.

DevOps Engineer – Bridges development and operations.

SRE (Site Reliability Engineer) – Ensures system uptime and performance.

📘 Tools Explored:
Jira – For Agile documentation, sprint planning, and issue tracking.

Scrum Framework – Learned ceremonies like Sprint Planning, Daily Standups, Reviews, and Retrospectives.

🛠️ Infrastructure as Code (IaC)
While I haven’t used it yet, I explored Terraform and learned that:

It's a powerful Infrastructure as Code tool.

It supports multi-cloud platforms like AWS, Azure, and GCP.

Will be focusing on it in upcoming weeks for automated deployments.

🔚 Week 2 Summary
✅ Created and connected virtual machines on AWS & Azure
✅ Managed private key sharing between Windows and Ubuntu
✅ Mastered shell scripting and basic Linux CLI
✅ Configured and used AWS CLI to manage S3 buckets
✅ Learned DevOps team structure and Agile collaboration
✅ Explored tools like Jira and Scrum
✅ Discovered Terraform and IaC principles

🚀 Onward to Week 3…
Week 2 was all about getting hands-on, solving real-world issues, and building confidence.
I'm excited to go even deeper into automation, CI/CD, and containerization in the next leg of my journey.

📢 Connect with me if you're on a similar DevOps path. Let's grow together!

#DevOps #AWS #Linux #ShellScripting #Azure #AWSCLI #Terraform #Scrum #Jira #Hashnode #DevOpsJourney #Week2 #Ubuntu #Agile #SRE #IaC
