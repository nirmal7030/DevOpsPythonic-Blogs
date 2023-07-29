---
title: "🚀 Deep Dive into Git & GitHub for DevOps Engineers 🚀"
datePublished: Sat Jul 29 2023 17:33:12 GMT+0000 (Coordinated Universal Time)
cuid: clkoajmhx000109iggaetfpmp
slug: deep-dive-into-git-github-for-devops-engineers
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1690651838018/dc53deee-af3f-4bce-9578-c1ca01c05939.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1690651855849/69819be4-6a77-4341-91f3-440504f660dd.jpeg
tags: cloud, aws, devops, trainwithshubham, devopspythonic

---

## Introduction 💡

Welcome to Day 9 of our DevOps journey! Today, we'll explore the fascinating world of Git and GitHub - the backbone of modern software development. 🌐 Whether you're a seasoned DevOps engineer or just starting your coding adventure, understanding version control systems like Git and collaboration platforms like GitHub is crucial for successful teamwork and efficient project management. Let's dive in! 🏊‍♂️

## What is Git and Why is it Important? 🌟

📜 Git is a distributed version control system 📜

* It tracks changes in source code during software development.
    
* Created by Linus Torvalds in 2005, it has since become the industry standard.
    

## 🚀 Why is Git Important? 🚀

* Facilitates collaborative coding among developers.
    
* Ensures a detailed history of code changes, helping track bugs and roll back to previous versions.
    
* Enables branching and merging, making experimentation and feature development seamless.
    
* Promotes a flexible and scalable workflow for development teams.
    

## Difference Between Main Branch and Master Branch? 🌳

🌟 In recent years, the terminology has shifted from "master" to "main" branch. 🌟

🌿 Main Branch 🌿

* The default branch represents the most stable version of the codebase.
    
* Synonymous with the production-ready code.
    
* More inclusive terminology, reflecting a respectful and diverse environment.
    

📜 Master Branch 📜

* Historically used as the default branch before the shift to "main."
    
* Some repositories may still refer to it as the main branch.
    

## Difference Between Git and GitHub? 🔄

🌟 Git 🌟

* A version control system installed on a local machine.
    
* Allows developers to manage code changes, branches, and commit history.
    
* Operates offline, perfect for individual developers or small teams.
    

🌐 GitHub 🌐

* A web-based hosting service for Git repositories.
    
* Provides a centralized platform for sharing and collaborating on code.
    
* Offers additional features like issue tracking, pull requests, and project management tools.
    

## How to Create a New Repository on GitHub? 🏗️

📝 Follow these steps to create a new repository "Devops" on GitHub: 📝

1. 🖥️ Log in to your GitHub account.
    
2. ➕ Click on the "+" sign in the top right corner and select "New Repository."
    
3. 🖋️ Name your repository "Devops" and add an optional description.
    
4. 🔒 Choose the repository's visibility (public or private).
    
5. 🆗 Click on "Create Repository."
    

## Difference Between Local & Remote Repository and How to Connect Them? 🔗

🌟 Local Repository 🌟

* Exists on your computer and holds the complete history of a Git project.
    
* Developers can make changes, create branches, and commit locally.
    

🌐 Remote Repository 🌐

* Hosted on a server or a platform like GitHub.
    
* Acts as a centralized location for collaboration and sharing.
    

🔗 Connecting Local to Remote Repository 🔗

## Task-1: Set User Name and Email Address 👤

* Open the terminal or Git Bash.
    
* Run these commands, replacing "Your Name" and "[**your@email.com**](mailto:your@email.com)" with your details:
    
    ```plaintext
    git config --global user.name "Your Name"
    git config --global user.email "your@email.com"
    ```
    

## Task-2: Create "Devops" Repository on GitHub 🏗️

1. 🖥️ Log in to your GitHub account.
    
2. ➕ Click on the "+" sign and select "New Repository."
    
3. 🖋️ Name the repository "Devops" and add a description.
    
4. 🔒 Choose visibility (public or private).
    
5. 🆗 Click on "Create Repository."
    

## Task-3: Connect Local to Remote Repository 🔗

1. 🖥️ In the terminal, navigate to your local repository's root folder.
    
2. 📡 Run this command, replacing &lt;GitHub\_Repository\_URL&gt; with your GitHub repository URL:
    

```plaintext
git remote add origin <GitHub_Repository_URL>
```

## Task-4: Create a New File and Push Commits 📝

1. 📁 Create "Day-02.txt" inside "Devops/Git" directory.
    
2. ✏️ Add content to the file.
    
3. 🖥️ In the terminal, navigate to the local repository's root folder.
    
4. ➕ Add the changes to the staging area:
    
5. ```plaintext
    git add Devops/Git/Day-02.txt
    ```
    
6. 💾 Commit the changes with a meaningful message:
    
7. ```plaintext
    git commit -m "Added Day-02.txt with content."
    ```
    
8. 🔗 Push the changes to the remote repository on GitHub:
    

```plaintext
git push origin main
```

## Conclusion 🏁

🎉 Congratulations on completing Day 9's tasks and mastering the basics of Git and GitHub! 🎉

🌐 Git empowers us with version control, enabling efficient teamwork and code management. 🌟 Main branch represents stability and inclusivity, leading to a better software development environment. 🔄 Git is the version control system on your local machine, while GitHub provides a collaborative online platform. 🏗️ Creating repositories on GitHub is simple, and connecting local to remote allows seamless code sharing.

Embrace these powerful tools to elevate your DevOps journey! 🚀 Happy coding! 😊