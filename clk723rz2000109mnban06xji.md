---
title: "Basic Linux Commands"
datePublished: Mon Jul 17 2023 16:04:51 GMT+0000 (Coordinated Universal Time)
cuid: clk723rz2000109mnban06xji
slug: basic-linux-commands
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1689609601261/b4f1cda3-7cc0-44f3-a212-25717dd377d1.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1689609878820/0d2244bb-c979-4c98-9f21-1784681de8c5.png
tags: linux, opensource, devops, trainwithshubham, devopspythonic

---

📚 Welcome back to our ongoing series on mastering Linux commands! In today's session, we will delve into some fundamental commands that will enhance your proficiency in navigating and manipulating files and directories. By the end of this tutorial, you'll be equipped with the knowledge to view file contents, change file permissions, remove directories, create files, and more. Let's get started! 💪🚀

📝 Here are the commands we will cover: ✨

## 📌 **View file contents** 👁️

To view the contents of a file, you can use the `cat` command. It displays the entire contents of a file. 📄

* Example: `cat file.txt` 📂
    

## 📌 **Change access permissions of files** 🔒

To control who can read, write, or execute a file, use the `chmod` command. It allows you to change file permissions. 🛡️

* Example: `chmod u+rw file.txt` 🔐
    

## 📌 **Check command history** ⏰

To view the list of commands you have executed, use the `history` command. It displays a numbered list of previously executed commands. 📜

* Example: `history` 📝
    

## 📌 **Remove a directory/folder** 🗑️

To remove an empty directory, use the `rmdir` command. To remove a directory with its contents, use `rm -r`. ♻️

* Example (empty directory): `rmdir myfolder` 📁
    
* Example (directory with contents): `rm -r myfolder` 🗂️
    

## 📌 **Create a file and view its content** 📝

To create a file, use the `touch` command. To view its content, use the `cat` command. 📄

* Example (create): `touch fruits.txt` ✍️
    
* Example (view content): `cat fruits.txt` 👀
    

## 📌 **Add content to devops.txt** ➕

To add content to a file, use the `echo` command with the `>>` operator. Each `echo` command adds a new line. ✏️

* Example:
    
    * `echo "Apple" >> devops.txt` 🍎
        
    * `echo "Mango" >> devops.txt` 🥭
        
    * `echo "Banana" >> devops.txt` 🍌
        
    * ...
        

## 📌 **Show top three fruits from the file** 🥇

To display the top three fruits from a file, use the `head` command with the `-n` option. 📊

* Example: `head -n 3 devops.txt` 📝
    

## 📌 **Show bottom three fruits from the file** 🥉

To view the bottom three fruits from a file, use the `tail` command with the `-n` option. 📊

* Example: `tail -n 3 devops.txt` 📝
    

## 📌 **Create another file and view its content** 📝

To create a file, use the `touch` command. To view its content, use the `cat` command. 📄

* Example (create): `touch Colors.txt` 🌈
    
* Example (view content): `cat Colors.txt` 👀
    

## 📌 **Add content to Colors.txt** ➕

To add content to a file, use the `echo` command with the `>>` operator. Each `echo` command adds a new line. ✏️

* Example:
    
    * `echo "Red" >> Colors.txt` 🔴
        
    * `echo "Pink" >> Colors.txt` 💗
        
    * `echo "White" >> Colors.txt` ⚪
        

## 📌 **Find the difference between fruits.txt and Colors.txt** 🔍

🔄 To compare the contents of two files, use the `diff` command. 📊

* Example: `diff fruits.txt Colors.txt` 📝
    

## **Conclusion 🎉**

  
In a world of Linux commands, we embarked on a thrilling journey filled with 🌟 knowledge and 🚀 empowerment! From peering into file contents with 👁️ to granting them fortresses of 🔒 permissions, we danced through directories, leaving no clutter behind. With the stroke of a virtual brush, files bloomed to life, sharing their tales through 📝 echoes of fruit and color. We crowned the top three 🥇 and discovered the depths of the bottom three 🥉, adding flavor to our command creations. And as we compared files with the 🔍 lens of "diff," we unveiled the secrets they held. Now, armed with 🗡️ emojis and boundless enthusiasm, we march forth, ready to conquer new Linux realms! 💪🐧

  
📢 Stay in the ☁️ cloud loop and blast off into the 🚀 DevOps universe! Join me on Hashnode, where I share my latest insights and articles about all things cloud and DevOps. Let's connect on LinkedIn ([https://www.linkedin.com/in/nirmal-mahale-605565215/](https://www.linkedin.com/in/nirmal-mahale-605565215/)) and explore the boundless possibilities of the tech cosmos together. 🌌 And hey, if you want to peek under the hood of my projects, hop on over to my GitHub ([https://github.com/nirmal7030](https://github.com/nirmal7030)). 🛠️

🙌 Your support and engagement mean the 🌍 to me. Together, let's dive deeper into the world of cloud ☁️, soar to new heights with DevOps 🚀, and make a positive impact in the tech universe. Thank you for reading and joining me on this exciting journey! 🎉✨