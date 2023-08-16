---
title: "Python Libraries for DevOps - 📜 Reading JSON and YAML 🐍"
datePublished: Wed Aug 16 2023 17:12:37 GMT+0000 (Coordinated Universal Time)
cuid: clldzqh53000509ib8subf3b9
slug: python-libraries-for-devops-reading-json-and-yaml
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1692205681069/6e1d4a33-7b02-4c64-9904-3a92c6bf4331.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1692205707022/f553be63-af57-4de6-86e8-e2effffb7117.png
tags: linux, aws, python, devops, devopspythonic

---

Hello, DevOps champs! Ready for another thrilling day of enhancing your DevOps arsenal? Today, we're diving into the fascinating world of file parsing, focusing on the vibrant realms of JSON and YAML. Inspired by the wisdom of the incredible Shubham Londhe, let's explore the essential Python libraries that can supercharge your DevOps journey. 🚀

## **Why File Parsing Rocks in DevOps**

Picture this: You're a DevOps magician, conjuring cloud services, orchestrating deployments, and automating infra like a boss. But what's the glue holding it all together? File parsing! As a DevOps aficionado, you'll often dance with configuration files - JSON and YAML files - that hold the secrets of your digital symphony. Time to learn the art of handling these files with Python's enchanting libraries. 🎩✨

## **Marvelous Python Libraries for DevOps**

Python isn't just a language; it's a playground of libraries that can turn DevOps dreams into reality. Let's explore the stars of today's show:

### **1\.** `os` and `sys` - 🖥️

The dynamic duo of system manipulation! These libraries let you tango with your operating system, allowing you to juggle files, directories, and command-line magic from within your Python scripts. 🎭🔮

### **2\.** `json` - 📚

The JSON library, a DevOps spellbook! It empowers you to conjure JSON out of thin air (or Python objects) and decipher JSON incantations back into Python-friendly forms. Perfect for summoning data between different systems. 📖🔍

### **3\.** `yaml` - 🧙‍♂️

Behold the YAML oracle! With this sorcery, you can transmute YAML scrolls into Python lore and vice versa. YAML's human-readable format makes it the perfect choice for configuration files, and Python's `yaml` library ensures a seamless translation. 📜🔮

## **Task 1: Crafting a Dictionary and Forging a JSON Scroll**

Time for action, brave DevOps apprentices! Let's sculpt a Python dictionary and then cast it into the depths of a JSON file. Observe the magic script in action:

```plaintext
import json

# Creating a mystical dictionary
data = {
    "name": "Code Conjurer",
    "role": "DevOps Enchanter",
    "spells": ["Python Magic", "Container Charms", "Cloud Conjuring"]
}

# Inscribing the dictionary into a JSON tome
with open("spellbook.json", "w") as json_scroll:
    json.dump(data, json_scroll, indent=4)

print("Spellbook inscribed in spellbook.json 📜🌟")
```

## **Task 2: Decrypting Cloud Service Names from the JSON Codex**

Time to uncover the arcane wisdom hidden within the JSON scrolls! We shall extract the service names of cloud providers using Python's ancient scripts:

```plaintext
import json

# Deciphering the JSON codex
with open("codex.json", "r") as json_codex:
    codex_data = json.load(json_codex)

# Extracting and revealing service secrets
print("🌩️ Cloud Service Secrets:")
for provider, service in codex_data.items():
    print(f"• {provider} : {service}")
```

And behold, the hidden knowledge shall be unveiled:

```plaintext
🌩️ Cloud Service Secrets:
• aws : ec2
• azure : VM
• gcp : compute engine
```

## **Task 3: Unfurling YAML Scrolls into JSON Chronicles**

Our final quest involves deciphering the mysteries locked within YAML scrolls and transcribing them into the Chronicles of JSON, adorned with emojis and bullet points:

```plaintext
import yaml
import json

# Unrolling the YAML scrolls
with open("scrolls.yaml", "r") as yaml_scroll:
    yaml_data = yaml.safe_load(yaml_scroll)

# Converting the YAML tales into JSON lore
json_lore = json.dumps(yaml_data, indent=4)

# Presenting the JSON chronicles with flair
print("📜 Ancient Cloud Chronicles:")
for provider, service in yaml_data.items():
    print(f"• {provider} : {service}")
print("\n📚 JSON Equivalent:")
print(json_lore)
```

## **Conclusion: 🌌 Unleash Your DevOps Wizardry**

Astounding feats, oh mighty DevOps sorcerers! You've unveiled the enigma of reading and interpreting JSON and YAML scrolls using Python's potent charms. With the guidance of libraries like `json` and `yaml`, you're now equipped to wield the power of configuration and data manipulation.

As you continue on your spellbinding journey, remember to keep learning and experimenting. From crafting dictionaries to inscribing JSON scrolls and unrolling YAML tales, you've leveled up your DevOps game. May your code be robust, your deployments smooth, and your DevOps adventures ever thrilling! 🧙‍♂️🌟