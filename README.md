# Ansible Apache Webserver Playbook 🚀
A collection of Ansible playbooks for automating server setup, configuration, and deployments.
This is my first Ansible playbook project.  
It installs **Apache Web Server**, enables it, and deploys a simple static website.

## Steps to Run

1. **Clone this repo:**
   ```bash
   git clone https://github.com/Aditya0784/ansible-playbooks-collection.git
   cd ansible-apache-playbook

2. **Run the playbook:**
   ```bash
   ansible-playbook -i inventory playbook.yml

3. **Verify the installation:**
   ```bash
   http://<server-ip>

4. **Inventory Structure:**
   * [webservers] – Servers where Apache will be installed.
   * Aliases like web1 make it easy to reference servers in playbooks.
   * Example:
     ```bash
     web1 ansible_host=203.0.113.10 ansible_user=ubuntu ansible_ssh_private_key_file=~/.ssh/id_rsa

## Requirements
  * Ansible installed on your control machine (pip install ansible)
  * Python 3
  * SSH key access to your web servers
  
  
## Made with by Aditya Rao
