---
title: "Basic Git & GitHub for DevOps Engineers"
datePublished: Thu Jul 27 2023 15:19:37 GMT+0000 (Coordinated Universal Time)
cuid: clklaw4oy000e09l74p8v2b15
slug: basic-git-github-for-devops-engineers
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1690380405413/1d868c07-3af9-43d2-abe4-80d713ce08ab.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1690471088893/c055dc59-9968-4218-bbd8-d379b68c7e7c.jpeg
tags: linux, github, git, devops, devopspythonic

---

Hey there, DevOps Engineers! Welcome to Day 8 of your journey, where we'll dive into the world of version control with Git and GitHub. 😎

## 🤔 What is Git?

Git is like a magic wand for developers! It's a version control system that allows you to track changes to your files and collaborate seamlessly with your team. Whether you're working on software projects or any other set of files, Git has got your back!

## 🌐 What is GitHub?

GitHub, on the other hand, is the enchanted castle that hosts Git repositories. 🏰 It's a web-based platform that makes version control a breeze. Microsoft's subsidiary, GitHub, offers all the functionalities of Git and adds its own amazing features. It's a favorite among developers for sharing, collaborating, and hosting open-source projects. 🌟

## 🔢 What is Version Control?

Version control is like a time machine for your files! 🚀 It keeps track of all changes made over time, allowing you to recall specific versions whenever you need. With version control, you can easily revert files, compare changes, and identify who did what, making it an indispensable tool for developers.

🤷‍♂️ How Many Types of Version Control Systems?

There are two main types of version control systems:

1. Centralized Version Control System (CVCS) 🎯 In this system, all files' versions are stored on a central server. Developers "check out" files to make changes and then "check in" the updates. Examples: Subversion and Perforce.
    
2. Distributed Version Control System (DVCS) 🚀 In the DVCS world, each developer gets a complete copy of the repository, including its entire history. This means more freedom and less dependency on a central server. Examples: Git, Mercurial, and Darcs.
    

## 🚀 Why Do We Use Distributed Version Control Over Centralized Version Control?

👥 Better Collaboration: With a DVCS, everyone on the team has a full copy of the repository. This fosters seamless collaboration without the constant need to communicate with a central server.

⚡ Improved Speed: DVCS allows developers to work faster. They can commit changes and perform version control actions more swiftly as everything is available locally.

🔧 Greater Flexibility: Work offline? No problem! DVCS lets you work independently and share changes later when you're back online. You can also choose who to share your changes with, giving you more control.

🛡 Enhanced Security: With DVCS, your repository's history is stored on multiple servers and computers, making it more resilient to data loss. Unlike CVCS, you won't lose everything if the central server has issues.

🎉 Embrace Git and GitHub, and you'll unleash the true power of version control and collaboration! So go ahead, start exploring, and let Git and GitHub be your allies on the DevOps journey! Happy coding! 🚀👨‍💻

## 🚀 Task 1: Install Git

* 🌐 Go to [git-scm.com/downloads](http://git-scm.com/downloads), the official Git website.
    
* 📥 Download the installer that matches your operating system.
    
* 🏃‍♀️ Run the installer and follow the on-screen instructions to finish the installation.
    
* ✅ Once the installation is done, open a terminal or command prompt, and type "git --version" to make sure Git is installed correctly. You should see the version number displayed.
    

## 🤝 Task 2: Create a GitHub Account

* 🌐 Open your web browser and go to [github.com](http://github.com).
    
* 🖱️ On the GitHub homepage, click on the "Sign up" button.
    
* 📝 Fill in the required information, like your username, email, and password.
    
* 💼 Choose a plan that suits you (Free or one of the paid options) based on your needs.
    
* 🔑 Complete the verification process, which might include solving a CAPTCHA or confirming your email.
    
* 🎉 Once you finish these steps, congratulations! You've successfully made your GitHub account. Now, you can start sharing and collaborating on your projects.
    

## 📝 Exercise 1: Create a New Repository on GitHub

* 🌐 Open your web browser and visit [github.com](http://github.com).
    
* 🔐 Log in to your GitHub account.
    
* ➕ On the GitHub homepage, click the "+" button at the top-right corner, then select "New repository" from the menu.
    
* 🏷️ Give your repository a meaningful name.
    
* 📄 You can also add a description to give more details about your repository.
    
* 🌐 Choose whether you want the repository to be public or private, depending on your needs.
    
* 🎉 Finally, click the "Create repository" button to create your new repository. That's it! Your central code storage is ready to go.
    

## 📂 Exercise 2: Clone the Repository to Your Local Machine

* 🌐 Go to your repository page on GitHub and click on the "Code" button.
    
* 📋 Copy the repository URL.
    
* 🖥️ Open the terminal or command prompt on your computer.
    
* 📂 Navigate to the directory where you want to save the repository.
    
* 📥 Use the command "git clone" followed by the repository URL you copied. For example: git clone [github.com/your-username/your-repository.git](http://github.com/your-username/your-repository.git)
    
* 🏁 Press Enter, and the repository will be cloned to your local machine.
    

## 🔄 Exercise 3: Make Changes, Commit, and Push

* 🚶‍♂️ Move to the repository directory.
    
* 📄 Create two files using the touch command.
    
* 🔍 Use the command "git status" to see the changes you made. It will show the modified files.
    
* ➕ Use the command "git add" followed by the file names to prepare the tracking changes. For example: "git add filename.txt" or "git add ." to track all changes. Now check the status, and our file is now tracked.
    
* 💼 Use the command "git commit" to save the changes with a meaningful message describing the modifications. For example: git commit -m 'Added new files'
    
* 🚀 Finally, use the command "git push" to upload the committed changes back to the repository on GitHub. For example: "git push origin main" or "git push origin master," depending on the branch name.
    

🎉 Conclusion 🎉 Congratulations! You've completed Day 8 of the #90DaysOfDevOps challenge. Today, you gained a solid understanding of Git and GitHub, covering tasks like creating repositories, cloning them locally, making changes, committing, and pushing back to GitHub. These core exercises are crucial for version control and collaborative software development. Keep up the fantastic work! 🎉🚀

📢 Stay in the ☁️ cloud loop and blast off into the 🚀 DevOps universe! Join me on Hashnode, where I share my latest insights and articles about all things cloud and DevOps. Let's connect on LinkedIn ([https://www.linkedin.com/in/nirmal-mahale-605565215/](https://www.linkedin.com/in/nirmal-mahale-605565215/)) and explore the boundless possibilities of the tech cosmos together. 🌌 And hey, if you want to peek under the hood of my projects, hop on over to my GitHub ([https://github.com/nirmal7030](https://github.com/nirmal7030)). 🛠️