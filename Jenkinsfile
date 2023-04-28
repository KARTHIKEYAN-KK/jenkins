pipeline {
    agent any
  
    stages {
        stage('Build') {
            steps {
                sh 'mkdir /home/ubuntu/api2'
                sh 'cp /var/lib/jenkins/workspace/Github/* /home/ubuntu/api2'
            }
        }
    }
}
