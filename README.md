 sudo dnf install wget -y
   47  sudo wget http://pkg.jenkins-ci.org/redhat-stable/jenkins.repo -O /etc/yum.repos.d/jenkins.repo
   48  sudo rpm --import https://pkg.jenkins.io/redhat/jenkins.io.key
   49   sudo  dnf install -y java-11-openjdk-devel
   50  sudo dnf install -y jenkins
   51  systemctl start jenkins
   52  systemctl enable jenkins
   53  systemctl status jenkins
   54  hostnamectl
   55  curl ifconfig.me
