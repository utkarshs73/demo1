pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo '### Maven clean install ...'
        sh 'mvn clean install'
      }
    }

  }
}
