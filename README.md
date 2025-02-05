# DevSecOps_L1
To automate the workflow process in CI/CD pipeline using GitHub Actions.

The workflow includes multiples services to ensure the automation process.
Step 1:
Make sure that you create an instance in AWS console or IAC and connect through SSH for the same, post that provide the follwing commands as given below.
sudo apt-get update -y
sudo apt-get upgrade -y
#adding the ansible personal package archive
sudo add-apt-repository --yes --update ppa:ansible/ansible
#installing ansible
sudo apt-get install -y ansible
ansible --version

apt-cache search ansible-lint
sudo apt-get install -y ansible-lint





