---
title: "🚀 DevOps Adventures: Day 6 - Unraveling File Permissions and ACL 💻"
datePublished: Sat Jul 22 2023 17:06:21 GMT+0000 (Coordinated Universal Time)
cuid: clke9i4du000a09l5ewomaq6o
slug: devops-adventures-day-6-unraveling-file-permissions-and-acl
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1690045500616/92d08be6-7251-4224-ab7a-069d495a47e1.avif
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1690045669468/8fc996fb-359a-487f-b25b-6c41a6f84361.avif
tags: linux, aws, devops, trainwithshubham, devopspythonic

---

Greetings, fellow DevOps enthusiasts! 🌟 Today, we delve into the mystical world of Linux file permissions and ownership. Understanding these concepts is crucial for every DevOps wizard as it allows us to control access to files and directories with magical precision! Let's embark on this enchanting journey of reading, learning, and implementing file permissions. 🧙‍♂️✨

## **📁 Linux File Permissions: The Magic of Ownership**

In the realm of Linux, each file and directory is protected by a unique set of permissions. These permissions are assigned to three distinct categories of users:

✨ **Owner**: The master of the file, possessing the highest magical control. The owner can read, write, and execute the file using the "chown" charm to change ownership permissions.

✨ **Group**: A collective of users sharing magical powers over the file. The group's permission can be altered with the "chgrp" enchantment.

✨ **Others**: All users with access to the mystical Linux system. The "chmod" spell empowers us to change permissions for other users.

## **💻 Task: Discovering the Power of File Permissions**

To put our magical knowledge into practice, let's create a simple file and observe its permissions using the "ls -ltr" incantation. 🧙‍♀️

🌟 Follow these steps to complete the task:

1. Create a simple file using your favorite text editor, such as Vim or Nano.
    
2. Check the permissions of the file using "ls -ltr". Witness the enchanting output, revealing the file's permissions and ownership.
    

Now, let's work our magic by changing the user permissions of the file and observe the changes with "ls -ltr". This exercise will deepen our understanding of file permissions! 🌠

**📜 Article: Unveiling the Mysteries of File Permissions**

In the mystical world of Linux, file permissions act as powerful enchantments that control access to our files and directories. The concept revolves around three magical categories: owner, group, and others, each holding unique powers. 🧙‍♂️✨

🌟 **Understanding Owner Permissions**: As the primary sorcerer, the file's owner has the authority to read, write, and execute the file at will. The "chown" charm enables the owner to transfer ownership to a new master.

🌟 **Embracing Group Permissions**: Group permissions bestow magical powers to users belonging to the file's group. The "chgrp" spell allows us to assign a new group to the file, sharing their magical abilities.

🌟 **Unleashing Others' Permissions**: Users beyond the file's owner and group are categorized as "others." The "chmod" incantation grants or restricts access to these users, achieving a delicate balance between openness and security.

Armed with this magical knowledge, we can confidently wield the power of file permissions, safeguarding our files and granting access as needed! 🔐💼

## **🔍 Access Control Lists (ACL): The Next Level of Magic**

* In our quest for even greater control, let's delve into Access Control Lists (ACL).
    
* These magical lists allow us to grant specific permissions to individual users or groups, surpassing the traditional owner, group, and others concept. 🗝️💫
    

**💡 Using getfacl and setfacl Charms**:

* With the "getfacl" spell, we can reveal the enchanting details of ACL for a file.
    
* As we harness the "setfacl" charm, we can bestow tailored permissions to different users, creating a truly customized magical experience.
    

Continue our magical journey through the realm of DevOps, mastering new spells, and uncovering hidden secrets. For any doubts or shared knowledge, don't forget to join our Discord Channel for #90DaysOfDevOps. Together, let's become DevOps wizards! 🚀🌟

In Day 6, we mastered Linux file permissions and ownership, wielding "chown," "chgrp," and "chmod" spells. Access Control Lists (ACL) added personalized enchantments. #90DaysOfDevOps 🧙‍♂️✨ #FilePermissions #ACL #DevOpsWizardry

📢 Stay in the ☁️ cloud loop and blast off into the 🚀 DevOps universe! Join me on Hashnode, where I share my latest insights and articles about all things cloud and DevOps. Let's connect on LinkedIn ([https://www.linkedin.com/in/nirmal-mahale-605565215/](https://www.linkedin.com/in/nirmal-mahale-605565215/)) and explore the boundless possibilities of the tech cosmos together. 🌌 And hey, if you want to peek under the hood of my projects, hop on over to my GitHub ([https://github.com/nirmal7030](https://github.com/nirmal7030)). 🛠️