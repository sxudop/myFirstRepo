pipeline {
  agent {
    dockerfile true
  }
  stages {
    stage('Docker script') {
     steps{
       sh('/var/jenkins_home/workspace/myDocker/script.sh')
	 }
	}
   }
  }

