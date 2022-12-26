 sudo dnf install wget -y
    sudo wget http://pkg.jenkins-ci.org/redhat-stable/jenkins.repo -O /etc/yum.repos.d/jenkins.repo
     sudo rpm --import https://pkg.jenkins.io/redhat/jenkins.io.key
      sudo  dnf install -y java-11-openjdk-devel
     sudo dnf install -y jenkins
     systemctl start jenkins
     systemctl enable jenkins
     systemctl status jenkins
     hostnamectl
     curl ifconfig.me
changew th port in AWS===8080
