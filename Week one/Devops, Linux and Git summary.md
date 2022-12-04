# **INTRODUCTION TO DEVOPS, OPERATING SYSTEMS AND LINUX OS, VERSION CONTROL WITH GIT.**

*This markdown file contains a review of concepts learnt on the Devops with Nana Course, extra resources used will be referenced and it may or may not be an exact representation of the course.*

*This file will contain a brief summary of the topics listed above.*

## **Introduction to DevOps.**

Basically from all the introduction to DevOps 
tutorials i have watched, DevOps was adopted to help reduce the time of product delivery to market. 

__"DevOps combines development and operations to increase the efficiency, speed, and security of software development and delivery compared to traditional processes."__ - GitLab.

__"DevOps is a combination of software developers (dev) and operations (ops). It is defined as a software engineering methodology which aims to integrate the work of software development and software operations teams by facilitating a culture of collaboration and shared responsibility."__

*The introduction video focused on the best way to use the course and concepts to be learnt from the course. Examples of concepts to be covered are: Cloud services, Linux, Git, Ansible, Kubernetes, Docker, Terraform and so on.*


>__This material from GitLab was very helpful and comprehensive to help me properly understand DevOps as a whole. - [what is DevOps?](https://about.gitlab.com/topics/devops/)__


## **Operating Systems and Linux** 

*This module covered the operating systems, Virtual machine setup, basic Linux and networking, shell scripting and best practices for linux servers.*

I have previous experience using vagrant and virtualbox so it was a walkthrough, however i already use a Linux distro - Ubuntu so i just played around with a few commands. I used Nano editor instead of vim because i am more comfortable with it.

The section on shell scripting started with the intro to shell, basic concepts & syntax (shebang and all), i must admit the word "shebang" sounds a bit weird, proceeded to networking (used the ifconfig, netstat, curl, wget, hostname, ping etc).

The lesson on SSH covered using digitalOcean to create droplets, using ssh keys to access it, copying a bash script using vagrant SCP module, executing a bash script on the remote server and cleaning up after i was done.

Best Practices:

1) Learnt to use SSH over password authentication and its safer.

2) Install/update security releases and packages.

3) Always have a firewall and make sure the server is hardened.

4) Unnecessary packages, ports and access should be removed/deleted.

5) Users should be created for tasks and root user should only be used for system administration.

> _I equally found the KodeKloud Linux course to be of immense help as it has hands on labs to go with the theory aspect of linux administration._ - [KodeKloud Linux Course](https://kodekloud.com/courses/linux-foundation-certified-system-administrator-lfcs/)

## **Version control with Git** 

The lesson in version control with Git covered the installation of git, setting up a Github account, creating a remote repository, generating and adding ssh keys to a github account, how to clone a remote repository to local machine and how to upload a local repository, name and email setup using the git config module, branches, and merging pull requests.

I made a pull request recently to a project and it was merged successfully, i learnt how to resolve merge conflicts, use commands like .gitignore, stash, git log to check history, creating aliases, write meaningful commit messages.

> _If you are seeing this on github, it should be proof enough of familiarity with the basics of git and github._

> _The Git documentation is rich and comprehensive and also reinforced my understanding of version control with git. - [Git and Github Doc](https://docs.github.com/en)._


