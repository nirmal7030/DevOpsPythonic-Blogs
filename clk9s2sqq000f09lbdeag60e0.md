---
title: "Shell Scripting for DevOps: Automating Your Way to Efficiency! 🚀"
datePublished: Wed Jul 19 2023 13:47:28 GMT+0000 (Coordinated Universal Time)
cuid: clk9s2sqq000f09lbdeag60e0
slug: shell-scripting-for-devops-automating-your-way-to-efficiency
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1689774300386/26e8ab54-a110-46ae-bf87-e12e426136eb.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1689774324243/3fee757a-6ace-4123-84e3-febbf8c66b6b.jpeg
tags: aws, cloud-computing, devops, shell-scripting, devopspythonic

---

## Introduction:

Welcome to the magical world of Shell Scripting! 🐚✨ In this blog post, we'll embark on an adventure where automation meets creativity, making shell scripting understandable even for non-IT students. Imagine having a wizard's wand that can automate tasks and bring efficiency to your daily life. That's precisely what shell scripting does in the realm of DevOps! So, let's hop on our broomsticks and discover the wonders of shell scripting together! 💻🔮

## 🐚 What is Shell Scripting?

* Shell scripting is like having a personal genie that follows your every command and performs tasks for you.
    
* It's a way to automate repetitive tasks, making your life easier and more productive.
    
* Think of it as your loyal sidekick, ready to assist you with tasks big and small!
    

## 🚀 Why is Shell Scripting important in DevOps?

* In the realm of DevOps, where speed and efficiency are key, shell scripting is the secret weapon!
    
* It allows you to wave your magic wand and automate processes like software deployments, system configurations, and much more.
    
* With shell scripting, you can save time, reduce errors, and focus on the truly important tasks at hand! ⚡✨
    

## 🐚 What is #!/bin/bash? Can we write #!/bin/sh as well?

* The line "#!/bin/bash" is like the enchanting spell that tells the computer to use the Bash interpreter, unlocking a world of powerful features for shell scripting! It's like having a treasure chest full of magical tools! 🛠️💫
    
* Yes, you can also write "#!/bin/sh" to use the default shell interpreter available on Unix-based systems.
    
* ```plaintext
          #!/bin/sh
          echo "Hello, World!"
    ```
    
* However, keep in mind that it might limit access to some advanced features. So, if you want the full magical experience, go for "#!/bin/bash" and unlock the true potential of shell scripting! 🧙‍♂️🔓
    
* ```plaintext
          #!/bin/bash 
          echo "Hello, World!"
    ```
    

### **🥅🧑‍💻Write a Shell Script which prints❓** `I will complete #90DaysOofDevOps challenge.`

✨ Example: Let's Print the #90DaysOfDevOps Challenge!

Imagine embarking on a journey called the #90DaysOfDevOps challenge. Let's create a spellbinding shell script that keeps you motivated every time you run it! Here's an example to inspire you:

📝 Create a new file called [`90days.sh`](http://90days.sh) and add the following magical script:

```plaintext
bashCopy code#!/bin/bash

echo "I will complete the #90DaysOfDevOps challenge! 🚀✨"
```

🌟 Save the file, open your terminal, and execute the following command to make the script executable:

```plaintext
bashCopy codechmod +x 90days.sh
```

🔮 Finally, run the script using:

```plaintext
bashCopy code./90days.sh
```

Magically, you'll see an inspiring message in your terminal, reminding you of your commitment to the challenge! Now, whenever you need a boost of motivation, just run the script and let the magic guide you to success! 💪✨

### **🕸️✨Write a Shell Script to take user input👤, input from arguments and print🖨️ the variables.💥🗨️🗨️**

Taking User Inputs and Arguments Shell scripts are not just about casting spells; they can also have a friendly conversation with you! Let's create an enchanting script that interacts with users by taking inputs and utilizing command-line arguments:

✨ Create a new file called `user_input.sh` and add the following captivating script:

```plaintext
bashCopy code#!/bin/bash

echo "Enter your name:"
read name

echo "Your name is: $name"

echo "Arguments provided: $@"
```

💡 This script uses its magic to prompt you to enter your name, reads the input, and then prints it along with any command-line arguments you provide. Here's how you can cast the spell:

```plaintext
bashCopy code./user_input.sh Nirmal Mahale arg1 arg2
```

✨ The output will mesmerize you:

```plaintext
yamlCopy codeEnter your name:
Nirmal Mahale
Your name is: Nirmal Mahale
Arguments provided: arg1 arg2
```

See how this spellbinding script interacts with you and captures your commands? It's like having a conversation with a mystical creature! 🧚‍♀️🌟

## **Using If-Else Statements in Shell Scripting 🔄**

Conditional statements, such as if-else, give your script the power to make decisions. Let's compare two numbers and conjure a message based on the comparison:

✨ Create a new file called `number_comparison.sh` and add the following spellbinding script:

```plaintext
bashCopy code#!/bin/bash

number1=10
number2=20

if [ $number1 -gt $number2 ]
then
  echo "Number 1 is greater than Number 2"
elif [ $number1 -lt $number2 ]
then
  echo "Number 1 is less than Number 2"
else
  echo "Number 1 is equal to Number 2"
fi
```

🌙 In this enchanting script, we compare two numbers and conjure a message based on the result. Cast the spell by running:

```plaintext
bashCopy code./number_comparison.sh
```

✨ The output will mesmerize you:

```plaintext
javascriptCopy codeNumber 1 is less than Number 2
```

With if-else statements, your script becomes a magical oracle that makes decisions based on the conditions you set! 🌠🔮

## Conclusion**🎉**

Congratulations on completing your magical journey into the world of Shell Scripting for DevOps! 🎉🌟 By harnessing the powers of shell scripting, you can automate tasks, save time, and achieve new levels of efficiency.

Remember, whether it's casting motivational spells, engaging in conversations with your scripts, or making decisions based on conditions, shell scripting empowers you to create your own magical experiences!

So, wave your wand, cast your spells, and embrace the wonders of shell scripting in your DevOps adventures! May your journey be filled with enchantment and success! ✨🚀💻

📢 Stay in the ☁️ cloud loop and blast off into the 🚀 DevOps universe! Join me on Hashnode, where I share my latest insights and articles about all things cloud and DevOps. Let's connect on LinkedIn ([https://www.linkedin.com/in/nirmal-mahale-605565215/](https://www.linkedin.com/in/nirmal-mahale-605565215/)) and explore the boundless possibilities of the tech cosmos together. 🌌 And hey, if you want to peek under the hood of my projects, hop on over to my GitHub ([https://github.com/nirmal7030](https://github.com/nirmal7030)). 🛠️