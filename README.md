# yum install curl policycoreutils-python openssh-server   -y 

# yum install postfix   -y  
# systemctl start postfix 
# systemctl enable postfix 
# systemctl status postfix 


# curl https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.rpm.sh | sudo bash 
# EXTERNAL_URL="http://35.229.79.166" yum install -y gitlab-ce 
# gitlab-ctl reconfigure 
# systemctl stop firewalld  
# systemctl disable firewalld
