/*
pipeline {
  agent any
  
  stages {
    stage('build') {
      steps {
        bat 'dir'
      }
    }
  }
}
*/
/*
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Build"
            }
        }
       stage('Test') {
            steps {
                echo "Test"
            }
        }
    }
}
*/

node {
    stage('Deploy') {
        retry(3) {
            echo "retry."
        }

        timeout(time: 3, unit: 'MINUTES') {
            echo "sleep."
        }
    }
}
