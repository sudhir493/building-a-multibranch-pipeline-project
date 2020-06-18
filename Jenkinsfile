pipeline {
  agent {
    docker {
      image 'ubuntu'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'go version'
      }
    }

    stage('Test') {
      steps {
        sh 'echo  "Sudhir"'
        sh 'pwd'
      }
    }

  }
}