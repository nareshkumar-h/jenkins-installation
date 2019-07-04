# jenkins-installation


```
sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins.io/redhat/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat/jenkins.io.key
sudo yum install jenkins -y
```

#### Start/Stop/Status
```
sudo service jenkins start
sudo service jenkins status
sudo service jenkins stop
```
