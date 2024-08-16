pipeline {
    agent {
        label 'AGENT-1'
    }
      options {
        timeout(time: 30, unit: 'MINUTES')
        disableConcurrentBuilds()
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo This is Build'
            }
        }
        stage('Test') {
            steps {
                sh 'echo This is test'
            }
        }
        stage('Deploy') {
            steps {
               sh 'echo this is deploy'
            }
        }
    }
}