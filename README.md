# DevSecOps_L1
To automate the workflow process in CI/CD pipeline using GitHub Actions.

The workflow includes multiples services to ensure the automation process.
Step 1:
Make sure that you create an instance in AWS console or IAC and connect through SSH for the same, post that provide the follwing commands as given below.
sudo apt-get update -y
sudo apt-get upgrade -y
sudo apt-get install -y docker.io #Installing docker
sudo systemctl start docker
sudo systemctl enable docker
# Add the current user to the Docker group
sudo usermod -aG docker $USER
# Log out and log back in
exit
# After logging back in, verify group membership
groups
docker ps #to jst check
docker pull ansible/ansible --all-tags #pulling ansbile docker image
docker pull ansible/ansible:ubuntu1404 #specificversion



