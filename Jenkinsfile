pipeline {
  agent {
    docker {
      image 'golang'
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
      }
    }

    stage('report') {
      steps {
        node(label: 'Sudhir_node1')
      }
    }

  }
}