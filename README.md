# 🚀 Ansible Playbooks Collection

A collection of **Ansible playbooks** for automating common system administration and DevOps tasks.

This repository is part of my journey into DevOps and automation using tools like Ansible.

---

## 📂 Repository Structure

```
.
├── copy_files.yml     # Copy files to remote servers
├── hello.yml          # Basic test playbook (Hello World)
├── module.yaml        # Practice with Ansible modules
└── ...
```

---

## ⚙️ Requirements

Before running these playbooks, make sure you have:

* Ansible installed
* SSH access to target machines
* Inventory file configured

Install Ansible (Ubuntu):

```
sudo apt update
sudo apt install ansible -y
```

---

## 🖥️ How to Use

1. Clone the repository:

```
git clone https://github.com/your-username/ansible-playbooks.git
cd ansible-playbooks
```

2. Run a playbook:

```
ansible-playbook -i inventory.ini copy_files.yml
```

---

## 📌 Example Playbooks

### 📄 copy_files.yml

Copies files from local machine to remote servers.

### 👋 hello.yml

Simple playbook to test connectivity and execution.

### 🧩 module.yaml

Demonstrates usage of different Ansible modules.

---

## 🎯 Goals

* Practice Ansible automation
* Build real-world DevOps skills
* Create reusable playbooks

---

## 📈 Future Improvements

* Add roles and reusable components
* Implement dynamic inventory
* Integrate with CI/CD pipelines
* Add real-world production scenarios

---

## 🤝 Contributing

Feel free to fork this repo and improve it. Suggestions are always welcome!

---

## 🧠 Author

**Irfan Ali**
DevOps Engineer🚀

---

## ⭐ Support

If you like this repo, give it a star ⭐
(helps more than coffee ☕ sometimes)
