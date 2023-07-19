---
title: "🚀 DevOps Adventures: Task-tastic with Shell Scripting! 💻"
datePublished: Wed Jul 19 2023 16:30:27 GMT+0000 (Coordinated Universal Time)
cuid: clk9xweim000g09mf4s6e6xxe
slug: devops-adventures-task-tastic-with-shell-scripting
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1689780606870/0f9a3473-6225-446a-8210-b1133346261a.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1689780620345/3d61e15f-6f22-4056-ae9c-5039ae50e5fb.png
tags: cloud, aws, devops, trainwithshubham, devopspythonic

---

Welcome back to Day 5 of the #90DaysOfDevOps challenge! Today, we'll embark on an exciting journey with Shell Scripting and explore the magic of automating tasks with the help of loops and commands. 🧙‍♂️✨

## 🐚 Task 1: Bash Script to Create Dynamic Directories! 📁

As DevOps enthusiasts, we love automation! So, let's create a magical bash script called [`createDirectories.sh`](http://createDirectories.sh) that takes three arguments: directory name, start number of directories, and end number of directories. The script will then create the specified number of directories with dynamic names.

Example 1:

```plaintext
./createDirectories.sh day 1 90
```

This will create 90 directories as day1, day2, day3, ..., day90.

Example 2:

```plaintext
./createDirectories.sh Movie 20 50
```

This will create 50 directories as Movie20, Movie21, Movie22, ..., Movie50.

🌟 Here's the enchanting [`createDirectories.sh`](http://createDirectories.sh) script:

```plaintext
#!/bin/bash

directory_name=$1
start=$2
end=$3

for (( i=start; i<=end; i++ ))
do
  dir_name="$directory_name$i"
  mkdir $dir_name
  echo "Created directory: $dir_name"
done
```

Get ready to watch the magic unfold as the script creates directories with dynamic names! 🌠🔮

## 📁 Task 2: Safeguarding Your Work with Automated Backups! 🛡️

As DevOps engineers, backups are essential for safeguarding our work. Let's create a magical backup script that automates the process! 🧹

🌟 Here's an enchanting [`backupScript.sh`](http://backupScript.sh) to create backups:

```plaintext
#!/bin/bash

# Define backup directory
backup_folder="/path/to/backup/folder" 

# Create a timestamp for the backup
current_date=$(date +%Y-%m-%d)
backup_file="backup_$current_date.tar.gz"

# Create a tarball of the entire repository
tar -czvf $backup_folder/$backup_file /path/to/your/work/directory
echo "Backup completed! File saved as $backup_file"
```

## 🧙‍♂️ Task 3: User Management Magic! 🧔👩

As we delve deeper into the DevOps world, understanding user management is vital. Let's create two enchanting users! 🧙‍♀️

🌟 To add users, use these magical commands:

```plaintext
#!/bin/bash

# Create two new users
useradd user1
useradd user2
```

💼 The users' names are entirely up to you! Feel free to choose any magical names you like! 🌟

## 🌠 Task 4:Display their usernames with the following spell

```plaintext
#!/bin/bash

echo "Magical Users:"
echo "---------------"
echo "User 1: $(getent passwd user1 | cut -d ':' -f 1)"
echo "User 2: $(getent passwd user2 | cut -d ':' -f 1)"
```

Now, execute the script and witness the magic as it displays the usernames of your newly created users! 🌟🎉

## Conclusion🎉

🚀 Celebrate Your Task-tastic Achievements! 🎉

Congratulations on completing these thrilling tasks! 🎉 You've harnessed the power of Shell Scripting to create directories, automate backups, and manage users like a true DevOps wizard! Keep practicing and embracing the magic of automation! 🌟💻

📢 Stay in the ☁️ cloud loop and blast off into the 🚀 DevOps universe! Join me on Hashnode, where I share my latest insights and articles about all things cloud and DevOps. Let's connect on LinkedIn ([https://www.linkedin.com/in/nirmal-mahale-605565215/](https://www.linkedin.com/in/nirmal-mahale-605565215/)) and explore the boundless possibilities of the tech cosmos together. 🌌 And hey, if you want to peek under the hood of my projects, hop on over to my GitHub ([https://github.com/nirmal7030](https://github.com/nirmal7030)). 🛠️