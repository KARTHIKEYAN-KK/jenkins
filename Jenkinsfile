pipeline {
    agent any
  
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/KARTHIKEYAN-KK/jenkins.git'
            }
        }
        stage('Build') {
            steps {
                sh 'cp -r ${WORKSPACE}/* /home/ubuntu/api'
            }
        }
    }
}
