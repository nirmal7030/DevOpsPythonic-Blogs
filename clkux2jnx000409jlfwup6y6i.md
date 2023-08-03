---
title: "Day 10 Task: Advance Git & GitHub for DevOps Engineers"
datePublished: Thu Aug 03 2023 08:50:24 GMT+0000 (Coordinated Universal Time)
cuid: clkux2jnx000409jlfwup6y6i
slug: day-10-task-advance-git-github-for-devops-engineers
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1691052487883/da53844e-dc24-415f-86c0-b759a49e1c53.webp
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1691052610788/37ef7c23-eda4-437c-88e0-9b3ef423410b.webp
tags: aws, github, git, devops, devopspythonic

---

Welcome back, DevOps Engineers! Today, we will dive deeper into Git and GitHub, focusing on Git branching, merging, reverting, and resetting. We'll make this learning journey more exciting with some fun emojis and organized bullet points! So, grab your virtual hard hats and let's get started! 🚀💻🎉

## **Git Branching 🌱**

Branching in Git allows us to work on different features, bug fixes, or experiments in isolation, without affecting other parts of the repository. Each repository has a default branch, usually called "master" or "main," and we can create multiple other branches to work on specific tasks.

* **Benefits of Branching:**
    
    * Isolate development work.
        
    * Develop features and fix bugs separately.
        
    * Safely experiment with new ideas.
        

## **Git Revert and Reset 🔙**

Sometimes, we need to undo changes that we've made in previous commits. Two commonly used tools for this purpose are `git reset` and `git revert`.

* **Git Revert:**
    
    * Reverts one or more commits by creating a new commit that undoes the changes.
        
    * Safer for collaborative workflows, as it doesn't rewrite history.
        
    * Useful for public repositories or shared branches.
        
* **Git Reset:**
    
    * Resets the current branch to a specific commit, discarding any changes after that point.
        
    * More powerful but riskier, as it can rewrite history.
        
    * Suitable for private branches or when working on local repositories.
        

## **Git Rebase and Merge 🔄**

In Git, we have two methods to integrate changes from one branch to another: `git rebase` and `git merge`.

* **Git Rebase:**
    
    * Integrates changes from one branch onto another by moving or reapplying commits.
        
    * Results in a cleaner, linear history without unnecessary merge commits.
        
    * Useful for keeping the commit history tidy and more manageable.
        
* **Git Merge:**
    
    * Combines changes from one branch into another by creating a new merge commit.
        
    * Preserves the commit history of both branches, resulting in a more complex history.
        
    * Useful when maintaining a more accurate record of branch integration points.
        

For a detailed comparison between Git Rebase and Merge, check out this [**article**](https://example.com/git-rebase-vs-merge).

## **Task 1: Hands-On 📝🤖**

Let's put our newfound knowledge into practice with a series of tasks:

* **Step 1 - Add New File:**
    
    * Create a text file called `version01.txt` inside the `Devops/Git/` directory.
        
    * Write the content "This is the first feature of our application" in the file.
        
    * Create a new branch named `dev` from the `master` branch.
        
    * Commit your changes with the message "Added new feature."
        
* **Step 2 - Push to Remote:**
    
    * Push the `dev` branch to the remote repository for review.
        
    
    ```plaintext
    # Assuming you have already initialized the repository and added the remote
    git checkout -b dev   # Create and switch to the 'dev' branch
    git add Devops/Git/version01.txt
    git commit -m "Added new feature"
    git push -u origin dev
    ```
    

## **Task 2: Hands-On 🚀🤖**

Continuing from Task 1, let's move on to the next set of actions:

* **Step 3 - Add More Content:**
    
    * Switch to the `dev` branch.
        
    * Edit `version01.txt` and add the following lines:
        
        * 1st line&gt;&gt; This is the bug fix in the development branch
            
        * Commit this with the message "Added feature2 in the development branch."
            
        * 2nd line&gt;&gt; This is gadbad code
            
        * Commit this with the message "Added feature3 in the development branch."
            
        * 3rd line&gt;&gt; This feature will gadbad everything from now.
            
        * Commit with the message "Added feature4 in the development branch
            
    
    ```plaintext
    # Switch to the 'dev' branch
    echo "This is the bug fix in the development branch" >> Devops/Git/version01.txt
    git add Devops/Git/version01.txt
    git commit -m "Added feature2 in the development branch."
    echo "This is gadbad code" >> Devops/Git/version01.txt
    git add Devops/Git/version01.txt
    git commit -m "Added feature3 in the development branch."
    echo "This feature will gadbad everything from now." >> Devops/Git/version01.txt
    git add Devops/Git/version01.txt
    git commit -m "Added feature4 in the development branch."
    ```
    
    * **Step 4 - Revert Changes:**
        
    * Restore the `version01.txt` file to a previous version where the content is "This is the bug fix in the development branch."
        
    * Use `git revert` or `git reset` based on your preference and understanding.
        
    
    ```plaintext
    # Revert using git revert
    git log   # Find the commit hash of the previous version you want to revert to
    git revert <commit_hash>
    
    # Reset using git reset
    git log   # Find the commit hash of the previous version you want to reset to
    git reset --hard <commit_hash>
    ```
    

Now you're well-equipped to handle branching, merging, reverting, and resetting in Git. These skills are vital for any DevOps Engineer, and with practice, you'll become a Git ninja! 🐱‍👤💪

I hope you enjoyed this creative blog and found it helpful in your DevOps journey. Feel free to explore more Git features and keep building your expertise.

Happy coding! 🚀😃🎈

📢 Stay in the ☁️ cloud loop and blast off into the 🚀 DevOps universe! Join me on Hashnode, where I share my latest insights and articles about all things cloud and DevOps. Let's connect on LinkedIn ([https://www.linkedin.com/in/nirmal-mahale-605565215/](https://www.linkedin.com/in/nirmal-mahale-605565215/)) and explore the boundless possibilities of the tech cosmos together. 🌌 And hey, if you want to peek under the hood of my projects, hop on over to my GitHub ([https://github.com/nirmal7030](https://github.com/nirmal7030)). 🛠️