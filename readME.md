# Jenkins Labs
List of Hands-on Labs on Jenkins

## Lab 1 : Install Jenkins on Ubuntu 16
- Installation commands :
		
		 $wget -q -O - https://pkg.jenkins.io/debian/jenkins-ci.org.key | sudo apt-key add -
		 $sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
		 $sudo apt-get update
		 $sudo apt-get install jenkins
		 $sudo apt-get update
		 $sudo apt-get install jenkins
- Verfication : 
	Acess Jenkins from the browser by using the IP:8080
		
# Jenkins Terminology
* JenkinsFile
* Jenkins Plugin
* Jenkins Pipline
* environment
* agent
* stages
* post

- Refrences :
   - https://wiki.jenkins.io/display/JENKINS/Installing+Jenkins+on+Ubuntu
   - https://jenkins.io/doc/pipeline/tour/getting-started/
		
