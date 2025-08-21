#  DevOps Hands-On: Linux + Nginx + Vagrant

This project is part of my **DevOps learning journey**, documenting hands-on labs and showcasing technical skills in a professional way.

In this lab, I deploy an **Nginx** server inside a **Vagrant-managed virtual machine**, serving **two different websites** as a practical exercise in Linux server configuration.

---

##  Technologies Used
- **Linux (Ubuntu)**  
- **Nginx** as web server  
- **Vagrant** for virtualization  
- **Git & GitHub** for version control  

---

##  Project Structure
```bash
.
├── index.html     # Main test page
├── test.txt       # Auxiliary test file
└── README.md      # Project documentation

---

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/99Diego/devops-hands-on-Linux-nginx.git
cd devops-hands-on-Linux-nginx

2. Start the environment with Vagrant:

```bash 
vagrant up

3. Access the virtual machine:

```bash
vagrant ssh

4. Test the configured Nginx websites from your browser:

http://localhost:8080
http://localhost:8081

---

## Lab Goals

- Practice basic Linux administration.

- Configure Nginx with multiple virtual hosts.

- Manage versions and workflow using Git/GitHub.

- Build a foundation for more complex DevOps projects.

---

## Next Steps

This is one of the first  hands-on lab of a series documenting my DevOps path. Upcoming labs will include:

- Advanced Nginx configuration.

- Dockerizing applications.

- Infrastructure automation with Ansible and Terraform.

- CI/CD pipelines with Jenkins and GitHub Actions.

---

## Author
Diego Lopez Arango

---

## Date
August 2025

