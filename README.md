# Provisioning docker and minikube

-	First clone the [repository](https://github.com/usegalaxy-in/biohackathon.git)
	-	`git clone https://github.com/usegalaxy-in/biohackathon.git`
-	Get the [gantsign.minikube](https://galaxy.ansible.com/gantsign/minikube) role
	-	`ansible-galaxy install -p roles/ gantsign.minikube`
-	Run the playbook to provision
	-	`ansible-playbook bh_2020-playbook.yml`