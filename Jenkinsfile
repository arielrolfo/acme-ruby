pipeline {
    agent {
      docker {
        image 'ruby'
      }
    }
    stages {
        stage('just say hi...') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Syntax check (lint)') {
            steps {
                sh 'ruby -c '
            }
        }
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
