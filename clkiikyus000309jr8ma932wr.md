---
title: "Package Manager in Linux"
datePublished: Tue Jul 25 2023 16:31:35 GMT+0000 (Coordinated Universal Time)
cuid: clkiikyus000309jr8ma932wr
slug: package-manager-in-linux
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1690302593913/4d1d1488-9f91-4262-97a4-c1a43efa589d.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1690302613801/a11c066c-abb3-4d75-90d1-0b98b971aa0e.jpeg
tags: cloud, linux, aws, devops, devopspythonic

---

## What is a package manager?

📦 A package manager in Linux is like a magical 🧙‍♂️ assistant that helps you find, install, update, and remove software easily! It's like having a personal 🛍️ store for all your software needs!

* 🏭 **Repositories**: Package managers have access to vast collections of software called repositories. These are like online stores with tons of free and open-source software ready to be installed.
    
* 🔍 **Searching**: You can search for software packages by name or keywords using the package manager. It's like searching for products in an online marketplace.
    
* ➕ **Installation**: When you find the software you want, you simply ask the package manager to install it. It takes care of all the complex steps like downloading, verifying, and setting up the software for you.
    
* 🔄 **Updates**: The package manager also keeps your software up-to-date. It regularly checks for updates and lets you know when new versions are available. Upgrading is as easy as clicking a button.
    
* ❌ **Removal**: If you no longer need a software package, you can ask the package manager to remove it, and it'll clean up all the related files for you.
    
* 📋 **Dependencies**: Sometimes, the software relies on other software to work correctly. Package managers handle these dependencies automatically, ensuring that everything works smoothly together.
    
* 🔐 **Security**: Package managers verify the authenticity of the software you install, reducing the risk of malicious or compromised packages.
    
* 🌟 **Convenience**: With a package manager, you save time and effort. No need to visit different websites, download installers, or worry about updates. Everything is streamlined and managed in one place.
    

## **What is a package?**

📦 In Linux, a package is like a 🎁 gift box filled with all the necessary goodies to install and use software hassle-free! It's a handy way to organize and distribute software

* 📦 **Definition**: A package is a single file or archive that holds all the 📂 files and 📋 information required for a software program.
    
* 🧩 **Dependencies**: Sometimes, software needs other pieces (dependencies) to work correctly. Packages include these dependencies, like having all the 🧩 puzzle pieces in one box.
    
* 🚀 **Installation**: When you want to use the software, you can easily install the package. It's like unwrapping the 🎁 gift and setting up the software for you.
    
* 🔄 **Updates**: Packages can be updated to newer versions. Just like getting the latest 📚 book edition with extra chapters and improvements.
    
* ❌ **Removal**: If you no longer need the software, you can remove the package. It's like cleaning up and putting everything back in the box.
    
* 🔐 **Security**: Packages are designed to be safe and secure. They come from trustworthy sources, like getting products from reputable 🛒 stores.
    
* 🌐 **Repositories**: Packages are typically stored in repositories, which are like big online 🏬 marketplaces. The package manager knows where to find the right package for you.
    

## Different kinds of package managers?

📦 **APT (Advanced Package Tool)** - APT is like a handy 🛠️ command-line Swiss Army knife, working with Ubuntu's Advanced Packaging Tool. Here are some examples of its use:

* **Install the Package**: `sudo apt-get install package_name` 🚀📦 (Getting and unboxing the software gift!)
    
* **Update the Package**: `sudo apt-get update` followed by `sudo apt-get upgrade` 🔄📦 (Refreshing the software gift box and getting the latest version!)
    

🍅 **YUM (YellowDog Update Manager)** - YUM is like a friendly 🐕 dog providing a command-line interface for managing packages in RHEL. Here are some examples of its use:

* **Install the Package**: `sudo yum install package_name` 🚀📦 (Fetching and unwrapping the package gift!)
    
* **Update the Package**: `sudo yum update` & `sudo apt-get upgrade` 🔄📦 (Refreshing the package gift box and getting the updates!)
    
* **Remove the Package**: `sudo yum remove package_name` ❌📦 (Removing the package gift from your system!)
    

🎁 **RPM (Red Hat Package Manager)** - RPM is like a well-known 🎁 gift box manager, the default package manager for Red Hat-based systems like Fedora, CentOS, and RHEL. Here's how you use it:

* **Install the Package**: `sudo apt install rpm` 🚀📦 (Unpacking the RPM gift!)
    

## **🐳 Docker Installation using Package Managers** 📦

Docker, the containerization marvel, allows us to encapsulate applications and dependencies in lightweight containers. Let's install Docker on both Ubuntu and CentOS using their respective package managers.

📌 **Ubuntu Installation (using apt)**:

