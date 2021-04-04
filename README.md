# Ansible-task
Step 1: Creating a Inventory file on ansible server with target hosts details


Step 2: Generate ssh keys on ansible server and exchange to target host

ssh-keygen -t rsa

Adding public key on targethost under authorized_keys and give chmod 600 om authorized_keys file

Step 3: Create a Playbook to install nginx 

Step 4: Execute play 

ansible-playbook play.yaml -i Inventory
