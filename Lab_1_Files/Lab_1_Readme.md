# Installation Jenkins on Ubuntu 16

## Resources used in this tutorial
	* Ubuntu 16

# Jenkins Installation 
	* Installation commands :
		wget -q -O - https://pkg.jenkins.io/debian/jenkins-ci.org.key | sudo apt-key add -
		sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
		sudo apt-get update
		sudo apt-get install jenkins
		sudo apt-get update
		sudo apt-get install jenkins
	
	*Verfication : 
		Acess Jenkins from the browser by using the IP:8080
		
	Refrences :
		https://wiki.jenkins.io/display/JENKINS/Installing+Jenkins+on+Ubuntu
		
		
# Tutorial on Jenkins 
		https://jenkins.io/doc/pipeline/tour/getting-started/