* Open your terminal and update package lists:
    
    ```plaintext
    codesudo apt update
    ```
    
* Install Docker using apt:
    
    ```plaintext
    codesudo apt install docker.io
    ```
    
* Verify Docker installation:
    
    ```plaintext
    codedocker --version
    ```
    

📌 **CentOS Installation (using yum)**:

* Open your terminal and update package lists:
    
    ```plaintext
    codesudo yum update
    ```
    
* Install Docker using yum:
    
    ```plaintext
    codesudo yum install docker
    ```
    
* Start Docker service:
    
    ```plaintext
    codesudo systemctl start docker
    ```
    
* Enable Docker to start on boot:
    
    ```plaintext
    sudo systemctl enable docker
    ```
    
* Verify Docker installation:
    
    ```plaintext
    codedocker --version
    ```
    

## **🏗️ Jenkins Installation using Package Managers** 📦

Jenkins, the automation powerhouse, empowers us to build, test, and deploy projects. Let's install Jenkins on both Ubuntu and CentOS using their respective package managers.

📌 **Ubuntu Installation (using apt)**:

* Add Jenkins repository key:
    
    ```plaintext
    wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
    ```
    
* Add Jenkins repository to sources list:
    
    ```plaintext
    sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
    ```
    
* Update package lists:
    
    ```plaintext
    sudo apt update
    ```
    
* Install Jenkins using apt:
    
    ```plaintext
    sudo apt install jenkins
    ```
    
* Start Jenkins service:
    
    ```plaintext
    sudo systemctl start jenkins
    ```
    
* Enable Jenkins to start on boot:
    
    ```plaintext
    sudo systemctl enable jenkins
    ```
    

📌 **CentOS Installation (using yum)**:

* Add Jenkins repository to yum repository list:
    
    ```plaintext
    sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins.io/redhat-stable/jenkins.repo
    ```
    
* Import Jenkins repository key:
    
    ```plaintext
    sudo rpm --import http://pkg.jenkins.io/redhat-stable/jenkins.io.key
    ```
    
* Install Jenkins using yum:
    
    ```plaintext
    sudo yum install jenkins
    ```
    
* Start Jenkins service:
    
    ```plaintext
    sudo systemctl start jenkins
    ```
    
* Enable Jenkins to start on boot:
    
* ```plaintext
        sudo systemctl enable jenkins
    ```
    

## **🔄 Systemctl vs Service: Unveiling the Differences** ⚔️

In the Linux realm, both systemctl and service commands are powerful warriors that handle services, but they have some differences in their functionality and usage. Let's explore their unique traits! 🌟

🔍 **Systemctl: The SystemD Champion** 🛡️⚙️

Systemctl is a fearless warrior that directly interacts with the SystemD service manager, wielding its might to manage services with finesse! 💪

✨ **Functionality**:

* Start, stop, and restart services with ease.
    
* Enable or disable services to control their behavior.
    

🛠️ **Usage**:

* Start Jenkins services: 🔥
    
    ```plaintext
    systemctl start jenkins
    ```
    
* Check Jenkins services status: 👀
    
    ```plaintext
    systemctl status jenkins
    ```
    

🔧 **Service: The Trusty Ally** 🤝⚙️

Service is a loyal ally that manages services by interacting with the SystemD process, complementing systemctl in its mission! 🤝

✨ **Functionality**:

* Start, stop, and restart services smoothly.
    
* Enable or disable services with precision.
    

🛠️ **Usage**:

* Start Jenkins services: 🔥
    
    ```plaintext
    service jenkins start
    ```
    
* Check Jenkins services status: 👀
    
    ```plaintext
    service jenkins status
    ```
    

##   
Conclusion :

Both "systemctl" and "service" commands are powerful tools for managing services in Linux. While "systemctl" directly interacts with the SystemD service manager, "service" complements it by interacting with the SystemD process. Both commands provide essential functionalities to start, stop, restart, enable, and disable services. Choose the command that suits your preferences and distribution, and embrace their power to become a Linux hero! 🐧💪 #LinuxMagic #ServiceManagement #SystemctlVsService

📢 Stay in the ☁️ cloud loop and blast off into the 🚀 DevOps universe! Join me on Hashnode, where I share my latest insights and articles about all things cloud and DevOps. Let's connect on LinkedIn ([https://www.linkedin.com/in/nirmal-mahale-605565215/](https://www.linkedin.com/in/nirmal-mahale-605565215/)) and explore the boundless possibilities of the tech cosmos together. 🌌 And hey, if you want to peek under the hood of my projects, hop on over to my GitHub ([https://github.com/nirmal7030](https://github.com/nirmal7030)). 🛠️