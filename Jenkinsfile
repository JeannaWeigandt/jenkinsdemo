pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        gitPush()
        withMaven()
      }
    }

  }
}