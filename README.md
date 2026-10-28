# Ansible Demo

An automated configuration management project for setting up infrastructure using Ansible.

## 🚀 Getting Started

### Prerequisites
Make sure you have Ansible installed on your control node:
```bash
sudo apt update
sudo apt install ansible -y
```

### Installation
Clone this repository to your local machine:
```bash
git clone https://github.com/saksh97/ansible-demo.git
cd ansible-demo
```

## 🛠️ Usage

1. **Configure Inventory:** Update the `hosts` or `inventory` file with your target server IP addresses.
2. **Check Connection:** Test connectivity to your nodes:
   ```bash
   ansible all -m ping
   ```
3. **Run the Playbook:** Execute your main setup playbook:
   ```bash
   ansible-playbook playbook.yml
   ```
