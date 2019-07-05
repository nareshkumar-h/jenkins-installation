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

#### Check Java Version
```
java -version
```
Note: Uninstall JDK 7
```
sudo yum remove java-1.7.0-openjdk
```
#### Install JDK 8
```
sudo yum install java-1.8.0-openjdk-devel
```
#### Check Java Version
```
java -version
```

#### Install Git
```
sudo yum install git -y
```

#### Install Plugins (Manage Jenkins -> Plugins )
* Maven Integration plugin
* GitHub Integration Plugin
* Deploy to container Plugin ( This plugin allows you to deploy a war to a container after a successful build. )

