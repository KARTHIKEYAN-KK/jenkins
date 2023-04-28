pipeline {
    agent any
  
    stages {
        stage('Test') {
            steps {
                sh 'rm -r /home/ubuntu/api2'
                sh 'mkdir /home/ubuntu/api2'
            }
        }
        stage('Build') {
            steps {
                sh 'cp /var/lib/jenkins/workspace/Github/* /home/ubuntu/api2'
            }
        }
    }
}
