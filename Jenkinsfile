pipeline {
  agent any
  stages {
    stage('prepare git') {
      steps {
        sh '''git checkout -b build-${BUILD_NUMBER}

echo "Created branch build-${BUILD_NUMBER}"
'''
      }
    }
    stage('build') {
      steps {
        sleep 2
      }
    }
    stage('test') {
      steps {
        sleep 2
      }
    }
    stage('prepare for package') {
      steps {
        sh 'echo "preparing to package"'
      }
    }
    stage('commit package') {
      steps {
        sleep 2
      }
    }
    stage('publish package') {
      steps {
        sleep 2
      }
    }
  }
}