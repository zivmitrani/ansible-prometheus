## Running ansible playbook in the relevant folder:
``` ansible-playbook playbook.yaml -i hosts.ini --extra-vars "@extravars.yaml" ```
## install the relevant role with galaxy:
``` ansible-galaxy install -r requirements.yml ```
## check the connection between ansible server and the hosts:
``` ansible servers -m ping -i hosts.ini -vvv ```