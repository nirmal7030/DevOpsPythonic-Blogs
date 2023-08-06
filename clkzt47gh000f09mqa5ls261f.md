---
title: "😎🚀 Day 11 Task: Advanced Git & GitHub for DevOps Engineers: Part-2 🚀😎"
datePublished: Sun Aug 06 2023 18:58:34 GMT+0000 (Coordinated Universal Time)
cuid: clkzt47gh000f09mqa5ls261f
slug: day-11-task-advanced-git-github-for-devops-engineers-part-2
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1691348233488/34aa704b-b54f-483e-9a36-fd2a1053a754.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1691348254551/6d6cb4cc-8f4d-43e6-aa14-b5055fcf2ec1.jpeg
tags: linux, aws, github, devops, devopspythonic

---

## Introduction:

Welcome back, DevOps Engineers! In this part of the series, we will dive deeper into some advanced Git concepts and commands that will help streamline your development workflow. We will cover Git stash, Git cherry-pick, resolving conflicts, and a practical hands-on exercise to reinforce your learning.

## **Git Stash:**

* 📦 `git stash` saves changes temporarily without committing.
    
* 🔄 Use `git stash pop` to apply stashed changes later.
    
* 🔍 `git stash list` shows the list of stashed changes.
    
* ❌ `git stash drop` deletes a stash.
    
* ❌ `git stash clear` deletes all stashes.
    

## **Cherry-pick:**

* 🍒 `git cherry-pick` applies specific commits to another branch.
    
* 📝 Create two branches and make commits on each.
    
* 🍒 Cherry-pick the desired commits.
    

## **Resolving Conflicts:**

* 🔍 `git status` checks for conflicting files.
    
* 🔍 `git diff` shows differences in conflicting versions.
    
* ✏️ Manually edit conflicting files.
    
* ✔️ `git add` marks resolved files.
    

### **Task-01: Git Stash and Applying Changes**

1. 📝 Create a new branch: Start by creating a new branch named "feature-branch" using `git checkout -b feature-branch`.
    
2. 🛠️ Make some changes: Modify the necessary files in the new branch.
    
3. 📦 Stash your changes: Use `git stash` to save the changes without committing them.
    
4. 🔄 Switch to a different branch: Now, switch to a different branch, for example, "development" using `git checkout development`.
    
5. 💾 Commit changes: In the "development" branch, make some changes and commit them using `git commit -m "Your commit message"`.
    
6. 📤 Apply stashed changes: Return to the "feature-branch" using `git checkout feature-branch`, then use `git stash pop` to apply the stashed changes on top of the new commits.
    

### **Task-01: Git Stash and Applying Changes**

```plaintext
# Task-01: Git Stash and Applying Changes

# Create a new branch and switch to it
git checkout -b feature-branch

# Make changes to the necessary files
# ...

# Stash your changes
git stash

# Switch to a different branch (e.g., development)
git checkout development

# Make some changes in the development branch and commit them
# ...

# Apply stashed changes on top of the new commits
git checkout feature-branch
git stash pop
```

### **Task-02: Cherry-pick and Rebase**

* 📝 Add lines to "version01.txt" for feature2.1 and commit.
    
* 📝 Add more lines for feature2.2 and commit.
    
* 📝 Finalize feature2 and commit.
    

```plaintext
# Task-02: Cherry-pick and Rebase

# Switch to the development branch
git checkout development

# Modify the version01.txt file as described in the task
# ...

# Commit changes for feature2.1
git add version01.txt
git commit -m "Added feature2.1 in development branch"

# Add more lines for feature2.2
# ...

# Commit changes for feature2.2
git add version01.txt
git commit -m "Added feature2.2 in development branch"

# Add final lines for feature2 completion
# ...

# Commit changes for feature2 completion
git add version01.txt
git commit -m "Feature2 completed"
```

### **Task-03: Cherry-pick in the Production Branch**

* 🔄 Switch to "production" branch.
    
* 🍒 Cherry-pick commit "Added feature2.2 in development branch".
    
* 📝 Add more lines after cherry-picked commit.
    
* ✔️ Commit changes for the optimized feature.
    

```plaintext
# Task-03: Cherry-pick in the Production Branch

# Switch to the production branch
git checkout production

# Cherry-pick the commit "Added feature2.2 in development branch"
git cherry-pick <commit_hash> # Replace <commit_hash> with the actual commit hash

# Add more lines after the cherry-picked commit
# ...

# Commit changes for the optimized feature
git add version01.txt
git commit -m "Optimized the feature"
```

## Conclusion

Git stash 📦, cherry-pick 🍒, and conflict resolution 🔧 are essential DevOps superpowers! Stash away changes, cherry-pick specific commits, and resolve conflicts like a pro 🚀🔧. Master these Git tricks to level up your DevOps skills and collaborate effectively 👥. Happy coding! 🎉🌟

📢 Stay in the ☁️ cloud loop and blast off into the 🚀 DevOps universe! Join me on Hashnode, where I share my latest insights and articles about all things cloud and DevOps. Let's connect on LinkedIn ([https://www.linkedin.com/in/nirmal-mahale-605565215/](https://www.linkedin.com/in/nirmal-mahale-605565215/)) and explore the boundless possibilities of the tech cosmos together. 🌌 And hey, if you want to peek under the hood of my projects, hop on over to my GitHub ([https://github.com/nirmal7030](https://github.com/nirmal7030)). 🛠️