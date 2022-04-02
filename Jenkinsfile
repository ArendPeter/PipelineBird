pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
		bat "echo 'Build triggered from github'"
		bat "dir"
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}
